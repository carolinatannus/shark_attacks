# Shark Attacks: which countries to avoid swimming at?

Status: Completed

## Objective

Using the shark attacks database, my goal was to understand *which countries have had the largest number of occurrences*, later ranking these regions by fatal attacks and, consequently arriving at the *ratio between the number of fatal attacks from occurrences per country*, with these not being the safest places to have a swim.

## Methods

  - Cleaning
  - Filtering
  - Grouping
  
## Technologies 

  - Python
  - Pandas

## Project Description

  For this project I used the dataset Global Shark Attacks available at Kaggle and shared by Toby Jolly. The original data contains 25.723 entries and 24 columns with information regarding shark attack incidents all over the world up until 2018. The database contains details regarding the incident's date, its type (eg: provoked), location, name of victim and activity he/she was engaged in (eg: surfing) and more.
  
  The database can be found through this link: <https://www.kaggle.com/teajay/global-shark-attacks>
  More information on where the data comes from can be seen here: <https://www.sharkattackfile.net/index.htm>

## Steps
  
  In order to go through the mentioned dataset, I followed the steps below:
  
  1) Importing libraries
  > In this case, pandas
  
  2) Reading and understanding database
  > Accessing the database itself and its characteristics (eg: from more than 25k rows, less than 9k were filled)
  
  3) General cleaning
  > Removing duplicates, rows with less than 50% of filled columns, and practically null columns
  
  4) Formulating questions
  > As mentioned, the guiding question was: "Which country has had the biggest number of incidents?"
  > From this point on, it was necessary to a) identify the columns to obtain the answer, b) filter and clean selected columns and c) organize the results
  > Once arriving at an initial result, I had to repeat this process to go further on the analysis new question at hand

## Conclusion
 
 
 
 * Note: from the initial database with almost 26k entries and 24 columns, my final table had 15 rows and 3 columns.

## Contact
  linkedin, github, medium, etc
