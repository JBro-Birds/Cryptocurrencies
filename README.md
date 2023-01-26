# Cryptocurrencies

## Overview of Project
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers.  The company, however, does not fully understand the cryptocurrency world. So, they’ve asked me to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.  I've been working with Martha, senior manager for Advisory Services Team at Accountability Accounting, to better understand what unsupervised learning is used for, how to process data, how to cluster, how to reduce dimensions, and how to reduce the principal components using PCA.  We are now at the point of putting all these skills to use by creating an analysis for our clients who are preparing to get into the cryptocurrency market.

### Purpose
The purpose of the project is to transform a data set that is not ideal and fit the data in a unsupervised learning machine environment in order to predict outcomes.  To group the cryptocurrencies, Martha decided on a clustering algorithm and using the PCA and K-means methods. She’ll use data visualizations to share her findings with the board.  

## Summary
The outcome of clustering using the PCA and K-means methods shows there are two main clusters.  First, using the Elbow Curve to find the best value for k shows four clusters should be used.  The 3D-scatter plot and hvplot.scatter plot shows that there are two main clusters with a few outliers representing the other two clusters.

![3D_scatter](https://raw.githubusercontent.com/JBro-Birds/Cryptocurrencies/master/support_images/3D_scatter.png)

![hvplot_scatter](https://raw.githubusercontent.com/JBro-Birds/Cryptocurrencies/master/support_images/hvplot_scatter.png)

