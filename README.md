# TriNIT_Research_Geeks_ML03
Tri_NIT Hackathon ML03

# Team:ResearchGeeks 

## Crop Prediction:
A web-based application powered by machine learning to recommend crop variety and also predict crop yeild.

The system aims to help farmers to cultivate proper crop for better yield production based on predictive analysis of the market also. 

For accurate prediction we use multiple features to train our model some of them being:
* soil composition
* rainfall
* nutrient contents of the soil
* previously planted crops 
* temperature
* return of investment
* time of the year(month)
* irrigation 

The USP of our project is that not only does it give prediction it also does future simulation for you. It compares the accuracy obtained by different network learning techniques and the most accurate result will be delivered to the end user.

Our website is also very user friendly in the means of collecting the input; it has the following features:-
* user then has to input values which will then be fed to the model for accurate prediction 
* the results will be displayed back to the user after prediction 

## Getting Started:
Our website is also very user friendly in the means of collecting the input; it has the following features:
* it supports contact in multiple ways; i.e users can choose in what way they are comfortable to communicate to ensure farmers are able to utilize the website to the best of their abilities 
* user then has to input values which will then be fed to the model for accurate prediction 
* the results will be displayed back to the user after prediction 

## Prerequisites:
Device should support any one of the popular browsers (Chrome, Firefox, Safari, IE9, and Opera)

## Features:
* accurate prediction model 
* user friendly and easy to use
* crop cycle simulation 

## Specifications:
* TOTAL 2 ANNs will be implemented.
* Bootstrap used for website. 

### RECOMMENDATION NETWORK 1: 
INPUT - NPK values, Rainfall, Temp 
OUTPUT - TOP 5 Crops ( out of 22 crop values)

* Datasets used - 
TO TRAIN: Parameters to 22 crops

* FOR INPUT:
Rainfall by month range and state
Temp by month range and state
Soil Type and Past Crops to NPK

### SIMULATION NETWORK2: ( Total 5 ) ( EACH CROP HAS ONE )
INPUT - NPK values, Water, Temp, Insects, Disease
OUTPUT - CROP YIELD

We implemented SHAP in here.

* Datasets used - 

* TO TRAIN: Parameters to Yield

* FOR INPUT:
Water - Rainfall by month range and state + Irrigation capability ( INPUT )
Temp by month range and state
Soil Type and Past Crops to NPK
Insects to Yield
Disease to Yield
 
## Data Understanding:
Crop Data
The data refers to district wise, crop wise, season wise and year wise data on crop covered area and production. The data is being used to study and analyse crop production, production contribution to district/State/country, Agro-climatic zone wise performance, and high yield production order for crops, crop growing pattern and diversification.

Along with that a couple of external factors that may affect the ANN were also taken into consideration; eg. Infestation of pests, Crop Diseases.  

## Dataset links: 
https://drive.google.com/drive/folders/1KGBeUZXXZ7sJvfTrvqhTIosqfasmaVYp?usp=sharing 

## Prediction models used :
Deep Learning with ANN 
* Two ANN models were used. 

## Further Work
The future scope is in weather prediction along with applications in other related prediction models. 

