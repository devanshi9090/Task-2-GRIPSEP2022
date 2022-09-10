# Task-2-GRIPSEP2022
#Devanshi Awasthi
To apply the kmeans clustering to the iris dataset, and thus, visualize the same

The data set given, was the iris dataset. The task assigned was to apply k means clustering to the dataset in order to divide the species into clusters based on several parameters given in the dataset.

Initially, several libraries were imported- like - Matplotlib, numpy, pandas and skLearn

The next step was to load the dataset with which we want to work on.

Now, we had to divide the dataset into 2 parts : 
a) This part consisted entirely on the parameters(x)
b) Had only the outcomes, i.e : The names of the species(y)
so : y = function (x)

Now for applying the k means clustering to the (x) above , we had to find the number of clusters required for the division of the output.

To find the nuber of clusters, we need to plot an elbow plot, which is a plot between 'WCSS' and 'the number of clusters'. Based on the obtained value between the plot, we select the number of clusters.

After selecting the number of clusters, we implements the k-means algo and thus, visualize it graphically/scatter plot.
