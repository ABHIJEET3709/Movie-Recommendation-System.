Overview

This project performs exploratory data analysis on a movie ratings dataset to extract insights relevant to recommendation systems. By combining user ratings with movie metadata, it highlights highly rated and widely rated movies, providing a foundation for building recommendation models.

Tech Stack

Python

Pandas

Matplotlib

Seaborn

Data

movies.csv: Movie titles and genres

ratings.csv: User ratings and timestamps

Approach

Data loading and validation

Dataset merging using movie identifiers

Aggregation of ratings to measure:

Total rating score per movie

Rating frequency per movie

Visualization of top movies based on these metrics

Results

Identified top-rated movies based on cumulative user ratings

Identified most popular movies based on number of ratings

Visualized trends to support recommendation insights

Usage

Run the Jupyter Notebook to reproduce the analysis and visualizations.

Notes

This project focuses on data exploration and insight generation. It can be extended with collaborative or content-based filtering techniques to build a full recommendation system.

Pro-Coder One-Line Summary (Optional)

Exploratory analysis of movie ratings data to derive insights for recommendation system development.
