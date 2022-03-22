In this project a graph is constructed for predicting links with machine learning techniques. 
Graph nodes represent Wikipedia pages and edges have a similar relationship to each other.
The technique applied is as follows:
  Similarity-based: For each pair of unconnected nodes in
  examined snapshot of the network, the similarity is calculated
  based on their topological characteristics (common neighbors, degree). Pairs with a high similarity value (which exceeds
  a threshold value), represent its future connections
  network.
  
  Node similarity metrics under consideration:
  - Jaccard Coefficient
  - Preferential Attachment
  - Resource Allocation
  
  Learning-based: Binary classification problem. The goal is to build a forecasting model
  two distinct categories ("existence of connection", "non-existence of connection").
  
  Dataset used:
    - http://konect.cc/networks/dbpedia-similar/
