# NY Airbnb Analysis

![image](https://github.com/jasondo-da/NY_Airbnb_Analysis/assets/138195365/ef8cd56a-8b6a-4632-af8f-317b638fdba8)

## Table of Contents

- [Project Introduction](#project-introduction)
    - [NYC Airbnb Project Google Sheet ](#nyc-airbnb-project-google-sheet)
- [Analysis Outline](#analysis-outline)
- [Executive Summary](#executive-summary)
    - [Conclusion](#conclusion)
    - [Key Findings](#key-findings)

## Project Introduction

In this project, I have been hired to be a consultant and assist my client, a real estate investor, in finding a vacation rental property within the Manhattan borough of New York City to invest in. The client seeks our expertise in finding and identifying the properties with the highest ROI based on the current Airbnb listing data. The key focus areas include cleaning and filtering data, determining popular neighborhoods, identifying customer-preferred property sizes, calculating occupancy rates, calculating expected revenue, and other external factors that could affect property performance.

### NYC Airbnb Project Google Sheet 
Full Google Sheet project link.

Link: [NYC Airbnb Project](https://docs.google.com/spreadsheets/d/1Chxvi7KDljdAGcoDFA8jMwv8xXIff41DNOTWdUam3nM/edit?usp=sharing)


## Analysis Outline

1. Explore and Filter the Data

- Filtered data for columns that will not be used for this analysis

- Filtered for Short-Term Rentals

- Included 7 Days or Less Minimum Night Requirements

- Removed listings with no reviews 

- Removed listings that are inactive since within the past year

- Created "neighborhood_clean" column

2. Determine Targeted Property Types


- Created a pivot table to find the most popular listings based on the number of total review

- Highlighted the top 10 neighborhoods by market share popularity

![Top 10 Most Popular Neighborhoods](https://github.com/jasondo-da/NY_Airbnb_Analysis/assets/138195365/562899ed-856b-4c12-8267-8f1e6c8b6022)

- Created a pivot table to compare bedroom size preferences

- Identified the most popular bedroom sizes preferred by customers

![Bedroom Size Preferences](https://github.com/user-attachments/assets/d9973c44-a61f-49af-8cf2-075dd7bb5a6c)


3. Calculate Occupancy Rates

- Created Columns for occupancy and day of the week

- Built pivot table for average occupancy

- Calculated for occupancy rate for each day of the week

![Occupancy Rate](https://github.com/jasondo-da/NY_Airbnb_Analysis/assets/138195365/174f76f8-b015-4003-a1f8-f3d3256681e1)


4. Estimate Revenue for Investment Properties

- Filtered for top 10 neighborhoods with the highest average review score

![Average Tennant Score for Top 10 Most Popular Neighborhoods](https://github.com/jasondo-da/NY_Airbnb_Analysis/assets/138195365/294e5110-3a03-4fb7-a38e-86bdfa22208b)

- Filtered for top 10 neighborhoods with the highest median revenue per visit

![Median Revenue by Neighborhood](https://github.com/jasondo-da/NY_Airbnb_Analysis/assets/138195365/8d1f9f0d-4460-4abd-aea8-309d1ccffe0c)

- Created a discount cashflow model for the properties of interest to find the current intrinsic value

![Discount Cashflow Model](https://github.com/jasondo-da/NY_Airbnb_Analysis/assets/138195365/e7d39d5c-a666-458d-826e-f3de84341140)


## Executive Summary

### Conclusion

In conclusion, depending on our client's appetite for yield and risk, the Lower East Side and Midtown neighborhoods would be the best locations for investing in Airbnb rental properties. The Lower East Side property would be the best for a risk-averse investor and the Midtown location would be better for revenue potential. For the best of both solutions, our client could also diversify their portfolio into both locations to minimize the risk and maximize the gains since they are looking for multiple properties to invest in.

### Key Findings

Based on the scraped data from Airbnb the most desirable neighborhoods in the Manhattan borough would be Lower East Side and/or Midtown New York. Depending on our client’s risk tolerance they can choose to invest in one or the other or even both if they are looking for some diversification in their real estate portfolio.

**Option 1 Lower East Side Property:** The Lower East Side neighborhood is one of the best locations for investors. The Lower East Side neighborhood has the largest market share out of all the Manhattan neighborhoods and can be viewed as one of the fastest-growing neighborhoods. Also, the Lower East Side neighborhood has above the median asking price, displaying that it is a higher demanded location when compared to its peers. Based on its location review it is also very competitive with the other top location review listings. Generally, the bedroom size preference for tenants is 1-2 bedrooms per rental based on the rental data volume by room. In addition, the best time to rent out your Airbnb in this area would be from Wednesday to Saturday based on the weekday demand data. Should there be any decline in the travel sector this location will be the most resilient to decline due to its higher market share. Adding together all these factors, it shows that this neighborhood could be seen as having the most potential for growth during a good market and the most resilient in bad market conditions making this location the best location for a more risk-averse investor. Based on current 2023 economic conditions and the median asking price revenue for a property in this area, the intrinsic value of this cash flow would be about $327,777.

**Option 2 Midtown Property:** The Midtown neighborhood is also one of the best locations for investors. Midtown is a top 5 market share location in the Manhattan area displaying how popular it is among Airbnb users. However, what makes Midtown more special is that it also has the highest asking price when compared to the other highest market share neighborhoods showing that there is a demand so strong for this location that most tenants would pay a premium to stay here over a competing location. When the travel market is doing well this location has the potential to be the highest-grossing revenue location by market share.  The location review for Midtown is also very competitive when compared to the other top 10 locations in market share. Like the Lower East Side neighborhood, the bedroom size preference for tenants is 1-2 bedrooms per rental. Also, the best time to rent out your Airbnb in this area would be from Wednesday to Saturday based on the weekday rental data. However, should there be a decline in the travel market this market will see a more noticeable decline in revenue than the Lower East Side location due to a lower market share popularity and higher asking price for renting. In conclusion, when adding all these factors together, the data shows that when the travel market is strong then the Midtown neighborhood has the highest revenue potential out of the top 10 locations by market share and should be considered by investors who are less risk-averse and desire higher yields. Based on current 2023 economic conditions and on the median asking price revenue for a property in this area, the intrinsic value of this cash flow would be about $339,278.28.

