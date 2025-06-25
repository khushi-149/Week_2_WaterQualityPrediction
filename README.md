# Water Quality Prediction

This project was developed during my one-month AICTE Virtual Internship with Edunet Foundation, sponsored by Shell, in June 2025. The objective was to build a machine learning model to predict multiple water quality parameters using multi-output regression techniques.

## Project Overview

Access to clean water is a critical global concern. Accurate prediction of various water quality metrics can aid in early pollution detection and enable timely intervention.

As an intern, I:
- Collected and preprocessed real-world water quality datasets  
- Applied supervised machine learning techniques for regression  
- Used a `MultiOutputRegressor` wrapped around a `RandomForestRegressor`  
- Evaluated the model using standard regression metrics  

## Technologies Used

- Python 3.13.5  
- Pandas, NumPy – Data handling and preprocessing  
- Scikit-learn – Machine learning model building and evaluation  
- Matplotlib, Seaborn – Data visualization  
- Jupyter Notebook – Interactive development and experimentation  

## Predicted Water Quality Parameters

The model predicts multiple important water quality indicators, including:
- NH₄ (Ammonium)  
- BOD5 (Biochemical Oxygen Demand)  
- Colloids  
- O₂ (Dissolved Oxygen)  
- NO₃ (Nitrate), NO₂ (Nitrite), SO₄ (Sulfate), PO₄ (Phosphate), Cl (Chloride)

## Model Performance

The model was evaluated using:
- R² Score  
- Mean Squared Error (MSE)  

Performance was satisfactory across all target variables, indicating a reliable model for multi-output environmental predictions.

## Model Link

https://drive.google.com/file/d/11hFcW3pJkcHRi4OgUC8_1LCMTTMm5eik/view?usp=sharing
