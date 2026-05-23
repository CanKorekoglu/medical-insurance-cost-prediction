# Medical Insurance Cost Prediction using Polynomial Regression

### Project Goal
This project aims to predict the annual medical insurance costs of individuals based on their demographic and physical features such as age, sex, body mass index (BMI), and smoking status.

### Technologies Used
* Python 3
* Pandas & NumPy (Data Manipulation)
* Scikit-Learn (Machine Learning Modeling & Evaluation)
* Matplotlib & Seaborn (Data Visualization)

### Approach and Methodology
1. **Data Preprocessing:** Categorical features (sex, smoker, etc.) were converted into numerical format using **One-Hot Encoding** to make them suitable for machine learning models. The *Dummy Variable Trap* was avoided to prevent multicollinearity.
2. **Baseline Model:** A standard Linear Regression model was trained to establish a performance baseline.
3. **Hyperparameter Tuning:** Polynomial Regression was applied to capture non-linear relationships in the data. Various polynomial degrees were tested to prevent overfitting.

### Results
The best performance was achieved using a Degree 2 Polynomial Regression, which successfully prevented overfitting while accurately predicting the medical insurance costs.
