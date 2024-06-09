# Titanic Survival Prediction using Random Forest Classifier

### Step 1: Load the Data 
The project begins with loading the Titanic dataset as CSV file using pandas library. The dataset contains information about individual passengers, such as their age, gender, ticket class, fare, cabin, and whether or not they survived. 

### Step 2: Explore the Data
Permormed Exploratory Data Analysis (EDA) to understand the structure and content of data. 
By using matplotlib.pyplot and seaborn libraries I visualized the data as follows:
1. Histogram plot to showcase Age distribution.
2. Bar chart to plot Suvival rate by Sex and Pclass

### Step 3: Preprocess the Data
This involves handling missing values, encoding categorical variables, and other preprocessing steps like droping unnecessary columns.
data cleaning contributes to improve the predictive performance of model.

### Step 4: Feature Selection
Selecting the features which are most relevant for predicting survival ['Pclass', 'Sex', 'Age', 'SibSp', 'Parch', 'Fare', 'Embarked'] and ['Survival'].

### Step 5: Model Building
I used a machine learnind algorith called Random Forest Classifier to build my model. 
First I imported required libraries. Then Split the data into training and validation sets. After that the model is trained and fit on the training set.
Lastly predictions are made using the Validation set.

### Step 6: Evaluate the Model
The output from the evaluation step provides us with the accuracy, precision, recall, and F1-score of the model.

### Conclusion
At a predictive accuracy of 82%, this model proves its potential to forecast the survival rate of Titanic Passengers.
This project offers insights on the important elements influencing survival rates during the Titanic accident in addition to demonstrating the useful application of machine learning algorithms on historical data.
