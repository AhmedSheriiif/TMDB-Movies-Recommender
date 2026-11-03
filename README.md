# TMDB Movies Recommender

Two movie recommender systems built on the [TMDB 5000 Movies](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) dataset:

1. **Content-based recommender** — recommends movies by similarity of plot summary/overview text (and other metadata such as cast/crew from `tmdb_5000_credits.csv`).
2. **Collaborative-style similarity** — recommends based on shared properties (genres, keywords, cast) rather than just text similarity.

See `recommend_on_summary.ipynb` for the implementation, and `REPORT.docx` for the full write-up (approach, evaluation, findings).

## Data

This repo doesn't commit the raw dataset (44MB of CSVs) — download `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv` from [Kaggle: TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) and place them in the repo root to run the notebook.

## Stack

Python, pandas, scikit-learn (text vectorization + similarity), Jupyter.
