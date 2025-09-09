# Webscraping project – with data cleaning and visualization

This personal project is made to learn how football data can be scraped from the web and prepared for analysis. I scraped **Fenerbahçe / Süper Lig** data from Wikipedia, cleaned the tables with **pandas**, and visualized the results in **Tableau**.

**Tools:** Python (requests, pandas, lxml) + Jupyter Notebook · Tableau Public  
**Output CSVs:** `data/processed/superlig_standings_clean.csv` (league) and `data/processed/fenerbahce_players_clean.csv` (players, if available)

The following three images are respectively:

1) **A bar chart of points by team** (from the cleaned league table).  
2) **A sub-dataset preview** (cleaned columns after pandas wrangling).  
3) **An interactive dashboard** (Tableau) showing the same data with filters.

![Points by Team](imagefolder/pts_by_team.png)
![Cleaned subset](imagefolder/superlig_standings_clean_head.png)
![Interactive dashboard](gifs/dashboard.gif)

_Reproduce:_ run the notebook(s) in `Webscraping project/` (or `notebooks/`) to scrape and clean, which will save the CSVs in `data/processed/`. Then open the CSVs in Tableau to build the visuals.
