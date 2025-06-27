# 🎬 Recommender Systems Projects

This folder contains two projects that demonstrate the creation of basic and item-based **Recommender Systems** using the MovieLens dataset. These were developed as part of my machine learning practice from Jose Portilla’s ML course on Udemy.

---

## 📁 Dataset Files Used:
- `u.data` – User-movie ratings (user_id, item_id, rating, timestamp)
- `u.item` – Movie metadata (movie titles, release dates)
- `Movie_id_titles` – Cleaned mapping of item_id to movie titles

---

## 🍿 Project 1: Simple Recommender System

### 🎯 Objective:
Build a movie recommendation system based on average user ratings and the number of ratings per movie.

### ⚙️ Steps Taken:
- Merged `u.data` with `Movie_id_titles` to get movie names
- Grouped by movie title to get:
  - Average rating
  - Number of ratings
- Created a pivot table with users as rows and movies as columns
- Used **Pearson correlation** to recommend similar movies to a given movie (e.g., “Star Wars”)

### 🧠 What I Practiced:
- Data wrangling with pandas
- Calculating correlations for recommendations
- Filtering by minimum number of ratings to improve quality

---

## 🎥 Project 2: Item-Based Collaborative Filtering

### 🎯 Objective:
Recommend movies based on a user’s previous ratings by finding similar movies that others rated highly.

### ⚙️ Steps Taken:
- Created a user-movie rating matrix
- For a specific user, fetched all movies they’ve rated
- Found similar movies to those using correlation across users
- Weighted recommendations by number of ratings to avoid rare movie bias

### 🧠 What I Practiced:
- Building an **item-based collaborative filter**
- How user preferences can be used to find item-item similarity
- Limitations of sparse user-item matrices and cold-start problems

---

## 🎯 Key Learnings

- Basics of building a movie recommendation engine
- Difference between **Simple Recommenders** vs **Collaborative Filtering**
- How to use correlation and rating count for quality recommendations
- Real-world handling of user-movie interaction data

---

> ✅ These projects gave me a strong foundation in how recommender systems work using real-world data. Code, analysis, and interpretations were practiced and written by me during the course.
