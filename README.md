# IS6335 Movie Visualization Project

A non-commercial academic project for IS6335 (Data Visualization) at City University of Hong Kong.

## Project overview

This project explores what drives movie success, using movie-level financial, audience, release, and cast/crew data. The analysis covers the relationships between budget, revenue, ratings, and popularity, as well as differences across genres, countries, release periods, and production companies.

## Data source

- **Dataset**: TMDB 5000 Movie Dataset
- **Original source**: The Movie Database (TMDb), a community-built movie and TV database. This product uses the TMDb API but is not endorsed or certified by TMDb.
- **Published on**: Kaggle, https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

The raw data files are not included in this repository. Please download them from the Kaggle link above.

## Data limitations

- Ratings and other attributes are entered by TMDb users and may not be consistent across titles.
- Budget and revenue values are not officially confirmed as USD or global revenue. Zero values are treated as missing.
- Popularity is a TMDb-specific activity score, not a box-office measure.

## Tools

- R (ggplot2, dplyr, sf, plotly) and Python (pandas, scikit-learn) for data processing and analysis
- Tableau for interactive dashboards

## Repository contents

- `README.md`: project description and data source documentation
- Analysis scripts (to be added)

No API keys, credentials, or personal information are stored in this repository.

## License and use

This repository is for academic coursework only. The data remains subject to the terms of TMDb and Kaggle.
