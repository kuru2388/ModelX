# ModelX Dementia Prediction - Machine Learning Hackathon

Binary classification model to predict dementia risk using non-medical variables from the NACC dataset.

## 📋 Prerequisites

- Python 3.10 only
- pip (Python package manager)
- Git

## 🚀 Quick Start

# -------------------------------
# CREATE VIRTUAL ENVIRONMENT
# -------------------------------

# Windows
python -m venv venv or PY -m venv venv


# Linux / Ubuntu / macOS
python3 -m venv venv


# -------------------------------
# ACTIVATE VIRTUAL ENVIRONMENT
# -------------------------------

# Windows PowerShell
venv\Scripts\Activate.ps1

# Windows CMD
venv\Scripts\activate.bat

# Linux / Ubuntu / macOS
source venv/bin/activate




### Step 1: Clone the Repository

```bash
git clone https://github.com/kuru2388/ModelX
cd modelx-dementia-prediction
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Add Your Dataset

Place the dataset file in the project folder:
- Download `Dementia Prediction Dataset.csv`
- Put it in the same folder as the Python file

Your folder structure should look like:
```
DeepVision/
├── model_x_team_deepvision.py
├── Dementia Prediction Dataset.csv
├── requirements.txt
└── README.md
```

### Step 4: Run the Model

```bash
python model_x_team_deepvision.py
```

**Note:** The script will run all 23 sections automatically from start to finish.

## ⏱️ Execution Time

- **Total runtime:** Approximately 10-20 minutes (depending on your hardware)
- **Section 8 (Hyperparameter Tuning):** Takes the longest (~5-10 minutes)

## 📊 What the Script Does

The script runs automatically through all sections:

1. ✅ **Section 1-2:** Load data and explore
2. ✅ **Section 3-5:** Preprocess and engineer features
3. ✅ **Section 6-7:** Train baseline and advanced models
4. ✅ **Section 8:** Hyperparameter tuning
5. ✅ **Section 9:** Evaluate on test set
6. ✅ **Section 10:** Model explainability (SHAP)
7. ✅ **Section 11-23:** Final analysis and save model

## 📁 Output Files Created

After running, you'll find these files:

```
├── best_dementia_model.pkl      ← Trained model
├── feature_scaler.pkl           ← Feature scaler
└── feature_names.pkl            ← List of features
```

## 📈 Expected Results

- **ROC-AUC Score:** ~0.75-0.85 (on test set)
- **Multiple visualizations** displayed during execution
- **Final model saved** for future use
