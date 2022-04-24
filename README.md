# SC1015-Data-Science-Project
Mini project for SC1015 Intro to Data Science and Artificial Intelligence. Done by Aryan, Hon Joo and Adrian.


Hello! We are Team 10, and our project aimed at identifying the causes of flight delays, and whether we could prevent them or not. Through our project, we also hope to provide recommendations to passengers and airports as to how they can reduce delays.

---

## Contributors:

1.Data Prep: @Teddies1 (Hon Joo)
2.Exploratory Data Analysis: @Adrenaline1560 (Adrian)
3.Machine Learning: @aryans1204 (Aryan)

---

## Our Dataset: 

We have used the 2018 US Flights dataset, which is a comprehensive dataset containing more than 7 million rows and 13 columns representing different features.

---

## Data Prep: 

Since our dataset was so large, we had to choose which useful information to extract from this dataset. We found that there were multiple missing values, so we removed these missing values from the dataset. Further, we encoded the categorical variables like airports and carriers as indexed numbers. We will keep a dictionary mapping these unique indexes to the string names, for future reference.

---

## Exploratory Data Analysis:

Now that we had cleaned our dataset, we were ready to do some basic exploration on the dataset. At this point, we tried finding the correlations between different features, removed outliers in the departure delays, studied the correlation between departure delays and arrival delays, and created histograms to study airports and airlines with highest delays. From our analysis, we concluded that [NAS_DELAY, LATE_AIRCRAFT_DELAY, ORIG, DEST, OP_CARRIER, CARRIER_DELAY] had the highest correlations with the departure delay. So, we'll be using these columns as the features for our prediction task.

---

## Machine Learning:

For our machine learning part, we used a variety of models, from Linear regression, Support Vector machines, neural network, and XGBoost. Using a 80-20 train test aplit, we trained on each of these models, and found that the XGBoost achieved the lowest training error while the neural network overfitted the least. Similarly, we found that in general our prediction models had not done very well in predicting the departure delays.

---
 
## References:

https://machinelearningknowledge.ai/how-to-use-sklearn-simple-imputer-simpleimputer-for-filling-missing-values-in-dataset/

