# A Pipeline For the Storage and Analysis of Irregularities in 2023 Nigerian Election. 
The allegations of vote manipulation and irregularities in the 2023 Nigerian presidential election have been widespread, prompting a thorough investigation into the matter.
A third party is in the process of pulling and reviewing the result data across the country.
This project involves building 
- a Pipeline for the storage of the data (after review) in a database
-  the analysis of the result.

An irregularity is described as the deviation or outlier value in the votes of a Party as compared to the values of its nearest neighbors.


## Files
- Rivers_checked : The election result for available polling units for rivers state. (case sample)
- ETL - script to extract the longitude and latitude of the polling units in the state (rivers state) and upload to the mongodb server
- Election_analysis : To analyze the data.
- Election_presentation : A presentation of the report.
- Webscrapping : A webscrapping script that pulls data from the inec portal about all registered polling units and their polling unit code. The polling unit code can serve as a unique identifer and can be used to join both data. 

## Tools
- MongoDB
- Plotly

## Coming Soon
 - Use of Dash for plotting
 - Automation weekly for uploading the reviewed CSVs
   
