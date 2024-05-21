# Lending Club Case Study
> he Lending Club Case Study is a project aimed at identifying the key factors that lead 
> to loan defaults by analyzing patterns in loan data. The project follows a systematic 
> approach that includes the following steps: Data Sourcing, Data Loading, 
> Data Cleaning and Handling, Data Deduplication, Data Standardisation, Data Filtering, 
> Data Segmentation, and Univariate and Bivariate Analysis.

## Table of Contents
* [General Info](#general-information)
* [Approach](#approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Key Driving Factors](#key-driving-factors)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending Club is the US based consumer finance company which specialises in lending various types of loans
- Consumer attributes and Loan attributes influence the tendency of default
- The case study aims to minimize financial losses for lending companies by identifying loan applicants who are likely to default. These defaulters are referred to as 'charged-off' customers. By using Exploratory Data Analysis (EDA), the study seeks to detect these risky applicants to reduce the incidence of credit loss, which occurs when borrowers fail to repay their loans.
- Loan data set provided to be used for this study. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Approach
1. Data Sourcing / Data Loading
2. Data Attributes Understanding High Level
3. Data Cleaning and Manipulation Activities
   - Missing Data Handling 
   - Missing Value Imputation 
   - Handling Data Types 
   - Data Standardisation 
   - Filter the Data 
   - Treating Outliers
4. Exploratory Data Analysis ( EDA)
   - Derived Metrics
   - Univariate Analysis 
   - Segmented Univariate Analysis 
   - Bivariate Analysis 
   - Multivariate Analysis
5. Data Visualisation 
   - Univariate Data Visualisation in Plots. 
   - Bivariate Data Visualisation in plots 
   - Multivariate Visualisation in plots.

## Conclusions
- NE - 60%, NV ~22%, SD-20%, AK-18% states where borrowers defaulted maximum
- With higher Rate of interest tendency to default is high near to 40%
- 14K-50K USD income group has the more tendency to default by 16-18% 
- Term 60 Months has the default rate higher near to 25%
- Dec, September and May months has higher default tendency rate near to 16%
- Small Business has the more tendency (27.5%) to default and then Renewable Energy and then Other/House.   
- Home Ownership (18.5%) with Other and Own and Rent has more tendency to default.
- Self Employed has the highest tendency (23%) to default, then 10+ and 7 Years.
- Sub Grade F5(49%), G3, G5 has the highest tendency to default to Compare to A4,A5, B3,B5 where total defaulters are more because total loans issued are also more.
- In Grade A  to Grade G (34%) borrowers to get defaulter is increased in tendency. 

## Key Driving Factors
Consumer Attributes
1. Address State
2. Grade and Subgrade
3. Purpose
4. Employment Length
5. Home Ownership

Loan Attributes
1. Loan Amount to Income Ratio 
2. Interest Rate
3. Term
4. Verification Status
5. Issued Month

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.0
- Pandas Library 
- Matplot Library 
- Seaborn Library 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Huge thanks to Upgrad coaches and respected faculties from IIIT Bangalore, Also the expert lectures taken during the course 
- Credits to Upgrad buddy and live session coaches.
- References - Upgrad Modules


## Contact
Created by [@kapasitejas] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->