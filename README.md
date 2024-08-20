**NAME :** SYED ARSHIYA ALEEM

**Company:** CODTECH IT SOLUTIONS

**ID:** CT6ML1166

**Domain:**  MACHINE LEARINING

**Duration:**  10TH JULY 2024 TO 25TH AUGUST 2024

**Mentor:**  MUZAMMIL AHMED


**Overview of the Linear Regression on House Prices Project** 

This project serves as a foundational exercise in applying linear regression techniques to real-world datasets, enabling better understanding of the relationships between variables in predicting outcomes.
![image](https://github.com/user-attachments/assets/2cfe6282-e6df-440f-b558-bdae744c89eb)           ![image](https://github.com/user-attachments/assets/ca0e238e-6906-4ad9-9643-7d91af3f0fc6)     ![image](https://github.com/user-attachments/assets/d70e1486-3295-4a06-aec0-5beaea6dfa43)     ![image](https://github.com/user-attachments/assets/f4bba127-2934-4e02-9bd6-4b881cbc0168)
![image](https://github.com/user-attachments/assets/d849948f-a5af-444e-b542-0b42880cef7a)                ![image](https://github.com/user-attachments/assets/7c9cbc74-67a1-46c0-9749-76be6a480adf)              ![image](https://github.com/user-attachments/assets/026fe99e-75a4-4b11-948d-8c036a8d6089)                   ![image](https://github.com/user-attachments/assets/fb10248e-44c8-40bd-a32a-cbf79c4d2479)                       ![image](https://github.com/user-attachments/assets/09a54b08-78ef-40fb-8e5e-d540b37e16bb)









**Objective**

The objective of this project is to build a predictive model using linear regression to estimate the prices of houses based on various features. The model is designed to understand the relationship between house prices and different factors such as area income, house age, the number of rooms, the number of bedrooms, and area population.

**Key Activities**

**Data Collection and Preprocessing:**


The dataset used for this project is USA_Housing.csv, which includes data on various features such as average area income, average area house age, average area number of rooms, average area number of bedrooms, area population, and house prices.
The data was loaded and explored to understand its structure and distribution.

**Exploratory Data Analysis (EDA):**


Performed pairwise plotting of variables using seaborn to visualize relationships between different features.
Created a correlation matrix to identify which features are most correlated with the house prices.

**Model Development:**


The dataset was split into training and testing sets using the train_test_split function from sklearn.
A linear regression model was built using the LinearRegression class from sklearn.
The model was trained on the training set and then used to predict house prices on the test set.

**Model Evaluation:**


The model's coefficients were analyzed to understand the impact of each feature on house prices.
Predictions were compared against actual house prices using scatter plots.
A residual plot was created to assess the model's performance and check for any patterns in the residuals that might indicate a poor fit.

**Technologies Used**


**Programming Languages:** Python

**Libraries:**


**Pandas**: For data manipulation and analysis.

**NumPy:** For numerical computations.

**Seaborn and Matplotlib:** For data visualization.

**Scikit-learn:** For implementing linear regression and other machine learning tasks.


**Key Insights**


**Correlation Analysis:** The correlation matrix revealed that certain features such as average area house age and the number of rooms have a significant positive correlation with house prices.

**Feature Impact:** The coefficients from the linear regression model indicated that average area house age and the number of rooms are the most influential features in determining house prices.

**Model Performance:** The residual plot and scatter plot of actual vs. predicted prices provided insights into the model's accuracy and highlighted areas where the model could be improved.
