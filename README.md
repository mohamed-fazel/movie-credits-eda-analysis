# 🎬 Movie Credits EDA Analysis

<p align="center">
  <strong>Data-driven exploration of movie casts, directors, and industry collaboration patterns using Exploratory Data Analysis.</strong>
</p>

<p align="center">
  Python • Pandas • NumPy • Matplotlib • Seaborn • Data Analytics
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Data%20Analysis-EDA-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/TMDB-Dataset-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />
</p>

---

# 📌 Project Overview

The film industry generates vast amounts of data through actors, directors, productions, and collaborations. Understanding these relationships can reveal fascinating insights about industry structure, opportunity distribution, and collaboration networks.

This project performs **Exploratory Data Analysis (EDA)** on the **TMDB Movie Credits Dataset** to investigate patterns in actor appearances, director activity, cast structures, and collaboration trends.

The analysis uncovers hidden industry dynamics and demonstrates how data analytics can be used to understand real-world entertainment ecosystems.

---

# 🎯 Project Objectives

* Analyze actor participation across movies.
* Identify the most active actors and directors.
* Explore cast size distribution.
* Investigate collaboration patterns within the film industry.
* Discover hidden trends in movie credits data.
* Generate meaningful insights through data visualization.
* Apply EDA techniques to a real-world entertainment dataset.

---

# 📂 Dataset Information

### Dataset Source

**TMDB (The Movie Database)**

### Dataset File

```text id="7ut2t0"
credits.csv
```

### Key Features

| Feature  | Description                                 |
| -------- | ------------------------------------------- |
| movie_id | Unique movie identifier                     |
| title    | Movie title                                 |
| cast     | List of actors appearing in the movie       |
| crew     | Production crew members including directors |
|          |                                             |

Director | Extracted from crew information |
| Cast Size | Number of actors per movie |

---

# ✨ Key Features

✅ Data Cleaning & Preprocessing

✅ Actor Frequency Analysis

✅ Director Activity Analysis

✅ Cast Size Distribution Analysis

✅ Collaboration Network Exploration

✅ Industry Pattern Discovery

✅ Statistical Analysis

✅ Data Visualization

✅ Insight Generation

---

# 🔄 Project Workflow

```text id="qj7v3n"
TMDB Credits Dataset
          │
          ▼
Data Cleaning
          │
          ▼
Data Extraction
(Cast & Crew)
          │
          ▼
Exploratory Analysis
          │
          ▼
Actor Analysis
Director Analysis
Cast Size Analysis
          │
          ▼
Visualization
          │
          ▼
Industry Insights
```

---

# 🎭 Actor Analysis

The project explores actor participation across thousands of movies.

### Analysis Performed

* Extraction of actor names from cast data
* Frequency analysis of actor appearances
* Identification of most frequent actors
* Dominance analysis within the industry
* Contribution analysis of top performers

### Key Findings

🏆 Most Frequent Actor:
**John Wayne**

🎬 Total Appearances:
**106 Movies**

👥 Total Unique Actors:
**47,481**

---

# 🎬 Director Analysis

Directors play a crucial role in shaping the film industry.

### Analysis Performed

* Director extraction from crew data
* Activity frequency calculation
* Distribution analysis
* Director contribution evaluation

### Key Findings

🏆 Most Active Director:
**John Ford**

🎥 Total Directed Movies:
**66 Movies**

👤 Total Unique Directors:
**17,572**

---

# 📏 Cast Size Analysis

The project investigates how many actors typically participate in a movie.

### Metrics Studied

* Average Cast Size
* Distribution of Cast Members
* Outlier Detection
* Large Ensemble Productions

### Result

🎭 Average Cast Size:
**12.37 Actors per Movie**

The majority of films contain moderate-sized casts, while a small number of productions feature exceptionally large ensembles.

---

# 🔗 Collaboration & Industry Insights

The analysis explores relationships among actors and directors.

### Investigated Areas

* Actor collaboration frequency
* Shared movie appearances
* Industry concentration patterns
* Opportunity distribution

### Major Observation

The movie industry follows a **Power-Law Distribution**:

* A small number of actors appear in many movies.
* Most actors appear only a few times.
* Director activity is similarly concentrated.

This reflects real-world inequality in visibility and opportunities within the entertainment industry.

---

# 📊 Visualizations Generated

The project includes several analytical visualizations:

### 🎭 Actor Analytics

* Top Actor Frequency Chart
* Actor Contribution Analysis
* Actor Collaboration Matrix

### 🎬 Director Analytics

* Director Activity Distribution
* Most Active Directors Bar Chart

### 📏 Cast Analysis

* Cast Size Histogram
* Cast Size Violin Plot
* Distribution Curves

### 🔥 Advanced Insights

* Actor Co-occurrence Heatmap
* Cumulative Contribution Analysis
* Industry Concentration Visualization

---

# 🧠 Key Insights

### Actor Statistics

| Metric              | Value      |
| ------------------- | ---------- |
| Total Unique Actors | 47,481     |
| Most Frequent Actor | John Wayne |
| Actor Appearances   | 106 Movies |

### Director Statistics

| Metric                 | Value     |
| ---------------------- | --------- |
| Total Unique Directors | 17,572    |
| Most Active Director   | John Ford |
| Directed Movies        | 66        |

### Industry Pattern

📊 Top 10 actors contribute only **0.63%** of total appearances.

This demonstrates the highly unequal distribution of opportunities and visibility in the film industry.

---

# 🛠️ Technology Stack

## Programming Language

* Python

## Data Processing

* Pandas
* NumPy

## Data Visualization

* Matplotlib
* Seaborn

## Development Environment

* Jupyter Notebook
* VS Code

---

# 📂 Project Structure

```text id="r02zba"
movie-credits-eda-analysis/

├── data/
│   └── credits.csv
│
├── notebook/
│   └── eda_movie_project.ipynb
│
├── outputs/
│   ├── visualizations/
│   └── reports/
│       └── summary.txt
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🚀 How to Run

### Clone Repository

```bash id="ggdkfa"
git clone https://github.com/mohamed-fazel/movie-credits-eda-analysis.git
```

### Navigate to Project Folder

```bash id="9l7mg4"
cd movie-credits-eda-analysis
```

### Install Dependencies

```bash id="q2ny4o"
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash id="iwm7u6"
jupyter notebook
```

### Open Notebook

```text id="8w6ij4"
eda_movie_project.ipynb
```

Run all cells sequentially.

---

# 📈 Project Outcomes

* Successfully analyzed thousands of movie credits records.
* Identified actor and director participation patterns.
* Uncovered power-law distributions within the industry.
* Generated meaningful visual insights.
* Demonstrated practical EDA techniques on entertainment data.

---

# 🚀 Future Enhancements

* Actor Recommendation System
* Movie Success Prediction
* Director Collaboration Network Analysis
* Interactive Dashboard using Streamlit
* Social Network Graph Visualization
* Genre-Based Industry Analysis
* Advanced NLP on Movie Metadata

---

# 👨‍💻 Author

### Mohamed Fazel

🎓 B.Tech Artificial Intelligence & Data Science

💻 AI Engineer | Prompt Engineer | Data Analytics Enthusiast

🔗 GitHub: https://github.com/mohamed-fazel

🔗 LinkedIn: https://www.linkedin.com/in/mohamed-fazel

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

Your support helps improve future Data Analytics and AI projects.

---

<p align="center">
  <strong>🎬 Turning Movie Data into Actionable Insights 📊</strong>
</p>
