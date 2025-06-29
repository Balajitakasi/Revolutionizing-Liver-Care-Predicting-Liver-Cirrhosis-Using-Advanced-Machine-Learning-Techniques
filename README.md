# Revolutionizing-Liver-Care-Predicting-Liver-Cirrhosis-Using-Advanced-Machine-Learning-Techniques.🩺

This project aims to develop a robust machine learning pipeline for the early prediction of liver cirrhosis using clinical and laboratory data. It follows best practices in data science and MLOps, including data versioning, model tracking, experiment management, and reproducibility.

🔍 Objective:
To predict liver cirrhosis status based on patient features, helping in early detection and intervention. The project includes:
•Data preprocessing and cleaning
•Feature selection using Random Forest
•Model training and hyperparameter tuning
•Evaluation using classification metrics and ROC-AUC
•Experiment tracking using DVC
•Model versioning and reproducibility.

📦 Tech Stack:
•Python 3.12
•Scikit-learn, Imbalanced-learn, Pandas, Matplotlib.
•DVC for data and experiment tracking
•Git & GitHub for version control and collaboration
•VS Code for development.

✅ Key Features:
•Balanced dataset using SMOTE to handle class imbalance
•Top feature extraction using Random Forest
•Multiple model training and performance comparison
•Visualizations: confusion matrix, ROC curves
•DVC experiment tracking and reproducibility
•Remote DVC storage setup for shared pipelines.

📊 Metrics Tracked:
•Accuracy
•Precision, Recall, F1-score
•ROC AUC Score.

🔁 Reproducibility:
To reproduce the entire pipeline:

dvc repro
dvc exp run
dvc exp show


🌐 Remote Storage

Data and model artifacts are stored and versioned using a DVC remote set at:

bash

dvc remote add -d local_remote ./dvc_storage

