# Cryptocurrencies
# Overview
The purpose of the Cryptocurrency analysis is to inform that team at Accountability Accounting about what cryptocurrencies are on the trading market and ways that they can be grouped together. Using unsupervised machine learning cryptocurrencies will be grouped together based on features and will allow possible investors to use the data in investment portfolios for their customers. With unsupervised machine learning we will preprocess the data for PCA, reduce dimensions, cluster cryptocurrencies using K-means, and visualize the results with 3D and 2D plots. 

# Analysis Results

Before beginning the Principal Component Analysis, the data was preprocessed and cleaned. Null values were removed as well as unecessary columns, the data was scaled, and categorical columns were numerically encoded. When this was complete we were able to move forward with the PCA. 

Three principal components were used on the Cryptocurrency data
![pca](https://github.com/aarce21/Cryptocurrencies/blob/main/images/pca.PNG)

Our next objective was to determine the number of cluisters the Cryptocurrency data could be divided into. This was determined using the K-means algorithm and visualizing it with an elbow curve. 

![elbow_curve](https://github.com/aarce21/Cryptocurrencies/blob/main/images/elbow_curve.PNG)

According to the elbow curve, 4 clusters should be used

Using the 4 clusters, the K-means model was then fit to the data and predictions on the class on Crypto were given. 
![predictions](https://github.com/aarce21/Cryptocurrencies/blob/main/images/predictions.PNG)

The prediction data was then added to the clustered dataframe table to show what class each of the Crypto categories they were predicted to fall into. The Class column was added to the end of the DataFrame
![table_predictions](https://github.com/aarce21/Cryptocurrencies/blob/main/images/table_predictions.PNG)
