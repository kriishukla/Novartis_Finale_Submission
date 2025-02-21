# Clinical Trial Recruitment Rate Prediction

## Overview
This project focuses on predicting the recruitment rates (RR) in clinical trials using a rich dataset containing trial characteristics such as study indication, phase, design, sponsor, and more. With machine learning models, including neural networks, the goal is to enhance clinical trial efficiency and resource allocation. The project stood among the **Top 30 out of 50k+ registrations** in a competition, showcasing its effectiveness and potential.

### Team Name: Inferior  
### Use-Case Number: 4  
### Team Members:
- Krishna Shukla  
- Email: Krishna22254@iiitd.ac.in  
- Phone: 8368400616  

---

## Achievements

- **Ranked in the Top 30** out of **50,000+ registrations** in a prestigious competition focused on predicting clinical trial recruitment rates.
- Achieved excellent model performance, particularly with Neural Networks, which outperformed other models in accuracy and error reduction.

---

## Project Structure

- **Title Page:** Project details and team members.
- **Abstract:** Overview of the recruitment rate prediction approach.
- **Introduction:** Importance of recruitment rate prediction in clinical trials and the challenges faced.
- **Methodology:**
  - Data Preprocessing
  - Exploratory Data Analysis (EDA)
  - Feature Engineering
  - Model Development & Evaluation (Linear Regression, KNN, Decision Tree, Random Forest, Neural Networks)
- **Results:** Performance comparison between models.
- **Conclusion:** Key insights and findings from the study.
- **Future Work:** Areas for improvement and future direction.

---

## Key Features

- **Data Preprocessing:**  
  - Importing libraries and data cleaning.
  - Handling categorical variables, missing values, and date features.
  - Sentiment analysis of text columns.

- **Exploratory Data Analysis (EDA):**  
  - Visualizations (scatter plots, box plots, violin plots) to explore data distributions.
  - Outlier detection and correlation analysis to find key feature relationships.

- **Feature Engineering:**  
  - Creation of interaction and polynomial features.
  - Feature scaling for model compatibility.
  - Feature selection based on correlation analysis.

- **Model Development:**  
  - Multiple machine learning models (Linear Regression, KNN, Decision Trees, Random Forest, Neural Networks) to predict recruitment rates.
  - Tuning and hyperparameter optimization for better performance.

- **Model Evaluation:**  
  - Comparing models based on test MSE, MAE, and R².

---

## Results

### Performance Metrics:

- **Neural Network (Best Model)**:  
  - Test MSE: 20.15  
  - Test MAE: 0.56  
  - Test R²: 0.98  

- **Random Forest Regressor**:  
  - Test MSE: 50.51  
  - Test MAE: 0.18  
  - Test R²: 0.95  

- **Linear Regression, KNN, Decision Tree:** Baseline models with moderate accuracy.

### Insights:

- The Neural Network model, with its ability to capture complex relationships, outperformed the other models significantly in terms of prediction accuracy and error minimization.

---

## Future Work

1. **Deployment and Scaling:**  
   Deploy the model to a cloud platform such as AWS or Azure to handle larger datasets and provide real-time predictions.

2. **Data Expansion:**  
   Incorporate more diverse clinical trial datasets to improve model robustness and generalization.

3. **Model Interpretability:**  
   Integrate explainable AI techniques to provide stakeholders with transparent predictions and insights into feature importance.

4. **User Interface Development:**  
   Build a user-friendly dashboard for users to input trial data and receive predictions on recruitment rates.

---

## Requirements

- Python 3.x
- pandas
- scikit-learn
- textblob
- numpy
- matplotlib
- seaborn
- tensorflow (for Neural Networks)

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/clinical-trial-recruitment-prediction.git
