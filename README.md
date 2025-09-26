AIML internship tasks and projects

Titanic Dataset Tasks:

Overview:

This repository contains the step-by-step solution for the AI/ML internship tasks focusing on data preprocessing and exploratory data analysis (EDA) using the Titanic dataset. All code, cleaned datasets, visualizations, and brief explanations are included.

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

Task 4 – Classification with Logistic Regression

Objective: Build a binary classifier using logistic regression and evaluate its performance with standard classification metrics.

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


