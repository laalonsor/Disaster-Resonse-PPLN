# Disaster Response Pipeline
Disaster Response Pipeline as part of Udacity Nanodegree: Data and Software Engineering

Figure8 has provided data from real emergency calls or disaster situations. The obective of this project is to try to recognize these categories in order to direct the most adequate and quicker response to the emergency messages. Using ML (Random Forest Classifier) we shold be able to predict the category.

### The process is as follow:
Data Processing: Assessing and cleaning the data, so that it can be utilized by machine learning algorithms.

Model training Data was passed through a pipeline and a prediction model is made.

Prediction and Visualization Making a web app for prediction and visualization, where user can see the outcome from emergency messages and the resulting category.

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/
