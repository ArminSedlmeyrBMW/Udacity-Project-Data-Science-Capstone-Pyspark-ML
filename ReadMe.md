# PySpark ML Project (Capstone)
This README file includes a summary of the project, and an explanation of the files in the repository.
link to github repo: https://github.com/ArminSedlmeyrBMW/Udacity-Project-Data-Science-Capstone-Pyspark-ML

### Project Motivation
I am a Udacity student who is doing the project Capstone project within this repo.

### Summary of the project
[**Why?**](https://www.smartinsights.com/digital-marketing-strategy/online-value-proposition/start-with-why-creating-a-value-proposition-with-the-golden-circle-model/)
The main goal of this project is to predict if a user will churn.

**How?**
1. This project takes data from a fictive music streaming service called sparkify
2. Then the data is wrangled and explored
3. Then the data is used to do feature engineering
4. Then three different ML-Models are calculated
5. Then the ML-Models are compared regarding to their power of prediction for the label if a user churns or not

**What?**
Reading in user behaviour data so we can classifiy if the user tends to churn, or not.

### Explanation of the files in the repository
data  
|- medium-sparkify-event-data.json # data to process, possible features and labels (medium size)
|- mini_sparkify_event_data.json # data to process, possible features and labels (mini size)

ML  
|- PySpark ML Notebook.html, the code and output which builds and evaluates the ML-model as html-file
|- PySpark ML Notebook.ipynb, the code and output which builds and evaluates the ML-model as ipynb-file
README.md

### Installations required:

- pyspark
- seaborn
- scipy
- pandas
- datetime
- re
- numpy
- matplotlib
- ibmos2spark
- os

### Instructions (how to run the notebook):
Notebook Options (boolean variables to choose):
show=False #Decide, wheter it makes sense, to show outputs of pyspark df's. will be slow, but good to unterstand certain steps
optimize=False #optimize grid-cv-search? will be slow, but proably better model performance
model_eval=True #Choose whether you like to see model evaluations.
plot=True #Choose if you want to see any EDA-Visualizations

### Summary
Please read my blog-post for this:
https://medium.com/p/54098f3cf6f5/
