This repository contains my solution to the IIT Madras Kaggle Competition, where the objective was to forecast system threats from structured log data. The project focuses on building robust machine learning models to support proactive cybersecurity strategies.

Problem Statement
Given system log data with various features, the task was to predict potential system threats accurately. Such predictions can help organizations detect vulnerabilities early and mitigate risks effectively.

Approach
Performed data preprocessing (handling missing values, encoding categorical features, scaling).
Conducted feature engineering to extract meaningful patterns from raw log data.
Implemented multiple ML models using scikit-learn, including:
Logistic Regression
Random Forest
Gradient Boosting
Tuned hyperparameters and evaluated performance using accuracy as the metric.

Results
Achieved 0.62040 accuracy, close to the competition’s top score of 0.69.
Gained insights into key threat-indicating features, improving interpretability.

Tech Stack & Dependencies
Programming Language: Python
Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn
Platform: Kaggle (IIT Madras competition environment)

How to Run

Clone the repository:
git clone https://github.com/<your-username>/system-threat-forecaster.git
cd system-threat-forecaster

Install dependencies:
pip install -r requirements.txt

Run the notebook:
jupyter notebook 21f3001176-notebook-t12025.ipynb

Competition Context
This project was developed as part of the IITM Data Science competition on Kaggle. It provided practical experience in applying machine learning to real-world structured datasets.

Future Work

Experiment with deep learning models (e.g., LSTMs for sequential logs).
Deploy as an interactive dashboard or API for real-time threat prediction.
Explore ensemble stacking for further accuracy improvements.
