# Cryptocurrencies
## Overview
In this module we will dive deeper into machine learning using unsupervised algorithms, which help us explore data when we're not sure what we're looking for. Now you can analyze data without a clear output in mind.

## Purpose
You'll work primarily with the K-means algorithm, the main unsupervised algorithm that groups similar data into clusters. We'll build on this by speeding up the process using principal component analysis (PCA), which employs many different features.

## Delieverable 1: Preprocessing the Data for PCA
With the knowledge of Pandas, we have preprocess the given dataset. Our preprocessed dataset is shown in the image below.
![1](https://user-images.githubusercontent.com/95719819/167287190-5cda773f-8bbd-48ed-8ed3-2ca36888b088.png)

## Delieverable 2: Reducing Data Dimensions Using PCA
With the knowledge of the Principal Component Analysis (PCA) algorithm, we have reduced the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame. Our new dataframe is shown in the image below.

![2](https://user-images.githubusercontent.com/95719819/167287264-88a1215c-919c-4efe-8760-71345e5f4793.png)

## Delieverable 3: Clustering Cryptocurrencies Using K-means
With the knowledge of the K-means algorithm, we created an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. Then, we ran the K-means algorithm to predict the K clusters for the cryptocurrencies’ data. Our dataframe with the predictions are shown in the image below.
![3](https://user-images.githubusercontent.com/95719819/167287408-8617b196-ee70-4aaa-a044-d6bb6b42b66c.png)

## Delieverable 4: Visualizing Cryptocurrencies Results
With the knowledge of creating scatter plots with Plotly Express and hvplot, we visualized the distinct groups that correspond to the three principal components you created in Deliverable 2. The below images show the dataframe and the scatter plot.

![4](https://user-images.githubusercontent.com/95719819/167287630-ca14f48a-bfc4-4cb5-b1c1-352edc76ad56.png)

![6](https://user-images.githubusercontent.com/95719819/167287655-dd41d474-ef48-41f6-b50d-74ea29a94be8.png)


Also, we created a table with all the currently tradable cryptocurrencies using the hvplot.table() function. The below image shows the table we created.
![5](https://user-images.githubusercontent.com/95719819/167287554-32f90824-8767-4476-8716-98b157f89f47.png)
