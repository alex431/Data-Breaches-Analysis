# Data-Breaches-Analysis

For the Code Louisville data analysis project, I wanted to look at some data related to cybersecurity. I was able to find and narrow my choice of data with the assistance of my mentors. I had to create an account with Kaggle to download the dataset. 

Cybersecurity has become an fasincinating field to me since I deep dive into the world of computers. The scope of an single breach is so massive, it could be overwhleming and it was at one point during this project. Companies typically like to keep tight lid when they get breached. In some cases, they remain secretive even when the breach becomes public knowledge.

I wanted to see if my interpertation deviates from the original analysis. During the data cleanup process, I combined some categories which altered the initial results. For example, I combined 'lost/stolen media' and 'lost/stolen computer' into 'lost/stolen' based on either evidence or similarities.

Upon investigation, I found some questions to ask against the dataset:
* What are the most or least frequent methods of an breach?
* What are the most or least frequent types of industry/sector that have been breached?
* How many records have been compromised?
* Are there any companies that have been breached more than once?
  - If so how many are there?
* What is the average number of compromised records in a breach?

Note: I started working on the project using python 3.10.7. Unfortuanely, I started to experience some non-related  python complications wtih my machine.Later, I tried to install python 3.11.0 after a fresh os installation. This version of python wasn't running smoothly when I tried to run my Jupyter notebook that consists of my code. In the end, I installed anaconda which it utilizes python 3.9.13.

Special Instructions: The pre-release version of Jupyter needs to be installed within Visual Studio Code.

## Required Packages to Install
* Pandas
* Seaborn
* Matplotlib
* Statistics

## Current Implemented Features
* Read in data from a local csv. Then each column of the dataframe was transformed into their own series.
* Utilized pandas's built-in functions to remove entries or replace values. For example, I dropped the entries that contain 'unknown' as their method for the breach.
* Wrote custom functions to assist with cleaning up the dataset. For example, I created a function that can replace a list of strings with a given string because there were too many similarities amongst the categories within the dataset.
* Utilized python's sum, min, and max functions to give an insight on the scope of compromised records.
* Imported the statistics package and utilized the mean function on the 'records' series. 
* Made 2 plots with seaborn. The first graph represents the number of occurrences vs the breach's method while the second graph represents the number of occurences vs the type of organization.
* Wrote in Jupyter's markdown cells explaining my thought process and code.

Source: https://www.kaggle.com/datasets/hishaamarmghan/list-of-top-data-breaches-2004-2021 

## Description of Data
The dataset contains the following columns:
- Entity 
  * The name of the company, organization, or institute
- Year
  * In what year did the data breach took place?
- Records
  * How many records were compromised? 
- Organization type 
  * What sector did the organization belong to?
- Method
  * How did the breach happen? 


 



