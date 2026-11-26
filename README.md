# 🩺 Diabetes Prediction Using Machine Learning

An end-to-end Machine Learning project that predicts diabetes using a **Decision Tree Classifier**. This project includes data preprocessing, exploratory data analysis (EDA), missing value handling, model training, evaluation, and an interactive web application developed using Streamlit.

## 🌐 Live Application

**Try the application here:**

[🚀 Diabetes Prediction – Live Demo](https://diabetes-prediction-2008.streamlit.app/)

## 📌 Project Overview

The main objective of this project is to develop a Machine Learning classification model that predicts whether an individual belongs to the diabetes or non-diabetes class based on eight health-related input features.

The trained Decision Tree model is integrated into an interactive Streamlit web application, allowing users to enter patient information and receive instant model predictions.

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computing
- **Matplotlib** – Data visualization
- **Scikit-learn** – Machine Learning model development
- **Joblib** – Model serialization and saving
- **Streamlit** – Web application development
- **Google Colab** – Model development and training
- **GitHub** – Version control and project hosting
- **Streamlit Community Cloud** – Application deployment

## 📊 Dataset Information

The project uses a diabetes dataset containing the following input features:

| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Glucose concentration |
| BloodPressure | Blood pressure measurement |
| SkinThickness | Skin thickness measurement |
| Insulin | Insulin level |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age of the individual |

### Target Variable

**Outcome**

- `0` – No Diabetes
- `1` – Diabetes

## ⚙️ Machine Learning Workflow

1. **Data Collection** – Load the diabetes dataset using Pandas.
2. **Exploratory Data Analysis (EDA)** – Analyze dataset structure, statistical information, data types, and distributions.
3. **Data Cleaning** – Identify invalid zero values in selected health measurements.
4. **Missing Value Handling** – Replace invalid zeros with missing values and impute using mean or median based on skewness.
5. **Data Visualization** – Visualize feature distributions and diabetes class distribution using Matplotlib.
6. **Train-Test Split** – Divide the dataset into 80% training and 20% testing data using stratified sampling.
7. **Model Training** – Train a Decision Tree Classifier.
8. **Model Evaluation** – Evaluate the model using accuracy, confusion matrix, and classification report.
9. **Decision Tree Visualization** – Visualize the trained Decision Tree using Scikit-learn.
10. **Model Deployment** – Save the trained model and preprocessing information using Joblib and deploy the application using Streamlit.

## 🤖 Machine Learning Algorithm

### Decision Tree Classifier

A supervised Machine Learning classification algorithm that makes predictions using a tree-like structure of decision rules.

**Model Configuration:**

- Algorithm: Decision Tree Classifier
- Maximum Depth: 4
- Random State: 42

## 📈 Model Evaluation Metrics

The model performance is evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

These metrics help evaluate the classification performance of the trained model.

## 💻 Web Application Features

- Simple and user-friendly Streamlit interface.
- Eight health-related input fields.
- Interactive patient information form.
- Automatic handling of invalid zero values.
- Consistent preprocessing using saved imputation values.
- Instant diabetes prediction.
- Diabetes and No Diabetes classification results.
- Clear prediction result display.

## 📂 Project Structure

```text
Diabetes-Prediction/
│
├── app.py
│   └── Streamlit web application
│
├── diabetes_model.pkl
│   └── Trained Decision Tree model
│       and preprocessing information
│
├── requirements.txt
│   └── Required Python libraries
│
└── README.md
    └── Project documentation
```

## 🚀 Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Diabetes-Prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd Diabetes-Prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit Application

```bash
streamlit run app.py
```

The application will open in your browser.

## 🌍 Deployment

The application is deployed using **Streamlit Community Cloud** and connected to GitHub.

**Live Application:**

https://diabetes-prediction-2008.streamlit.app/

## 🎯 Project Objective

This project demonstrates the practical implementation of a complete Machine Learning classification workflow, from data preprocessing and model development to building and deploying an interactive web application.

It provides hands-on experience with Python, Scikit-learn, Decision Tree Classification, and Streamlit deployment.

## ⚠️ Disclaimer

This application is developed for educational and demonstration purposes only. Its predictions are not medical diagnoses and should not be used for medical decisions. Consult a qualified healthcare professional for diabetes screening and diagnosis.

## 👨‍💻 Author

Developed as a Machine Learning project using Python and Streamlit.

---

⭐ If you find this project interesting, feel free to explore the repository and try the live application!
