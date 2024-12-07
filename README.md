#Overview
This project aims to predict the likelihood of lifestyle diseases, specifically Chronic Kidney Disease (CKD) and Vascular Diseases, using machine learning algorithms. By leveraging datasets from hospitals, this system helps healthcare professionals identify high-risk patients, facilitating early intervention and prevention strategies.

#Features
Disease Prediction: The system predicts whether a patient is at risk of developing CKD or vascular diseases based on lifestyle and medical data.
Data Preprocessing: Clean and preprocess real-world hospital datasets to make them suitable for machine learning models.
Model Training: Utilize machine learning algorithms like Logistic Regression, Random Forest, or Support Vector Machine to build prediction models.
Evaluation: Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.
Visualization: Visualize the relationships between different features and their impact on the prediction.
Datasets
The following datasets are used in the project:

Chronic Kidney Disease (CKD):

A dataset containing patient information such as age, blood pressure, glucose levels, and other indicators to predict CKD risk.
Vascular Diseases:

A dataset that includes details such as heart disease risk factors, cholesterol levels, smoking habits, and family history of vascular diseases.

#requirements
#python==3.10.13
blinker==1.7.0
click==8.1.7
colorama==0.4.6
Flask==3.0.2
Flask-Login==0.6.3
Flask-SQLAlchemy==3.1.1
greenlet==3.0.3
itsdangerous==2.1.2
Jinja2==3.1.3
joblib==1.3.2
MarkupSafe==2.1.5
numpy==1.26.4
scikit-learn==1.1.3
scipy==1.12.0
SQLAlchemy==2.0.28
threadpoolctl==3.3.0
typing_extensions==4.10.0
Werkzeug==3.0.1

#to clone this project
git clone https://github.com/yourusername/lifestyle-disease-prediction.git
cd lifestyle-disease-prediction
