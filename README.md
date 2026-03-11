# **Student Performance Prediction**

This project uses **machine learning regression models** to predict student academic performance based on demographic and academic factors.

**Gradio Demo:**  
https://7ec911dd0e4d380ee8.gradio.live/

---

## **Project Overview**

The notebook explores multiple machine learning models, compares their performance, performs **hyperparameter tuning**, and analyzes **feature importance** to understand which factors influence student outcomes.

Additionally, the project includes a **Gradio-based interface** to visualize model results and performance plots.

The dataset contains information about **student demographics and exam performance**.

---

## **Dataset Description**

### **Input Features**

- Gender  
- Race / Ethnicity  
- Parental Level of Education  
- Lunch Type  
- Test Preparation Course  
- Reading Score  
- Writing Score  

### **Target Variable**

- **Math Score**

The goal of this project is to **predict the Math Score based on the other attributes**.

---

## **Machine Learning Models Used**

The following regression models were implemented and compared:

### **1. Linear Regression**
A baseline regression model used to understand the **linear relationship between features and the target variable**.

### **2. Random Forest Regressor**
An **ensemble learning method** that uses multiple decision trees to improve prediction accuracy and reduce overfitting.

### **3. Gradient Boosting Regressor**
A **boosting-based ensemble model** that builds trees sequentially to minimize prediction errors.

### **4. XGBoost Regressor**
An optimized **gradient boosting algorithm** designed for high performance and scalability.

### **5. Stacking Ensemble Model**
A **meta-learning approach** where predictions from multiple models are combined to improve overall performance.

---

## **Hyperparameter Tuning**

To improve model performance, **GridSearchCV** was used for:

- Random Forest Regressor  
- Gradient Boosting Regressor  

This process searches for the best combination of parameters such as:

- Number of trees  
- Maximum features  
- Minimum samples per leaf  
- Minimum samples per split  

---

## **Model Evaluation Metrics**

The models were evaluated using the following metrics:

### **RMSE (Root Mean Squared Error)**

- Measures the **average prediction error**
- Lower RMSE indicates **better predictions**

### **R² Score (Coefficient of Determination)**

- Indicates how well the model **explains the variance in the data**
- Values range between **0 and 1**
- Higher values indicate **better performance**

---

## **Results Visualization**

Below is a sample visualization generated during the analysis:

<img width="809" height="165" alt="Model Results" src="https://github.com/user-attachments/assets/3887baaa-1d4d-4e78-93c4-6a3980672836" />

---

## **Conclusion**

This project demonstrates how **machine learning techniques** can be used to predict student performance and analyze factors affecting academic success.

By comparing multiple regression models and applying **ensemble learning techniques**, the project highlights how advanced models can achieve **more accurate predictions and deeper insights into student performance factors**.
