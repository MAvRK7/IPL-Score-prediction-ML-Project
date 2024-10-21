# Data Driven Cricket: A Machine Learning Approach to IPL Score Prognostication
Introduction:
This project focuses on predicting scores in Indian Premier League (IPL) matches using machine learning models. By leveraging historical match data, including various features such as batting team, bowling team, runs, wickets, overs, runs in the last 5 overs, and wickets in the last 5 overs, the aim is to forecast the total runs scored in a cricket match. Three different machine learning algorithms, namely Linear Regression, Random Forest, and Support Vector Machine (SVM), are employed to analyze the data and make predictions.

Dataset:
The dataset used in this project consists of comprehensive match statistics obtained from the IPL. It includes various features such as match ID, date, venue, batting team, bowling team, runs, wickets, overs, runs in the last 5 overs, wickets in the last 5 overs, striker, non-striker, and total runs.

In this IPL score prediction project, three distinct machine learning models are employed: Linear Regression, Support Vector Machine (SVM), and Random Forest (RF). 

**Linear Regression:** Linear Regression is a simple and interpretable model that assumes a linear relationship between the input features and the target variable, which in this case is the total runs scored in an IPL match. It works by finding the best-fit line that minimizes the difference between the predicted and actual total runs. Linear Regression is suitable for capturing linear dependencies in the data and provides insights into how each input feature contributes to the predicted outcome.

**Support Vector Machine (SVM):** SVM is a powerful algorithm used for classification and regression tasks. In this project, SVM is applied for regression to predict the total runs scored in IPL matches. SVM aims to find a hyperplane that best separates the input feature space into regions representing different classes. It is particularly effective in high-dimensional spaces and offers flexibility through the use of different kernel functions to model non-linear relationships between input features and total runs.

**Random Forest (RF):** Random Forest is an ensemble learning technique that constructs multiple decision trees during training and combines their predictions to make the final prediction. Each decision tree is trained on a random subset of the data and a random subset of features, which helps to reduce overfitting and increase model robustness. Random Forest is well-suited for capturing non-linear patterns and complex relationships in the data, making it a valuable model for predicting IPL scores where the outcome may not follow a simple linear trend.

Overall, the combination of these three models provides a comprehensive approach to IPL score prediction, leveraging their respective strengths to capture different aspects of the underlying data distribution and improve prediction accuracy.

Methodology:

Data Preprocessing: The dataset is preprocessed by filtering out irrelevant features, handling missing values, and selecting only consistently performing teams for analysis.
Feature Engineering: Categorical features are one-hot encoded, and date columns are converted to datetime format. The selected features are then arranged for model training.
Model Training: Three machine learning models, namely Linear Regression, Random Forest, and Support Vector Machine, are trained using the selected features.
Model Evaluation: Various evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared are used to assess the performance of each model.
Prediction: User-friendly functions are created to accept input values and predict the total runs scored using the trained models.


This work has been accepted by and presented at THE 15th INTERNATIONAL IEEE CONFERENCE ON COMPUTING, COMMUNICATION AND NETWORKING TECHNOLOGIES (ICCCNT) and will be published on IEEE Xplore soon
