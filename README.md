# Multiple Disease Prediction System

An end-to-end machine learning application that predicts the likelihood of multiple diseases based on user input. Built to assist healthcare professionals and patients in early risk assessment and proactive healthcare planning.

## 🔍 Diseases Covered

* ✅ **Heart Disease**
* ✅ **Lung Cancer**
* ✅ **Parkinson’s Disease**
* ✅ **Thyroid Disorder**
* ✅ **Diabetes** 

## 🚀 Features

* Interactive disease prediction UI built with **Streamlit**
* Multiple ML models trained and tested individually
* Pickle-based model persistence for fast, real-time predictions
* Clean, modular code with separate notebooks per disease
* Sidebar navigation using `streamlit-option-menu`

## 📁 Project Structure

```
├── Heart_Disease_Prediction.ipynb      # EDA + model for Heart Disease
├── Lung_Cancer.ipynb                   # EDA + model for Lung Cancer
├── Parkinson's_Disease_Detection.ipynb # EDA + model for Parkinson’s
├── Thyroid.ipynb                       # EDA + model for Thyroid
├── Multiple_Disease_Pred.py            # Streamlit app interface
├── models/                             # Contains trained .pkl model files
├── requirements.txt                    # List of dependencies
└── README.md                           # Project documentation
```

## 🛠️ Tech Stack

* **Language:** Python
* **Interface:** Streamlit
* **Machine Learning:** Scikit-learn
* **Others:** Pickle for model loading/saving

### 📦 Dependencies (`requirements.txt`)

```
numpy==1.24.2
pickle-mixin==1.0.2
streamlit==1.20.0
streamlit-option-menu==0.3.2
scikit-learn==1.0.2
```

## 💻 How to Run

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/multiple-disease-prediction.git
   cd multiple-disease-prediction
   ```

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**:

   ```bash
   streamlit run Multiple_Disease_Pred.py
   ```

4. **Use the sidebar** to navigate between different disease prediction tools.

## 📊 Model Development

Each `.ipynb` notebook includes:

* Data cleaning and exploration
* Feature selection and preprocessing
* Model training and evaluation
* Accuracy metrics and confusion matrix

Final models are saved using `pickle` and loaded into the main Streamlit script.

## ✅ Future Enhancements

* Add model interpretability (SHAP, LIME)
* Add user authentication and history tracking
* Cloud deployment (e.g., Streamlit Cloud, Heroku)
* Expand to more diseases and real-time data input

## 🙌 Contributing

Contributions are welcome! Please open an issue or pull request for discussion.

