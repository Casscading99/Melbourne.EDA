# Melbourne.EDA
Brief but in-depth analysis of a Dataset from Kaggle. 

 **Melbourne Housing Market Analysis**

I did some research on the Melbourne housing market and cleaned the data. Explored the market and used a dataset of more than 13,500 property sales. I found price trends, removed data points, and gave a picture of the real estate value.

**The Data Pipeline**

I followed a data science workflow for the analysis. The workflow kept the results reliable.

Data Cleaning:
- Handled values in BuildingArea and YearBuilt.
- Converted category data (Suburbs, Types) for grouping.Outlier Detection (Z‑Score):  
- I applied a Z‑score threshold of |z| > 3 to find properties.  
- I flagged 232 properties with prices that were pulling the average.
- 
**Exploratory Analysis:**  
- I checked how the physical attributes of rooms and Bathrooms relate to market price.  
- I checked the impact of Distance, from the CBD on property value.  

**Insights**
- price drivers: Rooms and Bathrooms have a link to the price ofabout 0.50.  
- Property type impact: Houses cost more than Units and Townhouses in the Melbourne area.Distance Factor: A clear negative correlation exists between distance from the city center and property cost.
