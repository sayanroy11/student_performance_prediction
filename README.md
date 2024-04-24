# student_performance_prediction
Predicting a student's performance in secondary education (high school)

In this problem, we try to predict a student's final year(3rd period) grade. The dataset consists of features like student's previous year grades, demographic, social and school related features collected by using school reports and questionnaires.

Methodology:
1. We start by reading the data into a dataframe.
2. We apply feature engineering techniques like mutual info regression and select K best to get the list of important features that can be used in predicting the final score.
3. Then we do some preprocessing with the data such as encoding the categorical variables and standardizing the data columns that have higher values.
4. The data is then split into training and test sets. We use 20% of the data for testing and 80% for training.
5. Next we train our model with various regression algorithms like decision tree, random forest, SVR.
6. The prediction accuracy score is highest for random forest regression with a score of 0.833.
7. On applying cross validation, we get an average score of 0.877.
