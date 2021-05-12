Abdallah_portofolio
Data science portfolio

# [Project 1: Airline fare prices prediction](https://github.com/Aellawah/Airline-fare-prices-prediction/blob/main/Airline%20prices%20prediction.ipynb)

Passengers want to check for flights fare prices in different airlines according to number of stops during their fights , so throught this dataset which consists of flights information of different airlines we will train our Machine learning model to predict prices for every flight based on specific features that we can reflect to users.

* We made some data cleaning on the dataset we dropped uneccessary columns , removed null values and changed some datatypes to fit our analysis
* we made features engineering by reshaping some categorical values by using one hot coding for nominal values and label encoding for ordinal values
* Seperated years and months and days from date columns to include them in the model
* We fitted our final data on RandomForestRegressor model

# [Project 2: Canadian superstore sales analysis](https://github.com/Aellawah/Canadian-superstore-sales-analysis/blob/main/Canadian%20Superstore%20sales.ipynb)

In this notebook we will explore Data of a canadian superstore that exists in different places around the world and try to gain some insights about the business and the most selling products.

* We have concluded that the sales trend over the years is increasing along the from 2011 to 2014
* Customers prefer to use Standard class & Second class as shipping modes
* The most profitable category is Technology & the most profitable sub category is Copiers
* People tend to buy more by the end of the year since the statistics shows that people buy more in the 4th quarter of each year
* The store can make more money when sending products to far areas which requires high cost of shipping 
* Best market per sales is APAC which is Asia pcific markets

# [Project 3: Advetising agency users behavior prediction](https://github.com/Aellawah/Advetising-agency-users-behavior-prediction/blob/main/Advertising%20agency%20dataset.ipynb)

In this project we will be working with an advertising data set, We are trying to enhance the criteria of the customers that we target with our ads so based on specific features about our customers such as Age,income,city,Gender,.. and other features We will create a model that predicts whether or not they will click on an our ads.

After wrangling our data we found was some outliers in 'Area income' column which we removed them to enhance our model
We have noticed that older people tend to click more on our ads than youth
The more the time people spend on internet the likely they click on our ads
The more the person gets old the less income he gets
We have fitted our data on a Logistic Regression model and Decision tree classification model
