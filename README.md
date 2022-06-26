![Intro_Image - Copy](https://user-images.githubusercontent.com/84449238/175822780-45506b6a-d57d-4325-b9c5-ae73ce48f87c.JPG)

# Big_Mart_Sales_Prediction-AnalyticsVidhya
Sales Prediction for Big Mart Outlets
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet.

Using this model, BigMart will try to understand the properties of products and outlets which play a key role in increasing sales.

Please note that the data may have missing values as some stores might not report all the data due to technical glitches. Hence, it will be required to treat them accordingly. 



Data Dictionary
We have train (8523) and test (5681) data set, train data set has both input and output variable(s). You need to predict the sales for test data set.



Train file: CSV containing the item outlet information with sales value
![Intro_Image2](https://user-images.githubusercontent.com/84449238/175238718-81b34162-50fb-42b9-9543-b083a34f909f.JPG)

Test file: CSV containing item outlet combinations for which sales need to be forecasted
![Intro_Image3](https://user-images.githubusercontent.com/84449238/175238755-d3d1d2ce-cea7-45b3-a9c4-1441f6c17bd4.JPG)

Submission file format
![Intro_Image4](https://user-images.githubusercontent.com/84449238/175238791-4a04f7a5-d6f8-4226-9f4a-414fc7e3aea5.JPG)

Evaluation Metric
Your model performance will be evaluated on the basis of your prediction of the sales for the test data (test.csv), which contains similar data-points as train except for the sales to be predicted. Your submission needs to be in the format as shown in sample submission.

We at our end, have the actual sales for the test dataset, against which your predictions will be evaluated. We will use the Root Mean Square Error value to judge your response.
