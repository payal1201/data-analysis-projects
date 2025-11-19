# Delhivery Logistics Performance Dashboard — README

## Project Overview
This project analyzes Delhivery’s logistics performance using feature-engineered trip-level data. The objective is to understand operational efficiency, identify bottlenecks, and highlight improvement opportunities through an interactive Tableau Dashboard.

The dashboard provides a unified view of trip performance, delays, city/state volumes, network efficiency, and delivery reliability, helping stakeholders make informed business decisions.

## Key Objectives
Clean, prepare, and feature-engineer logistics trip data for analysis.

Build a fully interactive Tableau dashboard to monitor operational KPIs.

Identify high-performing cities/states and network bottlenecks.

Evaluate delays, on-time performance, and route-level efficiency.

Present actionable business recommendations.

## Tech Stack
Python: Data cleaning & feature engineering

Tableau: Dashboard creation, interactivity, analytics

Excel / CSV: Data validation

GitHub: Project hosting & documentation

## Dashboard Components
The Tableau dashboard includes:

KPI Tiles
Total Trips

Avg Trip Duration

Avg Delay

On-Time %

Map View
Trips by Destination City

Delay heat-map patterns

Click city → entire dashboard updates

Time Series
Monthly trip volume trend

Average delay over time

Top Cities & Pareto
Top 10 cities by trips

80/20 cumulative contribution

Delay & Route Type Analysis
Delay distribution by route type

Cutoff vs Non-cutoff comparison

Trip Duration Distributions
Histogram

Boxplot

Actual vs OSRM Travel Time
Scatterplot with performance ratios

Details Table
Full route-level drill-down

## Key Insights
Maharashtra leads in overall volume; Gurgaon (Haryana) is the top single city.

A clear Pareto pattern exists — few cities contribute most trips.

On-time performance varies significantly by route type and city.

Some cities show consistent delay hotspots, indicating operational bottlenecks.

Actual travel time frequently exceeds OSRM predictions (factor > 1), hinting at route inefficiencies.

## Recommendations
Strengthen presence in Maharashtra and Haryana for quick volume gains.

Double down in Gurgaon with loyalty and retention campaigns.

Improve service quality in delay-heavy cities to reduce customer dissatisfaction.

Expand in Tier-2 cities showing growing demand.

Regularly analyze route factors to optimize planning and fuel efficiency.

Encourage repeat deliveries through personalized follow-ups.

## Dashboard Explanation
This dashboard is designed to help Delhivery evaluate its logistics network performance across India. It delivers:

Operational KPIs at the top for quick visibility.

Map-based city performance to detect geographic hotspots.

Trend lines to understand monthly delivery patterns.

Pareto analysis to identify high-impact cities.

Delay risk segmentation using route type and cutoff flags.

Network efficiency via OSRM vs Actual time comparison.

Fully interactive drill-down — selecting any city filters all charts.

Each visual was carefully curated for clarity, decision-making, and executive-level storytelling.

[![Open Story on Tableau Public](https://img.shields.io/badge/Open%20Story-Tableau%20Public-blue?logo=tableau)](https://public.tableau.com/app/profile/payal.shrawankar/viz/DelhiveryDashboard/InsightsRecommendations?publish=yes)

[![Open Dashboard on Tableau Public](https://img.shields.io/badge/Open%20Dashboard-Tableau%20Public-orange?logo=tableau)](https://public.tableau.com/app/profile/payal.shrawankar/viz/DelhiveryDashboard/InsightsRecommendations?publish=yes)


