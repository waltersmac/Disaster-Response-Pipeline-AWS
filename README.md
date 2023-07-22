# Disaster Response Pipeline for Figure Eight

## Project Description
In this project, I applied data engineering skills to analyse disaster data from Figure Eight to build a model for an API that classifies disaster messages. I created an Extract, Transform and load (ETL) process that takes in the messages and categories datasets and merges the two datasets, cleans the data and stores it in a SQLite database. I then created a machine learning pipeline to categorise these events so that I could send the messages to an appropriate disaster relief agency. My project also includes a web app where an emergency worker can input a new message and get classification results in several categories. The web app will also display visualisations of the data.


## Project Organisation

    ├── Makefile           <- Makefile with commands like `make requirements`
    ├── README.md          <- The top-level README for developers using this project.
    ├── app                <- Flask application scripts
    ├── data               <- Hold the messages and category csv files, also the process_data script
    ├── figures            <- Saved images from the notebooks and flask app webpage
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    └── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
                              generated with `pip freeze > requirements.txt`


## Resources Used for This Project
* Udacity Data Science Nanodegree: [here](https://www.udacity.com/course/data-scientist-nanodegree--nd025) <br>
* lightgbm: LGBMClassifier documentation: [here](https://lightgbm.readthedocs.io/en/latest/pythonapi/lightgbm.LGBMClassifier.html#) <br>
