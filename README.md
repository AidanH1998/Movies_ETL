# Movies_ETL

## Overview ##

The Project is to Extract data, Transform data sets, and Load the processes. 

* This project is creating ETL raw data to SQL database. 
* Then, extracting data from the source through Python. 
* Next, is cleaning and tranforming data in panda.
* The text that need to be numbers are also changed through using regular expressions 
* Lastly is bring in all data through PGAdmin for the final look.
#
* Wiki data, Kaggle data, and rating data are all organized to present
* extracting and tranforming Wiki data, Kaggle data, Rating data
* The final data will be loaded in SQL movie databases


## Results ##

Wiki was extracted through JSON and Kaggle and rating through csv. First we clean the wiki database by clearing things we don't need, like tv shows because we want movies. 
In the kaggle and Rating data we take out the repeated data, so we don't a squed charts. In the data sets we also merge data points we they are the same, or representing the same thing.
Once we Clean the data points for Wiki, kaggle, and ratings we can now load it towards the SQL moive database.
