🪨 Rock vs Mine — Sonar Signal Classification

📌 Project Overview
This project builds a Logistic Regression model to classify sonar signals as either a Rock or a Mine.
The model is trained on the UCI Sonar dataset, which contains 60 frequency band attributes per observation.

This is a classic binary classification problem, showcasing the use of Logistic Regression in machine learning.

🗂️ Dataset
Source: UCI Machine Learning Repository

Description: 208 samples with 60 numeric features each

Target:

M → Mine

R → Rock

🧰 Technologies Used
Python 🐍
pandas
numpy
scikit-learn (LogisticRegression)

🚀 Steps Performed
✅ Loaded & explored the dataset
✅ Split data into train/test sets
✅ Trained a Logistic Regression model
✅ Evaluated accuracy on the test set
✅ Predictions made on unseen data

📊 Results
Model: Logistic Regression
Accuracy: ~ 76%

Further improvements planned:
Add evaluation metrics: Precision, Recall, F1-Score
Plot ROC Curve & calculate AUC
Experiment with other classifiers

📁 How to Run
1️⃣ Clone this repo: 
git clone https://github.com/your-username/rock-vs-mine-logistic-regression.git
2️⃣ Install dependencies:
pip install -r requirements.txt
3️⃣ Run the notebook:
Open Rock_vs_Mine_Prediction.ipynb in Jupyter Notebook or Google Collab or VS Code and execute the cells.

