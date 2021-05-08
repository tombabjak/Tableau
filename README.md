# Tableau HW: Week 20 - NYC Citi Bike Data Analysis

Tom Babjak   
08May2021   
Tableau Story: https://public.tableau.com/profile/thomas.babjak#!/vizhome/HW_20_16204921968000/Story   

Analysis:

How does the average trip duration change by age?   
- In 2019, the average trip duration in NYC was highest among 16 year olds (almost 26 minutes), and leveled off to ~14 minutes after age 30
- This genearl trend continued into 2020, but with slightly higher averages (almost 32 minutes among age 16, leveling off to ~18 minutes after age 30)
- In both years, a slight 'bump' can be seen at age 30
  - One potential explanation could be higher usage among commuters around this age group
- Likewise, a small increase is observed in 19 year olds compared to younger users
  - College students going to class within biking distance of their living space could explain this slight bump
- Outliers/Issues:
  - A huge spike is observed in users born in 1970, most likely caused by the defaulted year when signing up for an account
  - Data was filtered for people born only in 1971 or later  
  - Y-axes for line graphs were inexplicably altered after uploading to Tableau Public

How does the proportion of short-term customers and annual subscribers change?   
- In 2019, Citi Bike subscribers accounted for ~86% of all trips
- In 2020, subscriber usage decreased to just over 76% of all trips
  - Increased usage by one-time customers, almost doubling
- While total usage in 2019 demonstrates an increase after the winter months, there is a dip in March-April of 2020 before beginning to increase
  - Most likely due to COVID-19 restrictions and social-distancing practices put into place at that time
  - Regardless, NYC in 2020 had around 1,000,000 more trips than in 2019
- Total rides peak in September in both years
- Outliers/Issues:
  - Customers count as both 24-hour pass and 3-day pass users, though these are not distinguished in the original data tables

So far, what has been the course of station popularity in 2021?     
- The map demonstrates each station's 'start trip' usage by day, from January 01 to March 31, 2021
- Station usage generally increases as warmer whether permits more ideal conditions for biking
- Stations in red are among the more 'popular', with more than 100 starttrips recorded in a single day
- Station ID 457 had the highest count of trips in a single day on March 27, with 565 trips started.
  - Followed closely by Station ID 2006 with 528 trips 
  - Both are located on the edge of Central Park in the densely-populated 10019 zipcode, aka Midtown West
- Outliers/Issues:
  - Little to no data was recorded between February 01 and February 02, 2021 
  - "The National Weather Service says that the February 1st snowstorm...had 17.2 inches of snowfall in Central Park, as of 7 a.m. on Tuesday. That puts it in the top 20 NYC snow storms on record, clocking in at number 17."
  - Source: https://gothamist.com/news/where-does-february-1st-snowstorm-rank-all-nyc-snow-events

