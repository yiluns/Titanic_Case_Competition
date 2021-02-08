# Titanic_Case_Competition

**This Titanic case competition's goal is to predict whether a passenger would survive the crash of Titanic based on different features such as passenger class, gender, fare fee, and so on. It is a binary classification problem, so I will use classification models such as logistic regression, support vector machine, random forest, K-Nearest Neighbors, and XGBoost to compare which model performs best. I will also use Randomized Search CV and  Grid Search CV to fine-tune hyperparameters to improve model performance.**

This notebook is divided into the following parts which basically follow the general data science methodogy:

1. **Data Importing**: Read the data file and combine training and test data together

2. **Exploratory Data Analysis**: In this section, I will understand the dataset by using .corr(), .describe(), pivot table, and visualization tools. I will find relationships between variables and some interesting insights from the data.

3. **Feature Engineering**: There are less than 15 variables in this dataset, so I will create more variables by creating dummy variables and customizing a couple of features. Hopefully, the new features created could help boost the model performance.

4. **Data Processing**: Standardize numerical variables. Getting data ready for modeling

5. **Model Building**: I will use baseline models without fine-tuning hyperparameters

6. **Hyperparameters Fine-tuning**: I will fine-tune hyperparameters of the models I use

7. **Results**: I will compare models' performance and use the best model to predict the test dataset.

**For the final model, I chose the XGBoost Classifier which had an accuracy score of 84.92% on the training dataset. I used this model to predict the survival status for people in the test set, and the final accuracy score was 77%. Considering the fact that I just started learning data science and finished this project in less than a week, I am pretty satisfied with the score. There are probably some more feature engineering I could do to improve the final score!**
