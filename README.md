# Fuel Economy Analysis
Overview This project focuses on analyzing fuel economy data using machine learning techniques. The dataset contains various features related to vehicle specifications, fuel types, and fuel costs.

# Dataset:
The dataset (vehicles.csv) used in this project consists of numerical and categorical fuel economy variables.

# Data Preprocessing:
Imputation: Missing values in numerical columns are filled using the median value of each respective column. Outlier Removal: Outliers are identified and removed from the dataset based on the interquartile range (IQR) method. Scaling: Numerical features are scaled using both StandardScaler and MinMaxScaler techniques.

# Model Training:
Three regression models are trained on the preprocessed dataset: Linear Regression Decision Tree Regressor Random Forest Regressor

# Evaluation:
The trained models are evaluated using the R-squared (R2) metric on both training and testing datasets to assess their performance. R2 score measures the proportion of the variance in the dependent variable that is predictable from the independent variables.

# Results:
Linear Regression: Achieved a training score of [0.99] and a testing score of [0.99]. Decision Tree Regressor: Achieved a training score of [1.0] and a testing score of [1.0]. Random Forest Regressor: Achieved a training score of [0.99] and a testing score of [0.99].

# Conclusion:
All Models Performed well outperformed the other models with the highest testing score.


---

# Titanic Survival Prediction

This project is built to predict passenger survival on the Titanic using Machine Learning techniques.
Unlike a typical tutorial-based implementation, this project was done with the intention of strengthening my practical understanding of data preprocessing, feature engineering, and model building workflows.
The primary focus of this project was to gain strong hands-on experience with real-world data handling and to improve my grip on essential Data Science tools and concepts.

---

# Objective
To build a classification model that predicts whether a passenger survived the Titanic disaster using structured data and supervised learning algorithms.

---

# Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Project Workflow

# Data Understanding & Cleaning
- Handling missing values
- Understanding feature distributions
- Removing irrelevant columns
- Data consistency checks

# Exploratory Data Analysis (EDA)
- Survival rate analysis
- Gender-wise survival comparison
- Passenger class impact on survival
- Correlation analysis

# Feature Engineering
- Encoding categorical variables
- Feature scaling using StandardScaler
- Preparing data for model training

# Model Building
- Train-Test Split
- Applied classification algorithms
- Model evaluation using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

# Key Learning Outcomes

Through this project, I strengthened my understanding of:

- End-to-end Machine Learning workflow
- Practical data preprocessing challenges
- Feature scaling and encoding techniques
- Model evaluation metrics
- Writing clean and structured ML notebooks

---

# Note :-
This project was developed primarily to improve my practical experience and build strong hands-on expertise in Machine Learning tools and workflows.

