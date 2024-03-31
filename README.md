# Sentiment-Analysis-of-Movie-Reviews

In the dataset each record represents a movie-review pair with movie title, description, genres, duration, director, actors, users' ratings, review text, reviewer name, etc. The files contain the ML model to predict sentiment of the review text.

### Process for building the model:
1. EDA
2. Data Cleaning (stopwords, lower, etc.)
3. Data Preprocessing (text into vectors, feature scaling, encoding)
4. Trained Models (Data Metrics, Hyperparameter Tuning, etc.)

### Three best model I got is-

1). Logistic Regression model
2). Linear support vector machine
3). Complement naive bayes

### Comparision between these Three models before hyper parameter tunning

**model 1 Logistic regression**

Accuracy_train: 0.8546991378686957 Accuracy_test: 0.8097380684557287 F_1_train: 0.8962216509044165 F_1_test: 0.865012769062386

**model 2 Linear svm**

Accuracy_train: 0.9190094729991403 Accuracy_test: 0.8029567732604853 F_1_train: 0.9405576260791622 F_1_test: 0.8567623764689392

**model 3 Complement navie bayes​**

Accuracy_train: 0.8587888380912589 Accuracy_test: 0.7973967539771815 F_1_train: 0.8984509068637365 F_1_test: 0.8571881654659961

**From above I can say that Logistic regression is performing well**

###Comparision between these Three models after hyper parameter tunning

**model 1 Logistic regression**

Accuracy_train: 0.8546991378686957 Accuracy_test: 0.8097380684557287 F_1_train: 0.8962216509044165 F_1_test: 0.865012769062386

**model 2 Linear svm**

Accuracy_train: 0.8842510384946046 Accuracy_test: 0.8085810702233649 F_1_train: 0.916102731349368 F_1_test: 0.8624162624162625

**model 3 Complement navie bayes**

Accuracy_train: 0.8693545665640894 Accuracy_test: 0.7930258717660292 F_1_train: 0.9021919588075358 F_1_test: 0.8468635563798925

**From above I can say that Logistic Regression is performing well**
