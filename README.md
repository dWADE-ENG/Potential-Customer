# Potential-Customer

This project is a binary classification model designed to predict the likelihood of a user becoming a customer based on structured input data such as age, income, education level, and engagement metrics. It demonstrates a full machine learning pipeline from preprocessing to prediction using scikit-learn.

🧠 Key Features

Exploratory Data Analysis (EDA)

Missing value treatment and encoding

Feature scaling and selection

Logistic Regression and Decision Tree classifiers

Model evaluation with confusion matrix, accuracy, precision, and recall

Prediction interface with example inputs

📊 Use Cases

Lead qualification and scoring for marketing teams

Sales targeting and conversion likelihood modeling

Educational demo of model-building pipeline in scikit-learn

🛠️ Tools & Libraries

Python

pandas, numpy, matplotlib, seaborn

scikit-learn

💡 Example Input
predict_customer(age=35, income=55000, education="Graduate", web_visits=12)


Returns a binary classification: 1 for likely customer, 0 for unlikely.
