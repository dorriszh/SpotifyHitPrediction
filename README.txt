------------
DESCRIPTION: 

This project aims to perform data processing and analysis on “The Spotify Hit Predictor Dataset (1960-2019)”. We are trying to predict if a song would be a hit using its basic information and audio features. We are focusing on studying the similarity between hit songs in terms of network algorithms: we construct a network based on our dataset, and then apply node classification algorithms to predict if a song would be a hit or not.

Our code includes 4 parts in Ipython Notebook, they can be run by orders: 
1.DataPreprocessing_Analysis_Baselines.ipynb (The preprocessing of data, analysis and plots on the dataset and implementation of baselines methods)
2.TrackNetwork.ipynb (Construction of our network)
3.TrackNetwork_RandomWalk.ipynb (Random Walk Algorithm)
4.TrackNetwork_GCN.ipynb (Graph Convolutional Networks)

Our cleaned data are stored in folder named "archive". This folder contains data of songs from 1960s to 2010s.

-------------
INSTALLATION: 

To run the code, 
1.Python 3.7 or above
1.Install Jupyter Notebook
2.Install the following packages:

Install numpy
Install pandas
Install matplotlib.pyplot
Install collections
Install sklearn
Install networkx
Install gensim
Install dgl
Install torch

4. Put "archive" folder with 4 .ipynb files.

----------
EXECUTION:

Simply open the notebooks sequentially: 
1.DataPreprocessing_Analysis_Baselines.ipynb
2.TrackNetwork.ipynb
3.TrackNetwork_RandomWalk.ipynb
4.TrackNetwork_GCN.ipynb

And run the cells...
