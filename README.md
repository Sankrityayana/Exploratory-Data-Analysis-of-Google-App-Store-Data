# Exploratory Data Analysis of Google App Store Data

This repository contains an exploratory data analysis (EDA) project focused on the Google Play Store dataset. The analysis provides insights into app characteristics, user ratings, installs, and other attributes available in the Google Play Store.

## Contents

- `EDA_of_Google_App_Store_Data.ipynb` — Main Jupyter Notebook containing all code, analysis, and visualizations.
- `googleplaystore.csv` — Main dataset with app information.
- `googleplaystore_user_reviews.csv` — Dataset containing user reviews.
- `license.txt` — License details for this repository.

## Overview

The project aims to:

- Perform data cleaning and preprocessing.
- Analyze distributions of app categories, ratings, reviews, installs, and other features.
- Visualize key relationships (e.g., between reviews and ratings, installs across categories, price vs. rating, etc.).
- Conduct statistical tests to explore hypotheses (e.g., whether free and paid apps differ in ratings).
- Summarize findings with clear visualizations and interpretations.

## How to Use

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Sankrityayana/Exploratory-Data-Analysis-of-Google-App-Store-Data.git
    cd Exploratory-Data-Analysis-of-Google-App-Store-Data
    ```

2. **Open the Jupyter Notebook:**
    - Ensure you have Python (3.x) and Jupyter installed.
    - Launch the notebook:
        ```bash
        jupyter notebook EDA_of_Google_App_Store_Data.ipynb
        ```

3. **Explore the Analysis:**
    - The notebook is organized in logical sections: data loading, cleaning, visualization, and statistical testing.
    - All major plots and results can be viewed interactively.

## Main Libraries Used

- `pandas` — data manipulation and analysis
- `numpy` — numerical operations
- `matplotlib` & `seaborn` — data visualization
- `scipy.stats` — statistical tests

## Example Insights

- Distribution of app categories and their popularity.
- Relationship between the number of reviews and app ratings.
- Comparison of installs across categories.
- Statistical significance of rating differences between free and paid apps.
- Trends in ratings over time.

## Data Sources

- [googleplaystore.csv](googleplaystore.csv): Contains information about thousands of Google Play Store apps.
- [googleplaystore_user_reviews.csv](googleplaystore_user_reviews.csv): User reviews and sentiment for the listed apps.

## License

Please see [license.txt](license.txt) for details.

## Author

- Sankrityayana

---

Feel free to open issues or submit pull requests if you want to contribute or have suggestions!
