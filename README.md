# IPL Statistics Dashboard

Interactive dashboard analyzing IPL cricket statistics (2008–2024) built with Python, Pandas and Plotly.

## Features
- Runs per match (time series)
- Top 10 run scorers
- Top 10 wicket takers
- Team win percentages
- Filters for **season** and **team**

## Data Source
- **Dataset:** <IPL Complete Dataset (2008-2024)> (Kaggle)
- **URL:** <https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020>
- **Files used:** `matches.csv`, `deliveries.csv`
- **Extraction date:** 13 October 2026

## How to Run
1. Download the dataset from the link above and place the CSV files next to the notebook
   (or update the paths in the notebook).
2. Install requirements:
   `pip install pandas plotly ipywidgets kaleido`
3. Open `ipl_dashboard.ipynb` in Jupyter and run all cells.
   The season/team dropdowns appear at the bottom of the notebook.

## Charts
See the `charts/` folder for PNG exports of each visual.

## Insights
See [insights.md](insights.md).

## Notes
- Team names were standardized (e.g., Delhi Daredevils → Delhi Capitals).
- Matches without a result were excluded from win-percentage calculations.
- Interactive widgets work in Jupyter only (not rendered on GitHub).
