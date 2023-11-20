# Geographical-Clustering-of-Potential-SubMarkets
A collective effort that involved using Python and Power BI to make a custom tailored GIS for Meritage Homes
![image](https://github.com/yumnazia/Geographical-Clustering-of-Potential-SubMarkets/assets/12965968/6dae5b72-9853-489e-8f14-f0bb7bedd759)

This project involved defining submarkets for Maricopa & Pinal counties in Arizona for Meritage Homes - a real estate company, to help identify potential areas to focus on for the development of Family houses, Luxury homes and old-age communities. 

The project involved combining data from various sources such as ESRI, Zillow, and MetroStudy to understand:
1. Availability of land and the number of days it has been available in the market
2. Demographics (age, income, etc)
3. Vacant development lots
4. Number of Schools and business centers

Based on the intial analysis we did, These graphs depict strong correlation among Average House Value and Average Income Per Household.
![image](https://github.com/yumnazia/Geographical-Clustering-of-Potential-SubMarkets/assets/12965968/06f7e750-e21e-4f70-afff-c40937950287)

We did elbow analysis for k-means clusters. The clusters formed indicated that the house value increases, the average house income increases, the crime index decreases and the number of days in market increases which also makes sense and luxury family houses ideally should be in a secure area close to schools and job centers and the more expensive a property, the more time it takes in getting sold.
![image](https://github.com/yumnazia/Geographical-Clustering-of-Potential-SubMarkets/assets/12965968/636f2158-5888-4342-8ea8-b7853ea76466)

Given the distinct features associated with property type, we established that it would be better if we have a dashboard with individual pages for different kinds of properties given the individual features that correspond to ranking. 

such as, for single family homes, Number of schools, number of businesses, education rate were dominant attributes to consider, for Old age communities, number of hospitals, population density and median age by zipcode were important, as for luxury homes, median age and number of hospitals came out to be the highest correlated attributes. 

### Process Flow for dashboard usage:
![image](https://github.com/yumnazia/Geographical-Clustering-of-Potential-SubMarkets/assets/12965968/03171627-5a19-4747-a568-4e90b08b8e7b)

### Limitations:
The data we gathered and used for development of this dashboard was static. In order to stay up-to-date, we'd need to refresh the data from time to time. 

Power-BI limited functionality - as we only had access to the free version of Power BI for this project, we encountered a few limitations with privacy and accessibility being on top. 


