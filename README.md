# Predicting customer сhurn from a company.

## Introduction:



### *Project Description:*
    Telecom operator TeleDom wants to combat customer churn.
    TeleDom needs a model that will predict whether a subscriber will terminate a contract.
    The operator's team collected personal data on some clients, information on their tariffs and services.
### *Project goal:*
    Train a model to predict customer churn based on the provided data.
### *Data Description:*
    Table contract_new.csv (contract information):
        - customerID — subscriber identifier;
        - BeginDate — contract start date;
        - EndDate — contract end date;
        - Type — payment type: once a year or twice a year or monthly;
        - PaperlessBilling — electronic payslip;
        - PaymentMethod — payment type;
        - MonthlyCharges — monthly expenses;
        - TotalCharges — subscriber's total expenses.

    Table personal_new.csv (customer personal data):
        - customerID — user identifier;
        - gender — gender;
        - SeniorCitizen — whether the subscriber is a pensioner;
        - Partner — whether the subscriber has a spouse;
        - Dependents — whether the subscriber has children.

    Table internet_new.csv (internet service information):
        - customerID — user identifier;
        - InternetService — connection type;
        - OnlineSecurity — blocking dangerous sites;
        - OnlineBackup — cloud file storage for data backup;
        - DeviceProtection — antivirus;
        - TechSupport — dedicated technical support line;
        - StreamingTV — streaming television;
        - StreamingMovies — movie catalog.

    phone_new.csv table (information about telephony services):
        - customerID — user ID;
        - MultipleLines — connecting a phone to multiple lines simultaneously.


### *Work plan:*
    Step 1. Loading data:
        - load the data
        - perform their initial inspection.
    Step 2. Exploratory analysis and data preprocessing
        - perform exploratory analysis of each data frame and, if necessary, perform preprocessing
    Step 3. Combining data
        - combine the selected features into one data frame by key.
    Step 4. Exploratory analysis and preprocessing of the combined data frame
        - perform exploratory analysis of the combined data frame
        - visualize the distribution of features and, if necessary, perform preprocessing
        - conduct correlation analysis.
        - draw conclusions about the available features: will they be needed for training the models.
    Step 5. Preparing data
        - prepare the data for training the model.
        - divide the data into two samples
    Step 6. Training machine learning models
        - train the models
        - select hyperparameters
    Step 7. Selecting the best model
        - select the best model
        - check its quality on the test sample
