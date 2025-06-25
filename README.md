🎓 Student Habit Performance Prediction using Machine Learning
This project uses machine learning techniques to predict student academic performance based on their study habits, lifestyle, and behavioral data. By analyzing key factors like study time, sleep duration, attendance, and extracurricular activity, the model aims to provide insights into student outcomes.

🎯 Objective
The goal is to build predictive models that assess how various habits and lifestyle choices influence academic performance. This can help educators and students identify improvement areas and make informed decisions.

🧠 Algorithms Used
Linear Regression
Used to model the relationship between habits and academic scores under the assumption of linearity.

K-Nearest Neighbors (KNN)
A distance-based algorithm that predicts performance by comparing similar students (neighbors) in the dataset.

📊 Dataset Features
Typical features in the dataset may include:

Study hours per day

Sleep hours per night

Attendance percentage

Participation in class

Extracurricular involvement

Assignment submission rate

Final score / grade (Target)

🔧 Workflow
Data Collection

Clean dataset representing student habits and performance.

Data Preprocessing

Handle missing values

Encode categorical variables

Normalize features (for KNN)

Exploratory Data Analysis (EDA)

Visualize correlations

Identify trends between habits and scores

Model Development

Train/test split

Train both Linear Regression and KNN models

Predict student performance (e.g., final score)

Model Evaluation

Metrics: R² Score, MAE, MSE

Compare models and interpret results

🛠️ Tools & Libraries
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📁 Files Included
student_data.csv – Dataset

student_model.ipynb – ML code and model analysis

README.md – Project overview
