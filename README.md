# DC Exurb Restaurant Analysis Using Yelp

**Authors:** Jaclyn Dwyer and Gary Schwaeber

![example](Images/Outdoor_Pic.jpeg)

## Overview
The project explores where to open a new restaurant between the DC exurbs of Southern Maryland and Northern Virginia. Yelp data analyzes the success and popularity of different categories of restaurants within these areas. 

## Business Problem 

Yelp data is used to determine where to put a new restuarant between the MD and VA exurbs of DC as well as what type of restaurant. The goal is to find some category of restaurant where there is an untapped or underdeveloped market.

## Data

Yelp users contribute ratings and reviews based on their experiences at a given business. Data sourced from the Yelp API provides information about the cateogry, rating, price, review count, and address of each restaurant. 
 - Review count measures popularity of a business.
 - Rating measures public opinion of a business. 
 - The review data is used to anecdotally support the findings from the business search data.
 

## Methods
The categories for each restaruant are split and placed in separate columns and a new dataframe is created to capture the attributes for each category. The goal is to find a category of restaurants that have high review counts and low ratings. This would show a category where the existing restaurants are popular, but the public opinion of them is low. 

## Results
Steakhouses and Cantonese restaurants have a high average review count and the lowest average rating. This shows an unmet satisfaction for restaruants in those categories.

![graph](Images/main_graph.png)


Steakhouses and Cantonese restaurant metrics are compared between each state to decide which category and where to place the new restaurant. 

![graph2](Images/review_count_graph.png) ![graph3](Images/rating_graph.png) ![graph4](Images/rc_graph.png)


Median household income is higher in VA than MD counties.

![graph4](Images/censusdata.png)


## Conclusion
![example](Images/Dim_Sum_Pic.JPG)

This analysis leads to the recommendation that a Dim Sum Cantonese restaurant in VA shows potential to be the most posperous.
 - Higher average review counts 
 - Lower average ratings 
 - Lower counts
 - Higher median household income in VA 
 
## Next Steps
While the data supports opening a Dim Sum Cantonese restaurant in VA there are some things to further consider and explore. 
 - Yelp data can only shed light on popularity and restaurant sentiment. It does not provide insight on potential profitability.
 - The length of how long a business has been open could bias the average review counts.
 - The current pandemic has changed dining trends which may not be reflected in the historical data from Yelp.


## Repository Structure

```
├── data
├── notebooks
├── Images
├── README.md
├── Yelp_Final_Presentation.pdf
└── Yelp_Final.ipynb
```


