
# Titanic Survival Analysis
This project aims to analyze factors influencing survival rates from the infamous sinking of the RMS Titanic on April 15, 1912. The Titanic, deemed "unsinkable," tragically sank after striking an iceberg, leading to the loss of 1,502 out of 2,224 passengers and crew due to insufficient lifeboats.
This project is implemented on common machine learning algorithms of XGBoost, Random Forest Classifier, KNeighborClassifier etc. 
This project envisions a comparative study between various algorithms also.
Maximum accuracy availed by the model is 88% and Kaggle public score is 0.7790.

### Dataset
The dataset used for this analysis contains passenger and crew information from the Titanic's ill-fated voyage. Key features include:

PassengerId: Unique ID for each passenger
Pclass: Ticket class (1st, 2nd, 3rd)
Name: Passenger name
Sex: Gender
Age: Age in years
SibSp: Number of siblings or spouses aboard
Parch: Number of parents or children aboard
Ticket: Ticket number
Fare: Fare paid
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Survived: Survival status (0 = No, 1 = Yes)

### Data Splits
Training Data: Used to build the model and contains 68% of the data.
Test Data: Used to evaluate the model’s performance and contains 32% of the data.
Objectives
Identify key factors affecting survival chances.
Evaluate model performance using metrics such as accuracy, R² score, and Mean Absolute Error (MAE).
Explore the repository to see detailed analyses, model training processes, and results of the Titanic survival prediction.

### Reference Data:
Will Cukierski. (2012). Titanic - Machine Learning from Disaster. Kaggle. https://kaggle.com/competitions/titanic
