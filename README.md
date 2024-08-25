Overview
In many e-commerce and product databases, the same product might be listed multiple times with slight variations in its name. This project leverages the power of transformer models, specifically BERT, to compare product names and identify those that are effectively the same. The model generates embeddings for each product name, and cosine similarity is used to measure the closeness between these embeddings.

Features
BERT Embeddings: Utilizes BERT to generate dense vector representations of product names.
Cosine Similarity: Compares these embeddings to identify similar products.
Unique Product Identification: Groups and counts similar products as a single entity.
Flexibility: The threshold for similarity can be adjusted according to the use case.
