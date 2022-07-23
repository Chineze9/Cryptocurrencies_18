# Cryptocurrencies_18

The Purpose of the Repository The senior manager for the advisory Services Team accountability Accounting, a prominent investment band, is interested in offering a new cryptocurrency investment portfolio for its customers.  I am asked  to create a report that includes what cryptocurrencies are on the trading market to create a classification system for tis new investment.   

Results 

Crypto df DataFrame was created using StandardScaler skleam library to standardize the features that stores all cryptocurrency names.  Then the Principal Component Analysis (PCA) algorithm was used to reduce the dimensions of the X DataFrame to three principal components to be placed in a new DataFrame.  These yielded three columns:  PC1, PC2 and PC3.  K-means algorithm was used to predict the K clusters for the cryptocurrencies’ data.  Then to visualize cryptocurrencies results, scatter plots with Plotly Express and hvplot which corresponded to the three principal components. Several tables were yielded and eventually, scatter plots with x=”totalCoinsMined” and y=”TotalCoinsupply” and by’”Class” that shows when you hover over the data point.  All Images uploaded to the Cryptocurrencies GitHub repository
