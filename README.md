# BiClustNet-Bipartite-Node-Clustering-in-Movie-Actor-Networks

## Project Description

The Clustering Assignment project is focused on clustering nodes in a bipartite graph (movie-actor network). It involves splitting the dense node representations into actors and movies and then applying clustering algorithms to group similar actors and movies.

## Tasks Completed

### Task 1: Clustering Actors

1. Read a graph from the given "movie_actor_network.csv" file, considering it as a bipartite graph.
2. Used the `stellergaph` and `gensim` packages to obtain 128-dimensional dense representations for every node in the graph.
3. Split the dense representations into actor nodes and movie nodes.
4. Applied a clustering algorithm to group similar actors.
5. Chose the number of clusters with the maximum score of Cost1.
6. Calculated Cost1 as the number of clusters divided by the number of nodes.
7. Calculated Cost2 as the number of clusters divided by the number of clusters.
8. Fitted the clustering algorithm with the optimal number of clusters and obtained cluster labels.
9. Converted the dense node vectors into 2-dimensional vectors using dimensionality reduction techniques, preferably T-distributed Stochastic Neighbor Embedding (t-SNE).
10. Plotted a 2D scatter plot with node vectors and assigned colors to nodes based on their clusters.

### Task 2: Clustering Movies

1. Considered only the movie nodes for this task.
2. Applied a clustering algorithm of choice.
3. Chose the number of clusters with the maximum score of Cost1.
4. Calculated Cost1 as the number of clusters divided by the number of nodes.
5. Calculated Cost2 as the number of clusters divided by the number of clusters.

## Visualizing Results

The project includes the visualization of actor and movie clusters, helping understand the grouping of similar nodes within the network.

## Conclusion

The Clustering Assignment project provides insights into clustering actors and movies within a bipartite graph. You can explore the provided code in the Jupyter Notebook to better understand the clustering results and adapt the techniques for similar tasks.

