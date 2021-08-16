# Surfs Up
## Climate analysis for a surf and ice cream shop business venture in Oahu, Hawaii
### Overview
This analysis includes a comparison of temperature data from June and December in Oahu in order to determine the feasibility of keeping the business open year round. In order to complete this analysis, weather data from multiple years was uploaded to Jupyter Notebook in order to use Python and Sqlalchemy to filter the data by specific months and put that data into seperate data frames. Then, a statistical analysis was performed on the data frames in order to compare the data between the two months.

### Results
The results of the statistical analysis for June and December are below:

![June_Summary](June_Summary.png) ![Dec_Summmary](Dec_Summary.png)

- Despite the mean temperature for December being almost 4 degrees lower than June, both mean tempatures are in the 70s, which is great weather for surfing and ice cream.
- One concern with December weather is that the temperature at the 25% percentile is lower than 70 degrees, which means there will certainly be days that may be too cold to draw customers. The 25% percentile for June is still above 70 degrees.
- While the max temps for June and Dec are only two degrees depart (83 degrees for Dec and 85 for June), there is a bigger difference when it comes to min temps. The difference there is 8 degrees, with a chilly 56 degrees for December and a milder 64 for June.
- Overall, June has a larger frequency of days above 80 degrees compared to December.
- Both months have low standard deviations and temperatures are largely centered around the mean, suggesting that there is not a large variation in tempature during these months. Plots of the data are below:




