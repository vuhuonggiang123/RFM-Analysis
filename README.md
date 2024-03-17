# RFM-Analysis
## Using RFM analysis to segment customers through Python programming
### 1. Introduction
SuperStore Company is a global retail company. So the company has many customers.

On the occasion of Christmas and New Year, the Marketing Department wants to run marketing campaigns to thank customers who have supported the company over the past time. As well as exploiting customers who have the potential to become loyal customers.

However, the Marketing Department has not yet been able to group each customer this year because the data set is too large to be processed manually like in previous years, so they asked the Data Analysis Department to segment customers to deploy each marketing program suitable for each customer group.

The Marketing Director also suggested using the RFM model, but in the past, when the company was small, the team could calculate and classify it themselves using Excel. Currently, the amount of data is too large, so they want the Data Department to build a flow to deploy Segmentation evaluation through Python programming.

### 2. Steps to approach
1. Prepare a data set suitable for the RFM model.
2. Determine how to calculate and calculate R, F, M scores for each customer.
_Note: Calculation date of R index is December 31, 2011"_
3. Provide a calculation method with scoring corresponding to a scale of 1 to 5 (Use the quintile method of Statistics)
4. Based on the classification table to segment customers
5. Visualize the number of segment sets with data dimensions 
6. Analyze the company's current status and give suggestions to the Marketing team

### 3. Insights and Recommendations
![image](https://github.com/vuhuonggiang123/RFM-Analysis/assets/162288604/d7de7180-5169-48e1-bb71-46f1094225ff)
![image](https://github.com/vuhuonggiang123/RFM-Analysis/assets/162288604/a2df655d-9a92-4842-bb5d-f197dcbbf22d)
![image](https://github.com/vuhuonggiang123/RFM-Analysis/assets/162288604/40a8abd3-d312-4c10-9767-29e4a48741f5)
* The company's customers are mainly in the Champions segment with more than 800 people at a rate of 19%. They are new customers who buy frequently and spend the most. This is also the customer segment that generates the main revenue for the company for more than 60% of total revenue. These customers are loyal, willing to spend generously, and likely to make another purchase soon. These are all very potential customers --> Company should take care of and encourage this group of customers to return more by setting up loyalty cards and special incentives for these customers. They are customers we should focus on for gratitude.

* However, there are more than 1,000 customers in the Hibernating customers and Lost customers segment at a rate of 27%. They are customers who have not returned for a long time, have low purchasing volume, purchasing infrequency and small shopping cart value. Lost customers often have buying behavior seeking variety or only buying once to experience and compare with other products and services. However, this number of customers is quite large, if we ignore them, it will cause a big lost of customers -> Company should do market research, find USP (Unique selling point) to convert Lost customer segment, and stimulate customers to buy more.

* The company should also focus on exploiting potential customers such as Loyal, At Risk and Potential Loyalist segment. The two customer segment Loyal and Potential Loyalist account for 19%, this is also the potential customer segment that is easy to convert to the Champions customers. In addition, At Risk customer segment with 423 customers, at a rate of 9.7%. They are customers who have made frequent purchases before with a fairly average shopping cart value. We can come up with a plan to re-attract this customer base by conducting surveys on the reasons why they stop buying
