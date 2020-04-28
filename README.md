# Text Clustering on Amazon Movie & TV Show Reviews Using Unsupervised Learning Models

Note: For the best view of the project, use this [link](https://nbviewer.jupyter.org/github/jamestorres1988/Text-Clustering-On-Amazon-Film-Reviews/tree/master/) on Jupyter nbviewer. There are formatting issues when using the github version. 

[Here's](https://www.kaggle.com/dm4006/amazon-movie-reviews) the original dataset. Luckily, we were able to get a processed version of the data [here](https://www.kaggle.com/ryati131457/web-data-amazon-movie-reviews-processed). The dataset consists of various movie reviews on Amazon. Our goal is see if we can cluster the data based on certain similarities. If we are successful, the model can be used to make a recommendation engine for movies. The idea is that if we can cluster the data, anyone that chooses a movie from one of the clusters will be recommended another movies from that same cluster. For now, we will focus on the clustering process.

We will first try to run different dimensionality reduction techniques. Then we will run different unsupervised learning models. Once we decide what the best models will be, we will then fine tune the parameters to get the best fit.
