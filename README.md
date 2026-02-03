# Airbnb NYC 2019 – Data Cleaning, Segmentation, and Feature Engineering (Excel)

## PROJECT OVERVIEW
This project deals with data cleaning in Excel. The Airbnb NYC 2019 dataset was gotten as a messy data. It was cleaned and standardized for further analysis. 

## DATASET
 Source: Airbnb listings and metrics in NYC, NY, USA (2019) - Kaggle Dataset. 
 Observations: The original dataset has 48,000 observations. It contains 16 columns. 
 About the dataset: This dataset describes the listing activity and metrics in NYC, NY for 2019.

 ## ISSUES IDENTIFIED IN THE DATASET
 Missing values in some columns.
 Extra space in text fields.
 Columns not useful for analysis.
 Numerical variables requiring segmentation.
 Names containing non-alphabetic characters. 
 Typographical errors in some columns. 

 ## DATA CLEANING
 
 ### 1. Handling Missing Values 
 Replaced blank values in non-numeric variables as "Not Provided."
 For the numerical variables like the review related variables, I replaced the missing values to "0". This shows "no review activity."
 
 ### 2. Text Cleaning and Standardization 
 Removed the extra spaces in the columns using the text-cleaning functions.
 Corrected typographical errors in the neighborhood and neighborhood group columns. 
 Standardized texts to ensure consistency. 
 Removed the names with non-alphabetic characters. 
 Removed columns irrelevant to the data analysis.
 
 ## FEATURE ENGINEERING AND DATA SEGMENTATION 
 
### Analytic Columns
More colums were added for further analysis.

### Data Segregation
Segmented the prices, number of reviews, minimum night stays to distinguish between hierachies.

 ## TOOLS USED 
 #### Microsoft Excel 
 
 ### Excel Functions Applied
Text Cleaning Funtions - TRIM, CLEAN, PROPER, SUBSTITUTE.
Logical Functions - IF, AND, OR, IFERROR, ISBLANK.
Data Validation.
Segmentation for further analysis.

## OUTCOME  
Improved the dataset's consistency and made it more interpretable. 
Prepared the data for more exploratory data analysis and visualization. 





 
