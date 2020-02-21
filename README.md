# pySparkNYCParkingTickets
Attempt to scientifically analyse the phenomenon of increased traffic violation tickets issued by the NYC Police Department.

### Objectives of the Assignment:    
•	Primarily, this Assignment is meant as a deep dive into the usage of Spark. As you saw while working with Spark, its syntax behaves differently from a regular Python syntax. One of the major objectives of this assignment is to gain familiarity with how analysis works in PySpark as opposed to base Python.  
•	Learning the basic idea behind using functions in PySpark can help in using other libraries like SparkR. If you are in a company where R is a primary language, you can easily pick up SparkR syntax and use Spark’s processing power.  
•	The process of running a model-building command boils down to a few lines of code. While drawing inferences from data, the most time-consuming step is preparing the data up to the point of model building. So, this assignment will focus more on exploratory analysis.  

## Problem Statement
Big data analytics allows you to analyse data at scale. It has applications in almost every industry in the world. Let’s consider an unconventional application that you wouldn’t ordinarily encounter.

New York City is a thriving metropolis. Just like most other metros its size, one of the biggest problems its citizens face is parking. The classic combination of a huge number of cars and cramped geography leads to a huge number of parking tickets.  
In an attempt to scientifically analyse this phenomenon, the NYC Police Department has collected data for parking tickets. Of these, the data files for multiple years are publicly available on Kaggle. We will try and perform some exploratory analysis on a part of this data. Spark will allow us to analyse the full files at high speeds as opposed to taking a series of random samples that will approximate the population. For the scope of this analysis, we will analyse the parking tickets over the year 2017.  
Note: Although the broad goal of any analysis of this type is to have better parking and fewer tickets, we are not looking for recommendations on how to reduce the number of parking tickets—there are no specific points reserved for this.  
The purpose of this assignment is to conduct an exploratory data analysis that will help you understand the data. Since the size of the dataset is large, your queries will take some time to run, and you will need to identify the correct queries quicker. The questions given below will guide your analysis.  
 
The dataset structure is available on this page along with the data.  
https://www.kaggle.com/new-york-city/nyc-parking-tickets

## General Guidelines:
1.	Your submission will consist of one Jupyter Notebook with all the codes. You should also write some subjective observations that you have made from this data in your Jupyter Notebook. Make sure that you run your file before submitting it.  
2.	If you make any specific assumptions related to these questions, be sure to state them.  
3.	Include all the necessary commands to prevent errors.  
4.	The queries may take time to get executed. Please have some patience. If you are getting errors with correct queries, restart the PySpark session and try again, as the session may have expired.  
5.	Keep a copy of the commands on your local drive so that you do not lose any work in case of session expiry.   
6.	If you want to run SQL commands, create an SQL view first. Also, if you make any changes in the table (like substitution or dropping null values), please ensure that you update the SQL view related to that table for further analysis.  
7.	Remember to stop Spark whenever you finish working on to the cluster. Use spark.stop().  

## Accessing the Dataset
The data for this assignment has been placed in HDFS at the following path:  
'/common_folder/nyc_parking/Parking_Violations_Issued_-_Fiscal_Year_2017.csv'

