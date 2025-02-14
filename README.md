# 🔬 Disease Outbreak Prediction System using ML

<div align="center">
  <img src="src/Disease%20Outbreak%20Prediction%20Logo.png" alt="Medical AI Logo" width="200"/>
  <br>
  <em>Harnessing the power of AI to predict health outcomes</em>
</div>

## 🌟 Overview

Welcome to the Disease Outbreak Prediction System - a powerful machine learning application designed to predict the likelihood of three critical health conditions:

- 🩸 **Diabetes**
- ❤️ **Heart Disease**
- 🧠 **Parkinson's Disease**

Built with cutting-edge machine learning algorithms, this system provides quick, accessible predictions to help identify potential health risks before they become critical.

## ✨ Features

- **Multi-Disease Analysis**: Three specialized prediction models in one application
- **User-Friendly Interface**: Clean, intuitive design for healthcare professionals or individuals
- **Instant Results**: Get predictions with the click of a button
- **Parameter Flexibility**: Input a wide range of medical parameters for comprehensive analysis

## 📊 Supported Predictions

### Diabetes Prediction
Analyzes factors including:
- Number of pregnancies
- Glucose levels
- Blood pressure
- Skin thickness
- Insulin levels
- BMI
- Diabetes pedigree function
- Age

### Heart Disease Prediction
Evaluates 13 critical parameters:
- Age and sex
- Chest pain types
- Resting blood pressure
- Cholesterol levels
- Fasting blood sugar
- ECG results
- Maximum heart rate
- Exercise-induced angina
- ST depression
- Slope of peak exercise ST segment
- Number of major vessels
- Thalassemia type

### Parkinson's Disease Prediction
Utilizes 22 voice parameter metrics including:
- Fundamental frequency variations
- Jitter and shimmer measurements
- Harmonic-to-noise ratios
- Nonlinear dynamical complexity features

## 🔧 Installation

Getting started is simple!

```bash
# Install required packages
pip install scikit-learn numpy pandas streamlit streamlit-option-menu

# Run the application
streamlit run app.py
```

## 🚀 Usage

1. Launch the application using the command above
2. Select the disease prediction type from the sidebar
3. Enter the required parameters in the input fields
4. Click the prediction button
5. View your results instantly!

## 💻 Technology Stack

- **Streamlit**: For the interactive web interface
- **Scikit-learn**: Powering our machine learning models
- **Pandas & NumPy**: For efficient data processing
- **Python**: The foundation of our application

## 🔍 How It Works

The system uses carefully trained machine learning models (Support Vector Machines and Random Forests) to analyze input parameters. Each model has been optimized for its specific disease prediction task, ensuring the highest possible accuracy while maintaining quick response times.

## 🌐 Why This Matters

Early detection is key to managing chronic diseases. This tool provides a quick, initial screening that can alert users to potential health concerns that warrant further medical investigation.

## 🤝 Contributing

This project is open to contributions! Whether you're fixing bugs, improving documentation, or proposing new features, your help is welcome.

## 👨‍💻 Contributors

- **Luqman Aftab Gudur** - Initial work and main Web App and Backend Model development

## ⚠️ Disclaimer

This tool is designed for preliminary screening purposes only and is not a substitute for professional medical advice, diagnosis, or treatment. Always consult qualified healthcare providers for any health concerns.

---

<div align="center">
  <p><i>Empowering Healthcare decisions through Artificial Intelligence</i></p>
</div>
