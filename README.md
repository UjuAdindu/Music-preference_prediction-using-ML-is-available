
Navigation Menu

Code
Issues
This project predicts user music preference based on their listening habits using machine learning techniques.

 0 stars
 1 fork
 1 watching
 1 Branch
 0 Tags
 Activity
Public repository
Uchenna-eucharia/Music-Preference-Prediction-using-ML
Folders and files
Name	
Latest commit
Uchenna-eucharia
Uchenna-eucharia
7 hours ago
History
README.md
7 hours ago
music prediction.ipynb
8 hours ago
music.csv
8 hours ago
Repository files navigation
README
Music Preference Prediction using Machine learing
Table of Contents
Project Description

Dataset

Tools

Exploratory Data Analysis

Features

Model Building

Model Performance

Project Description
This project predicts user music preferences based on their listening habits using machine learning techniques. It explores supervised learning algorithms to analyze patterns and classify music genres effectively.

Dataset
This dataset contains information about a sample of individuals and their music preferences, including age, gender, and genre. data source: kaggle

Tools
The language used is python the tool used is Google colab

Exploratory Data Analysis
Getting a sense of the data types (numerical, categorical).
Checking the size of the dataset (number of rows and columns).
Understanding the meaning and relevance of each feature (column).
Features
Age: Represents the age of the individual. This is a numerical variable.
Gender: A binary categorical variable, where:
1 = Male
0 = Female
Genre: A categorical variable that represents the genre of music preferred by the individual. The possible values are:
Hip-hop
Jazz
Classical
Dance
Acoustic
Model Building
Data Splitting: The dataset was split into 80% training and 20% testing using train_test_split.

Model Training: A model was selected and trained using the training data (feature_train, target_train).

Prediction: Predictions were made on the test set (feature_test).

Evaluation: Model performance was evaluated using relevant metrics (e.g., accuracy).

Model Performance
Evaluation Metric: The model's performance was evaluated using accuracy.

Results: The model achieved an accuracy score of 0.75, meaning it correctly predicted 75% of the test data.
