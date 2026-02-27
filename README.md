# Reddit
ML4N Project Reddit

## Project structure
* pre-processing.ipynb data exploration along with pre-processing steps for the supervised task
* supervised_genders.ipynb supervised task (gender detection form comments)
* KMEANS-pre-processing.ipynb pre-processing for clustering task using KMEANS
* HDBSCAN-pre-processing.ipynb contains pre-processing for clustering task using HDBSCAN this is different from KMEANS because we need to use a subsample so that executing HDBSCAN is feasible
* unsupervised.ipynb contains clustering with KMEANS and HDBSCAN along with cluster analysis
* LanguageModelsExploration.ipynb supervised tasks using FFNN using as data the concatenation of PCA‑reduced subreddit‑fraction features, and DistilBERT embeddings
* LanguageModelsExplorationJustEmbeddings.ipynb supervised tasks using FFNN using as data DistilBERT embeddings
