# Spark-AMD <img src="https://upload.wikimedia.org/wikipedia/commons/f/f3/Apache_Spark_logo.svg" width="50"/>

The aim of this project is to identify a scalable solution to detect pairs of similar items in a corpus of documents. The solution is implemented in Spark 3.1.1 and it is designed to scale with large datasets.

- To find similar items an application of locality sensitive hashing (LSH) designed for the Jaccard distance is considered.
- In the particular scenario considered in this project (i.e. finding similar Stack Overflow questions), LSH can be exploited to avoid redundant questions and direct users with similar questions in the same area.
- A series of experiments are carried out and discussed to see how Spark (set up on Google Colab) scales as the dimensionality of the dataset grows.
- The final results of the algorithm are then shared along with some examples of questions inferred as similar.

The solution is written with Python 3 in Google Colab for easier reproducibility of the results. The link to run the code can be found by clicking on the main.ipynb file from Github where there will be a button directing the user to Colab. Alternatively, you can directly click on this button <a href="https://colab.research.google.com/github/gregorio-saporito/Spark-AMD/blob/main/main.ipynb" target="_parent"><img src="https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="Open In Colab" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg"></a>
