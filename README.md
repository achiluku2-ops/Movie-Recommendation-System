# 🎬 Movie Recommendation System

A Machine Learning based **Movie Recommendation System** that suggests similar movies to users using **Content-Based Filtering**. The system analyzes movie genres and tags, converts them into numerical features using **TF-IDF Vectorization**, and recommends movies based on **Cosine Similarity**.

---

## 📌 Overview

This project recommends movies similar to a given movie title by comparing movie content rather than user ratings. It uses Natural Language Processing (NLP) techniques to extract meaningful features from movie metadata.

### Features
- Content-Based Movie Recommendations
- TF-IDF Feature Extraction
- Cosine Similarity Calculation
- Fast and Accurate Recommendations
- Simple User Input Interface

---

## 📂 Dataset

The project uses the **MovieLens Dataset**.

Files used:

- `movies.csv` – Contains movie titles and genres
- `ratings.csv` – Contains user ratings for movies

Dataset Source:
https://grouplens.org/datasets/movielens/

---

## 🧠 Model Used

### Content-Based Filtering

The recommendation engine works by finding movies with similar content.

#### Techniques Used

- **TF-IDF Vectorizer**
  - Converts movie genres/tags into numerical vectors.
  - Assigns importance to unique words.

- **Cosine Similarity**
  - Measures similarity between movie vectors.
  - Returns movies with the highest similarity scores.

---

## 🛠️ Libraries Used

- Pandas
- NumPy
- Scikit-learn
- NLTK

Install dependencies:

```bash
pip install pandas numpy scikit-learn nltk
```

---

## ⚙️ Workflow

### 1. Data Loading
Load movie and rating datasets.

### 2. Data Preprocessing
Handle missing values and prepare movie metadata.

### 3. Feature Extraction
Convert movie information into TF-IDF vectors.

### 4. Similarity Calculation
Compute cosine similarity matrix.

### 5. Recommendation Generation
Find movies with the highest similarity scores.

### 6. User Input Prediction
Accept a movie title and return recommendations.

---

## 🚀 How to Run

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
```

### Step 2: Install Dependencies

```bash
pip install pandas numpy scikit-learn nltk
```

### Step 3: Run the Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells sequentially.

---

## 📖 How to Use

1. Run all notebook cells in order.
2. Enter a movie name when prompted.
3. The system will generate the **Top 5 similar movie recommendations**.

---

## 📊 Sample Output

```text
Enter movie name: Toy Story

Top 5 Recommendations:

1. Toy Story 2
2. A Bug's Life
3. Monsters, Inc.
4. The Incredibles
5. Finding Nemo
```

---

## 📁 Project Structure

```text
Movie-Recommendation-System/
│
├── movies.csv
├── ratings.csv
├── Movie_Recommendation.ipynb
├── README.md
└── requirements.txt
```

---

## 🎯 Future Enhancements

- Hybrid Recommendation System
- Collaborative Filtering
- Deep Learning Based Recommendations
- Movie Poster Integration
- Web Application using Streamlit or Flask

---

## 👨‍💻 Author

**Akshay Sai**

B.Tech CSE (AI & ML)

---

## ⭐ If you like this project

Give this repository a **star ⭐** and support the project.
