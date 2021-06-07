# PyBer_Analysis
## Objective:
- An exploratory analysis of ride-sharing data from the PyBer app reveals trends across Urban, Suburban, and Rural city types. This data will be used to drive decision making regarding access and affordability across markets. 

## Resources:
- https://github.com/mcarson16/PyBer_Analysis/blob/main/Resources.zip
- Software: Python 3.7.6, Anaconda Navigator, Jupyter Notebooks, Pandas, Matplotlib

## Overview of Analysis:
- In the first analysis, a bubble chart models the relationship between supply of drivers, average fare, total number of rides per city, and city type (Urban, Suburban, or Rural). 
  - Additional illustration of these trends is modeled in Figs 2 through 7 in the Resources folder.
- In the second analysis, Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver are summarized by City Type. A layered line chart models trends over time for Total PyBer fares in Rural, Suburban, and Urban cities.

## Results:
- https://github.com/mcarson16/PyBer_Analysis/blob/main/PyBer%20Analysis.zip

### Initial Analysis:
![image](https://user-images.githubusercontent.com/83254435/120947673-d2c7b780-c705-11eb-9304-21f11f4e213d.png)
- Average Fares are highest in rural areas, but usage is the lowest of the 3 categories. This is likely due in part to the low supply of drivers, but could also be influenced by the greater distance between locations that is common in rural areas. While there are fewer total rides, the rides themselves are longer, and therefore more expensive.
- Average Fares are lowest in urban areas, but usage is the highest of the 3 categories. The supply of drivers is higher, which could contribute to the lower average fare. In addition, urban destinations tend to be closer together, which allows drivers to take numerous small fares in a short window of time.

### Second Analysis:
![image](https://user-images.githubusercontent.com/83254435/120947779-2c2fe680-c706-11eb-897c-21fedd86e7d7.png)

![image](https://user-images.githubusercontent.com/83254435/120945229-dbb48b00-c6fd-11eb-9bc1-09756155f426.png)
- The findings are consistent with the initial analysis. 
  - Across the sample of dates, Total Fares, Total Number of Rides, and Total Number of Drivers are highest for Urban Cities and lowest for Rural Cities.
  - Conversely, Average Fare per Ride and Average Fare per Driver are highest for Rural Cities and lowest for Urban Cities. 
- Usage of the service increases in all 3 categories in late February. This is most likely because of Valentine's Day. This is also the only spike in usage that occurs uniformly across the markets.
- The highest usage for the Rural city type occured at the beginning of April. A similar rise occured in the Urban city type, but not in the Suburban city type.

## Summary:
- Holidays present an opportunity to increase usage across city types. The use of incentives like discounts, or an increase in advertising in the weeks leading up to major holidays, could drive higher service usage in otherwise disparate markets.
- Demand for rides is lower in rural areas, which could be due to any combination of factors such as low population density, large distance between locations, lower average income, etc. The supply of drivers is also low, which limits access. Attempts to recruit a larger supply of drivers must consider the fact that fares are less frequent, though they do tend to be longer distance and therefore higher value.
- Marketing efforts are perhaps better spent with greater focus on the Suburban and Urban markets, where there are more potential customers and drivers, and desirable fare locations are both more common and closer together.
