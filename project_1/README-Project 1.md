# ![]Project 1: Exploring climate data of Singapore


### Problem Statement

You are working for a Havaianas footwear company. The company is looking at ways to optimise their limited resources (i.e. employees, time) to increase their sales revenue for the year ahead. With multiple goals to achieve (i.e. increase footfall, increase sales per transaction, increase no. of pairs of footwear sold), what is the key goal that helps Havaianas increase the sales revenue exponentially with least effort? Their retail shop is impacted by rainy weather conditions too. How can they plan their campaigns ahead to circumvent low sales beforehand?

This project aims to analyse Havaianas retail sales dashboard to identify the key factor that increases sales revenue greatly and the monthly weather patterns over the year to allow the various department team to better plan and allocate resources during the rainy seasons.

---

### Datasets

#### Provided Data

* [`rainfall-monthly-number-of-rain-days.csv`](./data/rainfall-monthly-number-of-rain-days.csv): Monthly number of rain days from 1982 to 2022. A day is considered to have “rained” if the total rainfall for that day is 0.2mm or more.
* [`rainfall-monthly-total.csv`](./data/rainfall-monthly-total.csv): Monthly total rain recorded in mm(millimeters) from 1982 to 2022

#### Additional Data
* [`havaianas_visitors.csv`](../data/havaianas_visitors.csv): Daily total visitors in Havaianas ION Orchard shop recorded in numbers from 1st January 2015 to 31st December 2015
* [`retail_sales.csv`](../data/retail_sales.csv): Retail numbers such as sales revenue, units sold, discounts given, basket size in Havaianas ION Orchard shop recorded from 1st January 2018 to 31st December 2018

---

### Data Dictionary

|Feature|Type|Dataset|Unit of measure|Description  
|---|---|---|---|---|
|total_rainfall|float|total monthly rainfall|millimetres (mm)|the average monthly rainfall recorded in year 2015|  
|traffic_in|float|total number of visitors per month at Havaianas retail shop|number of visitors|the average monthly number of visitors entering the Havaianas retail shop in the year 2015| 


---

### Outside Research

**Article: 8 Important Metrics for Retail Industry KPIs.**

This article explores the key metrics retail industries use to gauge performance. It provides insights that increasing sales volume and foot traffic instores are the top 8 metrics for performance.
https://www.tableau.com/learn/articles/retail-industry-metrics-kpis


**Article: How Seasonal Forecasting Can Affect Your Retail Sales**

This article explores how the weather affects the retail industry and how the use of seasonal forecasting can minimise the risks that weather brings while also driving sales.
https://www.ibm.com/blog/how-seasonal-forecasting-can-affect-your-retail-sales/


---

### Conclusions

**1. Weather Impact on Footfall:**  
A noteworthy observation is the clear inverse relationship between monthly total rainfall and footfall in the retail shop. Specifically, when there is a high amount of total rainfall in a given month, footfall tends to decrease, and conversely, lower rainfall months see an increase in shop visitors.
This weather-dependent trend underscores the importance of recognizing and adapting to seasonal variations, particularly during high rainfall months (February, March, June, July), where targeted marketing campaigns may serve to mitigate the anticipated dip in revenue.  
  
  
**2. Revenue Dynamics:**  
An analysis of revenue drivers revealed that shop revenue is positively linked to the number of visitors, while it shows a tendency to decline as the average sales per receipt and the price of footwear increase.
Notably, attracting more visitors to the shop emerges as a critical factor in augmenting sales revenue. Therefore, strategic efforts should focus on expanding the customer base.
Conversely, the data indicates that increasing prices or promoting higher sales per receipt may not yield the same positive impact on overall revenue and should be approached with caution. 
  

---

### Recommendations

**1. Seasonal Marketing Strategies:**  
Consider implementing targeted marketing campaigns during high rainfall months (February, March, June, July) to counteract the expected decrease in footfall. By engaging potential customers with compelling offers and incentives, the shop can strive to maintain revenue levels during inclement weather.  
  
**2. Footfall Enhancement:**  
Emphasize efforts to increase the number of visitors to the shop. Strategies could include enhancing the shopping experience, expanding product offerings, or utilising effective marketing tactics to attract new customers. A growing customer base has shown a strong positive impact on revenue.  
  
**3. Price and Sales Strategies:**  
Exercise caution when contemplating price increases or initiatives aimed at boosting sales per receipt. Given the observed data trends, the potential impact on overall revenue may not be as substantial as efforts to attract more visitors. Focus on providing value and meeting customer needs to encourage repeat visits and customer loyalty.

---

### Future Work

To further enhance the accuracy and reliability of our statistical analysis, we highly recommend an extended and comprehensive data collection effort that spans multiple years. This comprehensive data may include weather data, footfall statistics, revenue figures, and other key performance indicators. Furthermore, it is essential to ensure data quality and accuracy throughout the data collection process.


---

### Contact Details:
Linkedin: https://www.linkedin.com/in/yvonne-l-1a735344/
Email: yvonneeeelimpz@gmail.com
