# Data-Breaches-Analysis

For the Code Louisville data analysis project, I wanted to look at some data related to cybersecurity.I was able to find and narrow my choice of data with the assistance of my mentors. I had to create an account with Kaggle to download the dataset. 

Special Instructions: The pre-release version of Jupyter needs to be installed within Visual Studio Code.

<u>Required packages to install</u>
* Pandas
* Seaborn
* Matplotlib
* Statistics

<u>Current implemented features</u>
* Read in data from a local csv. Then each column of the dataframe was transformed into their own series.
* Ultized pandas's built-in functions to remove entries or replace values. For example, I dropped the entries that contain 'unknown' as their method for the breach.
* Wrote custom functions to assist with cleaning up the dataset. For example, I created a function that can replace a list of strings with a given string because there were too many similarities amongst the categories within the dataset.
* Made 2 plots with seaborn. The first graph represents the number of occurrences vs the breach's method while the second graph represents the number of occurences vs the type of organization.
* Wrote in Jupyter's markdown cells explaining my thought process and code.

<u>Description of Data</u><br>
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
  * How did the breach happened? 

 



