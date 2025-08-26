Project Overview


This project applies A/B testing methodology to real-world news data in order to evaluate which factors — such as time of publication or headline style — influence engagement. Data was collected via a public news API, cleaned, and then analyzed using Python libraries.

The project demonstrates practical skills in:

API integration and data acquisition

Data wrangling with pandas

Exploratory data analysis (EDA) and visualization

Statistical testing with scipy

Deriving actionable business insights from real-world data


Objectives

Data Acquisition – Pull article metadata (headline, source, timestamp, category) from a public news API.


A/B Test Simulation – Randomly assign articles into groups:

Group A: Morning (6 AM–12 PM) publications

Group B: Evening (6 PM–12 AM) publications

Alternative variable: Headline length or sentiment score.


Data Cleaning & Exploration – Handle missing values, convert timestamps, and filter outliers.


Analysis & Visualization – Explore article distributions by source, category, and length.


Hypothesis Testing – Conduct a two-sample t-test to compare mean engagement metrics.


Key Insights – Recommend which factor (time or headline characteristic) correlates with higher engagement.

