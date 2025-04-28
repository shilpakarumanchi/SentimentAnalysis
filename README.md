# Customer Sentiment Analysis - Equadorian Airways 

## Overview
Equadorian Airways, a European-based airline established in 1974, faced significant challenges due to the COVID-19 pandemic in 2020. As a result of the crisis, the airline reduced its workforce from 42,000 employees by 12,000 jobs. However, with the sharp rebound in travel demand in 2022, Equadorian Airways encountered a labor shortage, leading to the cancellation of over 1,500 flights.  

This project analyzes **global customer review data for Equadorian Airways from 2016 to 2023**. Passengers have rated six key services: **Ground and Cabin Staff, Entertainment, Food, Value for Money, and Seat Comfort**, assigning each a score from **1 to 5**. Additionally, the dataset includes details such as **departure country, seat type, aircraft model**, and other relevant factors for each review.  

The primary objective of this study is to assess whether the **airline’s workforce shortage impacted customer satisfaction**. By analyzing customer reviews, Equadorian Airways can gain valuable insights into **service gaps and areas for improvement** to enhance the overall passenger experience.

## Data Processing
- Python code used to clean the data inconsistencies and  to derive data insights can be found [here](https://github.com/shilpakarumanchi/python/blob/main/BA_cleaning.ipynb)
- Interactive dashboard generated in Tableau can be found [here](https://public.tableau.com/app/profile/shilpa.ln.karumanchi/viz/BA_customerreviews/Dashboard32)

## Executive Summary
![image](https://github.com/user-attachments/assets/3432f2d8-90b3-4d7b-850e-2c1d382db6f9)

- The **overall average rating is 2.9**, indicating **moderate satisfaction** among passengers.  
- **Cabin staff service (3.3)** and **ground service (3.0)** received the highest ratings, showing that customer service on the ground and in-flight staff interactions are well-regarded.  
- **Food & beverages (2.7) and in-flight entertainment (2.7)** received the lowest ratings, suggesting these areas require improvement.
  
## Insights Deep Dive 

### **Time Trends**  
- The **average overall rating remained relatively stable**, but a slight **decline is noticeable in recent years (2021–2023)**.  
- The **number of reviews peaked between 2017 and 2019** and saw a sharp decline during the COVID-19 pandemic (2020).  
- The number of reviews has remained **comparatively lower post-pandemic (2021–2023)**, suggesting a potential **decrease in customer engagement** or a reduced passenger volume.  

### **By Region**  
![image](https://github.com/user-attachments/assets/d52e79cf-c7d4-44d1-9f12-b1efc9db49ec)

- **Asia recorded the highest average rating** (approximately **3.3**), indicating **better customer satisfaction in this region**.  
- **North America (2.9), Africa (2.8), and South America (2.7)** received **lower ratings**, suggesting that Equadorian Airways should focus on improving services in these regions.  
- The **lowest number of reviews came from South America (5) and Africa (22),** making it difficult to draw strong conclusions for these regions and hence are removed from the analysis. 

### **By Seat Type**  
![image](https://github.com/user-attachments/assets/c374acc7-2510-4103-bda7-895b27abc11a)
- **Highest average rating (3.28)** across all seat types.  
- **Best ratings for seat comfort (3.57), cabin staff service (3.85), and food & beverages (3.07)**, indicating a premium experience.  
- **Premium Economy (2.97) slightly outperforms Business Class (2.96)** in overall rating, despite lower food and cabin staff ratings.  
- **Business Class has better food ratings (2.92 vs. 2.61), but Premium Economy has better entertainment (2.83 vs. 2.75)**.  
- **Ground service is the same (3.22 for Premium Economy, 3.01 for Business Class), suggesting consistency in service quality.**
- **Lowest overall rating (2.78), with the weakest scores in all categories.**  
- **Entertainment (2.63) and food (2.39) are particularly poor**, highlighting areas for improvement.  
- **Cabin staff rating (3.15) remains relatively strong, showing that customer service is still a positive factor.**  

### **By Aircraft Model**  
- **The A380 has the highest average rating**, with **124 reviews**, suggesting that larger aircraft provide a better passenger experience.  
- **Boeing 777-200 and Boeing 747-400 also received relatively high ratings**, indicating a consistent performance for these models.  
- **The “Others” category (583 reviews) had more mixed ratings**, requiring further analysis on specific aircraft types in this group.  

### **Recommendations**  

**Enhance In-Flight Entertainment & Food Quality**: Given the **low entertainment (2.7) and food (2.7) ratings**, Equadorian Airways should **upgrade content, improve screen quality, and offer better food options** to enhance the passenger experience.  

**Investigate the Declining Ratings in Recent Years**: Since ratings have shown a **slight downward trend from 2021–2023**, the airline should **analyze customer complaints and surveys** to identify pain points.  

**Improve Services in Lower-Rated Regions**: **North America, Africa, and South America have lower average ratings**, suggesting the need for **targeted improvements** in customer experience.  

**Optimize Aircraft Services Based on Performance**: Since the **A380 and Boeing 747-400 received higher ratings**, Equadorian Airways could **analyze what makes these aircraft perform better and apply similar improvements** to lower-rated models.  

- **Enhance Economy Class amenities**, particularly **food and entertainment**, to improve customer experience.  
- **Leverage Business Class strengths** by **improving entertainment offerings**, making it more competitive with Premium Economy.  
- **Maintain high standards in First Class** while identifying key differentiators that contribute to its success.  
