Who this project is for
- The repository contains files to support my project which is to analyse the rental prices in the Seattle area to 
advise a fictional client on where they should buy a property to put for rent to customers.

Installation instructions
- The user should have python 3.13 installed along with the libraries and files that are noted lower below

There are 4 main files:
- Udacity_seattlev6.ipynb - this is a jupyter notebook with the main source code for my project
- 3 data files called listings.csv.zip, calendar.csv.zip and reviews.csv.zip

The 3 data files above:
 - taken from Kaggle website (https://www.kaggle.com/datasets/airbnb/seattle/data): per the Kaggle website it describes each file as follows:
 - Listings, including full descriptions and average review score
 - Reviews, including unique id for each reviewer and detailed comments
 - Calendar, including listing id and the price and availability for that day

The main source file (Udacity_seattlev6.ipynb) when run in jupyter notebook will extract the other 3 files and give
the user various analysis.

Libraries used in python code:
- requests module - to help access urls on web
- zipfile module - to help with reading/writing to zip files
- io - to help with accessing data within files
- numpy - for data analysis
- pandas - for data analysis
- matplotlib - for visualisation
- seaborn - for visualisation
- sklearn - for creating predictive models eg. using linear regression

You can find my Medium post on the findings at: https://ommarhannan.medium.com/what-are-the-best-rental-opportunities-in-seattle-7ee685eecc61


