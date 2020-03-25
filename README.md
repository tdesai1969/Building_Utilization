# Building_Utilization
* We were tasked to analyze multi-tenant office space building card swipe data (million rows of key card data) in order to predict           occupancy rates by hour of the day, data can be used to create “Intelligent” buildings by efficiently using many resources                 like HVAC system & lighting of the buildining.
* Initially dummy data has been provided, an excel sheet that lists each of the tenant user's entry and exit in the building.
* 3 disparate tables, approximately 1000 rows, consisting of building occupant information 
  consisting of: Company Name, KeyCard ID, Time of Entry, Time of Exit, Point of Entry, etc
* Take sample data to train the model to ﬁnd occupancy rate by hour.
* We used Matplotlib to create box plots for each hour of the day to better understand the data and distribution of data.                     Used Tableau to visualize the card swipes trend by tenant. 
* Used various machine learning models like linear regression, KNN and Random Forest Regression
* We got best R2 value 0.98 using Random Forest Regression and were able to predict no of card swipes for next hour.
