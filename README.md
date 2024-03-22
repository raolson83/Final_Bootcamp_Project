# Final_Bootcamp_Project
This the final machine learning project for data analytics bootcamp.

# Overview
A wine company is seeking a new way to categorize their immense collection of wine. They wish to categorize it by the three different cultivars in which they receive wine.
Our group has been tasked to create a machine learning model that can analyze the wines based on their 13 main components, and accurately predict which cultivar the wine belongs too. 
To best serve our client we decided to have a competition of models. We will present 4 models to compete and at the end the model which is most accurate will be given to the company.
Round 1
Each model will be presented, showing how its built and the accuracy it delivers on predicting data.
Improvements
The models will have a chance to add hyperparameter tuning to increase accuracy
Round 2
The models will present their prediction accuracy and a wine

# Background Information
Data:
Results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. 
The analysis determined the quantities of 13 constituents found in each of the three types of wines.
Data for this project was sourced from UC Irvine and posted publicly to their Machine Learning Repository, found here: https://archive.ics.uci.edu/dataset/109/wine

# Process
ETL
The data will be extracted directly from sklearn.datasets. 
<ul>
  <li><code>from sklearn.datasets import load_wine
</code></li>
</ul>

