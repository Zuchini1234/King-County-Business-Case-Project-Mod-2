
# King County Real Estate Consultancy 
## Module 2 Final Project

![Seattle Skyline](https://github.com/Zuchini1234/King-County-Business-Case-Project-Mod-2/blob/master/Images/Seattle_Skyline.jpeg)

## Introduction

This project follows a Real Estate Consultancy firm KCC in King County, Washington. KCC serves a variety of clients, from sellers, to restaurants and real estate developers. The purpose of this project is to analyse housing in King County, Washington; specifically, to see whether KCC can identify which features of a house in King County are most indicative of its price. These insights will be used to drive value to our customers through market advice and guidance. The report will detail information that is deemed valuable and a few customer scenarios we have dealt with. 

To do so, this project will primarily be using linear regression (more on that below) through various Python libraries. 

## What is Linear Regression:

Linear Regression is a method of predictive modelling. It tries to predict an outcome (often referred to as the dependent variable or x) from an input variable (the independent variable or y). This can also be done with multiple input variables and is then called Multiple Linear Regression. This differs from Multivariate Linear Regression which predicts multiple dependent variables. The output of this method is scalar, in that it identifies both direction and magnitude of relationship. In other words, it identifies the expected change in y for every change in x. 

Even though Linear Regression is one of the least accurate prediction models, it is the most interpretable. There is an inverse correlation between the complexity, and by extent accuracy, of a model and its accuracy. Linear Regression is used because despite its lower relative accuracy compared to other Machine Learning models, it is highly interpretable. Linear Regression presents a model that can be scaled to acceptable accuracy by including multiple features while still being very easy to gain insight from and present. There is an interesting article on this topic on this link (https://towardsdatascience.com/model-complexity-accuracy-and-interpretability-59888e69ab3d). 

## Outline

This project is centred on a dataset containing property information from King County, Washington; containing features of a property such as square footage, rooms, floors, price and several others. The dataset used was modified for the purposes of this project, but the original dataset can be found on Kaggle on the following link: https://www.kaggle.com/harlfoxem/housesalesprediction. 

#### File Structure

1. README.md 

    This is the document you are reading right now! This contains an overview of the project, its execution and a few of the insights generated from it. 

2. student.ipynb 
    
    Contains the core code used to analyse the data and step-by-step descriptions of what is being done. This code follows multiple avenues, some of which did not form part of the conclusion but rather showed the process of getting there. There are multiple markdown cells through the jupyter notebook that explain the progression of work. 
    
3. slide_deck

    Contains slides for a presentation on the main actionable insights gained from this project.  
    
4. zippedData

    Contains the data that was used for this project. This dataset is different to the one that can be found on the Kaggle link above. 
    
5. Data
    
    File containing saved csv files of preprocessed data
    
6. Images

    Contains images used in the presentation material
   
## Questions and Scenarios

Figure: A distribution of the data points on a map with colours indicating price
![Price_Map](https://github.com/Zuchini1234/King-County-Business-Case-Project-Mod-2/blob/master/Images/Price_Map.png)

There are clear areas that are more expensive, and this will form part of our approach to answering the following questions.

**Question 1**

With which single feature of a property is it easiest to guess the value of a property?

We will not always have access to our data team and it is vital that we are able to gain as much insight from as little information as possible.

**Scenario 2**

A buyer approaches the firm looking for advice on purchasing a property against the following criteria

Minimum two bed

No real restriction on price

Plan to resell within a period of five years and wants a healthy profit

Buyer is prepared to invest in property.

The aim here is to identify features and areas where there is most likely to be an increase in price over the near term. This may include recommending properties that could easily be upgraded

**Scenario 3**

A real estate developer approaches the firm looking to expand into King County. What advice would you give them? How could they best realize a healthy profit with the insights this dataset offers? This developer is aimed at identifying cheaper opportunities and investing larger sums of money into long term development.

What areas and properties can we identify that would satisfy those criteria?

## Business Insights

1. Grade is the single feature with which it is easiest to guess price
2. Buyers can find the most value (lowest price/sqft_living) in Federal Way, Auburn, Algona, Milton, Pacific. With the worst value in Seattle. 
![Price_SqftLiving_Map](https://github.com/Zuchini1234/King-County-Business-Case-Project-Mod-2/blob/master/Images/Price_SqftLiving_Map.png)
3. Buyers should buy unrenovated houses built from 1960 to 2000 and invest in renovations if they want to realize large profits. 
4. Real estate developers should focus on Grade with construction if they want to maximize price.
5. The best areas for value for real estate developers are Burien, Normandy Park, Des Moines, SeaTac, Tukwilla, Vashon Island. 


### Please Enjoy!



