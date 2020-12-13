# House-Price-Pediction
The pricing of real estate has been a difficult decision in the Sindian District of New Taipei City, due to a lot of factors needed to be taken into consideration. However in reality, there are many restrictions and limitations to collect useful data to obtain the accurate price prediction. The aim of this project is to find a best linear regression model that can best capture the relationship between the housing price (per unit area) and its predictive regressors.

The real estate valuation dataset contains historical data from real estate market across 2012 to 2013. Within the dataset, each row represents a transaction record of a real estate property, whereas each column corresponds to a feature describing that record. The dataset contains 414 records of property sales (414 rows).

I used Linear regression model and tried multiplying two independent variables which are more correlating and removed some variables but the R- square value is not increased much and the P-value is violating the 95% confidence interval.So I used Log Transformation on some variables in order to increase the accuracy and R value. I applied different supervised algorithms and found the SVM and Random Forest gave more accuracy.
 
