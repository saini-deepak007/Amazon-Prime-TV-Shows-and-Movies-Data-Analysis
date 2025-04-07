# Amazon-Prime-TV-Shows-and-Movies-Data-Analysis



A comprehensive data analysis project exploring the catalog of Amazon Prime Video content, including TV shows and movies. This project utilizes data science techniques to uncover trends in content types, genres, release years, durations, ratings, and more. It is implemented using Python in a Jupyter Notebook and is ideal for gaining business or viewer insights into streaming platform content.



## 🧾 Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Key Insights](#key-insights)
- [How to Run](#how-to-run)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 📌 Overview

With the streaming industry becoming increasingly competitive, platforms like Amazon Prime need a clear understanding of their content landscape. This project explores the metadata of Amazon Prime content to identify patterns, evaluate genre diversity, and analyze temporal trends and audience suitability through ratings.

The analysis provides a foundation for understanding viewer preferences, platform strengths, and potential content gaps.

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA) on Amazon Prime's TV shows and movies.
- Discover patterns in content types, genres, release trends, and durations.
- Investigate audience targeting through age ratings.
- Visualize key trends to support strategic decisions for content planning.

---

## 📁 Dataset Description

The dataset includes metadata for Amazon Prime titles. While structure may vary slightly, typical columns include:

| Column Name    | Description                                          |
|----------------|------------------------------------------------------|
| `Title`        | Name of the movie or TV show                        |
| `Genre`        | Primary genre(s) of the content                     |
| `Director`     | Director of the movie or TV show                    |
| `Cast`         | Leading actors                                       |
| `Country`      | Country of origin                                    |
| `Date_added`   | When the content was added to the platform          |
| `Release_year` | Year the content was released                        |
| `Rating`       | Audience suitability rating (e.g., PG, TV-MA)       |
| `Duration`     | Duration in minutes or seasons (TV shows)           |
| `Type`         | Whether it’s a movie or TV show                      |
| `Description`  | Short description or synopsis of the content         |

---

## 🧰 Technologies Used

- **Python 3.8+**
- **Pandas** – for data cleaning and manipulation
- **NumPy** – for numerical operations
- **Matplotlib & Seaborn** – for data visualization
- **Google Colab / Jupyter Notebook** – for interactive analysis

---

## 📒 Project Structure

### 1. **Data Loading & Inspection**
- Load CSV/JSON dataset
- Preview columns, types, and basic statistics

### 2. **Data Cleaning**
- Handle missing/null values
- Format date columns
- Normalize categorical values (e.g., ratings)

### 3. **Feature Engineering**
- Extract year/month from `date_added`
- Standardize `duration` column for movies and TV shows
- Separate multiple genres for better analysis

### 4. **Exploratory Data Analysis (EDA)**
- **Content Type Breakdown**: Movies vs TV Shows
- **Content Release Trends**: By year or decade
- **Top Genres**: Most common genres and combinations
- **Rating Analysis**: Most frequent audience ratings
- **Country of Origin**: Distribution across nations
- **Duration Insights**: Common length of content

### 5. **Visualizations**
- Pie and bar charts for type, ratings, and genres
- Line graphs for year-wise content additions
- Heatmaps for correlation (e.g., year vs. rating trends)

---

## 🔍 Key Insights

> 📈 *Sample insights based on similar projects (can be updated with real ones):*

- Majority of content is **movies**, with **TV shows** forming a smaller portion.
- A peak in content addition was observed in **2019–2020**.
- **Drama** and **Comedy** are dominant genres across both movies and shows.
- Most content is rated **TV-MA** and **R**, indicating a mature audience.
- **USA** and **India** produce the most titles on the platform.

