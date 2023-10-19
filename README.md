# Client-Segmentation
A variety of approaches aimed at deriving value and business insights from customer segmentation and behaviour.

## Recency Frequency and Monetary value (RFM)

This analysis is feature engineering with the aim of creating metrics capable of dividing customers into segments that make sense for the client's business.

As the name suggests, RFM analysis divides customer behaviour into three variables: recency of last purchase, frequency of purchase and value of purchase.  Our aim is to divide users into 5 categories: New, Champions, Loyal, Promissory, Don't Lose, Hibernating, Lost. 
 
We have used the quintile ranges of the distribution of each of the variables as the division criteria for the 5 categories. And the result was the following segmentation

![image](https://github.com/MuriloHGomes/Client-Segmentation/assets/84083423/b6ca5732-6a0b-4050-85a2-32c32947bbbb)

From a business perspective, after segmentation it is interesting to learn more about the customer profile of each segment found. In this way we can gain insights for direct marketing and customer relationship actions. In the image below we can see the revenue and the average ticket for each segment.

![newplot (1)](https://github.com/MuriloHGomes/Client-Segmentation/assets/84083423/3f5f8050-76c1-49d3-8866-5a5695c9716a)

We found that the Don't Lose (Não Perder) segment currently has the same average ticket as the Champions (Campeões) segment. And also that Lost customers (Perdidos) represent 32% of the company's revenue. Therefore, together with the fact that only 3.5% of customers are loyal (Fiéis), we can assume that the company is struggling to create value and retain good customers. We can then suggest marketing actions such as a loyalty programme with gifts.

The next natural step in this analysis is to understand the flow between classes. Let's assume that, based on the previous result, the company decides to run a new ad focused on the Don't Lose (Não Perder) audience segment. Remember that this is possible because the data has been collected from the company's CRM and the customers have been uniquely identified. It would therefore be possible to target personalised ads to each segment. 

We can see in the following graph that 1 month after the last analysis and since the ad was implemented, the flow of users migrating from Don't Lose to Champions has been very small. In addition, a greater number of Champion users have moved to the Lost segment. 

![image](https://github.com/MuriloHGomes/Client-Segmentation/assets/84083423/8b561570-38f0-4de2-b42c-4917c70eae51)


Therefore, we have evidence that the campaign did not work in this first month. 
