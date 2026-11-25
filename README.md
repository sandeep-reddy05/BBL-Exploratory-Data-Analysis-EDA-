# 🏏 Big Bash League (BBL) – Exploratory Data Analysis

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of Big Bash League (BBL) cricket data using Python. The main objective is to analyze player performance, team performance, batting and bowling statistics, and scoring patterns.

The project uses match-level and ball-by-ball delivery data to explore cricket statistics and identify meaningful insights through data analysis and visualization.

## 📂 Dataset Description

The project uses two datasets:

**1. matches.csv**
- Match ID
- Teams
- Venue
- Toss Decision
- Match Winner
- Match Result
- Player of the Match
- Match Date

**2. deliveries.csv**
- Match ID
- Batsman
- Bowler
- Runs
- Extras
- Overs
- Innings
- Wickets
- Dismissal Information

The two datasets are connected using the Match ID.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Loading
- Imported the required Python libraries.
- Loaded match and delivery datasets.
- Explored the structure and dimensions of the datasets.

### 2. Data Understanding
- Examined rows and columns.
- Checked data types.
- Analyzed numerical and categorical columns.
- Identified missing values.

### 3. Data Cleaning
- Identified missing values and handled them using appropriate methods.
- Filled event-related missing values with meaningful placeholders.
- Converted the match date column into datetime format.
- Checked and handled duplicate records.
- Removed rows with missing critical bowling team information.

### 4. Data Merging
- Merged matches and deliveries datasets using Match ID.
- Created a consolidated dataset for further analysis.

### 5. Feature Engineering and Analysis

Calculated important cricket performance metrics:

- **Strike Rate:** Runs scored per 100 balls faced.
- **Economy Rate:** Runs conceded per over.
- **Boundary Count:** Number of fours and sixes.
- **Dot Balls:** Deliveries where no runs were scored.
- **Powerplay Runs:** Runs scored during overs 0–5.
- **Death Over Runs:** Runs scored during overs 16–19.
- **Player Average:** Runs scored per dismissal.
- **Team Scoring Rate:** Runs scored per over.

### 6. Data Visualization
- Used Matplotlib and Seaborn to create visualizations.
- Explored player and team performance.
- Analyzed batting and bowling patterns.
- Compared scoring performance across different teams.

## 📊 Key Analysis Areas

- Top-performing batsmen
- Bowling performance
- Team scoring patterns
- Batting strike rates and averages
- Bowling economy rates
- Powerplay and death-over performance
- Boundary and dot-ball analysis

## 🎯 Key Learnings

- Learned how to clean and prepare real-world datasets.
- Practiced data manipulation using Pandas and NumPy.
- Applied grouping, filtering, and aggregation techniques.
- Created calculated cricket performance metrics.
- Developed data visualizations using Matplotlib and Seaborn.
- Improved practical Exploratory Data Analysis skills.

## 📁 Project Structure

```text
BBL-Exploratory-Data-Analysis/
│
├── eda_bbl.ipynb
├── delivers_and_matches.zip
└── README.md
```

## ▶️ How to Run This Project

1. Clone or download this repository.
2. Install the required Python libraries.

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Download and extract the dataset ZIP file.
4. Open `eda_bbl.ipynb` using Jupyter Notebook or Google Colab.
5. Update the dataset file paths if required.
6. Run all cells to perform the analysis.

## 👨‍💻 Author

**Sandeep Reddy**

Aspiring Data Analyst | Python | SQL | Excel | Power BI
