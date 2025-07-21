#Diabetes Predictor
This project focuses on predicting the likelihood of diabetes in patients using machine learning techniques, specifically the Logistic Regression algorithm. It is built on the Pima Indians Diabetes Dataset, which contains health-related features collected from female patients of Pima Indian heritage aged 21 and above.

The main objective is to develop a supervised learning model that can accurately classify whether an individual is diabetic based on parameters such as glucose level, BMI, insulin, age, pregnancies, and blood pressure.

🔍 Key Highlights
Exploratory Data Analysis (EDA):
The dataset is explored using visualization libraries like Matplotlib and Seaborn to identify trends, correlations, and distribution of features. Pairplots, heatmaps, and distribution plots are used to reveal insights.

Data Preprocessing:

Handling missing or zero values in medically sensitive columns like glucose, insulin, BMI, etc.

Normalizing and preparing the data for model training.

Splitting the data into training and test sets using train_test_split.

Model Building:
The Logistic Regression model is implemented using Scikit-learn, trained on the processed data to learn patterns and relationships between features and the target outcome (diabetes presence).

Model Evaluation:
The model's performance is evaluated using:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

📊 Dataset
Source: Pima Indians Diabetes Database

Features: 8 Input Features + 1 Target Variable

Target: Binary outcome (0 = Non-diabetic, 1 = Diabetic)

🛠️ Technologies Used
Python

NumPy, Pandas – Data manipulation

Matplotlib, Seaborn – Data visualization

Scikit-learn – Model building and evaluation

💡 Use Case
This model can assist in early screening of diabetes based on common medical data, helping healthcare professionals prioritize further testing and consultation.
