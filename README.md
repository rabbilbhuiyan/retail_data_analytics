# Retail Data Analytics
The goal of this project is to predict the sales of a Retail outlet based on the historical data for sales. The retailer might want to know the sales of his outlet in different locations, which will give him a best understading of scaling his business and also use of best practices to improve the sales of outlet. Among other variables, Holidays and major events which come once a year, the retailer wants to see how these affect the strategic decisions for sales. In addition, the Markdowns are known to affect sales - retailer might want to predict which department will be affected and to what extent.  

The dataset is historical sales data for 45 stores located in different regions - each store contains a number of departments. The company also runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. 

The dataset consist of three excel sheets namely Stores, Features and Sales. Stores data indicate type and size of the store. Features table contains additional data about store, department, regional activites (Markdown, Fuel_price, Temperature), IsHoliday, Unemployment and CPI. While the Sales data contains the Weekly_Sales information by store, department and IsHoliday.

After EDA and correlation analysis, we found that Holiday affects the sales and also Markwon acitivities for different sotre during specific time. In this project, Holt Winters exponential smoothing forecasting technique was applied as in the dataset both trend and seasonality over the date was observed. The modle accuacy is quite satisfacotry as Mean Absolute Percentage Error was only 5.2 %. The graph below shows the prediction of sales for the year 2013.

![Sales_prediction_2013](https://user-images.githubusercontent.com/36482524/148239758-ddc2acf9-2ae3-4c32-84dd-af7109ca6eaa.png)
