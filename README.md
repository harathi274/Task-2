## Workflow Description

This project analyzes a simulated movie ratings dataset using Python within a Jupyter Notebook environment. The key workflow steps are:

### 1. Import Libraries
Essential libraries (`pandas`, `numpy`, `random`, `matplotlib`, `seaborn`) are imported for data manipulation, statistical analysis, and visualization.  
*Purpose:* Enables seamless data engineering and plotting.

### 2. Generate Sample Dataset
A synthetic dataset of 100 movies is programmatically created, assigning random genres, ratings (1–5), and user IDs for each movie.  
*Purpose:* Provides a realistic testing ground for the analysis workflow.

### 3. Data Cleaning & Preprocessing
- Removes duplicate and missing records.
- Sets genre as a categorical variable for efficient analysis.  
*Purpose:* Ensures data integrity and analytical accuracy.

### 4. Calculate Summary Statistics
- Computes the **mean**, **median**, and **mode** of all movie ratings.  
*Purpose:* Provides a quick statistical overview of rating trends.

### 5. Visualize Rating Distribution
- Plots a histogram with a KDE overlay to show frequency and density of ratings.
- Displays a boxplot to highlight median, interquartile range, and outliers.  
*Purpose:* Offers visual insights into how movie ratings are distributed.

### 6. Identify Top-Rated Movies
- Extracts the top 10 movies based on highest ratings.  
*Purpose:* Highlights standout titles in the dataset.

### 7. Identify Top Genres
- Calculates average rating per genre and sorts them in descending order.
- Bar chart visualizes genre performance.  
*Purpose:* Reveals genre popularity and audience preferences.

### 8. Print Summary Statistics
- Clearly prints the calculated mean, median, and mode for reference.

### 9. Display Sample Data
- Shows the first 10 rows of the dataset for a quick glance at movie records.
