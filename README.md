# Content-Based-Movie-Recommendation-System
A machine learning project that recommends movies based on content similarity using NLP techniques. Built by adapting real-world dataset of IMDb.

---

## 🚀 Project Overview

This project implements a content-based recommender system that suggests similar movies by analyzing:

- Movie overview/description  
- Genres  
- Directors  
- Cast members  

Instead of using user ratings, it focuses on movie metadata and textual features.

---

## 🧠 How It Works

1. Data cleaning and preprocessing  
2. Feature engineering (combining text columns into tags)  
3. Vectorization using NLP techniques  
4. Similarity calculation using cosine similarity  
5. Generating movie recommendations  

---

## 📊 Techniques Used

- Feature Engineering  
- Natural Language Processing (NLP)  
- CountVectorizer / TF-IDF  
- Cosine Similarity  

---

## 📁 Dataset Used

- IMDb Top 1000 Movies Dataset  

(The system is adaptable to any similar dataset)

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## 🎯 Example Usage

```python
recommend("The Dark Knight")

