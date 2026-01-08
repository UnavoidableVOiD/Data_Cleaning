# Netflix Data Analysis & Visualization

## Project Overview
This project analyzes the Netflix Movies and TV Shows dataset using Python. The goal is to perform data cleaning on a raw dataset, handle missing values, standardize data formats, and generate visualizations to understand content trends on the platform.

## Dataset
*   **Source:** [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
*   **Description:** The dataset consists of listings of all the movies and TV shows available on Netflix, along with details such as cast, directors, ratings, release year, and duration.
*   **Size:** ~8,800 rows and 12 columns.

## Technologies Used
*   **Python 3.x**
*   **Pandas:** For data manipulation, cleaning, and aggregation.
*   **Matplotlib & Seaborn:** For data visualization.

## Key Features
1.  **Data Cleaning:**
    *   Handled missing values in `Director`, `Cast`, and `Country` columns.
    *   Converted `date_added` from string format to DateTime objects.
    *   Removed null rows in critical columns like `Duration`.
2.  **Feature Engineering:**
    *   Extracted `Year` and `Month` from the added date to analyze temporal trends.
3.  **Visualization:**
    *   Comparison of Movies vs. TV Shows.
    *   Growth of Netflix content library over time.
    *   Distribution of Content Ratings (Target Audience).

## How to Run
1.  Install dependencies:
    ```bash
    pip install pandas matplotlib seaborn
    ```
2.  Ensure `netflix_titles.csv` is in the project directory.
3.  Run the analysis script or Jupyter Notebook.

## Author
Prabhat Acharya