# 🎬 IMDb Top 1000 Movies Analysis with Pandas

This project explores the **IMDb Top 1000 Movies** dataset using **Pandas** and **data visualization libraries** like Matplotlib and Seaborn. The dataset includes essential information about top-rated movies such as title, genre, director, runtime, release year, and IMDb ratings.

## 📂 Dataset Overview
The dataset includes:
- 🎞️ **Title**
- ⭐ **IMDb Rating**
- ⏱️ **Runtime**
- 📅 **Year**
- 🎬 **Genre**
- 🎥 **Director**
- …and more!

## 🧠 Tasks Performed

### ✅ Task 1: Load and Explore the Dataset
- Loaded the dataset using `pandas.read_csv()`
- Displayed the **first 5 rows**
- Checked **data types**, **shape**, and **missing values**

### ✅ Task 2: Data Cleaning
- Removed **duplicate rows**
- Filled missing **IMDb ratings** with the **mean**
- Converted the **Runtime** column from `"120 min"` string format to **integers**

### ✅ Task 3: Data Filtering & Sorting
- Filtered movies with **IMDb rating > 8.5**
- Listed **Action** and **Sci-Fi** genre movies
- Selected movies released between **2000–2015**
- Sorted dataset by **IMDb rating (descending)**

### ✅ Task 4: Aggregation & Grouping
- Computed **average IMDb rating per genre**
- Identified the **year with the most releases**
- Found **top 5 directors** by number of movies

### ✅ Task 5: Visualization (Matplotlib / Seaborn)
- 📊 Histogram of **IMDb ratings**
- 📉 Bar chart of **top 10 genres**
- 📈 Line plot showing **IMDb rating trends by year**

## 📁 File Structure
- `imdb_analysis.py`: All data cleaning, analysis, and visualization scripts
- `imdb_top_1000.csv`: Dataset file
- `README.md`: Project documentation

## 💡 Learnings
This project highlights how **Pandas** can be used for real-world data cleaning, analysis, filtering, grouping, and visualization — all essential skills in data science and analytics.

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn



