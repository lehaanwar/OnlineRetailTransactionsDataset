# Online Retail Transaction Dataset Project

**Online Retail Transaction Dataset Project** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* The dataset I used was from one of the five that was provided to us, Online Retail Transaction Analysis, please see the link below;
https://www.kaggle.com/datasets/abhishekrp1517/online-retail-transactions-dataset. 
The dataset included;

InvoiceNo - TransactionID
StockCode - Product ID
Description	- Name of products
Quantity - Number of units purchased
InvoiceDate - Day, month and year of purchase
UnitPrice - Price per unit
CustomerID - Unique customer identifier
Country - location of customer



## Business Requirements
* Analyse online retail transaction data to uncover sales patterns and trends, identify popular products and to understand customer behaviour to support targeted marketing and sales strategies.


## Hypotheses and how to validate?
1. Location vs Customer behaviour - Certain countries have higher total transaction values due to larger customer bases or higher purchasing power. Validation - I need to compare total sales and check the difference between different countries. The variables used - Country, CustomerID, Quantity, Unit Price.
2. Seasonal vs Sales - Products that have higher unit prices due to demand spikes during specific times of the year. Validation -  I need to compare seasonal months in the year (November, December) against the non-seasonal months (January, February) to check what months demand is higher. I will use Time Series to analyse alongside line plots and bar charts. The variables used - InvoiceDate, Quantity, Unit Price.
3. Price vs Quantity. Lower priced products will encourage higher quantities purchased. Validation - I need to compare the Unit Price and quantity and see if there is a correlation using scatter plots and heat maps. Variables used - Unit Price and Quantity.


## Project Plan
The High- level steps take as per below;
* Choosing a Dataset to analyse from Kaggle. 
Creating a business requirement and three hypotheses.
Cleaning the data by checking for duplicates, missing values and outliers.
Data Visualisations using Matplotlib, seaborn, plotly.
Analysing the data by validating hypotheses.
Conclusion to report the findings.

## The rationale to map the business requirements to the Data Visualisations
* Analyse online retail transaction data to uncover sales patterns and trends - Using libraries such as Seaborn and Matplotlib to show sales patterns and trends in the form of graphs and plots. 
-Identify popular products and to understand customer behaviour to support targeted marketing and sales strategies - Using data visualisation to show customers purchasing from different locations and identifying lower price products sell more to get better understanding of customer behaviours.

## Analysis techniques used
* Descriptive Statistics: Displayed total transaction values and calculated mean. 
Trend analysis - Using Time Series to analyse sales over time.
Data Visualisation such as plots, graphs and charts to show correlation between variables.
The structure of the data analysis is as follows;
Loading the raw data from a CSV file.
Looking at the data by using DataFrame methods.
Checking for duplicates, missing values and outliers in data.
Validating hypotheses by using libraries such as Matplotlib, Seaborn, plotly.
Concluding the data to report findings. 
Generative AI helped me with the code.

## Ethical considerations
* I did not have any issues with data privacy, bias or fairness whilst analysisng the data.
* I had no legal or societal issues.

## Unfixed Bugs
* I did use AI for issues that some were later fixed and some were left in the code. There was definetly gaps in my knowledge and I did refer back to the LMS handbook and AI to address these.
The error issue I faced were the following;
Importing libraries error 'No module named numpy'. I had to change the Python environment to Python venv.
Another error I had was whilst trying to load the raw data. I later found out that I had downloaded and Excel file instead of CSV. To fix this, I had to install openpyxl on the terminal, load the Excel file and then save to CSV so I have both files in my RawData folder. 
I also had an issue with Git Commit. I asked AI to help and then fixed the issue by asking help from Vasi.

## Development Roadmap
* I faced a few challenges with getting my code to work, downloading the raw data, commiting on Github. I also ran out of time as I had wi-fi issues during this project. There was definetly gaps in my knowledge.
I would like to better prepared, better organised and refresh my knowledge for future.

## Main Data Analysis Libraries
OS
Numpy
Pandas
Matplotlib
Seaborn
Plotly

## Credits 

* I used the raw dataset from https://www.kaggle.com/datasets/abhishekrp1517/online-retail-transactions-dataset
I used W3 Schools alongside the LMS to refresh my pandas and and other libraries knowledge. 
I used Chatgpt to help with some issues with loading, cleaning my data and github commiting.

## Acknowledgements (optional)
I would like to thank Vasi for his help in this project.