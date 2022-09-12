# Cryptocurrencies

## Overview
  Accountability Accounting, an investment bank, wants to provide their customers with a new cryptocurrency investment portfolio.  They have tasked me with creating a report that details what cryptocurriencies are currently on the trading market and how could they be grouped to create a classification system for this investment.
  
  Using Pandas, I preprocessed the data to perform PCA. I then applied a PCA (Principal Component Analysis) algorithm to reduce the dimensions of the data to three principal components and created a new dataframe.  Then using the k-means alogrithm, I created an elbow curve, using hvPlot, to find the best K from the new dataframe. I then ran the k-means alogrithm to predict K clusters.  
  
  Once the clusters were predicted, I visualized the data by using Plotly Express 3D to create a scatter plot to plot the three clusters.  Using hvplot.table, I created a table listing the tradable cryptocurrencies. Lastly, I created a scatter plot depicting the relationship between the total amount of coins mined and the total coin  supply.
