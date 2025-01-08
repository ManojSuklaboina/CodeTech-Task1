Name: Suklaboina Manoj
Company:CODTECH IT SOLUTIONS
id:CT6WDS17
domain:Data Analytics
duration:Nov/30/2024 to jan/15/2025


OVER VIEW OF THE PROJECT:
project:predictive modeling with linear regression

![image alt](https://github.com/ManojSuklaboina/CodeTech-Task1/blob/73d23905e4408b75cc2b3aa8123ddb489eb097c5/Screenshot%20(112).png)





objective:
The goal of the code is to perform simple linear regression on a dataset (Real estate.csv) to analyze the relationship between an independent variable (x) and a dependent variable (y). The model’s performance is evaluated using metrics like R-squared score and Mean Squared Error (MSE), and the results are visualized.

 

Technologies Used in the Code:
Python Programming Language:The entire code is written in Python, a versatile and widely-used programming language for data science and machine learning.
Pandas Library:Used for loading and manipulating the dataset (Real estate.csv).
NumPy Library:Converts data into arrays for numerical operations.
Scikit-learn Library:

Model Selection: To split data into training and testing sets.
Linear Regression: To build and train the linear regression model.
Performance Metrics: R2 square and mean squared error
Matplotlib Library:visualise the model performance


1. Import Libraries: 
   - Use tools for working with data, training models, and creating plots.

2. Load Data: 
   - Read a CSV file containing real estate data and check its shape (number of rows and columns).  

3. Select Features:  
   - Choose one column as the input (independent variable) and another as the target (dependent variable).  

4. Prepare Data:  
   - Convert the selected columns into arrays and reshape them so the model can use them properly.

5. Split Data: 
   - Divide the data into two parts:  
     - **Training set:** Used to teach the model.  
     - **Testing set:** Used to evaluate how well the model has learned.  

6. Train the Model:
   - Create a linear regression model and train it using the training data.  

   Evaluate the Model:
   - Check how well the model performs on both the training and testing data using an \(R^2\) score.  
   - A score close to 1 means the model predicts well; a score near 0 means poor performance.  

8. Calculate Error:  
   - Find the mean squared error (MSE) to see how much the predicted values deviate from the actual values.  
   - Lower values of MSE indicate better performance.  

9. Visualize Results: 
   - Use a scatter plot to show actual test data points and a line plot to show predicted results.  
   - Compare these to visually check the model’s accuracy.  

10. Model Insights: 
    - If the testing score is much lower than the training score, the model may be overfitting.  
    - Improve performance by using techniques like feature scaling or a larger dataset.  



  
 

