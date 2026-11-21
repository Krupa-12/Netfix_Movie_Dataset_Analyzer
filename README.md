# 🎬 Netflix/Movie Dataset Analyzer

An end-to-end Exploratory Data Analysis (EDA) and visualization pipeline built in Python to uncover content trends, genre distributions, duration patterns, and release metrics across a Netflix movie and TV show dataset.

## 🚀 Project Overview
This project transforms raw streaming metadata (`netflix_titles.csv`) into actionable insights through automated data cleaning, statistical profiling, and visual storytelling. It explores key questions around content growth over time, movie vs. TV show ratios, top-producing countries and directors, audience rating trends, and movie runtime distributions.

## ✨ Key Features
* **Data Cleaning & Preprocessing:** Handles missing values (`director`, `country`), removes duplicate `show_id` entries, parses multi-label genres, and extracts release/addition years.
* **Exploratory Data Analysis & Visuals:**
  * **Catalog Breakdown:** Pie chart and stacked bar chart comparing Movies (73.2%) vs. TV Shows (26.8%) overall and by release year.
  * **Geographic & Creator Insights:** Horizontal bar charts and a Country-vs-Content-Type heatmap highlighting the top 10 countries and top 10 directors.
  * **Genre & Rating Analysis:** Bar charts for content ratings, top 10 genres, and a cumulative Pareto chart of genre distribution.
  * **Runtime Profiling:** Histogram, scatter plot, and boxplots analyzing movie durations (averaging 123.2 minutes) across release years and top genres.
* **Automated Summary Reporting:** Programmatically generates and downloads a clean `summary_report.txt` containing key dataset metrics.

## 🛠️ Tech Stack
* **Language:** Python 3
* **Libraries:** Pandas, Matplotlib
* **Environment:** Google Colab / Jupyter Notebook

## 💻 How to Run
1. Open `PDS_implementation.ipynb` in **Google Colab**.
2. Run the first cell and upload `netflix_titles.csv` when prompted.
3. Execute the remaining cells sequentially to generate all visualizations and automatically download `summary_report.txt`.
