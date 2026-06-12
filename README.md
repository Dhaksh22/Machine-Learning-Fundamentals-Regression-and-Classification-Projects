# Fundamental Machine Learning Projects

A collection of beginner-friendly machine learning projects implemented in
Jupyter notebooks. The repository demonstrates data exploration,
preprocessing, model training, and evaluation using common regression and
classification algorithms.

## Projects

| Notebook | Problem | Model | Dataset |
| --- | --- | --- | --- |
| `Try_Linear_Regg.ipynb` | Predict student GPA | Linear Regression | `Student_performance_data _.csv` |
| `Try_Log_Regg.ipynb` | Predict loan approval status | Logistic Regression | `loan_approval_dataset.csv` |
| `Try_Naive_Baiyes.ipynb` | Classify SMS messages as spam or ham | Multinomial Naive Bayes | `spam.csv` |

## Topics Covered

- Exploratory data analysis with Pandas, Matplotlib, and Seaborn
- Data cleaning and preprocessing
- Feature scaling and categorical encoding
- Train/test splitting
- Linear and logistic regression
- TF-IDF text vectorization
- Multinomial Naive Bayes classification
- Regression and classification evaluation metrics

## Repository Structure

```text
.
|-- Try_Linear_Regg.ipynb
|-- Try_Log_Regg.ipynb
|-- Try_Naive_Baiyes.ipynb
|-- Student_performance_data _.csv
|-- loan_approval_dataset.csv
|-- spam.csv
|-- requirements.txt
|-- .gitignore
`-- README.md
```

## Getting Started

### 1. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.\.venv\Scripts\Activate.ps1
```

Activate it on macOS or Linux:

```bash
source .venv/bin/activate
```

### 2. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 3. Start Jupyter Notebook

```bash
jupyter notebook
```

Open any notebook and run its cells in order. Keep the notebooks and CSV files
in the same directory because the datasets are loaded using relative paths.

## Project Details

### Student GPA Prediction

Explores student performance data, normalizes numerical features, selects
features based on correlation, and trains a linear regression model to predict
`GPA`. The model is evaluated using RMSE and R-squared.

### Loan Approval Prediction

Preprocesses numerical and categorical loan application data and trains a
logistic regression classifier to predict `loan_status`. Evaluation includes
accuracy, precision, recall, F1 score, a confusion matrix, and a classification
report.

### SMS Spam Detection

Transforms message text into TF-IDF features and trains a multinomial Naive
Bayes classifier to identify spam and ham messages. Performance is measured
with accuracy, a confusion matrix, and a classification report.

## Notes

- These notebooks are intended for learning and experimentation.
- Results may vary if preprocessing steps, selected features, or train/test
  parameters are changed.
- Dataset files are included so each notebook can be run locally.

