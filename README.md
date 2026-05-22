# 🏏 IPL Cricket Data Analysis System

## 📌 Project Overview

The IPL Cricket Data Analysis System is a data analytics project built using Python to analyze Indian Premier League (IPL) cricket data. This project performs data cleaning, preprocessing, exploratory data analysis (EDA), and visualization to extract meaningful insights from IPL matches and ball-by-ball datasets.

The goal is to uncover patterns such as team performance, player statistics, match trends, winning factors, and season insights using data science techniques.

---

## 🎯 Project Objectives

- Analyze IPL match datasets
- Perform data cleaning and preprocessing
- Explore team and player performance
- Visualize match statistics
- Identify trends and patterns in IPL history
- Generate insights using graphs and statistical analysis

---

## 📂 Dataset Used

This project uses two IPL datasets:

### 1. Matches Dataset
Contains:

- Match ID
- Season
- Teams
- Venue
- Toss winner
- Match winner
- Player of the match
- Umpires

### 2. Deliveries Dataset

Contains:

- Match ID
- Innings
- Batting team
- Bowling team
- Over details
- Batsman runs
- Extra runs
- Total runs
- Wicket information

Dataset Source:
Kaggle IPL Dataset

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## 📦 Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 📊 Project Workflow

### Step 1: Import Libraries

Load required Python libraries.

### Step 2: Load Dataset

Read:

- matches.csv
- deliveries.csv

### Step 3: Data Exploration

- View shape of datasets
- Check data types
- Handle missing values
- Explore columns

### Step 4: Data Cleaning

- Remove null values
- Fix inconsistent records
- Convert data types

### Step 5: Exploratory Data Analysis

Performed analysis such as:

✔ Total IPL seasons  
✔ Team performance analysis  
✔ Most successful teams  
✔ Toss impact on match results  
✔ Player of the Match analysis  
✔ Top batsmen  
✔ Top wicket takers  
✔ Venue analysis  
✔ Winning trends

---

## 📈 Visualizations Included

This project contains multiple visualizations:

- Bar Charts
- Count Plots
- Pie Charts
- Histograms
- Heatmaps
- Team Performance Graphs
- Player Statistics Graphs

---

## 🔍 Sample Insights

- Teams winning toss often gain an advantage.
- Some venues favor chasing teams.
- Certain players consistently dominate across seasons.
- Team performance varies significantly over years.

---

## 📁 Project Structure

```bash
IPL-Cricket-Data-Analysis-System/
│
├── matches.csv
├── deliveries.csv
├── IPL_Cricket_Data_Analysis.ipynb
├── images/
├── README.md
```

---

## 🚀 How To Run Project

### Clone Repository

```bash
git clone https://github.com/yourusername/IPL-Cricket-Data-Analysis-System.git
```

### Move into folder

```bash
cd IPL-Cricket-Data-Analysis-System
```

### Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### Run notebook

```bash
jupyter notebook
```

Open:

```bash
IPL_Cricket_Data_Analysis.ipynb
```

---

## 📷 Project Screenshots

Add screenshots of:

- Dataset overview
- Data cleaning process
- Charts and visualizations
- Final insights

Example:

```md
![Dashboard](images/dashboard.png)
```

---

## 🔮 Future Improvements

- Add machine learning prediction model
- Predict match winners
- Create dashboard using Power BI
- Deploy using Streamlit
- Add live IPL API integration

---

## 🤝 Contribution

Contributions are welcome.

Fork this repository and create a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Nishikant Ghute

Aspiring AI | Data Science | Machine Learning Enthusiast

GitHub: https://github.com/yourusername
