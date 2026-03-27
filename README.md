# Netflix-Data-Analysis-using-Python-Pandas-Matplotlib-
# Netflix Data Analysis Project

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Netflix dataset using **Python, Pandas, and Matplotlib**.
The goal is to analyze content distribution, trends, and patterns in movies and TV shows available on Netflix.

---
##  Dataset
* Dataset Name: `netflix_titles.csv`
* Contains information about:
  * Type (Movie / TV Show)
  * Release Year
  * Rating
  * Country
  * Duration
  * Genres
---

## Technologies Used

* Python 
* Pandas 
* Matplotlib 
---

## Data Cleaning

* Removed missing values from important columns:

  * `type`, `release_year`, `rating`, `country`, `duration`
* Converted duration from string to integer (minutes)

---

## Analysis & Visualizations

### 1️ Content Type Distribution

* Bar chart showing number of Movies vs TV Shows

---

### 2️ Content Rating Distribution

* Pie chart showing percentage of content ratings
* Combined smaller categories into "Others" for clarity

---

### 3️ Movie Duration Analysis

* Histogram showing distribution of movie durations

---

### 4️ Release Year Analysis

* Scatter plot showing number of releases per year

---

### 5️ Top 10 Countries by Content

* Horizontal bar chart of top countries producing content

---

### 6️ Movies vs TV Shows Over Time

* Line plots comparing yearly trends of Movies and TV Shows

---

### 7️ Top 10 Genres on Netflix 🔥

* Visualized top 10 most popular genres using a horizontal bar chart

---

##  Key Insights

* Movies dominate the Netflix platform compared to TV Shows
* Content production increased significantly after 2010
* Most movies fall within a specific duration range
* A few countries contribute the majority of content
* Genres like Drama and International Movies are highly frequent

---

##  Output Files

The project generates the following visualizations:

* `movies_vs_tv_show.png`
* `content_rating.png`
* `movie_duration.png`
* `release_year_scatter.png`
* `countries.png`
* `movies_tv_shows.png`
* `genre visualization chart`

---

##  Future Improvements

* Use Seaborn for advanced visualization
* Add interactive dashboards (Plotly)
* Perform deeper genre-based analysis
* Apply machine learning for predictions

---

##  Author
**Tarik Jamil**

---

## ⭐ If you like this project


Give it a ⭐ on GitHub!
