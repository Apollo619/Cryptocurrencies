# Cryptocurrencies

## Overview of Analysis
Create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for ***Accountability Accounting***, a prominent investment bank who is interested in offering a new cryptocurrency investment portfolio for its customers. 

### Purpose:
Working with **Martha**, a senior manger for the ***Advisory Services Team***, we will generate an algorithm for unsupervised machine learning model that will cluster cryptocurrencies and use various data visualization to include in the report. 

## Results: 
The bulletins illustrate the generated algorithm and plots used to build the report for ***Accountability Accounting***.

- After performing ETL on the provided data set an elbow curve (see image below) was used to determine the number of clusters to include for *Kmeans* analysis. A red circle indicates the number of clusters used as it flattens after this point. 

![]( https://github.com/Apollo619/Cryptocurrencies/blob/main/resources/elbow_curve.PNG)

- The image below shows the script used to cluster the cryptocurrency data.

![]( https://github.com/Apollo619/Cryptocurrencies/blob/main/resources/K_means.PNG)

- The 3D Scatter plot (see image below) helps users to visually discern how the three variables used for cryptocurrency clusters effect the output. 
![]( https://github.com/Apollo619/Cryptocurrencies/blob/main/resources/3D_model.PNG)

- Next a table (see image below) was produced with pertinent information pertaining to cryptocurrency. The table allows users to sort data based on column name. 

![]( https://github.com/Apollo619/Cryptocurrencies/blob/main/resources/hv_table.PNG)

- Finally a scatter plot with the clustered data was created to visually identify how cryptocurrencies compare to each other based on **”Total Coin Supply”** versus **”Total Coins Mined”**. (see image below)

![]( https://github.com/Apollo619/Cryptocurrencies/blob/main/resources/scatter_plot.PNG)


## Summary:
Thanks to the designed algorithm for cluster analysis, ***Accountability Accounting*** has the ability to provide a cryptocurrency portfolio for its clients based on real crypto data.
