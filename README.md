This project focuses on predicting students' final grades (G3) using machine learning models. It uses two datasets — one for Mathematics and one for Portuguese — and applies two main approaches: separate modeling on each dataset and a merged modeling approach. The goal is to evaluate and compare the performance of different regression models and analyze how hyperparameter tuning affects their accuracy.
---

 Dataset

We used the [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance), which includes two separate datasets:
- `student-mat.csv` (Mathematics performance)
- `student-por.csv` (Portuguese language performance)

Each dataset contains demographic, social, and academic attributes, with the final grade (G3) as the target variable.

---

 Methodology

- Data preprocessing: handling missing values, encoding categorical features, merging datasets.
- Feature selection: manual logic-based filtering and correlation analysis.
- Model training: applied multiple regression models.
- Hyperparameter tuning:
  - `GridSearchCV` for Decision Tree, Random Forest, SVR
  - `Optuna` for Artificial Neural Networks (ANN)
- Evaluation metrics used:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - RMSE (Root Mean Squared Error)
  - R² Score

  Contributer
  -Imad Eddine Ahsatal
