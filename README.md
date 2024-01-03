
# Quran Search Engine

This project implements a search engine for the Holy Quran using various NLP techniques like TF-IDF, Sentence Transformers and BERT embeddings.

## Data
The Quran dataset from Kaggle is used containing 114 surahs and 6236 ayahs. The raw text is cleaned and preprocessed before feeding to models.

## Features
* Search ayahs based on user query using TF-IDF similarity
* Generate Ayah embeddings with SentenceTransformers and enable semantic search
* Create embeddings with multilingual AraBERT and search using FAISS index
* Visualize verses using t-SNE projections
* Find number of ayahs in each surah
* Cluster ayahs using similarity

## Models
* sklearn TfidfVectorizer
* SentenceTransformers distiluse-base-multilingual-cased
* AraBERT model from aubmindlab
* t-SNE for dimensionality reduction
* Faiss similarity search
* Agglomerative clustering

## Usage
The search functions take user's query as input and retrieve most similar ayahs from the entire Quran. Relevance can be further improved via hyperparameter tuning.

The notebook also demonstrates interactive visualizations like ayah counts per surah, embedding projections and clustering.

Overall, it provides a good foundation for building more personalized and context-aware Quran search solutions.

