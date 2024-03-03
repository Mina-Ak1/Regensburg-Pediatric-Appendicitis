# Regensburg-Pediatric-Appendicitis
Cleaning and exploring the data from Children’s Hospital St. Hedwig in Regensburg, Germany in order to build a model to predict the appendicitis diagnosis
https://archive.ics.uci.edu/dataset/938/regensburg+pediatric+appendicitis
This repository holds the data from a cohort of **pediatric patients with suspected appendicitis admitted with abdominal pain to Children’s Hospital St. Hedwig in Regensburg, Germany, between 2016 and 2021**. <br>

Each patient has (potentially multiple) ultrasound (US) images, aka views, tabular data comprising laboratory, physical examination, scoring results and ultrasonographic findings extracted manually by the experts, and three target variables, namely, diagnosis, management and severity. <br>

This data has 782 rows and 58 columns. There is a combination of binary, categorical, integer and continuous predictor columns. <br>

From column 25 onwards there are multiple columns with na values majorly. These columns are also very specialized and we might not be able to interprete them as good as the other columns. Therefore we will make a selection of the features that are good candidates for our model based on the number of NA values and colinearity.
