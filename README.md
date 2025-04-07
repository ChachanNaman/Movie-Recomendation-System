# 🎬 Movie Recommendation System 🔍

Welcome to the world of intelligent movie suggestions! This is a **Content-Based Movie Recommendation System** built using **Python** and **machine learning techniques** like **cosine similarity**, **TF-IDF vectorization**, and **natural language processing** to help users discover movies similar to the ones they love.

---

## 🚀 Project Highlights

- ✅ Cleaned and merged complex datasets (`movies.csv`, `credits.csv`)
- ✅ Extracted features like `genres`, `keywords`, `cast`, `crew`, and `overview`
- ✅ Used **NLP techniques** to preprocess text (lemmatization, stopword removal, etc.)
- ✅ Created a `tags` feature combining all key metadata
- ✅ Applied **CountVectorizer** to vectorize movie data
- ✅ Calculated **Cosine Similarity** to find movie similarity scores
- ✅ Built a killer `recommend()` function to suggest top 5 similar movies
- ✅ Integrated everything in a beautiful **Jupyter Notebook**

---

## 🧠 How It Works

1. **Data Preprocessing**:
   - Merges two main datasets: `movies` and `credits`
   - Selects key features: title, id, overview, genres, keywords, cast, crew

2. **Feature Engineering**:
   - Extracts top 3 actors, director from crew
   - Combines all key text info into a single `tags` column
   - Applies lowercase formatting, removes spaces, special chars, etc.

3. **Vectorization + Similarity**:
   - Uses `CountVectorizer` to create a word-frequency matrix
   - Computes **cosine similarity** between movie vectors
   - Finds top similar movies based on similarity scores

4. **Movie Recommendation Function**:
   - Input a movie name, get top 5 recommended movies
   - Example:
     ```python
     recommend('Avatar')
     ```

---

## 🛠 Tech Stack

- 🐍 Python 3
- 🧪 Pandas, NumPy
- 🧠 Scikit-learn (CountVectorizer, Cosine Similarity)
- 📚 NLTK (for NLP preprocessing)
- 📊 Jupyter Notebook

---

## 📸 Sample Output

**Input**: `Inception`  
**Recommendations**:
- The Dark Knight Rises  
- The Prestige  
- Interstellar  
- Memento  
- Batman Begins  

**AUTHOR** - NAMAN CHACHAN

**EMAIL** - chachannaman@gmail.com

