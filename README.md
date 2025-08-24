# Netflix-Data-Ananlysis
Data analysis and visualization of Netflix titles using Python (Pandas + Matplotlib).
# 📊 Netflix Data Analysis with Matplotlib
Exploratory Data Analysis (EDA) of Netflix dataset using Python, Pandas, and Matplotlib.  
This project visualizes trends in Netflix content such as Movies vs TV Shows, content ratings, release years, durations, and country distribution.
## 📂 Dataset
- Source: [Netflix Titles Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Shape: ~8,800 rows, 12 columns  
- Key columns used: `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`
## 📊 Visualizations
- Movies vs TV Shows count  
- Percentage of content by rating  
- Distribution of movie durations  
- Number of releases per year  
- Top 10 countries producing content  
- Movies vs TV Shows trend over time  

### Sample Plots:
![Movies vs TV Shows](plots/movies_vs_tvshows.png)  
![Content Ratings](plots/content_rating.png)
## 🛠️ Tools & Libraries
- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook

---

### 6. Results & Insights
```markdown
## 📈 Key Insights
- Netflix has more movies than TV shows, but TV shows have grown rapidly since 2015.  
- Most content is rated **TV-MA** or **TV-14**.  
- Average movie duration is around 90–120 minutes.  
- USA and India contribute the most titles on Netflix.  
