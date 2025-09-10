🧠 Parkinson’s Disease Detection
📌 Project Overview

This project applies machine learning models to detect Parkinson’s disease using biomedical voice measurements from the UCI Machine Learning Repository. The goal is to assist in early diagnosis by analyzing vocal features.

📊 Dataset

Source: UCI Parkinson’s Dataset

Size: 195 records × 24 columns

Target: status (1 = Parkinson’s, 0 = Healthy)

Features: Biomedical voice measures such as frequency, amplitude, and signal-to-noise ratio.

⚙️ Workflow

Data Preprocessing

Dropped irrelevant columns (name)

Scaled features with MinMaxScaler (range -1 to 1)

Split dataset into training & test sets

Model Training

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Gradient Boosting Classifier

Evaluation

Confusion Matrix (counts + percentages)

Accuracy, Precision, Recall, F1-score

Comparative analysis of models

📈 Results
Model	Accuracy	F1-score
Logistic Regression	92%	0.90
Decision Tree	88%	0.87
Random Forest	95%	0.93
Gradient Boosting	94%	0.92

✅ Random Forest performed the best with 95% accuracy and 0.93 F1-score.

📊 Visualizations

Distribution of status (Healthy vs Parkinson’s)

Histograms of key features

Confusion matrices for each model

Classification reports

🚀 Future Improvements

Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)

Feature importance analysis

Deploy best model with Streamlit/Flask for real-time predictions

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn
