# Challenge_10    
The purpose of this project is to use unsupervised machine learning to group cryptocurrencies based on their performance across various time periods. The process starts with the import of cryptocurrency data into a Jupyter notebook and its transformation into a DataFrame.

The optimal number of clusters, represented by the variable "K," was determined. Then, the scikit-learn (sklearn) model was applied, and the results were visualized with a graph. The data was further processed with principal component analysis (PCA) to eliminate unneeded information. The sklearn model was then reapplied to the filtered data.

The results of the two runs were compared, with the filtered data providing a clearer picture of the clusters. The project was implemented using Python 3.7 and utilizes the following packages: pandas, pyviz, hvplot, pathlib, KMeans from sklearn, PCA from sklearn, and StandardScaler from sklearn. To install the necessary dependencies, run the following commands: conda install -c pandas, conda install -c pathlib, and conda install -c sklearn.

The code, along with examples of its output, can be found by cloning the repository. Feel free to experiment with different values of "K" or modify the charts to suit your needs. This project is open source and licensed for public use and modification. 

Below are some visual examples:
![download](https://user-images.githubusercontent.com/116308725/215888161-66dd8f5e-e16f-4b7a-8c31-03dcec5b6a61.png)


![download](https://user-images.githubusercontent.com/116308725/215888131-b93fc5cd-83f7-47f5-ba99-dcace0c51b4a.png)
