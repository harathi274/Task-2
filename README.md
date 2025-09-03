# Movie Ratings Data Analysis

## Overview

This project analyzes a sample dataset of movie ratings using Python (Pandas, NumPy, Matplotlib, Seaborn) in a Jupyter Notebook. The goal is to demonstrate a standard workflow for:
- Cleaning and preprocessing raw ratings data
- Calculating summary statistics (mean, median, mode)
- Visualizing the distribution of ratings (histogram, box plot)
- Identifying top-rated movies and genres
- Displaying results in a simple dashboard

## Technologies Used

- Python (3.7+)
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn

## Dataset

A simulated dataset of 100 movies is generated in the notebook, featuring:
- `movieId`: Unique integer identifier for each movie
- `title`: Movie name
- `genre`: Selected from ['Action', 'Comedy', 'Drama', 'Thriller', 'Romance', 'Horror', 'Sci-Fi', 'Fantasy']
- `rating`: Random float between 1.0 and 5.0
- `userId`: Random integer between 1 and 30

You may replace this with your own ratings dataset for new analysis.

## Project Structure

```
├── README.md      # This file
├── movie_analysis.ipynb  # Jupyter notebook with full code & output
├── data/          # Optional: Place for external data files (if any)
```

## Getting Started

1. **Clone or download the repository**
2. Open the Jupyter notebook (`movie_analysis.ipynb`)
3. Run all cells. The notebook creates its own sample data, performs cleaning, calculates statistics, and outputs relevant plots.

### Installation

Make sure you have the following libraries installed:
```bash
pip install pandas numpy matplotlib seaborn
```

### Usage

Open the notebook and execute all cells. For a new dataset, replace the data generation cell with your own CSV import.

## Workflow & Methodology

1. **Data Creation/Import**: Create or load movie ratings data.
2. **Cleaning**: Remove duplicates, handle missing values, set correct data types.
3. **Statistics**: Calculate mean, median, and mode of ratings.
4. **Visualization**: Generate histogram (with KDE) and box plot of ratings.
5. **Top Insights**: Find top 10 movies by rating, and top genres by average rating.
6. **Dashboard**: Present findings using visualizations and summary tables.

## Results

- Displayed plots for distribution of ratings.
- Table of Top 10 rated movies.
- Bar chart for average rating per genre.
- Printed summary statistics (mean, median, mode).

All results are visible in the notebook output. Example images and tables are automatically created.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for bug fixes, enhancements, or new features.

## Acknowledgements

- Inspired by standard data science documentation practices.
- Libraries: Pandas, NumPy, Matplotlib, Seaborn

