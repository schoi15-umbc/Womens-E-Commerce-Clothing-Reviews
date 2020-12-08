# **Womens-E-Commerce-Clothing-Reviews**
![tips-for-buying-womens-clothes-online-main-image-1160x720](https://user-images.githubusercontent.com/70929605/101458204-91944d80-3904-11eb-8a31-de04610f85e7.jpg)



## **Table of Content**

[Overview](https://github.com/schoi15-umbc/Womens-E-Commerce-Clothing-Reviews#overview)-
[Goals](https://github.com/schoi15-umbc/Womens-E-Commerce-Clothing-Reviews#goals) -
[Motivation and Background](https://github.com/schoi15-umbc/Womens-E-Commerce-Clothing-Reviews#motivation-and-background) -
[Data](https://github.com/schoi15-umbc/Womens-E-Commerce-Clothing-Reviews#data) -
[Project Info](https://github.com/schoi15-umbc/Womens-E-Commerce-Clothing-Reviews#project-info) 


## **Overview**
This project is to see if we can predict diabetes based on 8 different factors by using Logistic Regression model and Decision Tree model, and finding out which factor affects the outcome the most. 

<pre>
Executive Code  : <a href=https://github.com/schoi15-umbc/Diabetes/blob/main/Codes/Diabetes_Report.ipynb>Executive Notebook </a> </a>

</pre>

## **Goals**
1. Data Preparation     : Cleaning data, and creating visualizations for deeper understanding of the dataset. 
2. Classification Model : Logistic regression model , Decision Tree model ,and Random Foreset were used and evaluated to find the highest accuracy in our prediction.

## **Motivation and Background**
![vector-illustration-monitor-with-tent-online-shop-words-vector-illustration_100456-105](https://user-images.githubusercontent.com/70929605/101458164-85a88b80-3904-11eb-8248-73816520ca39.jpg)


According to CDC's National Diabetes Statistics Report, 10.5% (34.2 million people) of USA's total population had diabetes in 2018's records. When looking at the reports over the years, it is clear that the rate is increasing yearly. In 2000, the percentage of people with diabetes was 4.4%, which means that is has more than doubled over 18 years. This caught my attention and encouraged me to look into data about diabetes. I will be looking at the different health factors and see which influences a patient to have diabetes, along with predicting diabetes with the different factors. 

## **Data**
The dataset is obtained from [Kaggle (Women’s Clothing E-Commerce dataset)](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews), originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient (female, over age 20) has diabetes, based on certain diagnostic measurements included in the dataset. It includes 2000 observations, each representing an individual. 
There are 9 Columns: 

1) Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.

2) Age: Positive Integer variable of the reviewers age.

3) Title: String variable for the title of the review.

4) Review Text: String variable for the review body.

5) Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.

6) Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.

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


2. MOE, W., & TRUSOV, M. (2011). The Value of Social Dynamics in Online Product Ratings Forums. Journal of Marketing Research, 48(3), 444-456. Retrieved December 8, 2020, from http://www.jstor.org/stable/23033850

3. Zhu, F., & Xiaoquan (Michael) Zhang. (2010). Impact of Online Consumer Reviews on Sales: The Moderating Role of Product and Consumer Characteristics. Journal of Marketing, 74(2), 133-148. Retrieved December 8, 2020, from http://www.jstor.org/stable/20619095

</pre>

<pre>
Contributors : <a href=https://github.com/schoi15-umbc>Sooyeon Choi</a>
</pre>

<pre>
Duration     : December 2020
Last Update  : 12.08.2020
</pre>
