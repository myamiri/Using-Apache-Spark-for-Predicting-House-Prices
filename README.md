# Using-Apache-Spark-for-Predicting-House-Prices


# Summary

1. Understanding the Data Set
2. Creating the Spark Session
3. Load The Data From a File Into a Dataframe
4. Data Exploration
5. Data Preprocessing
6. Feature Engineering
7. Building A Machine Learning Model With Spark ML
8. Evaluating the Model




# Problem

The problem here is to create a model that will predict the median housing value for a census block group (called "district" in the dataset) given the other attributes.



# Solution

I build a Linear Regression application using PySpark.

Apache Spark, once a component of the Hadoop ecosystem, is now becoming the Big-Data platform of choice for enterprises. 
It is a powerful open source engine that provides real-time stream processing, interactive processing, graph processing, 
in-memory processing as well as batch processing with very fast speed, ease of use and standard interface.




# Data

The California Housing data set appeared in a 1997 paper titled Sparse Spatial Autoregressions, written by Pace, R. Kelley and Ronald Barry and published in the Statistics and Probability Letters journal. 
The researchers built this data set by using the 1990 California census data.

The data contains one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people). 
In this sample a block group on average includes 1425.5 individuals living in a geographically compact area.

These spatial data contain 20,640 observations on housing prices with 9 economic variables




# Modeling

Build our Linear Regression model with these steps :

1- split the data into training and test sets.

2- Create an ElasticNet model

3- Fit the data to the model

4- Inspect the Model Co-efficients

5- Generate Predictions

6- Extract the predictions and the "known" correct labels

7- Inspect the Metrics

8- Use the RegressionEvaluator from pyspark.ml package





# Result

There's definitely some improvements needed to our model! 
If we want to continue with this model, we can play around with the parameters that we passed to your model, the variables that we included in your original DataFrame.

