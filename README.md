# 🎬 Movie Credits EDA Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a movie credits dataset to uncover patterns in actor appearances, director activity, and cast structures.

The goal is to understand how the film industry distributes opportunities among actors and directors, and to identify hidden trends using data.

---

## 📂 Dataset

* Source: TMDB Movie Dataset
* File Used: `credits.csv`

### Key Features:

* `movie_id`
* `cast` (list of actors)
* `crew` (includes director and other roles)

---

## 🛠️ Tools & Technologies

* Python 
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Key Analysis Performed

### 🎭 Actor Analysis

* Extracted top actors from cast data
* Identified most frequent actors
* Analyzed actor dominance

### 🎬 Director Analysis

* Extracted directors from crew data
* Identified most active directors
* Studied distribution of director activity

### 📏 Cast Size Analysis

* Calculated cast size per movie
* Analyzed distribution and outliers

### 🔗 Relationship Insights

* Actor collaboration patterns
* Industry distribution trends

---

## 📊 Visualizations

The project includes multiple visualizations such as:

* Actor co-occurrence heatmap
* Cast size distribution (Histogram & Violin Plot)
* Director activity distribution
* Cumulative contribution analysis
* Actor collaboration charts

---

## 🧠 Key Insights

* Total Unique Actors: **47,481**

* Most Frequent Actor: **John Wayne (106 movies)**

* Total Unique Directors: **17,572**

* Most Active Director: **John Ford (66 movies)**

* Average Cast Size: **12.37**

### 📊 Industry Pattern:

* Top 10 actors contribute only **0.63%** of total appearances
* Indicates **power-law distribution** (highly uneven industry structure)

---

## 🎯 Conclusion

The movie industry shows strong imbalance:

* A small group of actors dominate appearances
* Most directors have limited participation
* Cast sizes are generally moderate
* The overall structure reflects real-world concentration of influence

---

## 📁 Project Structure

```
movie-credits-eda-analysis/
│
├── data/
│   └── credits.csv
│
├── notebook/
│   └── eda_movie_project.ipynb
│
├── outputs/
│   └── reports/
│       └── summary.txt
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/mohamed-fazel/movie-credits-eda-analysis.git
```

2. Navigate to the project folder:

```bash
cd movie-credits-eda-analysis
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run `eda_movie_project.ipynb`

---

## 💼 Author

Fazel

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
