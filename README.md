# Student-Performance-Prediction
This project uses machine learning regression models to predict student academic performance based on demographic and academic factors.
Gradio link: https://7ec911dd0e4d380ee8.gradio.live/

The notebook explores multiple machine learning models, compares their performance, performs hyperparameter tuning, and analyzes feature importance to understand which factors influence student outcomes.

Additionally, the project includes a Gradio-based interface to visualize model results and performance plots.

The dataset contains information about student demographics and exam performance.

Input Features

Gender

Race / Ethnicity

Parental Level of Education

Lunch Type

Test Preparation Course

Reading Score

Writing Score

Target Variable

Math Score

The goal is to predict the Math Score based on the other attributes.

The following regression models were implemented and compared:

1️. Linear Regression

A baseline regression model used to understand the linear relationship between features and the target variable.

2️. Random Forest Regressor

An ensemble learning method that uses multiple decision trees to improve prediction accuracy and reduce overfitting.

3️. Gradient Boosting Regressor

A boosting-based ensemble model that builds trees sequentially to minimize prediction errors.

4️. XGBoost Regressor

An optimized gradient boosting algorithm designed for high performance and scalability.

5️. Stacking Ensemble Model

Hyperparameter Tuning

To improve model performance, GridSearchCV was used for:

Random Forest Regressor

Gradient Boosting Regressor

This process searches for the best combination of parameters such as:

Number of trees

Maximum features

Minimum samples per leaf

Minimum samples per split

The models were evaluated using the following metrics:

RMSE (Root Mean Squared Error)

Measures the average prediction error.

Lower RMSE indicates better predictions.

R² Score (Coefficient of Determination)

Indicates how well the model explains the variance in the data.

Values range between 0 and 1, where higher values indicate better performance.

<img width="809" height="165" alt="image" src="https://github.com/user-attachments/assets/3887baaa-1d4d-4e78-93c4-6a3980672836" />
