# Titanic Survivor Prediction
![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/640px-RMS_Titanic_3.jpg)

This data science project aims to build a predictive model to answer the question: "What types of people were more likely to survive?" using passenger data from the Titanic disaster. We will analyze various attributes of the passengers, such as their names, ages, genders, socio-economic classes, and more, to predict their likelihood of survival.

## Dataset Information
The dataset used in this project contains information about the passengers aboard the Titanic during its ill-fated voyage. It includes a range of features, including passenger names, ages, genders, socio-economic classes, cabin information, ticket details, and survival status.

### Data Dictionary
| Variable | Definition | Key |
|----------|------------|-----|
| survival | Survival status | 0 = No, 1 = Yes |
| pclass   | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd |
| sex      | Gender |
| age      | Age in years |
| sibsp    | Number of siblings/spouses aboard the Titanic |
| parch    | Number of parents/children aboard the Titanic |
| ticket   | Ticket number |
| fare     | Passenger fare |
| cabin    | Cabin number |
| embarked | Port of embarkation | C = Cherbourg, Q = Queenstown, S = Southampton |

## Objective
The main objective of this project is to develop a predictive model that can accurately determine the likelihood of survival for passengers based on their individual characteristics. By analyzing historical data and identifying patterns, the model will provide insights into the factors that influenced survival chances during the Titanic disaster.

## Approach
The project will involve several steps, including:
- **Data Preprocessing:** Handling missing values and cleaning the dataset.
- **Exploratory Data Analysis:** Analyzing data to understand trends and relationships.
- **Feature Engineering:** Creating new features to improve model performance.
- **Model Selection:** Exploring various machine learning algorithms, such as logistic regression, decision trees, random forests, and gradient boosting.
- **Evaluation:** Assessing model performance to determine the most effective method for predicting survival outcomes.