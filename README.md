# -Prodigy_TrackCode_Task1-
🏠 House Price Prediction using Linear Regression
This project is part of Task 1 from the Prodigy Internship Program. It demonstrates a simple machine learning workflow using Python to predict house prices based on selected features from a dataset.

📁 Dataset
The dataset used is train.csv, which contains information about houses, including features like:
GrLivArea: Above ground living area (in square feet)
BedroomAbvGr: Number of bedrooms above ground
FullBath: Number of full bathrooms
SalePrice: Actual selling price (target variable)

📌 Objective
Explore the dataset and visualize relationships between features using Seaborn.
Train a Linear Regression model using sklearn to predict house prices.
Evaluate model performance using Mean Squared Error (MSE) and R² Score.
Visualize predictions vs. actual values.
Allow the user to input custom values (area, bedrooms, bathrooms) and predict the estimated house price.

🔧 Technologies & Libraries Used
Python
Pandas
Matplotlib
Seaborn
Scikit-learn

📊 Workflow Summary
1.Data Loading & Cleaning:

Read CSV file using Pandas.
Select key features and drop missing values.

2.Visualization:

Use Seaborn’s pairplot to visualize relationships between features.

3.Model Building:

Split data into training and testing sets.
Fit a Linear Regression model on the training data.

4.Model Evaluation:

Predict on the test set.
Calculate Mean Squared Error and R² Score.
Plot actual vs. predicted values for all three features.

5.Interactive Prediction:

User can input custom values for:
Living Area (sq ft)
Bedrooms
Full Bathrooms

The model predicts and displays the estimated house price.


