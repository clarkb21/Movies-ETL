# Extract-Transform-Load Movies Analysis

## Purpose
- To prepare for a hackathon even, data was collected from Wikipedia and Kaggle resources, combined and cleaned, and loaded into a PostgreSQL database. 
- To complete this task, the ETL (Extract-Transform-Load) process was used to extract data using Pandas, clean the data and transform it into one dataframe, and then load it into a SQL database for long term storage.  

## Project Overview
- Using Python, Pandas, and Jupyter notebook, I extracted data from multiple sources. 
- The raw data was analyzed, cleaned, and structured into the desired form using Pandas. 
- The clean data was then stored in a PostgreSQL database. 


### Challenge Overview
- The steps to extract, transform, and load the data wants to be automated. A function was created for this process to be done automatically. 
- There were multiple steps to transforming the data into the desired structure. 
- The data had several duplicate columns from the multiple sources. 
- The data also had several duplicate rows and null values that needed to be removed. 


## Resources
- Data Source: Wikipedia JSON file, Kaggle CSV file, Movie Ratings CSV file
- Software:  Python 3.7.6, Conda 4.13.0, Jupyter Notebook 6.4.8, Pandas 1.4.3, pgAdmin 4 Version 6.8, PostgreSQL Version 11.16
- MSU Bootcamp Spot Module 8: https://courses.bootcampspot.com/courses/2508/pages/8-dot-1-1-extract-transform-load?module_item_id=635652

## Results
- A function was created to automate the process of performing the ETL process. 
- The movies dataset was successfully stored in a PostreSQL database for the hackathon event. 

![movies_query](https://user-images.githubusercontent.com/104038813/182166509-1ee96b6b-913c-4930-9445-dc4d5a8ade25.png)

- The ratings dataset was successfully stored in a PostreSQL database for the hackathon event. 

![ratings_query](https://user-images.githubusercontent.com/104038813/182174842-ab833075-1bc9-4af2-bd74-d15265ab64bc.png)



