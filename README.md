# Analysis of Customer Review data for British Airways
## Table of Contents
## Introduction
British Airways is a UK based airline that has been established in 1974. It is the second largest UK based carrier based on fleet size and passenger number. British Airways is the first passenger airline to have generated more than US$1 billion on a single air route in a year (from 1 April 2017, to 31 March 2018, on the New York-JFK – London-Heathrow route). In 2020, due to the crisis caused by the COVID-19 pandemic, British Airways had to reduce its 42,000-strong workforce by 12,000 jobs. According to the estimate by IAG, a parent company, it will take the air travel industry several years to return to previous performance and profitability levels. However, 2022 saw a dramatic increase in travel, and the company now faced a worker shortage, forcing it to cancel more than 1,500 flights. I wonder if this shortage in airline workforce had impacted the customer satisfaction.
 
## Overview of Dataset 
I have obtained global customer review data for British Airways from 2016 to 2023.  Passengers have rated six different services provided by the airline. This includes Ground and Cabin staff, Entertainemnt, Food, Value for money and Seat Comfort. A score of 1-5 has been provided for each of these services. We also have information on the departure Country, Seat type, aircraft model along with many other information for each of the reviews.

## Tools Used
- Python
- Tableau
  
## Data Cleaning
- I have merged the review data set with another data set taht had onformation on Continents where each country belongs.
- I have noticed '-1' values for many ratings. I replaced -1 ratings by the average rating within each service provided.
- I have generated a new variable "Average Rating" that shows the average of all the 6 services provided by the airline.
  
## Data Exploration & Analysis 
- Explored the start and end date of the reviews.
- Explored number of reviews by Country, by Continent & by Aircraft type.
- Explored summary of the ratings for each of the 6 services and overall rating by Continent, by Aircraft type & by seat type.
- [Link to view complete python code](https://github.com/shilpakarumanchi/python/blob/main/BA_cleaning.ipynb)

## Dashboard Generation
I have generated an interactive dashboard in Tableau that consists of:
- Line graphs displaying the average ratings & numbero of ratings per month for any of the 6 services and overall average rating.
- An interactive map that shows the average rating individually for 6 services and overall average rating by Continent.
- 2 bar graphs showing the ratings by COntinent & by type of aircraft.
- Summary ratings on the top for each of the 6 services and the overall rating.
- [Tableau dashboard](https://public.tableau.com/app/profile/shilpa.ln.karumanchi/viz/BA_customerreviews/Dashboard32?publish=yes)
  
## Results
The data for collected duirng a period of 7 years starting from March 2016 to October 2023.
 42 Countries have <10 reviews, during 7 years.
# 24 Countries have <5 reviews.
#Hence I have grouped the Countries by Continent.
#Highest number of reviews were provided from Europe with 1009 reviews followed by North America with 168 reviews.
#Lowest number of reviews were provided from South America  with 5 reviews followed by Africa with 22 reviews. 
#There should be a minimum sample size of 30 inorder to be able to produce any inference.
#Asia has the highest rating of 3.32, followed by Europe and NA with ratings of 2.92 and 2.88.
#Oceania (Australia & New Zealand) has the lowest average ratings of 2.58.
On average the services provided in first class received higher ratings than the other class types.
#Economy class has the least ratings in all service categories.
The air lines can work on the quality of food and beverages and entertainment services provided to Economy and preminum economy classes 
#to improve the ratings.
#In addition the quality of all the services can be improved in Oceania countries (Australia & New Zealand), for better ratings.
## Recommendations




