# Movie-Recommendation-System
A Python-based recommendation engine that leverages the TMDB API to provide personalized movie suggestions based on user interests.
## Overview
This project is an end-to-end data pipeline that automates movie data collection, performs rigorous cleaning, and implements a search-based recommendation system. It’s designed to help users discover films based on genres, ratings, and plot descriptions.

## Key Features
* **Dynamic Data Fetching:** Integrated with **TMDB API** to collect metadata for over 1,800 movies.
* **Automated ETL Pipeline:** Full data lifecycle from raw JSON extraction to structured CSV storage using **Pandas**.
* **Data Preprocessing:** Implemented feature scaling with `StandardScaler` and handled missing values/duplicates to ensure high-quality recommendations.
* **Content-Based Filtering:** Developed a custom recommendation engine that processes user queries (titles, years, or keywords) to deliver relevant results.
## Tech Stack
* **Core:** Python
* **Data Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (Preprocessing)
* **API:** Requests (REST API Integration)
* **Visualization:** Matplotlib, Seaborn
##  Project Structure
* `project_movie.ipynb`: The main Jupyter Notebook containing the source code.
* `movies_data_with_genres.csv`: The dataset generated through the API.
