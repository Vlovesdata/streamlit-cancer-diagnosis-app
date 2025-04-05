# 🧬 Breast Cancer Diagnosis – Interactive Streamlit App

This is an interactive Streamlit web application that predicts whether a breast mass is benign or malignant using a trained logistic regression model on the Breast Cancer Wisconsin Diagnostic Dataset. Users can simulate lab input using sidebar sliders or connect real data for predictive diagnosis.

# 🚀 Live App

🔗[Launch the App](http://localhost:8501/)

# 🧠 What the App Does

- Simulates predictions using real diagnostic measurements

- Accepts 30 cell nuclei measurements via sidebar sliders

- Visualizes input via grouped radar chart (mean, se, worst)

- Returns a prediction: Benign (0) or Malignant (1) with confidence score

- Powered by a trained Logistic Regression model


# 📊 Dataset Overview

- Source: [UCI Breast Cancer Wisconsin Diagnostic Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

- Samples: 569

- Features: 30 numeric features (mean, standard error, worst)

- Target: diagnosis
    - M = Malignant → 1
    - B = Benign → 0
 
# ⚙️ How to Run the App Locally

1. Clone the repository
```
git clone https://github.com/Vlovesdata/streamlit-cancer-prediction-app.git
cd streamlit-cancer-prediction-app
```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Launch the Streamlit app
```
streamlit run app/main.py
```


# 📦 Dependencies

- streamlit

- pandas

- scikit-learn

- plotly

- pickle5

Install them using:
```
pip install -r requirements.txt
```

