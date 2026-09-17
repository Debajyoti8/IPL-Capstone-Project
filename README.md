# IPL 2022 Capstone Project

An exploratory data analysis project on **Indian Premier League (IPL) 2022 match-level data** using Python, Pandas, Seaborn, and Matplotlib.

## 📌 Project Overview

The Indian Premier League (IPL) is a professional T20 cricket league in India featuring franchise teams representing different cities. This project analyzes IPL 2022 match data to derive meaningful insights into **match outcomes, player performances, team dynamics, scoring patterns, bowling performances, and toss-related factors**.

The analysis is implemented in a Jupyter Notebook using the dataset provided in `IPL.csv`.

## 🎯 Objectives

- Explore and understand the IPL 2022 match-level dataset.
- Perform basic data inspection and data-quality checks.
- Analyze team match-winning performance.
- Study toss winners and toss decisions.
- Examine first- and second-innings scores and wickets.
- Analyze player-of-the-match and top-scorer information.
- Study high-scoring batting performances.
- Analyze bowling performances and bowling figures.
- Visualize important patterns using bar plots and other plots.

## 📂 Dataset

The project uses `IPL.csv`, containing **74 IPL 2022 matches and 20 columns**. The notebook shows that all 74 records are non-null across the listed columns.

### Main Columns

| Column | Description |
|---|---|
| `match_id` | Unique match identifier |
| `date` | Match date |
| `venue` | Match venue |
| `team1` | First participating team |
| `team2` | Second participating team |
| `stage` | Match stage |
| `toss_winner` | Team that won the toss |
| `toss_decision` | Toss decision |
| `first_ings_score` | First-innings score |
| `first_ings_wkts` | First-innings wickets |
| `second_ings_score` | Second-innings score |
| `second_ings_wkts` | Second-innings wickets |
| `match_winner` | Winning team |
| `won_by` | Type of victory |
| `margin` | Winning margin |
| `player_of_the_match` | Player awarded Player of the Match |
| `top_scorer` | Top scorer of the match |
| `highscore` | Top scorer's score |
| `best_bowling` | Best bowling performer |
| `best_bowling_figure` | Bowling figures |

## 🔎 Data Exploration

The notebook performs:

- Dataset loading with Pandas.
- Inspection using `head()` and `info()`.
- Checking the number of rows and columns.
- Checking missing/null values.
- Analysis of categorical and numerical columns.
- Grouping and aggregation with Pandas.
- Sorting and selecting top results.
- Visualization using Seaborn and Matplotlib.

## 📊 Key Analysis

The notebook investigates questions such as:

- Which team won the most matches?
- How are match wins distributed among teams?
- How do toss decisions relate to match outcomes?
- Which players appear frequently as top scorers?
- Which players accumulate the highest batting scores?
- Which bowlers have notable bowling performances?
- How do first- and second-innings scores compare?
- What patterns can be observed from match margins and winning methods?

For example, the notebook's match-win analysis shows the following counts in the analyzed data:

- Gujarat — 12 wins
- Rajasthan — 10 wins
- Banglore — 9 wins
- Lucknow — 9 wins
- Delhi — 7 wins
- Punjab — 7 wins
- Kolkata — 6 wins
- Hyderabad — 6 wins
- Chennai — 4 wins
- Mumbai — 4 wins

## 📈 Visualizations

The project uses visualizations to make the analysis easier to interpret, including:

- Bar plots
- Horizontal bar plots
- Count plots
- Comparative categorical plots

Pandas plotting is also used where appropriate.

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas** — data loading, cleaning, grouping, aggregation and analysis
- **NumPy** — numerical operations
- **Seaborn** — statistical visualizations
- **Matplotlib** — plotting and customization

## 📁 Project Structure

```text
IPL-Capstone-Project/
│
├── IPL.csv
├── IPL_Capstone_Project.ipynb
└── README.md
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/Debajyoti8/IPL-Capstone-Project.git
```

2. Open the project folder:

```bash
cd IPL-Capstone-Project
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open:

```text
IPL_Capstone_Project.ipynb
```

5. Run the notebook cells sequentially.

## 📌 Project Type

**Exploratory Data Analysis (EDA)**

This project focuses on understanding IPL 2022 match data through data exploration, aggregation, and visualization rather than building a predictive machine-learning model.

## 👤 Author

**Debajyoti Chakraborty**

GitHub: [@Debajyoti8](https://github.com/Debajyoti8)
