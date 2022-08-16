A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is present in the CSV file.

The company is looking at prospective properties to buy to enter the market. One needs to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.


Step 1 - Reading Data.
Step 2 - Understanding the Data by visualizing continuous & categorical variables.
Step 3 - Data preparation:
			- Derive new columns using existance columns, if needed.
			- Removing column which are not needed.
			- Removing extreme data (outliers).
			- Create dummy variables for categorical data, having more than two unique values.
Step 4 - Model Building using LinearRegression, Lasso & Ridge.
Step 5 - Extract imp features which can explain much variance in data.
Step 6 - Model Evaluation:
			- Check how well these variables describe the price of a house.