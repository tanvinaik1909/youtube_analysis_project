# 📊 Unlocking YouTube Channel Performance Secrets

A data science project that analyzes YouTube video metrics to uncover trends, improve engagement, and optimize content strategy. This project explores patterns in views, likes, comments, duration, tags, and subscriber growth using Python libraries like Pandas, Matplotlib, and Seaborn.

---

## 📁 Dataset

The dataset (`youtube_channel_data.csv`) includes the following fields:

- `Video_ID` – Unique identifier of the video  
- `Title` – Title of the video  
- `Views` – Number of video views  
- `Likes` – Number of likes  
- `Dislikes` – Number of dislikes  
- `Comments` – Number of comments  
- `Upload_Date` – Date of upload  
- `Duration (mins)` – Video duration in minutes  
- `Tags` – Keywords related to video content  
- `Category` – Video content category  
- `Subscribers_Gained` – Subscribers gained from the video  

---

## 🎯 Objectives

- Identify high-performing video patterns
- Analyze relationship between views, likes, and subscribers
- Determine best content categories and upload times
- Discover common tags in successful videos
- Build simple regression to predict subscribers gained

---

## 🧰 Tech Stack

- 🐍 Python  
- 📊 Pandas, Matplotlib, Seaborn  
- 📘 Jupyter Notebook  
- 💡 Scikit-learn *(optional ML)*

---

## 📈 Key Visualizations

- Barplot: Top 5 most viewed videos  
- Scatterplot: Likes vs Views  
- Heatmap: Correlation among features  
- Pie chart: Category distribution  
- Boxplot: Views by Category  
- Regression: Subscribers vs Likes

---

## 🧠 Insights Extracted

- Short, educational content performs best
- Likes and comments strongly correlate with views
- Weekday uploads (especially Tuesday/Thursday) are more consistent
- Memes got more views but not subscribers
- Engagement score = likes + comments + subscribers is a strong success metric
