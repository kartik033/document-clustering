# document-clustering
Unsupervised Discovery of Document Topics using Semantic Embeddings and Clustering: A Project Analysis

# Project Objective and Scope
The objective of this project was to apply unsupervised machine learning techniques to a large text dataset of unlabeled text documents to automatically group them into different clusters by topic. Using a clustering algorithm and finding the underlying structure of the data without any prior knowledge of the document categories.

•	Dataset Composition: The data was collected from kagle, which was a composite dataset of six different topics: Biology, cooking, Cryptography, Do it yourself, robotics, and travel.(https://www.kaggle.com/code/akshatpathak/text-data-clustering/input)
•	Data volume: After data cleaning and duplication removal, there were 86,968 documents.

•	Technical Strategy: So the core methodology was in a two-stage process. First, leverage an advanced sentence transformer model, SBERT, to capture the semantic meaning, and each document was transferred into a numerical vector. Second, apply a partitioning algorithm to group them based on their proximity in the semantic space.

