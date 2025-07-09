

# 🎬  "Netflix EDA with Content-Based Recommendations”


### Netflix Data Analysis & Recommendation System with Python 📊🔍

Dive into the world of Netflix with Python! Analyze over 10,000+ titles and uncover trends, visual stories, and content similarities from your favorite streaming giant using data science and machine learning.

---

## 📌 Overview

Netflix, one of the world’s leading video streaming platforms, has a massive global library of **movies** 🎥 and **TV shows** 📺, serving **222M+ subscribers** (as of mid-2021). This project delivers a complete **exploratory data analysis (EDA)** of Netflix content and a **content-based recommendation engine** using Python.

You'll discover insights about genres, ratings, countries, time trends, and even get recommendations for what to watch next — all using real-world Netflix data.

---

## 🔍 Project Highlights

### 🧰 Libraries Used

* **Pandas** 🐼 – data manipulation
* **NumPy** 🧮 – numerical operations
* **Matplotlib** 📊 – visualizations
* **Seaborn** 📈 – statistical plotting
* **WordCloud** ☁️ – generate textual data clouds
* **Scikit-learn** 🤖 – ML & similarity computation

---

## 📊 Dataset Columns

| Column         | Description                              |
| -------------- | ---------------------------------------- |
| `show_id`      | Unique identifier for each title         |
| `type`         | Movie or TV Show                         |
| `title`        | Title of the content                     |
| `director`     | Director’s name                          |
| `cast`         | Main cast members                        |
| `country`      | Country of production                    |
| `date_added`   | Date added to Netflix                    |
| `release_year` | Year of original release                 |
| `rating`       | Maturity rating (e.g., TV-MA, PG)        |
| `duration`     | Duration in minutes or number of seasons |
| `listed_in`    | Genre(s) of the content                  |
| `description`  | Short summary or synopsis                |

---

## 📈 Key Insights & Visualizations

* 🌍 Country-wise Rating Distribution
* 🎭 Genre Trends by Country
* 🔞 Genre vs. Rating Matrix
* 📊 Correlation Heatmaps
* 🎤 Most Active Actors
* ⏱️ Content Duration Analysis
* 📅 Time Trends in Content Addition
* 👶 Age Group Classification
* 🎬 Top Genres & Directors
* 🌎 Global Content Distribution
* 🍿 Movie vs. TV Show Breakdown

---

## 🤖 NEW: Content-Based Recommendation Engine

A lightweight machine learning engine recommends similar titles based on the **title**, **genre**, and **description** of Netflix content.

```python
recommend("Stranger Things", n=5)
```

🎯 Suggests similar shows by comparing textual similarity using **TF-IDF** and **cosine similarity**. Great for demo, search enhancement, and personalized recommendations.

---

## 🎯 Goals of the Project

* Deliver intuitive, visual summaries of Netflix’s library
* Practice real-world EDA and text-based ML techniques
* Analyze how genres, countries, and ratings shape content strategy
* Explore growth and evolution of Netflix over the years
* Introduce a content recommender for viewers and analysts

---

## 🌟 Features

✅ Cleaned and preprocessed dataset
✅ Beautiful plots with Seaborn and Matplotlib
✅ Word clouds for cast, genres, and descriptions
✅ Year-wise and country-wise analysis
✅ TF-IDF–based recommendation system
✅ Easy-to-use `recommend("Title")` function

---

## 🔮 Future Enhancements

* 📊 Add interactive dashboards (Streamlit / Plotly Dash)
* 🎥 Sentiment analysis on content descriptions
* 🧠 Expand to collaborative filtering
* 🔄 Integrate with Netflix API or scrape for live updates
* 🔁 Compare with Prime Video, Hulu, Disney+

---

## 🤝 Contributors

* **Esha Yalagi**
* **Mudabbir**

---

## 🧠 Topics & Skills

`#ExploratoryDataAnalysis` `#DataVisualization` `#MachineLearning` `#ContentRecommendation`
`#Netflix` `#Python` `#Pandas` `#Seaborn` `#ScikitLearn` `#WordCloud`

---

## 📣 About

Explore Netflix’s World 🌍🍿
An engaging, visual deep-dive into Netflix’s content library using Python. Whether you're a data enthusiast, student, or Netflix binge-watcher, this project helps you uncover the data science behind content trends and intelligent recommendations.

---

Let me know if you want this also as a downloadable `README.md` file!
