**Problem Statement**

**CONTEXT**

Retail Rocket is a company that provides personalized real-time recommendations for web shoppers. Retail Rocket's services typically involve utilizing recommendation algorithms to analyze user behavior, preferences, and historical data to deliver personalized product recommendations.

Retail Rocket typically starts by collecting and analyzing user behavior data. This data includes information on users' browsing history, product views, clicks, purchases, and other interactions on the e-commerce platform

The dataset consists of three files: a file with behaviour data (events.csv), a file with item properties (item_properties.сsv) and a file, which describes category tree (category_tree.сsv),The behaviour data, i.e. events like clicks, add to carts, transactions, represent interactions ,A visitor can make three types of events, namely “view”, “addtocart” or “transaction”

Task : To predict properties of items in "addtocart" events based on "view" events, Implement collaborative filtering to find patterns based on user behavior i.e. Whether the user has view the items that 'added to the cart or not'.
Recommeder system creates a similarity between the user and items and exploits the similarity between user/item to make recommendations.

What recommeder system can solve ?

It can help the user to find the right product.
It can increase the user engagement. For example, there's 40% more click on the google news due to recommendation.
It helps the item providers to deliver the items to the right user.In Amazon , a decent amount of products get sold due to recommendation.
It helps to make the contents more personalized.
Recommender system Problem Domain/Statement
This notebook implements a ecommerece reocmmender system

Recommender system are used to suggest products based on their intrest or usage history.

For example, Amazon recommends products to purchase based on thh prievous items the cusotmer has bought from the site

In this project, I used item-based collabraive filter, Also used logisitc reression to help find any false posivie son the possible recommendations given out to clients

*****************************************************************************************************************************************************************************************
Business Metrics 
1) Converstion Rate
2) Churn Rate
3) Retention Rate
   
*****************************************************************************************************************************************************************************************
Solution

1)Analyzed who are the visitors who are buying 

2)visitors who are just viewing and added the item to the cart but never bought anything

3)Recommended items based on items bought together in previous purchase

4)Recommended items based on items in the same category

5)Got the conversion rate for each product

6)Got the churn rate of customers

7)Training the model using logistic regression

8)Predicted the sales of each product

9)Prepared the list of items that model predicted there will be no sales. Need to send this to ad campaign to improve the sales of those products or RetailRocket should stop buying these from vendors

8)Prepared the list of visitors who are not buying and just viewing and adding to cart to send to ad campaign

9)Prepared the list of churned customers to send to ad campaign to give customized deals to retain the customer
