# Admission Prediction using Machine Learning

## Overview
This project builds a machine learning model to **predict the probability of university admission** based on a student’s academic profile. The objective is to analyze key admission factors and develop a predictive system using real-world data.

This project demonstrates skills in **data preprocessing, exploratory data analysis, feature selection, model building, and evaluation**.

---

## Problem Statement
Universities evaluate multiple academic and profile parameters during admissions. This project aims to model that decision process and estimate the **chance of admission** for a given student profile.

---

## Dataset Description
The dataset contains student application data with the following features:

- GRE Score  
- TOEFL Score  
- University Rating  
- Statement of Purpose (SOP) strength  
- Letter of Recommendation (LOR) strength  
- CGPA  
- Research Experience  

**Target Variable:**  
- Chance of Admission (continuous value between 0 and 1)

---

## Tools & Technologies
- **Python**
- **Pandas & NumPy** for data manipulation
- **Matplotlib / Seaborn** for visualization
- **Scikit-learn** for machine learning
- **Jupyter Notebook**

---

## Approach
1. Data loading and validation  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature correlation analysis  
5. Model training using Linear Regression  
6. Model evaluation using R² score and Mean Squared Error  
7. Prediction on new inputs  

---

## Model Performance
- Evaluated using regression metrics
- Demonstrates strong correlation between CGPA, GRE score, research experience, and admission probability

---

## Project Structure

admission-prediction/
│
├── admission_prediction.ipynb
├── README.md
├── dataset.csv
└── requirements.txt


---

## Key Learnings
- End-to-end machine learning workflow
- Importance of feature selection in regression problems
- Interpreting regression metrics
- Writing clean and reproducible data science code

---

## Future Enhancements
- Implement advanced models (Random Forest, Gradient Boosting)
- Hyperparameter tuning
- Cross-validation
- Deploy the model as a web application

---

## Author
**Ayushman Panigrahi**  
Aspiring Data Scientist / Machine Learning Enthusiast

---

## License
This project is intended for educational and portfolio purposes.
