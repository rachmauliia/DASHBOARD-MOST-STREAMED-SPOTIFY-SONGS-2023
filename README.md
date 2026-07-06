# DASHBOARD-MOST-STREAMED-SPOTIFY-SONGS-202

## Overview

This project presents an interactive dashboard analyzing the most-streamed songs on Spotify based on the 2023 dataset. The dashboard was developed using Microsoft Excel to transform raw data into meaningful visual insights through data cleaning, Excel formulas, Pivot Tables, and charts.

The objective of this project is to demonstrate data analysis and dashboard development skills using Excel while providing insights into streaming trends, artists, release years, and song characteristics.

---

## Dashboard Preview

> *(Upload a screenshot of your dashboard inside the `images` folder and replace the filename below.)*

```markdown
![Dashboard Preview](images/dashboard.png)
```

---

## Tools Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Excel Formulas
- Data Cleaning
- Data Visualization

---

## Project Structure

```
Spotify-Streaming-Dashboard/
│
├── Dashboard_Spotify_Paling_Banyak_Distreaming_2023.xlsx
├── README.md
│
└── images/
    └── dashboard.png
```

---

## Dashboard Features

The dashboard provides several key insights, including:

- Top 10 Most Streamed Songs
- Top 10 Artists by Total Streams
- Songs Distribution by Release Year
- Major vs Minor Mode Distribution
- Average Streams by Mood Category (Valence)
- KPI Cards
  - Total Songs
  - Total Streams
  - Average Streams
  - Top Artist

---

## Data Cleaning Process

Before creating the dashboard, the dataset underwent several preprocessing steps:

- Removed corrupted records.
- Removed duplicate song–artist combinations.
- Converted numeric values stored as text.
- Standardized text formatting using `TRIM()`.
- Handled missing values by assigning **"Unknown"** labels.
- Verified numeric data types for accurate analysis.

Final cleaned dataset contains **948 records**.

---

## Excel Functions Used

Some of the formulas used include:

- `TRIM()`
- `LEFT()`
- `FIND()`
- `IF()`
- `ISBLANK()`
- `SUBSTITUTE()`
- `VALUE()`
- `RANK.EQ()`
- `COUNTIF()`
- `SUMIFS()`
- `COUNTIFS()`
- `AVERAGEIFS()`
- `INDEX()`
- `MATCH()`

---

## Visualization

The dashboard includes various chart types selected according to the nature of the data:

| Visualization | Purpose |
|---------------|---------|
| Horizontal Bar Chart | Top 10 Most Streamed Songs |
| Column Chart | Top 10 Artists |
| Column Chart | Songs by Release Year |
| Donut Chart | Major vs Minor Mode |
| Column Chart | Average Streams by Mood Category |

---

## Key Insights

- Identify the most-streamed songs in Spotify's 2023 dataset.
- Compare artist popularity based on total streams.
- Analyze music release trends across different years.
- Observe the distribution of musical modes (Major vs Minor).
- Explore the relationship between song mood (Valence) and streaming performance.

---

## Dataset

The dataset contains Spotify song information including:

- Track Name
- Artist
- Streams
- Release Year
- Danceability
- Valence
- Musical Key
- Playlists
- Charts
- Mode

---

## Skills Demonstrated

- Data Cleaning
- Data Transformation
- Dashboard Design
- Data Visualization
- Pivot Table Analysis
- Excel Formula Development
- Business Insight Presentation

---

## Author

**Rachma Nur Aulia Fitri**

Feel free to connect or provide feedback on this project!
