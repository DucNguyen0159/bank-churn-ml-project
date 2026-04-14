# Customer Churn Prediction

## Overview
This project predicts whether a customer will churn using machine learning models. The full workflow is implemented in **`BankChurnCode.ipynb`**.

## Dataset
- Bank customer dataset
- Features include age, balance, credit score, etc.

## Methods
1. **Logistic Regression** — interpretable linear baseline and coefficients  
2. **Neural Network** (`MLPClassifier`) — nonlinear patterns  
3. **Tree-based** — decision tree (tuned) **and** random forest, metrics compared between them.  
4. **KNN** — similarity-based predictions on scaled features; *k* chosen by cross-validation on the training set  

## Results
- Models are compared on the held-out test set using accuracy, precision, recall, and F1; the summary table also includes **AUC** for logistic regression (probability-based).  
- See `BankChurnCode.ipynb` for metrics tables, confusion matrices, ROC (logistic regression), tree and forest plots, and feature-importance charts

## Tools Used
- Python
- scikit-learn
- pandas, numpy, matplotlib

## Environment setup

Install dependencies into the Python environment you will use to run the notebook (recommended: Python 3.10+).

**Using pip (from the project folder):**

```bash
python -m pip install numpy pandas matplotlib scikit-learn
```

Using `python -m pip` ensures packages install for the same interpreter as `python` on your PATH.

**Optional: virtual environment**

```bash
python -m venv .venv
```

- **Windows (PowerShell):** `.venv\Scripts\Activate.ps1`
- **macOS / Linux:** `source .venv/bin/activate`

Then run the `pip install` command above inside the activated environment.

**Editor / notebook:** If imports show as unresolved but `pip` reports the packages as installed, your IDE or Jupyter kernel is using a different Python. Select the same interpreter (e.g. **Python: Select Interpreter** in the command palette) and pick the matching kernel for the notebook.

## Author
- Henry Nguyen
- Jessica Nguyen
- 
- 
