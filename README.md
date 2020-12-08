# **Womens-E-Commerce-Clothing-Reviews**
![tips-for-buying-womens-clothes-online-main-image-1160x720](https://user-images.githubusercontent.com/70929605/101458204-91944d80-3904-11eb-8a31-de04610f85e7.jpg)



## **Table of Content**

[Overview](https://github.com/schoi15-umbc/Womens-E-Commerce-Clothing-Reviews#overview)-
[Goals](https://github.com/schoi15-umbc/Womens-E-Commerce-Clothing-Reviews#goals) -
[Motivation and Background](https://github.com/schoi15-umbc/Womens-E-Commerce-Clothing-Reviews#motivation-and-background) -
[Data](https://github.com/schoi15-umbc/Womens-E-Commerce-Clothing-Reviews#data) -
[Project Info](https://github.com/schoi15-umbc/Womens-E-Commerce-Clothing-Reviews#project-info) 


## **Overview**
This project's goal is to help the E-Commerce company with their promotion plan and goes step by step from Data Cleaning, Exploratory Data Analysis (Visualization & Correlation), Modeling & Evaluation, and conclusion. In data cleaning, I try to find missing values and outliers, in EDA I have included basic information about the dataset being used along with several visualizations for better understanding. In modeling and evaluation, three different models, Logistic Regression, Decision Tree, and Random Forest are performed along with confusion matrix to evaluate our models All of our models end up getting a high accuracy score. 

<pre>
Executive Code  : <a href=https://github.com/schoi15-umbc/Womens-E-Commerce-Clothing-Reviews/blob/main/Codes/Technical_Notebook_withSummary.ipynb>Executive Notebook </a> </a>

</pre>

## **Goals**
1. Data Preparation     : Cleaning data, and creating visualizations for deeper understanding of the dataset. 
2. Classification Model : Using differenct Machinle Learning Algorithms such as Logistic regression model , Decision Tree model ,and Random Foreset to evaluate and find the best  accuracy for our prediction. 
3. Busuiness Goal       : The E-commerce company's annual goal is ot increase the number of customers. Our goal is to have our existing customers bring in new customers based off of a review rewards program. The more number of reviews and reccomendations that the customers submit, they get points to use for their next purchase. As a data scientist of the company, my team will be using the data that the compnay has collected and apply different regression models to predict the accuracy of customer reccomendations. 

## **Motivation and Background**
![vector-illustration-monitor-with-tent-online-shop-words-vector-illustration_100456-105](https://user-images.githubusercontent.com/70929605/101458164-85a88b80-3904-11eb-8248-73816520ca39.jpg)

E-Commerce is currently one of the fastest and dynamically evolving industries in the world, and data science/ machine learning is playing a huge role in it. There are 5 data science projects that every e-commerce company should do. First is to create a reccomendation system, which is a a subclass of information filtering system that seeks to predict the “rating” or “preference” a user would give to an item. Some popular recommendation systems are Collaborative filtering, Content Based Filtering, and Hybrid Recommendation Filtering. Second is Customer Lifetime Value Modelling, which predicts the net profit attributed to the entire future relationship with a customer. It helps the e-commerce company in several ways such as defining objectives for the company, optimising business marketing strategies, adjusgting campaign and advertisement, and so on. Thrid is Customer Retention- Churn Model, which refers to the ability of a company or product to retain its customers over some specified period.Having a solid number of customers help because they attract new customers to the company, along with providing feedbacks. And finally, Fraud detection system and improved customer service system is important. By using data science and machinle learning for these, the E-commerce company will be able to make improvments in their busienss. 
[Reference Article]( https://towardsdatascience.com/5-data-science-project-every-e-commerce-company-should-do-8746c5ab4604).


At the Spark+AI SUMMIT 2019, 2 data scientists from the company Wehkamp, Jerry Vos and Arnoud de Munnik, had a conference titled 'Applied Machine Learning for Ranking Products in an Ecommerce Setting'. Wekham is an As a leading e-commerce company in fashion in the Netherlands, and their data science team developed various machine learning projects based on the large scale dtata of products and customers they had with using Spark. Specifially focusing on the ranking of products, the team were able to use Spark on retrieving and processing the search phrases and their results, making click models, creating feature sets, training and evaluating ranking models, pushing the models to production using ElasticSearch and creating Tableau dash-boarding. You can watch the conference and get more details [here.](https://databricks.com/session_eu19/applied-machine-learning-for-ranking-products-in-an-ecommerce-setting) 



## **Data**
The dataset is obtained from [Kaggle (Women’s Clothing E-Commerce dataset)](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews). The dataset was taken from real commercial data and has been anonymized along with replacing the company's name in the review text and body to  “retailer”. There are 23486 orders and 10 different features containing categorical and numerical data, which are explained in detail below. 

1) Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.

2) Age: Positive Integer variable of the reviewers age.

3) Title: String variable for the title of the review.

4) Review Text: String variable for the review body.

5) Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.

6) Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended. This will be our target variable.

7) Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.

8) Division Name: Categorical name of the product high level division.

9) Department Name: Categorical name of the product department name.

10) Class Name: Categorical name of the product class name.


## **Project Info**

<pre>
Software Requirements
Language/Tool: Python (Anaconda)
Libraries: pandas, seaborn, numpy, matplotlib, sklearn, scipy
</pre>

<pre>
Related Studies

1. Agarap, Abien Fred. (2018). Statistical Analysis on E-Commerce Reviews, with Sentiment Classification using Bidirectional Recurrent Neural Network. 

2. MOE, W., & TRUSOV, M. (2011). The Value of Social Dynamics in Online Product Ratings Forums. Journal of Marketing Research, 
48(3), 444-456. Retrieved December 8, 2020, from http://www.jstor.org/stable/23033850

3. Munnik, A. D., & Vos, J. (2019, October). Applied Machine Learning for Ranking Products in an Ecommerce Setting. Conference session presented at Spark+AI SUMMIT 2019. from https://databricks.com/session_eu19/applied-machine-learning-for-ranking-products-in-an-ecommerce-setting

4. Zhu, F., & Xiaoquan (Michael) Zhang. (2010). Impact of Online Consumer Reviews on Sales: The Moderating Role of Product and Consumer Characteristics. 
Journal of Marketing, 74(2), 133-148. Retrieved December 8, 2020, from http://www.jstor.org/stable/20619095


</pre>

<pre>
Contributors : <a href=https://github.com/schoi15-umbc>Sooyeon Choi</a>
</pre>

<pre>
Duration     : December 2020
Last Update  : 12.08.2020
</pre>
