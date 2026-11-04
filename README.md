# Reddit
Since execution takes long time code is splitted in files to simplify.
This files contains per every section of the project the files associated with it.

## Project structure
* Section 1 – Data exploration and pre-processing
    * pre-processing.ipynb data exploration along with pre-processing steps for the supervised task
* Section 2 – Supervised learning – Classification
    * supervised_genders.ipynb
* Section 3 – Unsupervised learning – Clustering
    * KMEANS-pre-processing.ipynb pre-processing for clustering task using KMEANS
    * HDBSCAN-pre-processing.ipynb contains pre-processing for clustering task using HDBSCAN this is different from KMEANS because we need to use a subsample so that executing HDBSCAN is feasible
    * unsupervised-KMEANS.ipynb contains clustering with KMEANS along with cluster analysis
    * unsupervised-KMEANS-with_long_comments.ipynb contains clustering with KMEANS along with cluster analysis but without comment segmentations (comments are full length) this is just to explain why the segmentation step was performed
    * unsupervised-HDBSCAN.ipynb contains clustering with HDBSCAN along with cluster analysis
* Section 4 – Sentiment Analysis
    * sentiment_analysis.ipynb
* Appendix - Supervised Task with Language Models
    * LanguageModelsExploration.ipynb supervised tasks using FFNN using as data the concatenation of PCA‑reduced subreddit‑fraction features, and DistilBERT embeddings
    * LanguageModelsExplorationJustEmbeddings.ipynb supervised tasks using FFNN using as data DistilBERT embeddings
