# Indian Startup Ecosystem Funding Analysis
## Overview
**Welcome to the "Indian Startup Ecosystem Funding Analysis" GitHub repository! This project aims to provide a detailed analysis of funding data from the Indian startup ecosystem spanning the years 2018 to 2021. The repository includes datasets containing information about startups, their funding amounts, and details about the investors involved.**

## Project Objective
**The primary objective of this project is to offer a comprehensive understanding of the funding landscape within the Indian startup ecosystem during the specified years. By examining key aspects such as funding amounts, startup details, and investor information, users can gain insights into the trends and dynamics of the Indian startup scene.**

## Installation
 SETUP

Getting started -->
Create a remote Github repository

Clone the remote repository to the local 

Create a virtual environment<python -m venv env>

Activate the virtual environment
 <env/Scripts/activate>

Install the necessary packages



## DATA SOURCES


The Indian startup ecosystem has four data sources for the different four years.In these datasets there is startup's details, the funding amount received and the investor's information. 
The data sources are:
2018: The 2018 dataset is stored in the Git repository 'https://raw.github.com/Azubi-Africa/Career_Accelerator_LP1-Data_Analysis/main/startup_funding2018.csv'


2020 & 2021 : These two year periods have their datasets stored in the database. The database management system for the two datasets is Microsoft SQL SERVER. To access the database you can use open database connecting standard library pyodbc.

## CODE STRUCTURE

We start by connecting to all datasets separately we begin with the 2020 ,2021 ,2019 then the 2018 dataset .
We then import the necessary library packages. The individual datasets are then loaded as Pandas DataFrames. 
A connection is then established  using the pyodbc library for the 2021& 2020 datasats .
We visualize on the data info to understand the datatype of the data sets, for each year,  then visualize the missing values 

We then clean the data for each year separately before concatenating them.

This project is focussed on answering a few questions which are visualized:

Which year has the highest amount of investment?
Which sector received the highest amount of funding?
Which region has the most startups?
What is the distribution of funding stages among the top 10 startups?


 

 ## 📝LICENSE

 Acknowledgements
 This project is [MIT](./LICENSE) licensed.


## AUTHORS

🕵🏽‍♀️ **Georginah Njeri**

- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/georginahnjeri/)


##  Acknowledgements
I acknowledge my project team contributors the Azubi Africa tutors and trainers. 
