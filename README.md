# Enhanced Ecommerce Product Search and Recommendation Engine  

## Overview  
This project focuses on developing a hybrid search system that significantly enhances product retrieval accuracy in ecommerce platforms. By integrating traditional information retrieval methods with advanced semantic search techniques, we aim to improve the user experience when searching for products.  

## Features  
- **Hybrid Search Architecture**: Combines BM25 for ranked retrieval, fuzzy matching for handling typos and partial matches, and semantic embeddings for contextual understanding of queries.  
- **Data Preprocessing**: Utilizes [SymSpell](https://github.com/wolfgarbe/SymSpell) for efficient spell correction and [spaCy](https://spacy.io/)’s word vectors for query expansion. This addresses issues related to typos, ambiguous queries, and enhances the recall of relevant items.  
- **Fuzzy Relevance Scoring**: Implements fuzzy systems for better handling of similar but not exact matches, improving the chances of retrieving relevant products.  
- **Semantic Similarity Measures**: Leverages [SentenceTransformer](https://www.sbert.net/) to generate embeddings for products and queries, allowing us to measure cosine similarity for ranking results. This ensures that recommendations are not just relevant but also context-aware.  

## Dataset  
The dataset used for this project can be found at the following link:  

- **[Download Dataset](#)**  

For Google News vectors, which can enhance the natural language processing capabilities of the system, please use the following link:  

- **[Download Google News Vectors](#)**  

## Installation  
To get started with this project, clone the repository and install the necessary dependencies:  

```bash  
git clone https://github.com/yourusername/enhanced-ecommerce-search.git  
cd enhanced-ecommerce-search  
pip install -r requirements.txt
