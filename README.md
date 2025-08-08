# ML-Pipeline
# Vehicle Silhouettes Classification

This project implements a machine learning pipeline for multiclass classification of vehicle types based on their silhouettes.

## Dataset
The [Statlog (Vehicle Silhouettes) dataset](https://archive.ics.uci.edu/ml/datasets/Statlog+%28Vehicle+Silhouettes%29) from UCI Machine Learning Repository is used, containing 18 features describing different cars for a 4-class classification problem.

## Project Structure
1. Data Preprocessing:
   - Loading and exploring the data
   - Train/test split (65%/35%)
   - Standard scaling of features

2. Model Training:
   - Logistic Regression with hyperparameter tuning (GridSearchCV)
   - Evaluation using F1-score and accuracy

3. Results:
   - Best parameters: {'C': 10, 'penalty': 'l1'}
   - F1-score: 0.79
   - Accuracy: 0.78

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

## How to Run
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Open and run the Jupyter notebook
