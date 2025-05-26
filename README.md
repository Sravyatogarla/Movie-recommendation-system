# 🎬 Movie Recommendation System

This project is built as part of the **Edureka Data Science with SQL course**. It implements three different types of movie recommendation systems using the **MovieLens dataset**:

✅ Popularity-Based Recommender  
✅ Content-Based Recommender  
✅ Collaborative Filtering Recommender  

The project is built using Python, pandas, scikit-learn, and Plotly, and features **interactive inputs** for users to test different scenarios.

---

## 📚 Dataset Description

The data used in this project comes from the [MovieLens dataset](https://grouplens.org/datasets/movielens/100k/), a widely used dataset in recommender systems research.

- **movies.csv**: Contains `movieId`, `title`, and `genres`.  
- **ratings.csv**: Contains `userId`, `movieId`, `rating`, and `timestamp`.

---

## 📦 Project Structure

movie-recommendation-system/
├── README.md
├── LICENSE (MIT)
├── movie_recommendation_system.ipynb
├── movies.csv
├── ratings.csv


---

## 🎯 Recommender Systems Implemented

### 1️⃣ Popularity-Based Recommender
- Input: Genre, Minimum number of reviews, Number of recommendations
- Output: Top-rated movies in the selected genre

### 2️⃣ Content-Based Recommender
- Input: Movie title, Number of similar movies to recommend
- Output: Similar movies based on genre similarity using TF-IDF and Cosine Similarity

### 3️⃣ Collaborative Filtering Recommender
- Input: User ID, Number of similar users (K), Number of recommendations
- Output: Personalized movie recommendations based on user similarity

---

## 📊 Exploratory Data Analysis (EDA)

- **Genre Distribution**: Interactive bar chart showing the number of movies in each genre  
- **Rating Distribution**: Interactive histogram showing the distribution of user ratings

These visualizations are created using **Plotly** and displayed directly in the notebook.

---

## 🏃‍♂️ Getting Started

1️⃣ Clone this repository:

git clone https://github.com/YOUR_USERNAME/movie-recommendation-system.git

2️⃣ Navigate to the project directory:

---

- Key Highlights
  
1. Interactive user inputs for all three models

2. Colorful and interactive Plotly graphs

3. Clean and well-commented code with explanations

4. Practical application of data science concepts from Edureka course


---

### 📢 **What To Do Next**
1. Create your GitHub repo named `movie-recommendation-system`  
2. Add:
   - This `README.md`
   - `LICENSE` file (MIT)
   - Your `movie_recommendation_system.ipynb`
   - `movies.csv` and `ratings.csv`
3. Push to GitHub
4. 🎉 Done!

---

Would you like me to:
- ✅ **Generate the actual `LICENSE` file (MIT) for you?**
- ✅ **Provide a simple `git` setup cheat sheet** to push it easily?  
- ✅ **Create a custom cover/banner image for your repo?**  

