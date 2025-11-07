# YULU

## About YULU

  Yulu is India’s leading micro-mobility company that offers eco-friendly electric cycles and scooters to promote sustainable urban commuting. The company’s mission     is to reduce traffic congestion and carbon emissions by providing a convenient and affordable first and last-mile travel solution.

  Recently, Yulu has experienced a decline in revenue and aims to understand the key factors influencing demand for its shared electric cycles. By analyzing             operational and environmental data, the company seeks to improve its fleet utilization, optimize pricing strategies, and enhance user satisfaction.

## Data Source - 
https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/428/original/bike_sharing.csv?1642089089

## Project Objective

### Key Goal – How You Can Help Here

  The project focuses on understanding and modeling the factors that drive ride demand for Yulu’s electric cycles.

  The company wants to know:

  Which variables are significant in predicting the demand for shared electric cycles in the Indian market?

  How well those variables describe and influence electric cycle demand patterns?

To achieve this, the project applies data analytics and statistical methods to identify key demand drivers such as weather, temperature, season, holidays, and user   type. Time-based features (hour, day, weekday) were also engineered from the datetime field to capture daily and weekly usage trends, helping Yulu optimize             scheduling and resource allocation.

## Insights & Recommendations

### Key Insights - 

Season & Weather Influence: Ride demand significantly varies by season and weather (ANOVA, p < 0.05). Fall shows peak demand, while spring and rainy seasons show lower rides.

Working vs. Non-working Days: No significant difference in mean rides (t-test, high p-value), indicating stable usage throughout the week.

Weather–Season Dependency: Chi-square test revealed strong correlation; certain weather conditions are more frequent in specific seasons.

### Recommendations -

Smart Fleet Reallocation: Increase bike availability in high-demand seasons (fall, summer) and reduce during low-demand or poor-weather days.

Time & Day Planning: Prioritize office zones during weekdays and recreational areas during weekends for efficient resource utilization.

Targeted Promotions: Offer discounts and referral programs during low-demand periods to boost engagement.

User Segmentation: Introduce loyalty rewards for registered users and flexible pricing to attract casual users.

Predictive Modeling: Develop a demand forecasting model using temperature, weather, season, and working day features to optimize fleet allocation and pricing dynamically.

## For More Information : [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1MbjWDbYnvltNqc42nk4zy9D9QzMLVmXY?usp=sharing)


  
