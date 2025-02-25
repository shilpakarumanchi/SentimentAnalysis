# British Airways Customer Sentiment Analysis

## Overview
British Airways, a UK-based airline established in 1974, faced significant challenges due to the COVID-19 pandemic in 2020. As a result of the crisis, the airline reduced its workforce from 42,000 employees by 12,000 jobs. However, with the sharp rebound in travel demand in 2022, British Airways encountered a labor shortage, leading to the cancellation of over 1,500 flights.  

This project analyzes **global customer review data for British Airways from 2016 to 2023**. Passengers have rated six key services: **Ground and Cabin Staff, Entertainment, Food, Value for Money, and Seat Comfort**, assigning each a score from **1 to 5**. Additionally, the dataset includes details such as **departure country, seat type, aircraft model**, and other relevant factors for each review.  

The primary objective of this study is to assess whether the **airline’s workforce shortage impacted customer satisfaction**. By analyzing customer reviews, British Airways can gain valuable insights into **service gaps and areas for improvement** to enhance the overall passenger experience.

## Data Processing
- Python code used to clean the inconsistencies and  to derive data insights can be found [here](https://github.com/shilpakarumanchi/python/blob/main/BA_cleaning.ipynb)
- Interactive dashboard generated in Tableau can be found [here](https://public.tableau.com/app/profile/shilpa.ln.karumanchi/viz/BA_customerreviews/Dashboard32?publish=yes)

## Executive Summary
![Screenshot 2025-02-24 094205](https://github.com/user-attachments/assets/a2157714-28ac-45f1-b456-d95d96d08308)

- The **average overall rating** is **4.2**, suggesting a decent customer satisfaction level.  
- **Entertainment has the lowest rating (1.4)**, indicating that passengers are significantly dissatisfied with in-flight entertainment.  
- **Food beverages (2.4) and value for money (2.8)** also have relatively low ratings, showing room for improvement in these areas.
  
## Date Deep Dive
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

### **Trends in Entertainment Ratings**  
- The **average entertainment rating has fluctuated over time**, with notable declines around 2021 and 2023.  
- A potential **downward trend is visible**, requiring further investigation into recent changes in in-flight entertainment quality.  

### **Regional Variations**  
- The **heatmap suggests variations in entertainment ratings across different countries**, indicating that customer satisfaction is not uniform globally.  
- Specific countries may have worse entertainment experiences, which British Airlines should investigate further.  

### **Aircraft Model Impact**  
- **A380 and Boeing 747 models have the highest entertainment ratings (2.9 and 2.6, respectively).**  
- **Smaller aircraft like A319 (-1.0) and A320 (-0.5) have significantly lower ratings**, suggesting that entertainment systems may be less advanced or unavailable in these models.  

## Recommendations 

#### **Enhance In-Flight Entertainment**  
- Given the **low entertainment rating (1.4)**, we should focus on:  
  - Expanding **content availability** to cater to diverse passenger preferences.  
  - **Upgrading screens** and in-flight systems for a better viewing experience.  
  - Ensuring a **seamless entertainment experience** across all aircraft models.  

#### **Focus on Low-Rated Regions & Aircraft Models**  
- **Oceania (Australia & New Zealand)** shows lower satisfaction across multiple services, indicating a need for **enhanced in-flight offerings**.
- Aircraft such as **A319, A320, and A321** received lower entertainment ratings, indicating a need for Upgrading in-flight entertainment systems on these aircrafts.  

#### **Improve Economy & Premium Economy Experience**  
- Economy and Premium Economy passengers report **lower ratings** for food, beverages, and entertainment.  
- The **quality and variety** of in-flight meals and refreshments can be enhanced.  
- **seat comfort** and **entertainment options** can be tailored for these travelers.  

#### **Monitor Trends & Customer Feedback**  
- The **entertainment rating showed a decline in 2021 and 2023**.  
- We should **Analyze customer complaints and conduct surveys** to pinpoint recurring issues and address service gaps proactively**.  

#### **Considerations for Statistical Validity**  
- The **number of reviews dropped significantly from April 2020 to September 2021**, likely due to reduced travel during COVID-19.  
- When analyzing data by **region (South America & Africa)**, sample sizes are **too small (<30 reviews)** to draw meaningful conclusions.  
- Future studies should **focus on regions with sufficient data** to make statistically valid inferences.  

#### **Next Steps**  
- Conduct further investigations into **entertainment differences by aircraft type** to identify targeted improvement opportunities.  
- Implement **regional service enhancements** based on country-specific trends in **entertainment, food, and service quality ratings**.  
- Use **customer sentiment analysis** to prioritize changes that will have the most impact on passenger experience.  






