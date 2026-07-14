# 🎬 Movie Recommendation System

A Movie Recommendation System built using Machine Learning that recommends movies based on user preferences. The project uses content-based filtering to suggest movies similar to the one selected by the user.

## 📌 Features

- Recommend movies based on similarity
- Fast and accurate recommendations
- User-friendly interface
- Displays top recommended movies
- Scalable recommendation pipeline

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle
- TMDB Dataset

---

## 📂 Project Structure

```
Movie-Recommendation-System/
│
├── app.py                  # Streamlit application
├── movie_list.pkl          # Processed movie dataset
├── similarity.pkl          # Similarity matrix
├── requirements.txt        # Project dependencies
├── README.md
└── assets/
```

---

## 📊 Dataset

The project uses the TMDB (The Movie Database) dataset containing information such as:

- Movie Title
- Genres
- Keywords
- Cast
- Crew
- Overview

These features are combined to generate movie recommendations.

---

## ⚙️ How It Works

1. Load the movie dataset.
2. Clean and preprocess the data.
3. Combine important textual features.
4. Convert text into numerical vectors using **CountVectorizer**.
5. Calculate cosine similarity between movies.
6. When a user selects a movie, the system retrieves the most similar movies based on cosine similarity scores.

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

### Navigate to the project folder

```bash
cd movie-recommendation-system
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
streamlit run app.py
```

---

## 📸 Demo

Example Recommendation:

Input:

```
Avatar
```

Output:

```
Guardians of the Galaxy
John Carter
Star Trek
The Avengers
Aliens
```

---

## 🧠 Machine Learning Concepts Used

- Data Preprocessing
- Feature Engineering
- Count Vectorization
- Cosine Similarity
- Content-Based Recommendation

---

## 📈 Future Improvements

- Collaborative Filtering
- Hybrid Recommendation System
- Personalized User Profiles
- Movie Posters using TMDB API
- Ratings and Reviews Integration
- Deep Learning-based Recommendations

---

## 📦 Requirements

```
streamlit
pandas
numpy
scikit-learn
```

or install all dependencies using

```bash
pip install -r requirements.txt
```

---

## 🎯 Applications

- OTT Platforms
- Movie Recommendation Websites
- Entertainment Applications
- Personalized Recommendation Systems

---

## 👨‍💻 Author

**Mohit Sharma**

AI/ML Developer

- Python
- Machine Learning
- Deep Learning
- Generative AI
- LangChain
- FastAPI

---

## ⭐ If you found this project helpful, please consider giving it a Star!
