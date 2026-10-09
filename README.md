# 🎬 Movie Recommendation System using KNN

A Machine Learning-based movie recommendation engine that utilizes the **Nearest Neighbors** algorithm to suggest personalized movies based on user genre preferences.

---

## 📌 Project Overview
This project processes a movie dataset containing various genre features and builds a **K-Nearest Neighbors (KNN)** model using Scikit-Learn. When provided with target genre inputs, the model computes feature proximity to recommend the top 5 most relevant movies along with their IMDB ratings.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-Learn (`NearestNeighbors`)

---

## 📊 Dataset Features
The model evaluates movies based on the following binary genre features:
- **Biography**
- **Drama**
- **Thriller**
- **Comedy**
- **Crime**
- **Mystery**
- **History**

---

## 🚀 How It Works
1. **Feature Extraction:** Extracts binary genre indicators from the movie dataset.
2. **Model Training:** Fits an unsupervised `NearestNeighbors` model on the dataset feature space.
3. **Inference:** Accepts genre vector input and computes the nearest Euclidean/Minkowski distances to return the top $k=5$ matching movies.

---

## 💻 How to Run

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/Movie-Recommendation-ML-Model.git](https://github.com/YOUR_USERNAME/Movie-Recommendation-ML-Model.git)
cd Movie-Recommendation-ML-Model
