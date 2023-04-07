Goal : To predict Housing Price using Population status in Boston Housing dataset.

Link : https://www.kaggle.com/datasets/puxama/bostoncsv

Linear Regression Using Python Scikit learn Hands-on-: Boston
Housing Prices Dataset
• Environment: Python 3 and Jupyter Notebook
• Library: Pandas
• Module: Scikit-learn

Understanding the Dataset
Before we get started with the Python linear regression hands-on, let us explore the dataset. We will be
using the Boston House Prices Dataset, with 506 rows and 13 attributes with a target column. Let’s take a
quick look at the dataset.

Let’s take a quick look at the dataset.
This data frame contains following columns:
• Crim: Per capita crime rate by town
• Zn: Proportion of residential land zoned for lots over 25,000 sq. ft.
• Indus: Proportion of non-retail business acres per town
• Chas: Charles River dummy variable (= 1 if tract bounds river; 0, otherwise)
• Nox: Nitrogen oxides concentration (parts per 10 million)
• Rm: Average number of rooms per dwelling
• Age: Proportion of owner-occupied units built before 1940
• Dis: Weighted mean of distances to five Boston employment centers
• Rad: Index of accessibility to radial highways
• Tax: Full-value property tax rate per $10,000
• Ptratio: Pupil–Teacher ratio by town
• Black: 1000(Bk – 0.63) ^2, where Bk is the proportion of Blacks by town
• Lstat: Lower status of the population (percent)
• Medv: Median value of owner-occupied homes in $1000s


In this Python Linear Regression example, we will train the model to predict the price.
Model Building
Now that we are familiar with the dataset, let us build the Python linear regression models.
Simple Linear Regression in Python
Consider ‘lstat’ as independent and ‘medv’ as dependent variables
Step 1: Load the Boston dataset
Step 2: Have a glance at the shape
Step 3: Have a glance at the dependent and independent variables
Step 4: Visualize the change in the variables
Step 5: Divide the data into independent and dependent variables
Step 6: Split the data into train and test sets
Step 7: Shape of the train and test sets
Step 8: Train the algorithm
Step 9: Retrieve the intercept
Step 10: Retrieve the slope
Step 11: Predicted value
Step 12: Actual value
Step 13: Evaluate the algorithm
