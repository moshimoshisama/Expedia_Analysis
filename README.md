# Expedia_Analysis
Topic: **Travel Preferences During the Covid-19 Recovery Period: Data Analytics Models Run on Expedia Dataset**

--------

# Goal
Find patterns and trends behind by performing statistical analysis, graphical and numeric summaries. 
Apply machine learning analytic models based on our needs, such as ensemble models, Naive bayes models and logistic regression model.

--------

# Dataset
Datasets are provided by Expedia, which could be download from the following link:
https://www.dropbox.com/sh/qg5h8k1tas8cj7k/AACUraPI79TtPbYFZ2qllOhqa?dl=0

The paper described the dataset in details:
http://ceur-ws.org/Vol-2974/invited1.pdf

I did not upload the sampled dataset that I use into this repo, but similar dataset could be generated from 3_sample_data_prep.ipynb.

-------

# Instruction
Part1: Preliminary explore on the data with Pandas
Part2: Preliminary explore on the data with PySpark
Part3: Sample the data
Part4: Statistical Analysis based on Sampled dataset
Part5: Ensemble and NB models on click through and transaction prediction
Part6: Logistic Regression Model on click through and transanction prediction

# Model Results
|Model/Marco F1 Score |	Transaction Negative |	Transaction Positive |	Transaction Accuracy |	Click Through Negative |	Click Through Positive |	Click Through Accuracy|
|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|
|Random Forest |	0.61 |	0.71 |	0.67 |	0.75 |	0.77 |	0.76|
|Bagging |	0.62	0.66 |	0.64 |	0.63	0.70 |	0.67|
|Extra Trees |	0.63 |	0.65 |	0.64 |	0.63 |	0.69	0.66|
|Ada Boosting |	0.57 |	0.69 |	0.64 |	0.56 |	0.72 |	0.66 |
|Gradient Boosting	0.57	0.71	0.65	0.55	0.73	0.66


