## Cyclistic Bike-Share Business Case
Converting Casual Riders into Annual Members

Author: Andre Zeni — Business Data Analyst

### Project Summary

This project analyzes historical bike-share trip data from Cyclistic (Q1 2019 vs Q1 2020) to answer a key business question:

How can Cyclistic increase revenue by converting more casual riders into annual members?

Using R, I built a complete end-to-end workflow including data cleaning, descriptive analysis, behavioral segmentation, operational insights, and strategic recommendations for the marketing team.

This repository contains the full, reproducible analysis script and supporting documentation.

### Business Impact

Cyclistic’s revenue model relies heavily on annual members.
However, ride data revealed:

Casual rider trips grew +93% YoY (2019 → 2020)

Member trips grew only +10.7%

Casual riders increasingly used bikes for longer, leisure-oriented trips

### Key Insights
#### 1. Growth Dynamics

Total rides increased +15.9% YoY

Casual segment saw exponential growth

Casual riders represented a growing share of total trips

#### 2. Behavior Differences

Members → shorter rides, weekdays, commuting

Casual riders → longer rides, weekends, leisure hotspots

#### 3. Conversion Opportunity Segments

High-potential conversion groups:

Casual riders taking short/medium rides (<20 mins)

Casual riders riding on weekdays

These riders behave similarly to members.

#### 4. Operational Insights

Longer casual rides increase redistribution pressure

Start/end station analysis identifies tourist vs commuter zones

Optimizing inventory and station capacity supports conversion

### Tools & Technologies

R (Tidyverse, lubridate, ggplot2)

data.table (optional performance version included)

Tableau Public (executive dashboard)

Kaggle (interactive notebook + dataset hosting)

This repo focuses on the analytical R code and documentation.



These insights indicate a substantial untapped conversion opportunity, enabling data-driven decisions around pricing, marketing, and product design.
