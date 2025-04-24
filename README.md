# Semantic Movie Recommender 🎬

A content-based movie recommendation system built using Python and natural language processing. It leverages TF-IDF vectorization and Word2Vec embeddings to analyze and compare plot summaries, enabling semantic movie recommendations based on user input.

---

## 💡 Features

- TF-IDF + Cosine Similarity recommendation engine  
- Word2Vec-based semantic similarity engine  
- Custom input for keyword or sentence-based querying  
- Clean, modular notebook implementation  
- Uses TMDB 5000 Movie Dataset

---

## 🧠 Technologies Used

- Python  
- Scikit-learn  
- Gensim  
- Pandas / NumPy  
- Jupyter Notebook

---

## 📁 Dataset

- [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Semantic-Movie-Recommender.git
   cd Semantic-Movie-Recommender
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook
   ```

4. Open `Semantic-Movie-Recommender.ipynb` and run all cells.

---

## 📥 Example Input

```python
user_input = "A thief who steals corporate secrets through the use of dream-sharing technology"
```

Expected output (top 5 semantically similar movies):
```
1. Inception
2. Interstellar
3. The Matrix
4. Source Code
5. Edge of Tomorrow
```

---

## 📸 Visual Output

### 🔹 TF-IDF Recommendations
![TF-IDF Output](./Screenshot%202025-04-24%20041129.png)

### 🔹 Word2Vec Recommendations
![Word2Vec Output](./Screenshot%202025-04-24%20041140.png)

---

## 📃 License

This project is licensed under the MIT License.
