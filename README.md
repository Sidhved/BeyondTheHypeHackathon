# Medical Condition Prediction Project

## Project Overview
This project aims to predict medical conditions using patient data through machine learning. The pipeline includes exploratory data analysis (EDA), data preprocessing, and model training using logistic regression as a baseline model.

## Repository Structure
```
│   ├── EDA.ipynb         # Exploratory Data Analysis
│   └── Training.ipynb    # Model Training Pipeline
├── models/
│   └── baseline_logistic_model.pkl # Trained model
└── README.md
└── .gitignore
```

## Data Description

### Input Features:
- **Patient Demographics**: PatientID, State, Sex, AgeCategory
- **Physical Measurements**: HeightInMeters, WeightInKilograms, BMI
- **Medical History**: HadAngina, HadStroke, HadAsthma, etc.
- **Lifestyle Factors**: SmokerStatus, ECigaretteUsage, AlcoholDrinkers
- **Healthcare Access**: ChestScan, HIVTesting, FluVaxLast12, etc.

### Target Variable:
- Binary classification target indicating medical condition

## Notebooks

### EDA.ipynb
- Data loading and initial inspection
- Feature correlation analysis
- Numerical conversion of categorical variables
- Visualization of feature relationships

### Training.ipynb
- Loads preprocessed data
- Implements baseline logistic regression model
- Evaluates model using AUROC metric
- Includes ROC curve visualization

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/Sidhved/BeyondTheHypeHackathon.git
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run notebooks in order:
   - First run EDA.ipynb for data analysis
   - Then run Training.ipynb for model training

## Model Performance
- Baseline Logistic Regression model evaluated using AUROC
- Results and performance metrics available in Training.ipynb

## Future Improvements
1. Feature engineering and selection
2. Implementation of advanced models
3. Hyperparameter tuning
4. Cross-validation implementation
5. Model interpretability analysis

## Contact
For any questions or feedback, please contact [Your Name/Team]
