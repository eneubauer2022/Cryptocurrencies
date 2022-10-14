# Cryptocurrencies

## Overview

In this module we were using Unsupervised Machine learning to analyze cryptocurrency to determine if there are any trends in the data. We preformed some data preprocessing and then used a clustering algorithm and hvPlot to visualize the results.

## Preprocessing the Data

We had to run through several steps to prepared the data: including dropping null values, using our tradeable or mined cryptocurrencies, using the get_dummies functions to assign numbers to the categories, and scaling the data using StandScaler() method within Panada.

![image](https://github.com/eneubauer2022/Cryptocurrencies/blob/main/Images/pca.png)

## Elbow Curve

The elbow curve helped us determine that the optimal number of clusters was 4. We then used this in our K-Means model.

![image](https://github.com/eneubauer2022/Cryptocurrencies/blob/main/Images/elbow.png)

## 3D Scatter plot

Below is the 3D scatter plot that shows the 4 different clusters.

![image](https://github.com/eneubauer2022/Cryptocurrencies/blob/main/Images/scatter.png)

## hvTable

![image](https://github.com/eneubauer2022/Cryptocurrencies/blob/main/Images/hvplot.png)

## hvScatter

![image](https://github.com/eneubauer2022/Cryptocurrencies/blob/main/Images/scatter.png)

