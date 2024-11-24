Description of the Notebook

This notebook explores traditional NLP feature engineering methods for analyzing and clustering text data. It uses a small corpus of categorized documents and applies various preprocessing, feature extraction, and clustering techniques. Key highlights include:
	1.	Data Preprocessing:
	•	Removes special characters and stopwords.
	•	Normalizes text using tokenization.
	2.	Feature Engineering:
	•	Bag of Words (BoW): Creates a sparse matrix of word occurrences in the corpus.
	•	Bag of N-grams: Captures sequences of adjacent words (bigrams).
	•	TF-IDF: Assigns importance to words based on their frequency across documents.
	3.	Document Similarity:
	•	Computes similarity using cosine similarity on TF-IDF features.
	4.	Clustering:
	•	Uses hierarchical clustering and K-means to group similar documents.
	•	Visualizes relationships using a dendrogram.
	5.	Topic Modeling:
	•	Applies Latent Dirichlet Allocation (LDA) to identify underlying topics.
	•	Extracts topic-word distributions and assigns topic labels to documents.

This notebook demonstrates a mix of classical feature extraction and clustering methods, serving as a foundation for basic text analytics and machine learning tasks in NLP.
