# Cryptocurrencies
Unsupervised Machine Learning and Cryptocurrencies

## Application introduction

This application uses unsupervised learning to analyze data on the cryptocurrencies traded on the market. Our investors are interested in offering a new cryptocurrencies investment portfolio for the customers. The company, however, is lost in the immense universe of cryptocurrencies. Thus, we implement the machine learning models to present a report of what cryptocurrencies are on the trading market and how cryptocurrencies could be grouped toward creating a classification for developing this new investment product.

The data we have is not ideal, so it has been processed to fit the machine learning models. Since there is no known output for what we are looking for, we decided to use unsupervised learning. To group the cryptocurrencies, we decided on a clustering algorithm to help determine about investing in this product. 

## Goals and steps
- Prepare the data for dimensions reduction with PCA and clustering using K-means.
- Reduce data dimensions using PCA algorithms from sklearn.
- Predict clusters using cryptocurrencies data using the K-means algorithm form sklearn.
- Create some plots and data tables to present the clustering results.

Please refer to the Challenge.ipynb file:
[Link to code](https://github.com/keyoumao/Cryptocurrencies/blob/master/Challenge.ipynb) 


## Data Visulization
- **a 3D scatter plot using Plotly Express to plot the clusters using the clustered_df DataFrame. 
This plot includes the following parameters on the plot: hover_name="CoinName" and hover_data=["Algorithm"] to show this additional info on each data point:**

![alt text](https://github.com/keyoumao/Cryptocurrencies/blob/master/newplot.png "Logo Title Text 1")


- **a scatter plot using hvplot.scatter to present the clustered data about cryptocurrencies 
This plot has x="TotalCoinsMined" and y="TotalCoinSupply" to contrast the number of available coins versus the total number of mined coins. Use the hover_cols=["CoinName"] parameter to include the cryptocurrency name on each data point:**

![alt text](https://github.com/keyoumao/Cryptocurrencies/blob/master/bokeh_plot.png "Logo Title Text 1")

We can clearly see the all the cryptocurrencies are catogorized into four groups. These clustering results can be futher utilized as inputs for neuron networks training.

## Contact:
https://keyoumao.github.io/
