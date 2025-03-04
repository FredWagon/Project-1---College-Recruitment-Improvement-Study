# Project 1 - College Recruitment Improvement Study  
 The Computer Science department at the County College of Morris (CCM) runs surveys at the end of a semester for students taking CMP that are NOT enrolled in a CMP major. The results of these surveys are used for recruitment initiatives.  

### Purpose  
The purpose of this study is to demonstrate simple data import, exploratory data analysis (EDA), data transformation, data cleaning and data analysis using Python and Jupyter Notebooks. We will answer 4 basic questions because of this study:  
1. What are the changes over time (2020-24) in age demographics?  
2. What non-CMP degree/programs have the highest occurrences of respondents taking a Computer Literacy Course? Conversely, what are the least?  
3. What are the most effective information sources for non-CMP respondents seeking additional Computer Science courses? Conversely, what are the least?  
4. What interests are survey respondents seeking the most? Conversely, what are the least?  

### Code (survey.ipynb)  
The code is contained in the 'survey.ipynb' file and is intended to be run in JupyterLab environment. The code includes all activities from data import, through EDA, data transformation, cleaning and analysis. The code also includes observations and conclusions as markdown blocks in the notebook file. Please note that executing the code will generate files in this directory. These files are intended for off-line analysis and viewing at certain points in the code.  

### Input Files (Raw Data)  
The raw data files used in this analysis are included and must be located in the same directory as the code above.  
* Non-Majors Survey Results - Fall 2020.csv  
* Non-Majors Survey Results - Fall 2021.csv  
* Non-Majors Survey Results - Fall 2022.csv  
* Non-Majors Survey Results - Fall 2023.csv  
* Non-Majors Survey Results - Fall 2024.csv  

### Cleansed, Consolidated, Transformed Data File (pt15 - survey(transformed, consolidated, cleansed).csv)  
The 'pt15 - survey(transformed, consolidated, cleansed).csv' file is the final version of the data prior to analysis. It is an intermediate output file generated by the code execution, after the transformation, consolidation and cleansing of the raw data. Please note that the cleansing operations were focused on the dataset as a whole (invalid records, etc.) and the specific columns used in this analysis:  
* 'year'  
* 'age'  
* 'degreeenrolled'  
* 'infosource' (multiple fields)  
* 'interest' (multiple fields)  

The cleansing operations looked specifically at those fields to make any data corrections. Performing analysis on any other fields in the dataset will require EDA and cleansing specifically focused on those fields. See the markdown fields in the 'survey.ipynb' code for details and rationale of the transformation, consolidation and cleansing operations.  

### Analysis Results  
Results of the analysis are contained in the markdown cells of the 'survey.ipynb' file:
* Part 15: Exploratory Data Analysis - Finalize after transforming, consolidating and data cleansing  
* Part 16: Data Analysis - What are the changes over time (2020-24) in age demographics?  
* Part 17: Data Analysis - What non-CMP degree/programs have the highest occurrences of respondents taking a Computer Literacy Course? Conversely, what are the least? 
* Part 18: Data Analysis - What are the most effective information sources for non-CMP respondents seeking additional Computer Science courses? Conversely, what are the least?  
