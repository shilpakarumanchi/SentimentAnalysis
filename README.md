# British Airways Customer Sentiment Analysis

## Overview
British Airways, a UK-based airline established in 1974, faced significant challenges due to the COVID-19 pandemic in 2020. As a result of the crisis, the airline reduced its workforce from 42,000 employees by 12,000 jobs. However, with the sharp rebound in travel demand in 2022, British Airways encountered a labor shortage, leading to the cancellation of over 1,500 flights.  

This project analyzes **global customer review data for British Airways from 2016 to 2023**. Passengers have rated six key services: **Ground and Cabin Staff, Entertainment, Food, Value for Money, and Seat Comfort**, assigning each a score from **1 to 5**. Additionally, the dataset includes details such as **departure country, seat type, aircraft model**, and other relevant factors for each review.  

The primary objective of this study is to assess whether the **airline’s workforce shortage impacted customer satisfaction**. By analyzing customer reviews, British Airways can gain valuable insights into **service gaps and areas for improvement** to enhance the overall passenger experience.

## Data Processing
- Python code used to clean the inconsistencies and  to derive data insights can be found [here](https://github.com/shilpakarumanchi/python/blob/main/BA_cleaning.ipynb)
- Interactive dashboard generated in Tableau can be found [here]([https://github.com/user-attachments/assets/1c6d6e94-16c1-4d8f-b21c-5457e1823a6e](https://public.tableau.com/app/profile/shilpa.ln.karumanchi/viz/BA_customerreviews/Dashboard32))

## Executive Summary
![image](https://github.com/user-attachments/assets/2ff996b7-cc74-4c0f-950a-4bc283b4f559)

- The **average overall rating** is **4.2**, suggesting a decent customer satisfaction level.  
- **Entertainment has the lowest rating (1.4)**, indicating that passengers are significantly dissatisfied with in-flight entertainment.  
- **Food beverages (2.4) and value for money (2.8)** also have relatively low ratings, showing room for improvement in these areas.
  
## Insights Deep Dive
- A total of 1,324 reviews were collected from 56 countries over a seven-year period (March 2016 – October 2023).
- Out of these 56 countries, 42 have fewer than 10 reviews, and 24 have fewer than 5 reviews, making it necessary to group them by continent for meaningful analysis.
- The highest number of reviews came from Europe (1,009 reviews), followed by North America (168 reviews).
- The lowest number of reviews came from South America (5 reviews) and Africa (22 reviews).
- Asia recorded the highest overall rating (3.32), followed by Europe (2.92) and North America (2.88).
- Oceania (Australia & New Zealand) had the lowest average rating (2.58), indicating a potential need for service improvements.
- Among airline services, cabin staff received the highest ratings, followed by ground services.
- Food and beverages received the lowest ratings, followed closely by in-flight entertainment.
- The A380 aircraft had the highest average rating (3.2), while the A320 had the lowest (2.7).
- First-class services consistently received higher ratings, while Economy Class (2.7) and Premium Economy (2.8) had the lowest satisfaction levels across all service categories.
- The **average entertainment rating has fluctuated over time**, with notable declines around 2021 and 2023.  
- The **heatmap suggests variations in entertainment ratings across different countries**, indicating that customer satisfaction is not uniform globally.  
- **A380 and Boeing 747 models have the highest entertainment ratings (2.9 and 2.6, respectively).**  

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






