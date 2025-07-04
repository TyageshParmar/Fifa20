# ⚽ FIFA 20 Player Data Analysis & Clustering

This project explores the **FIFA 20 player dataset** to analyze footballer statistics, discover trends in player attributes, and cluster similar players based on skill metrics. The project includes end-to-end data analysis, exploratory insights, and unsupervised learning using clustering techniques.

## 📌 Project Objectives

1. Perform a complete exploratory data analysis on FIFA 20 player data.
2. Analyze football skills and **cluster players** based on their attributes.
3. Answer key questions including:
   - Top 10 countries producing the most professional players.
   - The age when player performance (overall rating) typically peaks.
   - Which offensive role (ST, RW, LW) is paid the most on average?

## 📊 Dataset

- Dataset: `players_20.csv`
- Source: EA Sports (FIFA 20 Career Mode dataset)
- Attributes include: player name, age, nationality, position, skill ratings, wages, potential, etc.

## 🧠 Techniques Used

- Exploratory Data Analysis (EDA)
- Data preprocessing & scaling
- Feature selection for skill metrics
- KMeans Clustering
- Elbow Method & Silhouette Score evaluation
- Role-based wage analysis
- Age vs. Overall Rating trend visualization

## 🤖 Clustering Summary

Players were clustered based on selected skill attributes using **KMeans**. The optimal number of clusters was determined using:
- Elbow Method
- Silhouette Scores

This revealed meaningful player archetypes based on performance stats.

## 📈 Key Insights

- **England, Germany, and Spain** produce the most players.
- Player **performance tends to peak around age 27–29**, then declines.
- **Strikers (STs)** tend to earn more than wingers (RW, LW), though wage varies widely by club and rating.

## ⚠️ Challenges Faced

- High-dimensional data required **feature scaling** for fair clustering.
- Choosing the number of clusters required **iterative evaluation**.
- Certain **categorical features** were not directly usable and required encoding or exclusion.

## 🛠️ Tools & Libraries

- Python, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (KMeans, preprocessing)

---

### 👤 Author

**Tyagesh Parmar**  
AI & Data Science Enthusiast  
[GitHub](https://github.com/TyageshParmar) | [LinkedIn](https://linkedin.com/in/tyageshparmar)
