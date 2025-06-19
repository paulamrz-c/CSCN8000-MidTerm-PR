# **AAIML MID-TERM PART B***

Welcome to my MID-TERM exam PART B.

This repo contains:

### - The jupyter notebook 
The notebook `NB_LR_8963215_AAIML_MidtermPartB.ipynb`  implementing:

- Data exploration with the Iris and Wine datasets

- Model training and prediction using:

    - Gaussian Naive Bayes
    - Multinomial Naive Bayes
    - Logistic Regression

- Model evaluation through:

    - Accuracy score
    - Confusion matrices
    - Cross-validation with cross_val_score

- Visual comparisons (scatter plots and bar charts)

### HTML Export (for GitHub Pages)
You can view the published notebook [here](https://paulamrz-c.github.io/CSCN80000-MIDTERM-PR/NB_LR_8963215_AAIML_MidtermPartB.html)

## Quick Start

```bash
python -m venv venv
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.\venv\Scripts\activate
pip install -r requirements.txt
python -m ipykernel install --user --name=venv --display-name "Python PR (venv)"
jupyter notebook

```

### 🐍 Python Installation (if not already installed)

This project requires **Python 3.10 or higher**.

To check if Python is installed, open PowerShell and run:

```powershell
python --version
```

If you get a message saying that Python is not recognized, you can download and install it directly using the following commands:

```powershell
curl -o python-installer.exe https://www.python.org/ftp/python/3.12.3/python-3.12.3-amd64.exe
Start-Process python-installer.exe
```

This will download the official Python installer and launch it.
➡️ Make sure to check the option “Add Python to PATH” during installation.

Once installed, reopen PowerShell and verify:

```powershell
python --version
```

## Data-sources

- Iris Dataset – Scikit-learn

- ine Dataset – Scikit-learn