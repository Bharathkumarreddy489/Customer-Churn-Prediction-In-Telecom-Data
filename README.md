Customer Churn Prediction Project:
This repository contains the code, dataset, report, and Power BI dashboard for a customer churn prediction project. The project aims to analyze customer data from a telecommunications company to predict customer churn and provide actionable insights to reduce churn rates.

Project Overview:
The project includes:
  1. Exploratory Data Analysis (EDA) to understand the dataset and identify key features.
  2. Data preprocessing steps such as handling missing values, encoding categorical variables, and splitting the data into training and testing sets.
  3. Model building using machine learning algorithms including Decision Tree, Random Forest, and K Nearest Neighbors (KNN) classifiers.
  4. Evaluation of model performance before and after balancing the dataset using SMOTEENN.
  5.Power BI dashboard creation to visualize insights and provide recommendations for reducing customer churn.
Model Performance Metrics:
This section provides an overview of the performance metrics of the machine learning models before and after balancing the dataset using SMOTEENN.

Model	                          Accuracy (Before)	Precision (Before)	Recall (Before)	F1-Score (Before)	Accuracy (After)	Precision (After)	Recall (After)	F1-Score (After)
Decision Tree Classifier	          79.96%	            68.09%	           46.67%	         55.38%	              93.76%	          92.82%	       95.90%	           94.34%
Random Forest Classifier	          80.03%             	69.11%	           45.33%          54.75%	              95.13%	          93.25%	       98.11%	           95.62%
K Nearest Neighbors (KNN)	          77.83%	            61.54%	           44.80%	         51.85%	              97.95%	          97.51%	       98.74%	           98.12%
These results demonstrate a significant improvement in model performance metrics after balancing the dataset, with higher accuracy, precision, recall, and F1-scores across all three models.


