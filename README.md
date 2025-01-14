# Heart Disease Prediction Using Machine Learning


## Introduction
Predicting the likelihood of heart disease is crucial for timely diagnosis and treatment. This project automates the initial prediction process by leveraging machine learning, potentially reducing patient wait times and easing the workload for medical professionals.

## Data
- **Dataset**: [Heart Disease Dataset](https://www.kaggle.com/johnsmith88/heart-disease-dataset)
- **Rows**: 303
- **Features**: Includes blood pressure, chest pain type, cholesterol levels, etc.

## Exploratory Data Analysis (EDA)
1. **Correlation Insights**:
   - `thalach` and `slope` are positively correlated.
   - `age` and `thalach` are negatively correlated.
   - `cp` and `exang` are negatively correlated.
2. **Feature Relationships**:
   - Resting blood pressure (`trestbps`) somewhat correlates with age and fasting blood sugar (`fbs`).
3. **Data Summary**:
   - Average age ~55 years.
   - Mix of numerical and categorical features (converted using one-hot encoding).

## Visualizations
- Explored trends and distributions (age, gender, chest pain type, etc.).
- Illustrated the relationship between features (blood pressure, cholesterol) and heart disease outcomes.
- Compared different ML model metrics via charts/plots.

## Machine Learning & Models
We used multiple machine learning algorithms to predict heart disease:
1. **K Nearest Neighbors (KNN)**
2. **Logistic Regression**
3. **Naive Bayes**
4. **Random Forest Classifier**

## Outcomes
- **Naive Bayes** consistently achieved the highest performance (precision, recall, F1 score, and accuracy).
- Demonstrated the efficacy of machine learning in automating disease risk prediction.

## Future Scope
1. **Additional Data**: Including larger and more diverse datasets could improve model generalizability.
2. **Feature Engineering**: Adding more relevant health metrics (e.g., ECG readings, lifestyle factors) may enhance accuracy.
3. **Deployment**: Integrating the best model (Naive Bayes) into a real-time system could assist doctors in faster, more informed diagnoses.

## Tech Stack
- **Python** (NumPy, Pandas, Matplotlib, Seaborn)
- **Scikit-learn** for machine learning models
- **Jupyter Notebook** or similar environment for development

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YourUsername/heart-disease-prediction.git
