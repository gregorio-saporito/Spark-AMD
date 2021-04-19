# Spark-AMD

The aim of this project is to identify a scalable solution to detect pairs of similar items in a corpus of documents. The solution is implemented in Spark 3.1.1 and it is designed to scale with large datasets.

- To find similar items an application of locality sensitive hashing (LSH) designed for the Jaccard distance is considered.
- In the particular scenario considered in this project (i.e. finding similar Stack Overflow questions), LSH can be exploited to avoid redundant questions and direct users with similar questions in the same area.
- A series of experiments are carried out and discussed to see how Spark (set up on Google Colab) scales as the dimensionality of the dataset grows.
- The final results of the algorithm are then shared along with some examples of questions inferred as similar.
