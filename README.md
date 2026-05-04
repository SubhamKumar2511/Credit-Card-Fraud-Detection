# Credit Card Fraud Detection

A Streamlit application for exploring, training, and testing machine learning models on the credit card fraud detection dataset.

## Overview

This project lets you:

- Upload the `creditcard.csv` dataset
- Explore the class imbalance and feature distributions
- Train and evaluate multiple classification models
- Test predictions on random or manual transaction inputs

## Features

- Interactive Streamlit UI
- Dataset summary and visual analysis
- Class imbalance handling
- Model training with:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- Evaluation metrics:
  - ROC-AUC
  - Precision-Recall AUC
  - F1 score
  - Precision and recall
  - Confusion matrix
- Transaction prediction for sampled or manual inputs

## Dataset

The app expects a CSV file named `creditcard.csv` with the standard columns:

- `Time`
- `V1` to `V28`
- `Amount`
- `Class`

Where:

# Credit Card Fraud Detection

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white" alt="Python 3.10+" />
  <img src="https://img.shields.io/badge/Streamlit-App-FF4B4B?logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white" alt="Pandas" />
</p>

<p align="center">
  A Streamlit dashboard for detecting fraudulent credit card transactions with interactive analytics, model training, and live predictions.
</p>

## ✨ Overview

This project lets you:

- 📂 Upload the `creditcard.csv` dataset
- 📊 Explore class imbalance and feature distributions
- 🤖 Train and evaluate multiple machine learning models
- 🔍 Test predictions using random or manual transaction inputs

## 🚀 Features

- 🎨 Clean, custom Streamlit interface
- 📈 Dataset summary and visual analysis
- ⚖️ Class imbalance handling
- 🧠 Model training with:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- 📉 Evaluation metrics:
  - ROC-AUC
  - Precision-Recall AUC
  - F1 score
  - Precision and recall
  - Confusion matrix
- 🧪 Transaction prediction for sampled or manual inputs

## 📦 Dataset

The app expects a CSV file named `creditcard.csv` with these columns:

- `Time`
- `V1` to `V28`
- `Amount`
- `Class`

Label meaning:

- `Class = 0` means a legitimate transaction
- `Class = 1` means a fraudulent transaction

The dataset is not included in the repository. Upload it through the app sidebar when running locally.

## 🛠 Requirements

- Python 3.10+
- Packages listed in `requirements.txt`

## ⚙️ Installation

```bash
git clone <https://github.com/SubhamKumar2511/Credit-Card-Fraud-Detection>
cd aipro
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## ▶️ Run the App

Start the app with the helper script:

```bash
./run.sh
```

Or run Streamlit directly:

```bash
streamlit run projectai.py
```

## 🧭 Usage

1. Launch the app.
2. Upload `creditcard.csv` from the sidebar.
3. Choose a model and class imbalance strategy.
4. Open **Train & Evaluate** to train the model.
5. Open **Predict Transaction** to test random or manual inputs.

## 🏗 Project Structure

- `projectai.py` - Main Streamlit application
- `requirements.txt` - Python dependencies
- `run.sh` - Helper script to create the virtual environment and launch Streamlit

## 📌 Notes

- The app uses caching and local preprocessing to keep the workflow responsive.
- `run.sh` creates `.venv` automatically if it does not exist.
- If you publish this on GitHub, consider linking the dataset instead of committing the CSV directly.
