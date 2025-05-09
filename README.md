Heart disease is one of the leading causes of death worldwide. Thus, preventing and detecting it early has become more important than ever. Data-driven systems that can accurately predict heart disease can play a major role in improving medical diagnosis, allowing for early intervention and better patient outcomes. This is where Machine Learning comes into play. By analyzing patterns in health-related data, Machine Learning can help in predicting heart disease with a high level of accuracy.
In this project, we built a heart disease prediction system using machine learning techniques. The project involved analyzing datasets that included both clinical parameters (like blood pressure, cholesterol, glucose levels) and lifestyle factors (such as smoking, physical activity, and diet). We trained separate models on clinical data, lifestyle data, and a combination of both to see which approach yields the best results.

The entire model training process was done using Python in Jupyter Notebook. For classification, we used various algorithms including:
1. Logistic Regression (Scikit-learn)
2. Decision Tree Classifier (Scikit-learn)
3. Random Forest Classifier (Scikit-learn)
4. XGBoost (Extreme Gradient Boosting) (Scikit-learn)

The frontend of the project was built using HTML, CSS, and JavaScript, designed to be user-friendly for lab technicians or healthcare staff who may not have technical backgrounds. It allows users to enter health data into a form easily. This frontend is connected to a Flask backend, which handles data processing, feeds the data into trained ML models, and returns real-time predictions.
This is a binary classification problem where the input features are a mix of clinical and lifestyle values, and the output is a prediction: whether the person is at risk of heart disease or not. The system helps provide fast and accurate risk assessments and is especially helpful in medical environments that require quick, data-supported decisions.

Technologies used:
1. Python, Jupyter Notebook
2. Scikit-learn, XGBoost
3. HTML, CSS, JavaScript
4. Flask (Backend framework)

We used three datasets in this project:
1. Dataset 1 (Clinical parameters): https://www.kaggle.com/datasets/thisishusseinali/uci-heart-disease-data
2. Dataset 2 (Lifestyle Parameters): https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset
3. Dataset 3 (Combination of both Lifestyle and Clinical parameters): https://www.kaggle.com/datasets/iamsouravbanerjee/heart-attack-prediction-dataset

Accuracy achieved for dataset 1: 96% (Random Forest Classifier)

Accuracy achieved for dataset 2: 89% (Logistic Regression)

Accuracy achieved for dataset 3: 63% (XGBoost)
