# Lichess_data_Analysis


An exploratory data analysis of over **20,000 Lichess games**, answering two key chess questions:
1. **Does White really have an advantage?**
2. **What are the best openings for White and Black?**

## Key Findings

- **White wins ~55%** of the time, Black wins ~40%, and draws account for ~5% — confirming the well-known first-move advantage.
- **Top openings for White** (by win count): Scandinavian Defense: Mieses-Kotroc Variation, Sicilian Defense, Scotch Game, and others.
- **Top openings for Black** (by win count): Van't Kruijs Opening, Sicilian Defense, Sicilian Defense: Bowdler Attack, and others.

## Dataset

- **Source:** [Lichess Games Dataset on Kaggle](https://www.kaggle.com/datasnaek/chess)
- **Size:** 20,058 games
- **Columns include:** player ratings, openings (name + ECO code), winner, victory status, number of turns, and move sequences.

## Tools Used

- Python 3
- Jupyter Notebook
- `pandas` — data loading and analysis
- `matplotlib` — visualizations (bar charts, pie charts)

## How to Run

1. Clone the repo or download the notebook
2. Install dependencies:
