# Rock vs Mine Prediction using Logistic Regression

This project uses Logistic Regression to classify sonar signals as either **rock** or **mine**, based on data from the **UCI Machine Learning Repository**. The model is trained on numerical features derived from sonar signal frequencies to predict the nature of the object detected.

## Project Overview
This Python project demonstrates a simple binary classification task using Logistic Regression.  
By analyzing the sonar dataset, the model learns to distinguish between rocks and mines (metal cylinders) based on signal characteristics.

## Dataset
- **Name:** Sonar Dataset  
- **Source:** UCI Machine Learning Repository  
- **Format:** CSV file without headers  
- **Description:**  
  Each row contains 60 frequency-based numeric attributes followed by a label:  
  - R = Rock  
  - M = Mine  

## Technologies Used
- Python 3.x  
- NumPy  
- Pandas  
- Scikit-learn  

## Project Workflow
1. Load the dataset using Pandas  
2. Explore and analyze the data using `describe()` and `groupby()`  
3. Split the dataset into training and testing sets (90%-10%)  
4. Train the model using `LogisticRegression` from scikit-learn  
5. Evaluate model performance using accuracy scores for training and test data  
6. Predict whether a given sonar signal corresponds to a rock or mine  

## Author
Developed by **Saurabh**  
Feel free to connect or contribute to the project.
