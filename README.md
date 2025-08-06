# 🚀 YouTube Trending Videos Analysis 🎬📊

This project explores **trending video patterns, audience engagement**, and **content performance** based on YouTube trending data. Using **Python libraries like Pandas, Matplotlib, Seaborn, and NumPy**, I extracted actionable insights into what makes videos go viral.

---

## 🎯 Project Objective

To analyze a dataset of trending YouTube videos to uncover patterns related to:

- 🔝 Most frequent trending channels  
- 📅 Best days for videos to trend  
- 📈 View growth over time  
- ❤️ Engagement metrics (like ratios, comment ratios)

---

## 📁 Dataset Info

- 📂 Source: Kaggle — [YouTube Trending Videos Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)
- 📍 Country analyzed: [e.g., US or IN]
- 📈 Rows: ~40,000+ trending video entries
- 📅 Timeframe: Multiple months

---

## 🧹 Data Cleaning

✔ Handled missing values and duplicates  
✔ Parsed `publish_time` and `trending_date` into usable formats  
✔ Converted object datatypes into datetime  
✔ Removed outliers in views/likes/comments

---

## 📊 Key Visualizations

| Insight                            | Visual Type            |
|------------------------------------|-------------------------|
| Top 10 Trending Channels           | Horizontal Bar Chart    |
| Best Days for Trending             | Day-wise Heatmap        |
| Views vs Likes (Correlation)       | Scatter Plot            |
| Engagement Ratios                  | Distribution Plot       |
| Views Over Time                    | Line Chart              |

> 📂 All graphs saved inside `/visuals/` folder.

---

## 🔍 Sample Insights

✅ **T-Series** and **MrBeast** are among the most frequently trending channels  
✅ **Saturdays** have the highest likelihood of a video trending  
✅ **Engagement rate** (likes/views) is higher in videos < 3 minutes  
✅ **Comments spike** when videos trend early after publishing  
✅ **Trending does not always mean most viewed**, but it often boosts visibility

---



