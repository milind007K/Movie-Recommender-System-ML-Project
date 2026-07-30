<div align="center">

# 🎬 Movie Recommender System

### A Machine Learning based Content Recommendation Engine built using Python, Streamlit & TMDB API

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python">
  <img src="https://img.shields.io/badge/Machine%20Learning-Content%20Based-success">
  <img src="https://img.shields.io/badge/Streamlit-Web%20Application-ff4b4b?logo=streamlit">
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn">
  <img src="https://img.shields.io/badge/License-MIT-green">
</p>

<p align="center">
A smart movie recommendation system that suggests similar movies based on content similarity using Machine Learning.
</p>

---

## 📌 Table of Contents

- About the Project
- Demo
- Features
- Tech Stack
- Project Architecture
- Machine Learning Pipeline
- Dataset
- Recommendation Process
- Project Structure
- Installation
- Usage
- Screenshots
- Future Improvements
- Learning Outcomes
- Contributing
- License
- Author

---

# 🎯 About the Project

Choosing a movie to watch can be difficult because thousands of movies are available across different genres and platforms.

This project solves that problem by recommending movies similar to the one selected by the user.

The recommendation engine uses **Content-Based Filtering**, where each movie is represented by its features such as:

- Genres
- Keywords
- Overview
- Cast
- Crew

The system converts these features into vectors using **CountVectorizer** and calculates similarity using **Cosine Similarity**.

The web application is developed using **Streamlit**, while movie posters are fetched dynamically using the **TMDB API**.

---

# 🎥 Demo

### Home Page

> Add Screenshot Here

```
<img src="Screenshots/Screenshot 2026-07-30 120151.png">```

---

### Recommendation Result

<img src="Screenshots/Screenshot 2026-07-30 120523.png">
```
screenshots/recommendation.png
```
<img src="Screenshots/Screenshot 2026-07-30 120505.png">
---

# ✨ Features

✅ Interactive Streamlit Interface

✅ Content-Based Recommendation System

✅ Top 5 Similar Movie Recommendations

✅ Movie Poster Fetching using TMDB API

✅ Fast Recommendation using Cosine Similarity

✅ Clean and Responsive UI

✅ Machine Learning Model Integration

---

# 🛠 Tech Stack

## Programming Language

- Python

## Machine Learning

- Scikit-Learn

## Data Processing

- Pandas
- NumPy

## Web Framework

- Streamlit

## API

- TMDB API

## Model Storage

- Pickle

## Version Control

- Git
- GitHub

---

# 🧠 Machine Learning Pipeline

```
Dataset
     │
     ▼
Data Cleaning
     │
     ▼
Feature Engineering
     │
     ▼
Combine Important Features
     │
     ▼
Text Vectorization
(CountVectorizer)
     │
     ▼
Cosine Similarity Matrix
     │
     ▼
Save Model (.pkl)
     │
     ▼
Streamlit Application
     │
     ▼
Movie Recommendation
```

---

# ⚙ How Recommendation Works

### Step 1

User selects a movie.

↓

### Step 2

The movie is converted into a vector.

↓

### Step 3

The system searches the similarity matrix.

↓

### Step 4

Movies with the highest cosine similarity score are selected.

↓

### Step 5

Movie posters are fetched from TMDB API.

↓

### Step 6

Top 5 recommendations are displayed.

---

# 📊 Dataset

This project uses the **TMDB 5000 Movie Dataset**.

Files used:

- movies.csv
- credits.csv

Dataset contains:

- Movie Title
- Genres
- Overview
- Keywords
- Cast
- Crew
- Release Date
- Popularity

---

# 📁 Project Structure

```
Movie-Recommender-System
│
├── app.py
├── notebook.ipynb
├── README.md
│
├── dataset
│   ├── movies.csv
│   └── credits.csv
│
├── model
│   ├── similarity.pkl
│   └── movie_list.pkl
│
├── screenshots
│   ├── home.png
│   └── recommendation.png

```

---

# 📦 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Movie-Recommender-System.git
```

---

## Move to Project Folder

```bash
cd Movie-Recommender-System
```

---

## Create Virtual Environment (Optional)

Windows

```bash
python -m venv venv
```

Activate

```bash
venv\Scripts\activate
```

Mac/Linux

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
streamlit run app.py
```

Open browser

```
http://localhost:8501
```

---

# 📸 Screenshots

## Home Page
<img src="Screenshots/Screenshot 2026-07-30 120151.png">

---

## Recommendations
<img src="Screenshots/Screenshot 2026-07-30 120523.png">
---

# 📚 Libraries Used

- pandas
- numpy
- scikit-learn
- streamlit
- requests
- pickle

---

# 📈 Future Improvements

- User Login System
- Collaborative Filtering
- Hybrid Recommendation System
- Deep Learning Recommendation
- Personalized Recommendations
- Movie Trailer Integration
- Genre Filters
- IMDb Ratings
- Watchlist Feature
- Deployment on Cloud

---

# 🎓 Learning Outcomes

This project helped in understanding:

- Data Cleaning
- Feature Engineering
- NLP Basics
- Text Vectorization
- CountVectorizer
- Cosine Similarity
- Recommendation Systems
- Streamlit Development
- API Integration
- Model Deployment
- Git & GitHub

---

# ❓ Why Content-Based Filtering?

Content-Based Filtering recommends movies based on movie attributes instead of user ratings.

Advantages:

- No cold start for new movies
- Fast recommendations
- Easy to implement
- Works well with metadata

---

# 🚀 Future Deployment

The application can be deployed using:

- Streamlit Community Cloud
- Render
- Railway
- Hugging Face Spaces

---

# 🤝 Contributing

Contributions are welcome!

If you have suggestions for improving the recommendation engine or UI:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# 📝 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Milind Khorgade**

B.Tech Artificial Intelligence & Machine Learning

Shri Ramdeobaba College of Engineering and Management

📧 Email: Milindkhorgade07@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/milind007k/

🐙 GitHub: https://github.com/milind007K

---

# ⭐ If you like this project

Give this repository a ⭐ on GitHub.

It motivates me to build more Machine Learning projects.

---
