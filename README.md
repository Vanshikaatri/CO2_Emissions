**CO2 Emissions Analysis with Machine Learning**

**Overview**
This project demonstrates the use of machine learning algorithms to analyze and predict CO2 emissions of vehicles. The dataset contains features like engine size, fuel consumption, and cylinders that are used to predict or classify CO2 emissions into categories. The project applies two machine learning algorithms:

Naive Bayes Classification for categorizing CO2 emissions into low, medium, or high.
Support Vector Machine (SVM) for predicting the exact CO2 emissions (continuous values).
The project uses R and popular libraries like e1071, caret, and ggplot2 for model building, evaluation, and visualization.

**Key Features**
Naive Bayes: Applied for classification of CO2 emissions into categories (Low, Medium, High).
Support Vector Machines (SVM): Used for predicting continuous CO2 emissions values.
Data Preprocessing: Includes handling missing data, feature engineering, and normalization.
Visualization: The project includes plots to evaluate model performance, such as confusion matrices for classification and scatter plots for regression results.

**Project Workflow**
Load the Dataset: Import the co2.csv dataset.
Preprocess the Data: Handle missing values, convert columns to appropriate data types, and create a target variable (CO2_Category) for classification.
Train Models:
Train a Naive Bayes model to predict emission categories.
Train a Support Vector Machine (SVM) model for predicting CO2 emission values.
Evaluate Models:
Evaluate classification performance using confusion matrix for Naive Bayes.
Evaluate regression performance using Root Mean Square Error (RMSE) for SVM.
Visualize Results: Create plots to visualize the performance of both models.

**Results**
Naive Bayes: Accurately classifies vehicles into emission categories with a confusion matrix.
SVM: Predicts the CO2 emissions with an RMSE value, showing how close the model is to the actual values.

**Conclusion**
This project highlights the practical application of machine learning in environmental data analysis. By leveraging Naive Bayes for classification and SVM for regression, we can predict and classify CO2 emissions based on vehicle attributes. This analysis can help provide insights into vehicle emissions and contribute to sustainability goals.

