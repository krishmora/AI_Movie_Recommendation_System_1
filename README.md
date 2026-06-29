# AI_Movie_Recommendation_System_1

# 🎬 AI Movie Recommendation System

## 📌 Project Overview

The **AI Movie Recommendation System** is a beginner-friendly Artificial Intelligence project that recommends movies based on a user's preferences. The system asks the user to select a **genre**, **mood**, and **language**, then uses **Content-Based Filtering** with **TF-IDF Vectorization** and **Cosine Similarity** to recommend the most relevant movies.

This project demonstrates how AI can personalize recommendations, similar to streaming platforms such as Netflix and Amazon Prime Video.

---

## 🎯 Objectives

* Build a simple AI-based recommendation system.
* Learn how recommendation engines work.
* Understand Content-Based Filtering.
* Apply Machine Learning techniques to recommend movies based on user preferences.

---

## 🚀 Features

* User-friendly command-line interface.
* Accepts user preferences:

  * Genre
  * Mood
  * Language
* Validates user input.
* Uses TF-IDF Vectorizer to convert text into numerical features.
* Uses Cosine Similarity to calculate movie similarity.
* Displays the Top 5 recommended movies.
* Shows movie details including:

  * Title
  * Genre
  * Mood
  * Language
  * Year
  * IMDb Rating
  * Match Score
  * Description

---

## 🛠️ Technologies Used

* Python 3
* Pandas
* Scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity

---

## 💻 Example Input

```
Preferred Genre: Action
Preferred Mood: Inspiring
Preferred Language: Telugu
```

---

## 📊 Example Output

```
🎬 RECOMMENDED FOR YOU

1. RRR
Genre: Action
Mood: Inspiring
Language: Telugu
IMDb Rating: 8.1
Match Score: 98.5%

2. Baahubali
Genre: Action
Mood: Inspiring
Language: Telugu
IMDb Rating: 8.0
Match Score: 95.2%

...
```

---

## 🤖 AI Concepts Used

### Content-Based Filtering

The recommendation system suggests movies based on their features rather than other users' preferences.

### TF-IDF (Term Frequency-Inverse Document Frequency)

TF-IDF converts movie information into numerical vectors so the computer can compare them mathematically.

### Cosine Similarity

Cosine Similarity measures how closely the user's preferences match each movie. Movies with higher similarity scores are recommended first.

---

## 📈 Workflow

1. Load the movie dataset.
2. Combine movie features.
3. Convert text into TF-IDF vectors.
4. Accept user preferences.
5. Convert user preferences into a vector.
6. Calculate similarity using Cosine Similarity.
7. Rank movies by similarity score.
8. Display the top recommendations.

---

## 🌍 Real-World Applications

* Movie recommendation platforms
* OTT streaming services
* Music recommendation systems
* Book recommendation systems
* Online shopping product recommendations
* Personalized content recommendation

---

## 🔮 Future Improvements

* Add more movies to the dataset.
* Include movie posters.
* Recommend based on user ratings.
* Build a graphical user interface (GUI).
* Deploy as a web application using Streamlit or Flask.
* Add collaborative filtering for improved recommendations.

---

## 📚 Learning Outcomes

After completing this project, you will understand:

* Python programming
* Data preprocessing
* Recommendation systems
* Content-Based Filtering
* TF-IDF Vectorization
* Cosine Similarity
* Basic Machine Learning concepts

---


This project is developed for educational purposes and is free to use for learning and academic projects.
