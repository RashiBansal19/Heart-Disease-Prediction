# ❤️ Heart Disease Prediction Using Machine Learning

A Machine Learning project that predicts whether a person is likely to have heart disease using **Logistic Regression**.

## 📌 Project Overview

This project uses patient medical information to predict the presence or absence of heart disease. The complete workflow is implemented in **Python using Google Colab**.

The project covers data collection, data exploration, data preprocessing, categorical encoding, model training, model evaluation, and prediction.

## 📊 Dataset

The dataset used in this project was obtained from **Kaggle**.

**Dataset Name:** Heart Disease Dataset UCI  
**Dataset File:** `HeartDiseaseTrain-Test.csv`

The dataset contains **1,025 records and 14 columns**.

### Main Features

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak
- Slope
- Number of Vessels
- Thalassemia
- Target

### Target Variable

- `0` → No Heart Disease
- `1` → Heart Disease

## 🛠️ Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn
- Logistic Regression

## 🔄 Project Workflow

```text
Kaggle Dataset
      ↓
Data Collection
      ↓
Data Exploration
      ↓
Data Preprocessing
      ↓
Categorical Encoding
      ↓
Train-Test Split
      ↓
Logistic Regression
      ↓
Model Evaluation
      ↓
Heart Disease Prediction
```

## 🧹 Data Preprocessing

The dataset contains both numerical and categorical features.

Categorical features were converted into numerical features using **one-hot encoding** with Pandas `get_dummies()`.

The dataset was divided into:

- **80% Training Data – 820 records**
- **20% Testing Data – 205 records**

## 🤖 Machine Learning Model

### Logistic Regression

Logistic Regression was used as the classification algorithm because the project predicts one of two outcomes:

- Heart Disease
- No Heart Disease

## 📈 Results

| Dataset | Accuracy |
|---|---:|
| Training Data | **86.95%** |
| Testing Data | **84.88%** |

The model achieved approximately **84.88% accuracy on the testing dataset**.

## 🔮 Prediction

After training the model, new patient information can be provided to predict whether the person is likely to have heart disease.

The model produces a binary prediction:

```text
0 → No Heart Disease
1 → Heart Disease
```

## 📁 Project Structure

```text
Heart-Disease-Prediction/
│
├── HeartDiseasePrediction.ipynb
├── HeartDiseaseTrain-Test.csv
└── README.md
```

## 🚀 How to Run

1. Clone or download this repository.
2. Open `HeartDiseasePrediction.ipynb` in Google Colab or Jupyter Notebook.
3. Upload `HeartDiseaseTrain-Test.csv`.
4. Run the notebook cells sequentially.
5. View the model evaluation and prediction results.

## 🎯 Conclusion

This project demonstrates the application of Machine Learning to heart disease prediction using the Kaggle Heart Disease Dataset.

The Logistic Regression model achieved **84.88% testing accuracy** and demonstrates a basic end-to-end Machine Learning workflow, from data preprocessing to model training, evaluation, and prediction.

## ⚠️ Disclaimer

This project is created for **educational purposes only**. The predictions should not be considered a substitute for professional medical diagnosis or treatment.
