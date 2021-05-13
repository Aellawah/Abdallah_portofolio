Abdallah_portofolio
Data science portfolio

# [Project 1: Airline fare prices prediction](https://github.com/Aellawah/Airline-fare-prices-prediction/blob/main/Airline%20prices%20prediction.ipynb)
![](/Images/WWS-AirlinesAirports-720x300.jpg)

Passengers want to check for flights fare prices in different airlines according to number of stops during their fights , so throught this dataset which consists of flights information of different airlines we will train our Machine learning model to predict prices for every flight based on specific features that we can reflect to users.

* After wrangling the data we have changed the data columns types to fit our analysis and removed null values records.
* we applied feature engineering on several columns to extract values from them and include them in our machine learning model such as dividing date columns into years months days and seperating categorical columns into seperate values that can be used idividually in our model, used label encoding for ordinal data and hot encoding for nominal data
* we fitted the data after transformation on Random Forest Regressor model which gave us a pretty good results.


# [Project 2: Canadian superstore sales analysis](https://github.com/Aellawah/Canadian-superstore-sales-analysis/blob/main/Canadian%20Superstore%20sales.ipynb)
![](Images/shopping-cart-supermarket-empty-shelves-40320116.jpg)

In this notebook we will explore Data of a canadian superstore that exists in different places around the world and try to gain some insights about the business and the most selling products.

* We have concluded that the sales trend over the years is increasing along the from 2011 to 2014
* Customers prefer to use Standard class & Second class as shipping modes
* The most profitable category is Technology & the most profitable sub category is Copiers
* People tend to buy more by the end of the year since the statistics shows that people buy more in the 4th quarter of each year
* The store can make more money when sending products to far areas which requires high cost of shipping 
* Best market per sales is APAC which is Asia pcific markets

# [Project 3: Advetising agency users behavior prediction](https://github.com/Aellawah/Advetising-agency-users-behavior-prediction/blob/main/Advertising%20agency%20dataset.ipynb)
![](Images/marketing.png)

In this project we will be working with an advertising data set, We are trying to enhance the criteria of the customers that we target with our ads so based on specific features about our customers such as Age,income,city,Gender,.. and other features We will create a model that predicts whether or not they will click on an our ads.

* After wrangling our data we found was some outliers in 'Area income' column which we removed them to enhance our model
* We have noticed that older people tend to click more on our ads than youth
* The more the time people spend on internet the likely they click on our ads
* The more the person gets old the less income he gets
* We have fitted our data on a Logistic Regression model and Decision tree classification model

# [Project 4: The Movie database analysis](https://github.com/Aellawah/The-Movie-database-analysis-/blob/main/TMDB.ipynb)
![](Images/clapperboard-movie_101884-274.jpg)

In this notebook, I will investigate the TMDB mavie dataset, The Movie Database (TMDB) is a popular user editable database for movies and TV shows, It has columns for variables such as release year, revenue, budget, director, runtime, and popularity, as well as the IMDB ID for each entry, we have reached alot of conclusions such as:

* we have conluded that people tend to like movies more along the years since the popularity and interest increased from 2005 to 2015 
* Movies are becoming shorter over the time as the statistics shows that the runtime of the movie decreased along the years from 2005 until 2015 
* Revenues from movies are increasing along the years which is also related to popularity of the movies along the years
* Number of movies produced every year increased along the years
* Even though it seems that the revenue is increasing with budget on some level, it is clear that some of the most profitable movies had budgets lower than average.
* It seems that more popular movies produce more revenue. However, some popular movies are not necessarily profitable, and vice versa.

# [Project 5: Diamonds prices prediction](https://github.com/Aellawah/Diamonds-prices-prediction/blob/main/Diamonds%20prices%20prediction.ipynb)
![](Images/Hero_Cut_700x394.jpg)

In this notebook, we will try to build a model to predict the prices of diamonds based on various features of diamond like carat weight, cut quality ,etc.
some of the conclusions

* After wrangling the data we found that there were no null values in the data ,there were no duplicated rows in the data,There were some outliers in the features which we removed them
* We constructed features engineering on categorical columns in our dataset to utitlize them in our model
* After transforming the data We have fitted the data on a Linear regression model which gave us R2 of 89% 
* We tried to use another model that would enhance the previous results so we used Random Forest Regressor which gave us R2 of 98%

# [Project 6: Udemy courses analysis](https://github.com/Aellawah/Udemy-Dataset/blob/main/Udemy.ipynb)
![](Images/udemy-free-courses-banner.png)

This Data set contains 3000+ entries for all courses data & subjects in Udemy application which we need to investigate to answer questions about subscribers and courses prices
How many courses for each subject is udemy offering?

Questions that we want to answer are:

* Which subject has the maximum number of Courses?
* How many free courses are there for every subject?
* How many paid courses are there for every subject?
* What are the Top selling books?
* What the courses that are pubished in year 2015?
* What is the maximum number of Subscribers for each level of courses?
* Is there a relationship between number of lectures and number of subscribers?
* Is there a relationship between the price of the course and the number of subscribers
* What is the kind of relationship between price and number of lectures

# [Project 7: London housing prices](https://github.com/Aellawah/London-housing-data/blob/main/Londing%20Housing%20Data.ipynb)
![](Images/1835445_London-houses-136327763-Nadina-shutterstock.jpg)

This data set contains 13000+ wich is centered around london housing market, it contains alot of additional relevant data related to Averge housing prices , number of houses sold , number of crimes committed

Questions that we want to answer are:

* How many records are there where the crimes are zero in England?
* What is the Minimum Average price per year in England?
* What is the Maximum Average price per year in England?
* What are the Most 5 areas that has high number of crimes?
* What is the Relationship between the Average Price and the number of houses sold ?
* What is the Most year that had crime cases?
* What is the Least year that had crime cases?
* How many houses were sold in every area?
* What the is the Top Five areas that sold houses along the years?
* What the is the Least Five areas that sold houses along the years?
