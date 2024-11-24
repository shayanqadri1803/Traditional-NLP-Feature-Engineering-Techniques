# NLP Feature Engineering with Traditional Methods

This project demonstrates **traditional NLP feature engineering techniques** for analyzing and clustering text data. Using a small corpus of categorized documents, it showcases preprocessing, feature extraction, and clustering methods.

---

## 📋 Overview

### 1. **Data Preprocessing**
   - Text normalization: Lowercasing, removing special characters, and stopwords.
   - Tokenization: Splitting text into meaningful tokens.

### 2. **Feature Engineering**
   - **Bag of Words (BoW)**:
     - Creates a sparse matrix representing word occurrences in documents.
   - **Bag of N-grams**:
     - Captures sequences of adjacent words (e.g., bigrams).
   - **TF-IDF (Term Frequency-Inverse Document Frequency)**:
     - Weighs word importance based on frequency across documents.

### 3. **Document Similarity**
   - Computes pairwise document similarity using **cosine similarity** on TF-IDF features.

### 4. **Clustering**
   - **Hierarchical Clustering**:
     - Groups similar documents into clusters and visualizes relationships with a dendrogram.
   - **K-Means Clustering**:
     - Assigns topic-based clusters using features extracted from topic modeling.

### 5. **Topic Modeling**
   - Applies **Latent Dirichlet Allocation (LDA)** to identify hidden topics.
   - Extracts topic-word distributions and assigns topic labels to documents.
