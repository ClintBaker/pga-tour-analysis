# PGA Tour Tournament Performance Analysis

Portfolio data analysis project exploring which strokes gained metrics are most associated with strong PGA Tour tournament outcomes.

## Project Overview

This notebook analyzes PGA Tour tournament-level player performance data to answer two core questions:

- Which strokes gained components are most strongly associated with better finishing position?
- What statistical differences exist between Top 10 finishes and non-Top 10 finishes?

The workflow includes data verification, cleaning, exploratory analysis, correlation analysis, and simple regression-based modeling.

## Quick View

- Open the rendered notebook on GitHub Pages: [PGA Tour Analysis (Live)](https://clintbaker.github.io/pga-tour-analysis/pga_tour_analysis.html)
- Local HTML file (in this repo): [`pga_tour_analysis.html`](./pga_tour_analysis.html)

## Key Findings

- `sg_app` (strokes gained on approach) shows the strongest relationship with improved finishing position.
- Top 10 finishers gain more strokes across all major categories than non-Top 10 players.
- Approach performance has strong practical impact: players in the highest approach tier are far more likely to finish Top 10 than players in the lowest tier.

## Dataset

- **Source:** [PGA Tour Golf Data (2015-2022) on Kaggle](https://www.kaggle.com/datasets/robikscube/pga-tour-golf-data-20152022)
- **Author:** Rob Mulla
- **Local file used in this repo:** `pga_raw_data.csv`

## Tech Stack

- Python
- pandas
- NumPy
- matplotlib
- SciPy (`linregress`)
- Jupyter Notebook

## Repository Structure

- `pga_analysis.ipynb` - main analysis notebook
- `pga_tour_analysis.html` - rendered notebook for quick browser viewing
- `pga_raw_data.csv` - local dataset used for the analysis
- `requirements.txt` - Python dependencies

## How To Run

1. Clone this repository.
2. Create and activate a virtual environment.
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter:

   ```bash
   jupyter notebook
   ```

5. Open and run `pga_analysis.ipynb`.

## Notes

- The notebook expects `pga_raw_data.csv` to be in the project root.
- Results are reproducible from the provided notebook workflow.

## Author

Clinton Baker
