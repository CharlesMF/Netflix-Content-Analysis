#  Netflix  Content Strategy Analysis
> **Term Project**: Analysis of content distribution and popularity prediction using Random Forest.

## Project Overview (專案簡介)
This project analyzes the content strategy of streaming platforms (Netflix) and builds a machine learning model to predict the "popularity" (IMDb Score) of a show based on its features.

**Key Goals:**
1.  **Content Distribution**: Visualize the ratio of Movies vs. TV Shows and genre trends over the years.
2.  **Popularity Prediction**: Build a **Random Forest Classifier** to predict if a show will be a "Hit" (IMDb > 7.0).
3.  **Insight Discovery**: Identify key factors (e.g., Director, Duration, Genre) that drive higher ratings.

## Technologies Used (使用技術)
This project applies concepts from the following IBM Data Science courses:
* **Python for Data Science**: Data manipulation using `Pandas` and `Numpy`.
* **Data Analysis with Python**: Data cleaning, merging datasets, and feature engineering (One-Hot Encoding).
* **Data Visualization with Python**: Interactive charts using `Plotly` and static plots with `Seaborn/Matplotlib`.
* **Machine Learning with Scikit-Learn**: Building `Random Forest` models, `Confusion Matrix`, and `Feature Importance` analysis.

## Key Insights & Visualizations (分析成果)


* **Feature Importance**: We found that **Duration** and **Director** have a higher impact on popularity than Genre alone.
* **Content DNA**: High-rated shows tend to cluster around specific genres like *Documentaries* and *History*, while generic *Action* movies have lower average scores.

## How to Run (如何執行)
1.  Clone this repository.
2.  Install required packages:
    ```bash
    pip install -r requirements.txt
    ```
3.  Open `Netflix_Popularity_Analysis.ipynb` in Jupyter Notebook or Google Colab.
4.  Ensure `netflix_titles.csv` and the IMDb dataset are in the same directory.

## Dataset
* **Netflix Movies and TV Shows**: [Kaggle Link](https://www.kaggle.com/datasets/shivamb/netflix-shows)
* **IMDb Scores**: [Kaggle Link](https://www.kaggle.com/datasets/thedevastator/netflix-imdb-scores)

