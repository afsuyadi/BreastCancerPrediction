# BreastCancerPrediction
An artificial intelligence program that is used to predict whether the sample data indicates cancerous cells from breast tissue

Problem Statement : The medical team needs support to predict whether the sample tissue that is analyzed is categorized as benign or malignant condition using computer programs.

Workflow :
1. Obtain the data
- the data is obtain from medical sampling in breast tissue
- the data contain a lot of features

2. Data processing and loading
- import the dependencies
- import the dataset from sklearn.datasets
- construct a desired array based from the dataframe
- conduct Exploratory Data Analysis based from the array
- Drop any null values

3. Model building and validation
- Extract the feature columns and targeted columns
- Build training data and testing data
- Validate the training & testing data using accuracy score
- Conduct model fitting

4. Build the predictive system
- Define the expected function
