# Assignment 1: Data Analysis & Visualization
**Siddhartha Mishra**  
Data Analysis and Visualization - CS4379G.251

This repository contains Assignment 1 for the course. It includes a Jupyter notebook that analyzes the Netflix titles dataset to investigate how the number of titles added to Netflix has changed over time, along with grouped summaries and visualizations.

---
## How to Run the Notebook
1. **Clone the repository**
   ```bash
   git clone 
   cd A1
   ```
2. **Create and activate a virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install required packages**:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

4. **Run the notebook**:
   - Open `notebooks/analysis.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
   - Run all cells from top to bottom.
   - **Note:** Start Jupyter from the project root (`A1/`) so the data path resolves correctly, or the notebook will auto-detect the path when run from the `notebooks/` folder.
---

## Dataset

The analysis uses the **Netflix titles dataset** (`data/netflix/netflix_titles.csv`), containing ~8,800 titles with columns such as type, title, date_added, release_year, rating, duration, and more.
---

## What I Found

- **Trend over time:** The number of titles added to Netflix grew steadily from 2008 to 2019, with a sharp increase from 2016 onward. The peak was around 2019–2020 (~2,000 titles), followed by a slight decline, possibly due to COVID-19 and shifts in content acquisition.

- **Content mix:** Movies outnumber TV shows (about 6,100 vs 2,700). TV-MA and TV-14 are the most common ratings for both, indicating a focus on mature and teen audiences.

- **Release years:** Most titles on Netflix were originally released in recent decades (2000s–2020s), with a right-skewed distribution. The platform has acquired many recent titles while also including some older classics.
