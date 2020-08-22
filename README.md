# Project 2: Data cleaning & manipulation

*Imogen Rickert*

*August 2020 cohort, Berlin, 22.08.20*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description

I started with a messy data set: [Shark Attack](https://www.kaggle.com/teajay/global-shark-attacks/version/1). I imported it, used my data wrangling skills to clean it up and prepare it to be analyzed, and then exported it as a clean CSV data file.


## Questions & Hypotheses
What are the questions you would like to answer with your analysis? What did you feel were the answers to those questions before answering them with data?

## Dataset

I used the [Shark Attack](https://www.kaggle.com/teajay/global-shark-attacks/version/1) dataset.

It is a table of shark attack incidents compiled by the Global Shark Attack File. 


## Workflow

I began by importing my data into Jupyter Notebook and examining the data. I considered various pandas methods that I could apply to begin to clean the dataset and make it easier to read and work with. 

In the end I chose to make the following changes, checking as I worked that the changes were successful:

1. Removed whitespaces from column names
2. Made column names lowercase
3. Replaced white spaces in column names with underscores
4. Renamed a column
5. Removed two columns with too many missing values
6. Renamed incorrect values in a column
7. Changed values in a column based on a condition
8. Created two new columns grouping data into categories

Further explanation on the above changes can be found in the jupyter notebook file.

I finished by exporting the improved dataset as a new csv file: 'sharks_clean_IR.csv'.


## Organization

I began by examining my dataset and finding various parts that needed cleaning. I then decided which of the many possible improvements to make, keeping track in a list. 

My repository contains the jupyter notebook file with headings and explanations accompanying the code, as well as the new csv file and this readme file. 


## Links
Include links to your repository, slides and kanban board. Feel free to include any other links associated with your project.

[Repository](https://github.com/imogen-rickert/Data_cleaning_manipulation)  





