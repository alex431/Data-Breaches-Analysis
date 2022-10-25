# Data-Breaches-Analysis

For the Code Louisville data analysis project, I wanted to look at some data related to cybersecurity.I was able to find and narrow my choice of data with the assistance of my mentors. I had to create an account with Kaggle to download the dataset. 

Special Instructions: The pre-release version of Jupyter needs to be installed within Visual Studio Code.

Required packages to install:
* Pandas
* Seaborn
* Matplotlib

Current implemented features:
* Read in data from a local csv. Then each column of the dataframe was transformed into their own series.
* Wrote custotim functions to assist with cleaning up the dataset. For example, I created a function that can replace a list of strings with a given string because there were too many similarities amongst the categories within the dataset.
* Made 2 plots with seaborn. The first graph represents the number of occurrences vs the breach's method while the second graph represents the number of occurences vs the type of organization
* Wrote in Jupyter's markdown cells explaining my thought process and code.

Description of Data<br>
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

 



