# Cryptocurrencies
![mod18.PNG](PNGs/mod18.png)

## Overview

The purpose of this assignment was to dive deeper into machine learning using unsupervised algorithms, which enables to explore data without a clear output in mind. The task primarily entailed working with the K-means algorithm, the main unsupervised algorithm that groups similar data into clusters.

An analysis was created for a hypothetical client who was preparing to get into the cryptocurrency market. A CSV containing cryptocurrency data was provided for the analysis. A report that included what cryptocurrencies were on the trading market, and how they could be grouped to create a classification system for the new investment was created. The following questions were considered for data preparation:

- What knowledge do we hope to glean from running an unsupervised learning model on this dataset?
- What data is available? What type? What is missing? What can be removed?
- Is the data in a format that can be passed into an unsupervised learning model?
- Can I quickly hand off this data for others to use?

The following steps were also taken:

- Preprocessed the data for PCA (Principal Component Analysis)
- Reduced data dimensions using PCA
- Clustered cryptocurrencies using K-means
- Visualized the results



## Resources

- Pandas
- Scikit-learn 
- Plotly to create graphing library that makes interactive, publication-quality charts
- hvplot (high-level plotting library that uses HolovViews and Bokeh)


## Results

### Fig.1
![elbowcurve](PNGs/elbowcurve.png)

- 4 clusters are determined in this Elbow Curve


### Fig.2
![3D.PNG](PNGs/3D.png)

- Data classified into 4 groups
- **BitTorrent** is the clear outlier while the other 3 clusters have relatively clear boundaries


### Fig.3 & 4
**TotalCoinsMined vs. TotalCoinSupply**
![hvplot1.PNG](PNGs/hvplot1.png)


![hvplot2.PNG](PNGs/hvplot2.png)

- This clustering did not provide much insight into the cryptocurrencies' trend. More features should be added to extract meaningful groupings.
