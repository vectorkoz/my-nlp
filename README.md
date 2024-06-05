# my-nlp
This repo contains my Natural Language Processing projects.

## topic-extraction-text-clustering
This project looked at two separate NLP problems:
 - Clustering texts with unknown labels,
 - Selecting most relevant words for each label from texts with known labels.

This project was completed using Python, Jupyter Notebook, scikit-learn, pandas, numpy, matplotlib, seaborn.

The texts in the project had labels that split them into distinct groups. It was clearly shown that it was possible to represent texts via TF or TF-IDF, reduce dimensionality via T-distributed Stochastic Neighbor Embedding and use a clustering algorithm to produce good clusters that aligned with the actual text labels (see below).
![Clustering visualization](https://github.com/vectorkoz/my-nlp/blob/main/topic-extraction-text-clustering/data/clustering_TF-IDF%20%2B%20TSNE%20%2B%20GMM%20Three%20FOX%20categories.png?raw=true)

It was also shown that it's possible to obtain text topics by applying Non-Negative Matrix Factorization (NNMF) to TF-IDF data. Using NNMF, it's possible to extract most relevant words for each topic, and therefore, since NNMF topics usually aligned well with the original text labels, for the original labelled "topics" as well (see below).
![Top 10 words](https://github.com/vectorkoz/my-nlp/blob/main/topic-extraction-text-clustering/data/10words_FOX%20NEWS-health-sports-Science_technology.png?raw=true)

### Links
 - [Data source](https://sites.google.com/site/qianmingjie/home/datasets/cnn-and-fox-news) - texts of news articles posted on CNN and FOX News websites in 2014, labelled by the news website sections.
 - [All code for the project](https://github.com/vectorkoz/my-nlp/blob/main/topic-extraction-text-clustering/project_text_processing.ipynb)
 - [Detailed project report](https://github.com/vectorkoz/my-nlp/blob/main/topic-extraction-text-clustering/REPORT.pdf)
