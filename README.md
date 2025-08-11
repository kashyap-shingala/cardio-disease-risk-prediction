# Machine-Learning-Cardiovascular-Disease-Classification

🫀 Cardiovascular Disease Prediction
This project builds a machine learning model to predict whether a person has cardiovascular disease based on medical and lifestyle attributes. The final model is deployed using Streamlit for an interactive and user-friendly experience.

📊 Dataset
Contains 70,000 medical records with features such as age, gender, blood pressure, cholesterol, glucose levels, BMI, smoking, alcohol intake, and physical activity.

Target variable: cardio (1 if disease is present, 0 otherwise).

🔧 Workflow
1. Data Preprocessing  
Handled missing/outlier values, scaled numerical features, and encoded categorical variables.

Engineered BMI (Body Mass Index) from height and weight.

2. Exploratory Data Analysis (EDA)  
Visualized distributions, correlations, and class imbalances to understand feature importance and trends.

3. Model Building  
Built pipelines for multiple models including:

Logistic Regression

Random Forest

Gradient Boosting (Best performer)

K-Nearest Neighbors

Decision Tree

Used GridSearchCV for hyperparameter tuning.

Evaluated using Accuracy, Precision, Recall, F1-score, and ROC-AUC.

4. Deployment  
Developed a Streamlit app where users can input health attributes and receive:

Disease prediction

Probability score of having cardiovascular disease
