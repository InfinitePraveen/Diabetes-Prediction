# Diabetes Prediction using Decision Tree Classifier

## Project Overview
Build a machine learning model to predict diabetes using the Pima Indians Diabetes Dataset with a Decision Tree Classifier. Skills: Decision Tree, Scikit-learn, Binary Classification.

## Dataset
- Source: Pima Indians Diabetes Dataset
- Samples: 768
- Features: 8 (Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age)
- Target: Outcome (0 = Non-diabetic, 1 = Diabetic)

## Project Structure
```
diabetes-prediction/
├── diabetes_prediction.ipynb
├── diabetes.csv
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation

```bash
pip install -r requirements.txt
jupyter notebook diabetes_prediction.ipynb
```

## Results
Training Accuracy: ~85%

Testing Accuracy: ~75%

Best Features: Glucose, BMI, Age

## Requirements
numpy==1.24.3
pandas==2.0.3
scikit-learn==1.3.0
matplotlib==3.7.2
seaborn==0.12.2
jupyter==1.0.0

## License
MIT License

Author
Praveen Kumar
GitHub: @InfinitePraveen
