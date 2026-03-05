# Reddit
ML4N Project Reddit
Since execution takes long time code is splitted in files to simplify.

## Project structure
* pre-processing.ipynb data exploration along with pre-processing steps for the supervised task
* supervised_genders.ipynb supervised task (gender detection form comments)
* KMEANS-pre-processing.ipynb pre-processing for clustering task using KMEANS
* HDBSCAN-pre-processing.ipynb contains pre-processing for clustering task using HDBSCAN this is different from KMEANS because we need to use a subsample so that executing HDBSCAN is feasible
* unsupervised-KMEANS.ipynb contains clustering with KMEANS along with cluster analysis
* unsupervised-HDBSCAN.ipynb contains clustering with HDBSCAN along with cluster analysis
* LanguageModelsExploration.ipynb supervised tasks using FFNN using as data the concatenation of PCA‑reduced subreddit‑fraction features, and DistilBERT embeddings
* LanguageModelsExplorationJustEmbeddings.ipynb supervised tasks using FFNN using as data DistilBERT embeddings
