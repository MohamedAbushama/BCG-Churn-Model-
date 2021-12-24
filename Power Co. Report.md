# Churn Analysis Report

## Content

> 1. Introduction
> 2. Importing And Loading datasets 
> 3. Exploring Datasets
> 4. Wrangling and Cleansing
> 5. EDA
> 6. Feature Engineering
> 7. Segmentation
> 8. Prediction Models 
> 9. Key Findings
> 10. Recommendation

### Introduction

***We have three datassets one includes features of the power company SME clients, one for the history consumption and prices, and last one for the target feature which is churn instance, the business Problem is to figure out which are the most effective features have a tangible impact on our target feature, and what is recommended for the power company as a way to reach minimum churn rate for those clients by using these data through statistical modelling and prediction modelling as well***

# Conclusion 

> 1. Only 10 % of the dataset are churned clients.
> 2. We have discovered that churned clients have the highest electricity consumption in January and the loyal clients in April
> 3. For Gas consumption churned clients have the highest in March and loyal clients in April.
> 4. The highest churn rate in 2016 was in Feb, Mar, June & Nov.
> 5. The highest electricity consumption rate for loyal clients is in May with the least in September, while for churned the highest is in January.
> 6. We saw that the price energy for the first period of churned clients is higher than the price range for the same period for loyal clients and the range for both in the second period
> 7. Around 15 % of the total clients number are Gas clients.
> 8. 8 % of the gas clients are churned the rest are loyal 
> 9. 10 % of Non_Gas clients are churned 
> 10. We observed that the higher the contract period the less probability of the client to churn.

> 11. We found that May and July have the highest electrical consumption in 2016
> 12. May and November has the highest gas consumption 
> 13. Churned Companies consumed the most at January
> 14. Most churned clients have churned in January and February 
> 15. Most of Gas clients churned in Febeuary and April
> 16. February has the highest price in the first period & second period, and we got that gas and non gas companies highest churn rate was January and February 
> 17. from the above barplot we can see that loyal companies have higher mean contract period  than churned clients
> 18. loyal Gas clients have slightly highest contract duration than non-gas clients.
> 19. churned gas clients have lowest contract duration than non-gas clients


### Recommendation 

##### After creating the logistic regression model adn predict the probaility of churn for easch price point we estimated the price elasticity of demand and we found that the consumer most likely is price sensitive so the discount factor will be of high impact if we need to reduce the churn rate for those companies which have churned by a calculable amount .

#### The churned customers represents about 10% of the SME clients 

##### Predictive churn model can predict the companies going to churn, although the customer is price sensitive but the most factors affect the churn rate are consumption and net margin 

##### Discount of 20% will be effective in reducing churn rate, but with taking into consideration carefully for which customers, maybe we could provide the highest valuable customer with the highest churn probabilities 


```python

```
