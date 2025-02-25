# Analysis of Customer Review data for British Airways

## Overview
British Airways is a UK based airline that has been established in 1974. It is the second largest UK based carrier based on fleet size and passenger number. In 2020, due to the crisis caused by the COVID-19 pandemic, British Airways had to reduce its 42,000-strong workforce by 12,000 jobs. According to the estimate by IAG, a parent company, it will take the air travel industry several years to return to previous performance and profitability levels. However, 2022 saw a dramatic increase in travel, and the company now faced a worker shortage, forcing it to cancel more than 1,500 flights. I wonder if this shortage in airline workforce had impacted the customer satisfaction. In addition, analysis of the customer reviews can guide the airlines to unerstand the sectors where they can improve the service.
 
Here we have global customer review data for British Airways from 2016 to 2023.  Passengers have rated six different services provided by the airline. This includes Ground and Cabin staff, Entertainemnt, Food, Value for money and Seat Comfort. A score of 1-5 has been provided for each of these services. We also have information on the departure Country, Seat type, aircraft model along with many other information for each of the reviews.

## Data Processing
- Python code used to clean the inconsistencies and non-sensical values can be found [here](https://github.com/shilpakarumanchi/python/blob/main/BA_cleaning.ipynb)
- Python code used to derive data insights can be found [here]
- Interactive dashboard generated in Tableau can be found [here](https://public.tableau.com/app/profile/shilpa.ln.karumanchi/viz/BA_customerreviews/Dashboard32?publish=yes)

## Executive Summary
![Screenshot 2025-02-24 094205](https://github.com/user-attachments/assets/a2157714-28ac-45f1-b456-d95d96d08308)

- The **average overall rating** is **4.2**, suggesting a decent customer satisfaction level.  
- **Entertainment has the lowest rating (1.4)**, indicating that passengers are significantly dissatisfied with in-flight entertainment.  
- **Food beverages (2.4) and value for money (2.8)** also have relatively low ratings, showing room for improvement in these areas.  

### **Trends in Entertainment Ratings**  
- The **average entertainment rating has fluctuated over time**, with notable declines around 2021 and 2023.  
- A potential **downward trend is visible**, requiring further investigation into recent changes in in-flight entertainment quality.  

### **Regional Variations**  
- The **heatmap suggests variations in entertainment ratings across different countries**, indicating that customer satisfaction is not uniform globally.  
- Specific countries may have worse entertainment experiences, which British Airlines should investigate further.  

### **Aircraft Model Impact**  
- **A380 and Boeing 747 models have the highest entertainment ratings (2.9 and 2.6, respectively).**  
- **Smaller aircraft like A319 (-1.0) and A320 (-0.5) have significantly lower ratings**, suggesting that entertainment systems may be less advanced or unavailable in these models.  

### **Recommendations:**  
1. **Improve In-flight Entertainment**: Given the **low entertainment rating (1.4)**, British Airlines should enhance content availability, upgrade screens, and ensure a seamless user experience across all aircraft.  
2. **Address Regional Differences**: Identify specific **countries with low ratings** and improve entertainment offerings accordingly.  
3. **Focus on Specific Aircraft Models**: Upgrade entertainment options in **A319, A320, and A321 aircraft**, as these have notably lower ratings.  
4. **Monitor Trends & Customer Feedback**: Given the **decline in entertainment ratings in 2021 and 2023**, British Airlines should analyze customer complaints and conduct surveys to understand key issues.  

  
## Results
- There are a total of 1324 reviews collected from 56 Countries, duirng a period of 7 years starting from March 2016 to October 2023.
- Among the 56 Countries, 42 Countries have <10 reviews & 24 Countries have <5 reviews. Hence, I have grouped the Countries by Continent.
- Highest number of reviews were provided from Europe (1009 reviews) followed by North America (168 reviews).
- Lowest number of reviews were provided from South America  (5 reviews) followed by Africa (22 reviews). 
- Asia has the highest overall rating of 3.32, followed by Europe and North America with overall ratings of 2.92 and 2.88.
- Oceania (Australia & New Zealand) has the lowest average ratings of 2.58.
- Among the services provided by the air line, highest rating is assoiated with cabin staff service, followed by ground service.
- Lowest rating is associated with food and beverages followed by entertainment.
- Aircraft A380 has hihgest Average rating of 3.2 and A320 is associated with the lowest Average rating of 2.7.
- On average the services provided in first class received higher ratings than the other class types.
- Economy class has the least ratings (2.7) with respect to all the services, followed by Premium Economy class (2.8).

## Recommendations
- In statistics, there has to be a minimum sample size of 30 inorder to be able to make any inference. Hence, it is advisable to avoid inferences with resepct to Sounth America and Africa, due to very low sample size.
- From the time series analysis, we can notice that there is no difference in ratings before and after Covid-19.
- However, we notice very low number of reviews when Covid has started (i.e. from Apr 2020 to Sept 2021).
- The air lines can work on the quality of food and beverages and entertainment services provided to Economy and Preminum Economy classes to improve the ratings.
- In addition the quality of all the services can be improved in Oceania countries (Australia & New Zealand).
- More investigation can be perofrmed with respect to the differences in ratings by aircraft types.




