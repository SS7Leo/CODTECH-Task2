**Name:** SAI SUSANTH R

**Company:** CODTECH IT SOLUTIONS

**ID:** CT08DS1634

**Domain:** Data Science

**Duration:** 5th June 2024 to 5th July 2024

**Mentor:** G.SRAVANI


##  Overview of the project

###  Project: PREDICTIVE MODELING WITH LINEAR REGRESSION ON "CALIFORNIA HOUSING" DATASET
Train a linear regression model using the training data to find the best-fit line that predicts the target variable. Then, use the trained model to predict values on the test data and evaluate its performance using metrics like mean squared error and R-squared.

###  Key Activities
  - Data Collection and Preprocessing: Gather data, clean it (handle missing values, outliers), and preprocess (normalize or scale features if necessary).

  - Feature Selection: Choose the relevant features that will be used as predictors in the model.

  - Data Splitting: Split the dataset into training and testing sets to evaluate the model's performance.

  - Model Training: Initialize and train the linear regression model using the training data.

  - Model Prediction: Use the trained model to make predictions on the testing set.

  - Model Evaluation: Assess the model's performance using metrics such as mean squared error (MSE) and R-squared (R²).

  - Model Tuning: Adjust model parameters or refine features to improve performance if necessary.

  - Visualization: Visualize the regression line, actual vs. predicted values, and residuals to understand model behavior and diagnose issues.

  - Deployment: Deploy the model for use in real-world applications, ensuring it performs well on unseen data.

  - Monitoring and Maintenance: Continuously monitor the model's performance and update it as needed to maintain accuracy and relevance.

###  Technologies and Libraries Used
  - Python: The programming language used to write the script.

  - Libraries:

      pandas: For data manipulation and analysis.

      numpy: For numerical operations and array manipulation.

      matplotlib: For creating static, interactive, and animated visualizations in Python.

      scikit-learn: For machine learning, including tools for model building, evaluation, and dataset loading.

  - Machine Learning Model:

      Linear Regression: A regression model used to predict a continuous target variable based on one or more predictor variables.
    
  - Dataset:

      California Housing Dataset: A dataset included in scikit-learn for housing prices in California.
    
  - Data Handling:

      DataFrame: Using pandas DataFrame to store and manipulate tabular data.

      Train-Test Split: Using scikit-learn to split the dataset into training and testing sets.

  - Model Evaluation Metrics:

      Mean Squared Error (MSE): For measuring the average squared difference between the predicted and actual values.

      R-squared (R²): For measuring the proportion of variance in the dependent variable that is predictable from the independent variable(s).

  - Data Visualization:

      Scatter Plot: To visualize the relationship between median income and median house value.

      Regression Line: To show the fit of the linear regression model on the training data.

      Histogram: To visualize the distribution of residuals.

###  Output

![Screenshot 2024-07-03 082720](https://github.com/SS7Leo/CODTECH-Task2/assets/140295932/54086d67-769b-4684-b9d2-05001b978eb8)

![Screenshot 2024-07-03 082602](https://github.com/SS7Leo/CODTECH-Task2/assets/140295932/9b9c4cf5-243a-4707-b7a6-bd539b020714)

![Screenshot 2024-07-03 082614](https://github.com/SS7Leo/CODTECH-Task2/assets/140295932/53689fc8-cef9-4890-b7b2-3811d9825862)

![Screenshot 2024-07-03 082626](https://github.com/SS7Leo/CODTECH-Task2/assets/140295932/3874ef32-d8f7-44ac-bf43-cbe6c47e7631)

###  Program Explanation
  - Importing Libraries: Essential Python libraries for data manipulation (pandas), numerical operations (numpy), data visualization (matplotlib), and machine learning (scikit-learn) are imported.

  - Loading the Dataset: The California Housing dataset is fetched using fetch_california_housing() and stored in a pandas DataFrame.
    
  - Displaying Initial Data: The first few rows of the dataset are displayed to get an overview of the data structure.

  - Feature and Target Selection: The feature MedInc (median income) is selected as the predictor variable (X), and MedHouseVal (median house value) is selected as the target variable (y).

  - Data Splitting: The dataset is split into training and testing sets using train_test_split(), with 80% for training and 20% for testing.

  - Model Initialization and Training: A linear regression model is created and trained on the training data using LinearRegression().fit().

  - Predictions and Evaluation: Predictions are made on the test set, and the model's performance is evaluated using mean squared error (MSE) and R-squared (R²) metrics.

  - Visualization:

        Regression Line: The regression line is plotted against the training data to visualize the model fit.
    
        Actual vs Predicted Values: Scatter plots for actual and predicted values on the test set are created to compare the model's predictions against the true values.
    
        Residuals Distribution: A histogram of the residuals (errors) is plotted to analyze the distribution of prediction errors.
    
###  Key Insights
  - Model Performance: The MSE and R² values provide quantitative measures of the model's accuracy. A lower MSE indicates fewer prediction errors, while a higher R² suggests a better fit of the model to the data.

  - Linear Relationship: The visualization of the regression line and the scatter plots help in understanding the linear relationship between median income and median house value. The fit of the regression line shows how well the model captures this relationship.

  - Residual Analysis: The distribution of residuals indicates whether the model errors are randomly distributed. A normal distribution of residuals suggests that the model's assumptions are met, and it is appropriately capturing the underlying data patterns.

  - Predictive Insights: The scatter plot of actual vs predicted values helps in identifying how well the model generalizes to unseen data. Clustering of points around the regression line in the test data scatter plot indicates good predictive performance.

  - Interpretability: Using a single feature (median income) makes the model easy to interpret. It shows how changes in median income influence house values in California, providing valuable insights for stakeholders.









