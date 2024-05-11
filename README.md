# IBM-EDA
EDA - using IBM HR dataset and prediction of employee attrition 


# Introduction:
This report presents the findings and insights from a project aimed at analyzing factors contributing to employee attrition and building a predictive model to identify employees most likely to leave the company. The project utilized a dataset obtained from IBM HR Analytics, containing information on various employee attributes.

# Data Cleaning and Preprocessing:
The dataset was thoroughly cleaned and preprocessed to prepare it for analysis. This involved:
Checking for missing values and duplicates (none were found).
Encoding categorical variables using LabelEncoder to convert them into numerical format.
Conducting preliminary analysis to understand the distribution and summary statistics of the dataset.
Exploratory Data Analysis (EDA):

# Age Distribution and Attrition:
The age distribution of employees was visualized using a histogram, revealing a diverse range of ages.
A boxplot was used to analyze the relationship between age and attrition, indicating that younger employees were more likely to leave the company.

# Attrition Analysis:
The count of attrition cases was visualized using a bar plot, revealing that approximately 16% of employees had left the company.
Attrition rates were further explored across different departments, highlighting variations in attrition rates among departments.

# Factors Influencing Attrition:
Several factors influencing attrition were analyzed, including job role, education field, job level, marital status, and overtime.
Bar plots and countplots were used to visualize attrition trends across these factors, providing insights into which groups were more likely to leave.

# Random Forest Classifier:
A Random Forest Classifier was chosen as the predictive model for employee turnover prediction.
Random Forest is an ensemble learning method that builds multiple decision trees during training and outputs the mode of the classes (classification) or the mean prediction (regression) of the individual trees.
It is robust to overfitting, handles non-linear relationships well, and is capable of handling large datasets with high dimensionality.
The classifier was trained on the preprocessed dataset to predict employee attrition based on various input features.

# Performance Evaluation Metrics:
Several performance evaluation metrics were used to assess the effectiveness of the predictive model, including:
Accuracy Score: Measures the overall accuracy of the model in predicting employee attrition.
Classification Report: Provides a summary of different performance metrics (precision, recall, F1-score) for each class (attrition and non-attrition).
Confusion Matrix: Visualizes the true positives, true negatives, false positives, and false negatives of the model's predictions.
ROC AUC Score: Measures the area under the Receiver Operating Characteristic curve, indicating the model's ability to discriminate between classes.

# Conclusion:
The project provided valuable insights into the factors influencing employee attrition and demonstrated the effectiveness of using a Random Forest Classifier for predictive modeling. By leveraging these insights and the predictive model, organizations can proactively address employee turnover challenges and implement targeted retention strategies for a more sustainable and productive workforce.
