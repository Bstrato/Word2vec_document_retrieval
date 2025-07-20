# Neural Information Retrieval with Word Embeddings
- This project implements neural information retrieval techniques using word embeddings on a Yelp restaurant review dataset. The assignment focuses on comparing word2vec-based document retrieval with traditional TF-IDF methods.

# Dataset
- Source: Yelp restaurant reviews
- Documents: Individual user reviews
- Preprocessing: Tokenization, stemming, normalization, and stopword removal

# Implementation
#Word Embedding Model
- Library: Gensim word2vec
- Training: 10 epochs on review data (or subset if computational resources are limited)
- Document Representation: Average of word embeddings for all terms in document
- Similarity Metric: Cosine similarity between query and document vectors

# Query Evaluation
#The system retrieves top 3 most similar documents for these 10 queries:
- general chicken
- fried chicken
- BBQ sandwiches
- mashed potatoes
- Grilled Shrimp Salad
- lamb Shank
- Pepperoni pizza
- brussel sprout salad
- FRIENDLY STAFF
- Grilled Cheese

# Key Features
- Word2vec model training and document vectorization
- Cosine similarity-based document ranking
- Performance comparison with TF-IDF baseline
- Relevance analysis of retrieved documents

# Key Features
- Training time documentation
- Top 3 documents with similarity scores for each query
- Relevance analysis comparing neural IR vs. TF-IDF approaches

# Requirements
- Python with Gensim library
- JSON parsing capabilities
