# 🎬 Movie Recommender System

A **Content-Based Movie Recommendation System** built with **Python**, **Pandas**, **NLTK**, and **Scikit-learn**. This project recommends movies similar to a user's selected movie by analyzing movie metadata such as genres, keywords, cast, director, and plot overview.

---

## 📌 Features

- 📊 Data cleaning and preprocessing
- 🎭 Feature extraction from movie metadata
- 📝 Text preprocessing (tokenization & stemming)
- 🔍 Bag-of-Words representation using CountVectorizer
- 📐 Cosine Similarity for recommendation
- 🎬 Recommend similar movies instantly
- 💾 Save trained model using Pickle

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- CountVectorizer
- Cosine Similarity
- Pickle
- Jupyter Notebook

---

## 📂 Dataset

This project uses the **TMDB 5000 Movie Dataset**.

Files:

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

The datasets are merged using the movie title and processed to create meaningful features for recommendation.

---

## ⚙️ Project Workflow

1. Load datasets
2. Merge movie and credits data
3. Clean missing and duplicate values
4. Extract important features:
   - Genres
   - Keywords
   - Cast
   - Director
   - Overview
5. Create a combined **tags** feature
6. Apply text preprocessing:
   - Lowercasing
   - Tokenization
   - Stemming
7. Convert text into vectors using **CountVectorizer**
8. Compute movie similarity using **Cosine Similarity**
9. Recommend the most similar movies

---

## 📈 Recommendation Method

This project uses a **Content-Based Filtering** approach.

Movies are represented as numerical vectors using the **Bag-of-Words** model. Similarity between movies is calculated with **Cosine Similarity**, allowing the system to recommend movies with similar content.

---

## 🚀 Example

```python
recommend("Avatar")
```

Example output:

```
Guardians of the Galaxy
John Carter
Star Trek
Aliens
The Fifth Element
```

---

## 📁 Project Structure

```
Movie-Recommender-System/
│
├── Movie Recommender System Data Analysis.ipynb
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── movie_list.pkl
├── similarity.pkl
└── README.md
```

---

## 🔮 Future Improvements

- TF-IDF Vectorization
- Word2Vec / FastText Embeddings
- BERT Sentence Embeddings
- Hybrid Recommendation System
- Collaborative Filtering
- Deep Learning Models
- Web Application using Django or Flask
- Streamlit Interactive Interface

---

## 👨‍💻 Author

**Abdellah Saidi**

🌐 Portfolio  
https://codebyabdellah.vercel.app/

💻 GitHub  
https://github.com/abdellahsaidi

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

---

## 📄 License

This project is open-source and available under the **MIT License**.