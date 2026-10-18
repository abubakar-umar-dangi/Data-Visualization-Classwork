# Data Visualization Exercises

Weekly data visualization exercises from my MSc Data Science course: Jupyter notebooks (weeks 2–8) and two Streamlit dashboards (weeks 9–10), built with Python, Pandas and Plotly.

## Highlights

- Seven datasets covering flowers, financial time series, wine chemistry, restaurant bills, global development, car-share demand and African economic geography (with a GeoJSON map).
- Every exercise is built around one clear visualization question.
- Consistent chart design, with informative titles and meaningful labels.
- Two interactive Streamlit dashboards.
- A single `requirements.txt` for reproducibility.

## Structure

`week02`–`week08` contain Jupyter exercises.  
`week09` and `week10` contain Streamlit dashboards.  
`data/` contains the new datasets and the map GeoJSON.

## Run

```bash
pip install -r requirements.txt
jupyter notebook
```

For dashboards:

```bash
streamlit run week09/app.py
streamlit run week10/app.py
```

## Dataset notes

- Iris, Stocks, Tips, Carshare and Gapminder are distributed through Plotly Express example datasets.
- Wine chemistry comes from scikit-learn's built-in wine recognition dataset.
- African indicators are extracted from the included Natural Earth GeoJSON attributes so the map join is reproducible.
