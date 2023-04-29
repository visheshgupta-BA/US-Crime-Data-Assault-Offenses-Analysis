<h1 align="center"><b>US-Crime-Data-Assault-Offenses-analysis</b></h1>


## Data Description
The FBI collects the US assault offenses data through the UCR Program’s NIBRS. This table provides the number of offenses distributed by offense type. This table counts offense types using the following rules:
* Offenses – if the offense type in Data Element 6 (UCR Offense Code) is:
  * Crime Against Person: count one for each victim, i.e., Victim Segment.
  * Crime Against Property: count one for each unique offense type.
  * Crime Against Society: count one for each unique offense type.
* The data used in creating this table were from law enforcement agencies submitting 12 months of NIBRS data to the FBI UCR Program for 2012 and were converted and published in CIUS, 2012. Upon meeting both criteria, the agencies’ actual NIBRS submissions were used in this table.

## Data Cleaning & Exploratory Data Analysis
The data cleaning and exploratory data analysis involves the following tasks:
1. Top 5 states with the highest number of Assault offenses registered in all the agency types except cities. (Show pivot of sub-types of Assault offenses)
2. Which category of crimes was most registered in universities?
3. Compare offenses at Michigan State University with offenses at all other universities.
4. Which provinces have state agencies with the lowest number of digital offenses registered (Credit Card/Automated Teller Machine Fraud, Wire Fraud)?
5. Which category of agency type and their respective agency names have the highest number of offenses registered per million people?

## Data Modelling
The data modelling task involves building a linear regression model that fits best to the provided data. The features for the model include Population, Drug/Narcotic Offenses, Drug/Narcotic Violations, Drug Equipment Violations, Theft from Building, Theft from Coin-operated Machine, Theft from Motor Vehicle, and Theft of Motor Vehicle Parts or Accessories. The target variable is the total number of offenses. 

## Self-Service Business Intelligence Dashboard
The FBI UCR dataset (cleaned) will be uploaded in the data warehouse using (GCP Big Query) and connected with a self-service business intelligence tool which is (Tableau). An interactive dashboard will be created to showcase the insights and visualizations derived from the dataset.

## Conclusion
The US-Crime-Data-Assault-Offenses-analysis project involves cleaning and analyzing the US assault offenses data, building a linear regression model, and creating an interactive dashboard using a self-service business intelligence tool. The project aims to derive insights and provide valuable information regarding the US assault offenses data.
