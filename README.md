# 🎬 Movie Recommender System

A Machine Learning based Movie Recommendation System that recommends movies similar to the one selected by the user.

The application is built using Python, Streamlit, Scikit-learn, and the TMDB API for fetching movie posters.

---

## 📌 Features

- Recommend Top 5 similar movies
- Displays movie posters
- Interactive Streamlit Web App
- Content-Based Recommendation System
- Fast Recommendation using Cosine Similarity

---

## 🚀 Demo

<img src="screenshots/home.png" width="800">

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle
- TMDB API

---

## 📂 Dataset

Dataset Used:

- TMDB Movies Dataset
- TMDB Credits Dataset

---

## 🧠 Machine Learning Workflow

1. Load movie dataset
2. Data Cleaning
3. Feature Engineering
4. Create Tags
5. Text Vectorization
6. CountVectorizer
7. Cosine Similarity
8. Recommendation Generation

---

## 📊 Project Flow

User selects a movie

↓

Movie converted into vector

↓

Cosine Similarity calculated

↓

Top 5 similar movies selected

↓

Movie posters fetched using TMDB API

↓

Displayed on Streamlit

---

## 📁 Project Structure

```
Movie-Recommender-System/
│
├── app.py
├── notebook.ipynb
├── README.md
├── requirements.txt
├── model/
├── dataset/
└── screenshots/
```

---

## ⚙ Installation

Clone Repository

```bash
git clone https://github.com/yourusername/Movie-Recommender-System.git
```

Go inside folder

```bash
cd Movie-Recommender-System
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run App

```bash
streamlit run app.py
```

---

## 📸 Screenshots

### Home Page

<img src="screenshots/home.png">

### Recommendation

<img src="screenshots/recommendation.png">

---

## 📚 Future Improvements

- Hybrid Recommendation System
- User Login
- Rating Prediction
- Deploy on Streamlit Cloud
- Search Autocomplete

---

## 👨‍💻 Author

Milind Khorgade

LinkedIn: (Your LinkedIn)

GitHub: https://github.com/yourusername
