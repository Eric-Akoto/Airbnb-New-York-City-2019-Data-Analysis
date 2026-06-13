# Airbnb New York City 2019 Data Analysis
![Image Alt](https://github.com/Eric-Akoto/Airbnb-New-York-City-2019-Data-Analysis/blob/main/Screenshot.png?raw=true)
## Project Overview
This project analyzes Airbnb listings in New York City using the AB_NYC_2019 dataset. The objective was to explore pricing patterns, room type distributions, host activity, availability trends, and customer review behavior to generate business insights that can support hosts, investors, and travelers in making informed decisions.
The analysis was conducted using Microsoft Excel, Power Query, Pivot Tables, Pivot Charts, and dashboard visualization techniques.
_______________________________________________________________________
## Objectives
The main objectives of this analysis were to:
-	Understand how Airbnb prices vary across neighborhoods and boroughs.
-	Determine how room types influence listing prices.
-	Identify the most common room types available in New York City.
-	Examine the relationship between listing availability and pricing.
-	Analyze host activity and identify hosts managing multiple properties.
-	Investigate the impact of customer reviews on pricing.
-	Discover geographical patterns in Airbnb listings.
_______________________________________________________________________
## Dataset Description
Data Source: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data.

The dataset contains Airbnb listings across New York City in 2019.
Key Variables
| Variable | Description |
|----------|-------------|
| `id` | Unique listing identifier |
| `name` | Description of listing |
| `host_id` | Unique host identifier |
| `host_name` | Name of host |
| `neighbourhood_group` | Borough location |
| `neighbourhood` | Specific neighborhood |
| `latitude` | Geographic latitude |
| `longitude` | Geographic longitude |
| `room_type` | Type of accommodation |
| `price` |	Nightly rental price |
| `minimum_nights` | Minimum booking requirement |
| `number_of_reviews` | Total reviews received |
| `last_review` | Latest Review Date |
| `reviews_per_month` |	Average monthly reviews |
| `calculated_host_listing_count` |	Average monthly reviews |
| `availability_365` | Number of available days per year |
_______________________________________________________________________
## Data Cleaning and Preparation
Several preprocessing steps were performed before analysis:
1. Imported the dataset using Power Query.
2. Identified and Removed errors and null values in:
   
        -	host_id
        -	host_name
        -	longitude
        -	last_review
        -	reviews_per_month
4. Normalized data in the "name" column.
5. Verified data types for dates, numbers, and text fields.
6. Added new columns to the dataset:
   
        -	availability_range
        -	review_range
_______________________________________________________________________
## Analysis Methodology
The analysis was performed primarily using Pivot Tables and Pivot Charts.
The following analytical questions were investigated:
### Pricing Analysis
1. Which neighborhoods and boroughs have the highest Airbnb prices?
Median pricing was analyzed across neighborhoods and boroughs to identify premium Airbnb markets.

2. What is the relationship between availability and price?
Listings were grouped by availability ranges and compared against average pricing to identify occupancy and demand patterns.

3. Are highly reviewed listings more expensive?
Average prices were compared across review categories to understand whether highly reviewed listings command premium rates.
_______________________________________________________________________
### Room Type Analysis
1. Which room type is most common?
   
The distribution of:

        -	Entire Home/Apt
        -	Private Room
        -	Shared Room
   
was analyzed to determine market composition.

3. How does room type affect pricing ine each borough?
Room types were compared using median prices to determine how accommodation style influences listing value across boroughs.

4. Which room type has the best balance between affordability and reviews?
Room types were grouped by median pricing and compared against average number of reviews to identify the room type with the best balance between affordability and customer engagement.

5. How are room types distributed across boroughs?
Room type counts were analyzed by borough to identify regional preferences.
_______________________________________________________________________
### Host Analysis
1. Who owns the most listings?
Hosts were ranked according to the number of listings managed.

2. Which hosts generate the highest potential revenue?
Revenue estimates were calculated using listing prices and host portfolios.

3. What percentage of listings belong to multi-property hosts?
Hosts were categorized into:

        -	Single-property hosts
        -	Multi-property hosts
   
to evaluate market concentration.

5. How are host listings distributed across boroughs?
Host activity was analyzed geographically.
_______________________________________________________________________
## Key Findings
### Pricing Insights
-	Significant price differences exist between boroughs.
-	Premium neighborhoods command substantially higher rates.
-	Location is one of the strongest determinants of Airbnb pricing.
-	Availability shows an inverse relationship with price in many cases, suggesting higher-priced listings experience stronger demand.
-       Highly reviewed listings are the least expensive listings, while rarely reviewed listings are the most expensive.
### Room Type Insights
-	Entire Home/Apt listings are the most expensive accommodation type.
-	Private Rooms represent a large portion of the market and offer lower-cost alternatives. They have the best balance between affordability and customer engagement. Private rooms are also more popular in all the boroughs except Manhattan.
-	Shared Rooms are the least common and least expensive category.
-	Room type strongly influences pricing behavior.
### Host Insights
-	A relatively small group of hosts manages a large share of listings.
-	Multi-property hosts contribute significantly to overall market supply.
-	Certain hosts operate on a commercial scale rather than as occasional renters.
-	Host activity is concentrated in major boroughs with high tourism demand.
-       Michael is the host with the most listings while Sonder (Nyc) generates the most revenue among the hosts.
### Review Insights
-	Listings with strong review activity generally indicates higher customer engagement.
-	Reviews can influence booking performance and perceived value.
-	Customer feedback serves as an important indicator of listing popularity.
_______________________________________________________________________
## Business Recommendations
Based on the analysis, the following recommendations are proposed:
For Hosts
-	Consider offering Entire Home/Apt accommodation where feasible, as they command higher prices.
-	Maintain high review scores by providing excellent guest experiences.
-	Optimize availability to balance occupancy and revenue.
For Investors
-	Focus on neighborhoods with strong demand and favorable pricing trends.
-	Evaluate borough-level market opportunities before investing.
-	Analyze occupancy indicators alongside pricing metrics.
For Airbnb
-	Monitor the growing influence of multi-property hosts.
-	Encourage review participation to improve platform trust.
-	Develop targeted strategies for underperforming neighborhoods.
_______________________________________________________________________
## Tools Used
-	Microsoft Excel
-	Power Query
-	Pivot Tables
-	Pivot Charts
-	Data Cleaning Techniques
-	Exploratory Data Analysis (EDA)
-	Dashboard Design
_______________________________________________________________________
## Conclusion
This project demonstrates how descriptive and exploratory data analysis can uncover valuable insights from Airbnb market data. The findings reveal that location, room type, host behavior, and customer engagement all play important roles in determining listing performance and pricing. These insights can support strategic decision-making for hosts, investors, and platform managers while providing a foundation for future predictive analytics and machine learning applications.
