# ⚽ Football Match Analysis using StatsBomb Data

## Overview

This project analyzes a football match between **FC Barcelona and Real Madrid** using event-level data from the **StatsBomb Open Dataset**. The goal is to explore different aspects of match performance through data analysis and visualization.

Using Python and football analytics libraries, the project investigates attacking, passing, defensive, and goalkeeping performance during the match.

---

## Objectives

The analysis focuses on several key areas:

* Shot creation and goal probability
* Passing patterns and ball progression
* Player positional activity (heatmaps)
* Defensive actions and pressing behavior
* Goalkeeper performance

These analyses help demonstrate how event-level football data can be used to understand tactical and statistical aspects of a match.

---

## Technologies Used

* **Python**
* **statsbombpy** – accessing StatsBomb event data
* **pandas** – data manipulation
* **matplotlib** – data visualization
* **mplsoccer** – football pitch visualizations

---

## Project Structure

```
match-analysis.ipynb
README.md
```

The main analysis is contained in a Jupyter Notebook which includes:

1. Data loading and preprocessing
2. Shot analysis
3. Passing analysis
4. Player heatmaps
5. Defensive analysis
6. Pressing intensity (PPDA)
7. Goalkeeper analysis

---

## Analysis Performed

### Shot Analysis

* Shot outcome distribution
* Goal probability calculation
* Shot maps showing spatial shot locations

### Passing Analysis

* Pass completion rate
* Forward pass detection
* Player pass maps

### Player Activity

* Heatmaps illustrating where players were most active on the pitch

### Defensive Analysis

* Defensive event counts
* Defensive action locations
* Pressing intensity using **PPDA (Passes Per Defensive Action)**

### Goalkeeper Analysis

* Save counts
* Goals conceded

---

## Key Visualizations

The project includes several football analytics visualizations such as:

* Shot maps
* Player pass maps
* Activity heatmaps
* Defensive action maps
* Bar charts comparing team statistics

These visuals help highlight tactical patterns and team performance.

---

## Key Insights

Some observations from the analysis include:

* Differences in attacking efficiency between the teams
* Distinct passing patterns and ball progression styles
* Areas of high defensive activity during the match
* Variation in pressing intensity between the teams

These insights demonstrate how data can reveal tactical behavior during a match.

---

## Future Improvements

Potential extensions to the project include:

* Passing network visualizations
* Expected Goals (xG) analysis
* Player performance comparison across multiple matches
* Interactive dashboards for match analytics

---

## Data Source

StatsBomb Open Data
https://github.com/statsbomb/open-data

---

## Author

Mayank Kumar Singh
