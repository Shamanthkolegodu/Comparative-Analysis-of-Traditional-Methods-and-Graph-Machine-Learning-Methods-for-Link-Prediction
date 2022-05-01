# Comparative-Analysis-of-Traditional-Methods-and-Graph-Machine-Learning-Methods-for-Link-Prediction
* Comparative Analysis of Traditional Methods and Graph Machine Learning Methods for Link Prediction on **Game of Thrones Season 3 data**
* To compare traditional, similarity-based methods with GraphML algorithms like GCN, GraphSAGE and GAT for link prediction.


### Steps followed :
* Perform EDA on the dataset
    - Check for isolates, self-loops, etc

* Calculate the following measures:
    - Betweenness
    - PageRank
    - Local clustering coefficient
* Find communities using Spectral Clustering
* Link Prediction using Traditional Methods
    - Perform comparison for 3 similarity measures **Jaccard, Adamic Adar and Preferential Attachment**.
    - Finding the best similarity measure along with the optimal threshold for said similarity measure.
* Link Prediction using GraphML
    - Perform link prediction using
        - GCN
        - GraphSAGE
        - GAT
    - Comparing the three models using Loss and AUC.
* Performing a comparison between traditional and GraphML
    - What are the metrics?
    - Which is performing better? Is there any reason you can think of, as to why this might be happening?
    - Any analysis or insights you can draw from this, that may relate to the season’s plot?

##### Part of UE19CS345- NETWORK ANALYSIS AND MINING course @PES University.
