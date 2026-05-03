# E-commerce Purchase Prediction (Real-Time Machine Learning)

## Project Overview
This project focuses on predicting whether a user will make a purchase during an online session using machine learning models.

Unlike a typical academic exercise, this project is designed to simulate a **real-world scenario**, where predictions must be made **in real time**, using only the data available while the user is actively browsing.

The goal is not only to achieve good performance, but to understand how machine learning models behave in practical environments and how they can support business decisions.

---

## Objective
- Predict user purchase intent (`Revenue`) during a session  
- Compare multiple machine learning models  
- Design the solution considering real-world constraints:
  - Avoiding data leakage  
  - Using only real-time features  
  - Supporting potential business actions  

---

## Dataset
- **Source:** Online Shoppers Purchasing Intention Dataset  
- Session-based data including:
  - Page visits and durations  
  - Bounce rates and exit rates  
  - Traffic type and user behavior  

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Analyzed feature distributions and relationships  
- Identified patterns associated with purchasing behavior  
- Evaluated correlations between variables  

### 2. Data Cleaning & Preparation
- Checked for missing values and inconsistencies  
- Encoded categorical variables  
- Prepared data for modeling  

### 3. Feature Selection (Real-Time Focus)
- Selected features that are realistically available during a session  
- Excluded variables that could introduce **data leakage** (e.g., `PageValues`)  

---

## Models Implemented
- Logistic Regression  
- Random Forest  
- Gradient Boosting  

### Evaluation Approach
- Cross-validation for model selection  
- Validation set for performance comparison  
- Confusion matrix analysis  

---

## Results & Insights
- Compared models using classification metrics  
- Analyzed False Positives and False Negatives  
- Focused on understanding model behavior, not just accuracy  

---

## Real-World Considerations
This project was built with practical constraints in mind:

- Predictions must be made **during the session**  
- Only features available in real time are used  
- The model could support actions such as:
  - Triggering discounts  
  - Showing recommendations  
  - Improving user engagement  

---

## Error Analysis
- Identified patterns where models consistently fail  
- Compared errors across different models  
- Highlighted trade-offs between model complexity and interpretability  

---

## Future Improvements
- Deploy the model as a simple API  
- Explore additional feature engineering techniques  
- Optimize inference time for real-time use  
- Build an end-to-end pipeline  

---

## Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## Author
Juan Andrade  
AI & Machine Learning Student  

- LinkedIn: https://www.linkedin.com/in/juan-andrade  
