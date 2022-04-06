# Project Name
> The project problem statement is to understand the factors affecting the housing pricing for Surprise Housing and gauge by how much does these factors describe the demand


## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]
* [Acknowledgements]
* [Subjective Questions on Linear Regression]

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

## Conclusions
- <b> Conclusions from EDA </b>
	- Material and Finish: The conclusion that we can draw is that majority of the house in the dataset has average(5), above average(6), and Good(7) quality house.
	- Identified the neighborhood which houses homes that goes at largest price
	- Anlysis on the age and price of the property
- <b> Conclusions from Regression Models </b>
    - The proposal is to move ahead with Lasso Regression Model. The model was able to bring down the number of dependable variables to 34. 
	- Based on the Lasso Model - Top 5 price drivers are as follows:
    
    -1. GrLivArea - Above Grade Living Area - In Layman's term the larger the square feet of the house better chance of making the price
    -2. OverallQual - Overall Quality - This variable can help convey the story on a conceptual level - It could possibly capture intricate design features on a high level
    -3. GarageCars - The number of car space could be a direct correlation to the luxury factor of these houses
    -4. KitchenQual - Kitchen is an integral part of any home - Hence Kitchen Quality shall capture this
    -5. BsmTQual - Another Qualitative factor that is a significant contributor to the price - Larger Basement space is always an added addition to the housing market. 
-
 <b> Evaluation Metrics </b>
    - R2 Score on Test Data Set :0.812
    - R2 Score on Train Data Set : 0.879
	- Lambda (Penalty Parameter) :0.001

## Technologies Used
- pandas - version 1.2.4
- seaborn - version 0.11.1
- statsmodels - version 0.12.2
- scikit learn - version 0.24.1

## Acknowledgements

- This project was based on the linear regression assignment from Upgrad ML/AI Course

## Subjective Questions
- Contains a PDF Solution to some subjective questions based on the case study/

## Contact
Created by [@Bala129] - feel free to contact me!
