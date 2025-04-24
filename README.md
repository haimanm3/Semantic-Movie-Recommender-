# Semantic Movie Recommender

A simple content-based recommendation system that uses TF-IDF vectorization and Word2Vec to compare movie plot summaries. The system recommends movies semantically similar to a given user input (keywords or a favorite movie’s plot).

## About

This project implements a content-based movie recommender using natural language processing techniques. It leverages TF-IDF vectorization and Word2Vec embeddings to analyze and compare movie plot summaries, enabling the recommendation of semantically similar movies based on user input.

## Technologies Used

- Python  
- Jupyter Notebook  
- Scikit-learn  
- Gensim  
- Pandas  
- NumPy  

## Dataset

The system utilizes the [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata), which includes movie overviews, titles, genres, and other metadata.

## Features

- TF-IDF-based cosine similarity for baseline recommendations  
- Word2Vec vector embeddings for deeper semantic analysis  
- Custom function to fetch top-N recommendations  
- Clean, easy-to-follow notebook format  

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Semantic-Movie-Recommender.git
   cd Semantic-Movie-Recommender
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open the notebook and follow along.

## License

This project is licensed under the MIT License.
