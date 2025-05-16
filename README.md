# Project 1: Data Analysis and Insight of Cost of Living dataset 
## Data Overview: 
The "Cost of Living" dataset contains information on cost of living and average monthly income across various countries and regions from 2000 to 2023. It provides insights into economic conditions, geographical location, and time periods influence affordability and financial stability. 

This dataset could be sourced from economic reports, government databases, or financial surveys.
The data consists of 202 rows (country-year combinations) and 5 columns (variables), capturing essential details about income levels, living expenses, and regional distinctions.
## Data Cleaning
Missing Value: 
* There are 2  missing values in Average Monthly Income. I deleted completely those values to prevent inaccurate calculations as income data is crucial for affordability analysis.
* The other missing values are in the Region. In this case, I assigned the correct region based on country names.

Duplicate rows:
* There are 2 duplicate values found and removed.
## Descriptive Statistics
Insight 1: Income Levels Reveal Regional Disparities
![image](https://github.com/user-attachments/assets/d971420f-940e-4dc7-906f-fa8812e3b384)

Figure.1. Average Monthly Income across six regions

From 2000 to 2023, Africa has the highest average monthly income at about 4695, while North America has the lowest at around 3764. This data highlights regional variations in income levels, with Africa and Oceania leading in higher income averages among the regions listed.

Insight 2: Cost of Living Varies Widely Across Regions
![image](https://github.com/user-attachments/assets/afec8b3c-bc28-498e-9df9-8fa0b71815ac)

Figure.2. Average Cost of Living across six regions

Over the same period, Africa recorded the highest average cost of living at around 3963, while Europe has the lowest at approximately 3554. Oceania and North America also show relatively high costs of living, close to Africa's. Asia and South America have mid-range values, indicating a moderate cost of living in these regions. This data highlights the variation in living expenses across different regions globally.
