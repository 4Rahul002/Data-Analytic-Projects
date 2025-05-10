# 📊 Netflix Movies & TV Shows EDA

A complete Exploratory Data Analysis (EDA) project on the Netflix Movies and TV Shows dataset. This project involves univariate, bivariate, and multivariate visualizations, outlier handling, winsorization, pair plots, and insights on trends across content types, genres, countries, and more.

---

## 📁 Dataset

* **File**: `NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv`
* **Source**: Netflix Titles (Movies + TV Shows)
* **Entries**: 7787 rows
* **Columns**: 12 attributes including title, type, director, cast, country, rating, duration, genre, etc.

---

## 📌 Project Structure

```
├── Netflix Eda Charts.py       # Python script with 15+ visualizations and insights
├── README.md                   # Project documentation
├── assets/                     # Folder for generated charts/images (if saved)
├── requirements.txt            # Python dependencies
```

---

## 🎯 Objectives

* Analyze the distribution of Netflix content (type, rating, country, year, etc.)
* Visualize genre patterns and duration differences
* Detect and treat outliers using Winsorization
* Handle missing values, duplicates, and convert text data into usable formats
* Generate actionable business insights

---

## 📊 Visualizations Included

1. Content Type Distribution
2. Top Countries by Content Count
3. Rating Distribution
4. Content Release Year Histogram
5. Top Genres
6. Type vs Rating
7. Content Added to Netflix per Year
8. Country vs Type Comparison
9. Duration by Type (Boxplot)
10. Correlation Heatmap
11. Cluster-style Countplot of Countries
12. Pie Chart of Top 5 Directors (excluding 'Not Available')
13. Word Cloud of Descriptions
14. Extra Chart: Average Duration by Genre (Movies)
15. Pairplot of Numeric Features

---

## 🧹 Data Cleaning Steps

* Filled missing values with appropriate labels (e.g. 'Not Available')
* Converted `date_added` to datetime
* Extracted year and duration as numerical values
* Removed or capped outliers using Z-Score and Winsorization
* Flagged outliers for optional filtering
* Removed duplicates

---

## 📦 Setup Instructions

1. Clone the repo:

```bash
git clone https://github.com/yourusername/netflix-eda.git
cd netflix-eda
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the analysis:

```bash
python Netflix\ Eda\ Charts.py
```

---

## ✅ Requirements

* Python 3.7+
* pandas
* matplotlib
* seaborn
* wordcloud
* scipy

---

## 📌 Key Insights

* \~70% of the content on Netflix is Movies
* USA, India, and UK are top content producers
* Documentaries and Dramas are the most popular genres
* Most content added between 2018-2020
* TV Shows are typically shorter in duration compared to Movies

---

## 📬 Contact

Made with 💻 by Rahul M Chavan
* LinkedIn:linkedin.com/in/rahul-m-chavan-90b915241/

