# Portfolio_Introdution

# [Project 1: Big Data Analysis on San Francisco Crime Data](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4180839976313880/2327985936119052/456269828228637/latest.html)
* This project aims to perform **OLAP analysis** on the huge data of San Francisco Crime records from 2003 to 2018 with approach of Big Data Techniques
* The Structure we use to perform OLAP is Spark Dataframes 
* Clustering location data to get the best number of clusters to help the police to improve the resolution police

![](/images/sf_p1.png)


# [Project 2: Dallas Child Poverty Analysis With Regression Approach](https://github.com/treerway/DallasPoverty/blob/master/%5BCPAL%5D%20Group%204%269%20Final%20Python%20Code.ipynb)
* This project aims at identifying indicators that would represent the level to which family plays a role in child poverty in a given census tract. We aim at creating a score for all census tracts in Dallas. This score would tell us how well the census tract is doing in terms of family.
* Generally, we expand our indicator from only one to five comprehensive indicators
* The methodology of combining indicators we use is Pearson Correlation and features the importance of random forest 

![](/images/Map.png)

# [Project 3: Customer Behaivor Prediction for Bank Campaign](https://github.com/treerway/Bank_Campagin/blob/main/projec1_classification.ipynb)
* In this project, we are interested in predicting whether one single client will subscribe to a long-term deposit product 
* in bank campaign conducted by marketing phone
* we complete the EDA, data preprocessing, and use grid-search to tuning the model to get the performance 
* we use the roc-auc score as the metrics to evaluate different model

![](/images/bak_cam.png)

# [Project 4: Amazon Prime Videos Prediction](https://github.com/treerway/Amazon_Prime_Video/blob/main/Amazon_Prime_Video_Analysis.ipynb)
* Now, we hava data measuring how much a movie is consumed by the audiences per day. Amazon Prime Video is a Website based video watching platform. 
* The team is interested in predicting the popularity of every single movie to figure out some ways to improve the watching times.
* The best model we developed is random forest. According to the different metrics, the R-square is 0.51
* Due to the importance figure, the prime video team is supposed to introduce a more highly_voted movie.
* The position of a single movie is another key factor to absorb the attention of the audience. Based on our analysis, we have the below plot 

![](/images/plot_final.png)

# [Project 5: Bank Customer Churn Prediction](https://github.com/treerway/customer_churn/blob/main/Bank%20Customer%20Churn%20Prediction.ipynb)
* In this project, we use supervised learning models to identify customers who are likely to churn in the future. Furthermore, we will analyze top factors that influence user retention. 
* Also, we build logistic model and convert model lanuage to human readble language to interpret the customer behavior to keep customer away from churn
* Logit(Exited = 1) = -0.06367794 + 0.751*Age - 0.52*IsActiveMember - 0.2591*Gender + 0.228*Geo_Germany + 0.162*Balance - 0.12*Geo_Farance - 0.089*Geo_Spain - 0.0637 * CreditScore - 0.0586*NumOfProdcuts - 0.0452*Tenure - 0.0199*HasCrCard + 0.0137*Salary + 0.0137*EstimatedSalary

![](/images/churn_auc.png)
