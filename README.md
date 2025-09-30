AIML internship tasks and projects

Overview:

This repository consists of internship tasks completed as part of the Elevate Labs program.
____________________________________________________________________________________________________________________________________________________________________________________________________________________________

📌 Task 1 – Titanic Data Preprocessing

Objective: Learn how to clean and prepare raw data for ML.

🔄 Steps Performed

- Loaded the Titanic dataset and explored its structure using head(), info(), describe(), and isnull().sum().

- Handled missing values:

  - Age → filled with median.
  
  - Embarked → filled with mode.

- Encoded categorical variables: Sex and Embarked using one-hot encoding.

- Standardized numerical features (Age, Fare) using StandardScaler for uniform scaling.

- Visualized outliers using boxplots; applied scaling instead of removing them.

- Exported the cleaned dataset as cleaned_titanic.csv.

Files Added:

  - train.csv (original dataset)
  
  - cleaned_titanic.csv (cleaned dataset)
  
  - Task 1 code notebook/script
____________________________________________________________________________________________________________________________________________________________________________________________________________________________

📌 Task 2 – Exploratory Data Analysis (EDA)

Objective: Understand data using statistics and visualizations.

🔄 Steps Performed

- Generated summary statistics (describe(include='all')) to understand data distribution.

- Plotted histograms for all numeric features to check spread and skewness.

- Plotted boxplots for all numeric features to detect outliers.

- Created a correlation heatmap to analyze feature relationships.

- Created pairplots to visualize interactions between features and survival.

- Made feature-level observations:

  - Higher-class passengers (Pclass=1) had better survival.

  - Females (Sex=0) survived more than males.

  - Younger passengers had slightly better survival than seniors.

  - Extreme Fare values indicate anomalies.

Files Added:

  - Task 2 code notebook/script
  
  - Visualizations: histograms, boxplots, heatmaps, pairplots
  
  - Observational notes and inferences

____________________________________________________________________________________________________________________________________________________________________________________________________________________________

📂 Task 3 – Linear Regression

🎯 Objective: Understand how to implement Linear Regression models (simple & multiple), evaluate them with error metrics, visualize regression lines, and interpret coefficients to understand feature impact.

🔄 Steps Performed

- Loaded the House Price (Housing) dataset and explored its structure using head(), info(), and describe().

- Preprocessed the dataset by:

  - Separating features (area, bedrooms, bathrooms, stories, etc.) and target (price).

  - Encoding categorical variables (mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus) using one-hot encoding.

- Split the data into train (80%) and test (20%) sets using train_test_split.

- Trained Linear Regression models:

  - Multiple Regression with all features.

  - Simple Regression with a single feature (area).

- Evaluated the models using:

  - Mean Absolute Error (MAE)

  - Mean Squared Error (MSE)

  - R² Score

- Plotted the regression line (for simple regression: area vs price).

- Interpreted model coefficients to understand how each feature influences house price.

____________________________________________________________________________________________________________________________________________________________________________________________________________________________

Task 4 – Classification with Logistic Regression

📌 Objective: Build a binary classifier using logistic regression and evaluate its performance with standard classification metrics.

🔄 Steps Performed

- Loaded the Breast Cancer Wisconsin dataset from scikit-learn.

- Split data into train (80%) and test (20%) sets.

- Standardized features using StandardScaler to ensure uniform scaling.

- Trained a Logistic Regression model with scikit-learn (LogisticRegression).

- Made predictions and calculated probabilities for the test set.

- Evaluated the model using:

  - Confusion Matrix

  - Classification Report (Precision, Recall, F1-score)

  - Accuracy Score

  - ROC-AUC Score

- Plotted the ROC Curve to visualize performance across thresholds.

- Experimented with a custom decision threshold to analyze trade-offs between precision and recall.

- Explained the role of the sigmoid function in mapping linear outputs into probabilities.
____________________________________________________________________________________________________________________________________________________________________________________________________________________________

Task 5 – Decision Trees and Random Forests

📌 Objective: Learn and implement tree-based models (Decision Tree and Random Forest) for classification, analyze overfitting, interpret feature importances, and evaluate performance using cross-validation.

🔄 Steps Performed

- Loaded the Heart Disease dataset and explored its structure.

- Split the data into training (80%) and testing (20%) sets.

- Trained a Decision Tree Classifier using scikit-learn.

- Visualized the Decision Tree using plot_tree() to interpret splits.

- Analyzed overfitting by comparing a full-depth tree with a depth-limited tree.

- Trained a Random Forest Classifier with 100 trees and compared accuracy with Decision Tree.

- Evaluated both models using:

  - Accuracy Score

  - Confusion Matrix

  - Classification Report (Precision, Recall, F1-score)

- Performed Cross-Validation to check consistency of Random Forest performance.

- Plotted Feature Importances to interpret the most influential predictors.

- Explained the difference between single tree vs ensemble (Random Forest) and their pros/cons.

____________________________________________________________________________________________________________________________________________________________________________________________________________________________

Task 6 – K-Nearest Neighbors (KNN) Classification

📌 Objective: Learn and implement the K-Nearest Neighbors algorithm for classification problems, experiment with different K values, evaluate performance, and visualize decision boundaries.

🔄 Steps Performed

- Loaded the Iris dataset (150 samples, 4 features, 3 classes).

- Normalized features using StandardScaler to ensure fair distance-based calculations.

- Split the data into training (80%) and testing (20%) sets.

- Trained a KNeighborsClassifier using scikit-learn.

- Experimented with different values of K (1, 3, 5, 7, 11, 15) and compared accuracy results.

- Evaluated the model using:

  - Accuracy Score

  - Confusion Matrix

  - Classification Report (Precision, Recall, F1-score)

- Plotted an Accuracy vs K graph to identify the optimal K value.

- Visualized decision boundaries (using two selected features) to understand how KNN classifies regions.

- Explained the effect of K on bias-variance tradeoff and sensitivity to noisy data.



