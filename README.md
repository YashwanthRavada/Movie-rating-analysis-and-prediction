# 🎬 Movie Rating Analysis and Prediction System

## 📌 Project Overview

The **Movie Rating Analysis and Prediction System** is a Machine Learning project that analyzes movie data and predicts IMDb movie ratings using various features such as release year, duration, votes, genre, director, and actors.

The project uses Exploratory Data Analysis (EDA) to identify patterns and relationships in movie ratings and compares **Random Forest Regressor** and **CatBoost Regressor** to predict ratings.

## 🎯 Objectives

* Analyze movie ratings and identify trends in the dataset.
* Explore the relationship between movie features and ratings.
* Identify top genres, directors, and actors based on ratings and movie counts.
* Build and compare machine learning regression models.
* Predict movie ratings using relevant movie attributes.

## 📂 Dataset

**Dataset:** IMDb Movies India

The dataset contains information about Indian movies, including:

* Movie name
* Year of release
* Duration
* Genre
* IMDb rating
* Number of votes
* Director
* Lead actors

## 🛠️ Technologies Used

| Technology   | Purpose                         |
| ------------ | ------------------------------- |
| Python       | Programming language            |
| Pandas       | Data manipulation               |
| NumPy        | Numerical operations            |
| Matplotlib   | Data visualization              |
| Seaborn      | Statistical visualization       |
| Scikit-learn | Machine learning and evaluation |
| CatBoost     | Gradient boosting regression    |

## ⚙️ Project Workflow

### 1. Data Preprocessing

* Loaded the IMDb Movies India dataset.
* Removed missing values and duplicate records.
* Converted year, duration, and votes into appropriate numeric formats.

### 2. Exploratory Data Analysis (EDA)

* Analyzed distributions of ratings, movie durations, and votes.
* Visualized the relationship between votes and ratings.
* Identified the most common genres, directors, and actors.
* Examined average ratings across genres, directors, and years.
* Generated a correlation heatmap.

### 3. Feature Engineering

Created average rating features for:

* Genre
* Director
* Actor 1
* Actor 2
* Actor 3

These features were used alongside year, votes, and duration for model training.

### 4. Model Training

Two regression models were implemented:

* **Random Forest Regressor**
* **CatBoost Regressor**

The dataset was split into 80% training data and 20% testing data.

### 5. Model Evaluation

The models were evaluated using:

* **R² Score:** Measures how well the model explains rating variation.
* **Mean Absolute Error (MAE):** Measures the average absolute prediction error.
* **Mean Squared Error (MSE):** Measures the average squared prediction error.

### 6. Rating Prediction

The trained model predicts a movie rating based on input features such as year, votes, duration, and average ratings of its genre, director, and actors.

## 📊 Results and Visualization

The project includes:

* Distribution plots for movie ratings and numeric features.
* Genre and director rating comparisons.
* Actor popularity analysis.
* Average rating trends over the years.
* Feature importance visualization.
* Actual vs. predicted rating comparison.
* Model performance comparison.

## 🚀 How to Run the Project

### Prerequisites

Install Python and the required libraries.

```bash
pip install numpy pandas matplotlib seaborn scikit-learn catboost jupyter
```

### Steps

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Navigate to the project folder:

```bash
cd <your-project-folder>
```

3. Place the IMDb Movies India dataset in the appropriate directory.

4. Open the Jupyter Notebook:

```bash
jupyter notebook
```

5. Run the notebook cells in sequence.

## 📁 Project Structure

```text
Movie-Rating-Analysis-and-Prediction/
│
├── movie rating analysis and prediction system.ipynb
├── IMDb Movies India.csv
└── README.md
```

## 🔮 Future Improvements

* Develop a web application for interactive movie rating predictions.
* Add more movie-related features to improve prediction performance.
* Implement hyperparameter tuning for better model optimization.
* Prevent data leakage by calculating target-based average ratings using training data only.
* Deploy the trained model as a prediction API.

## 👨‍💻 Author

**Yashwanth Ravada**

Computer Science Engineering | AI & Machine Learning

---

⭐ If you find this project interesting, consider giving the repository a star!
