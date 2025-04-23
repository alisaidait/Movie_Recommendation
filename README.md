# 🎬 Movie Ratings Analysis & Recommendation System

An advanced data science project analyzing movie ratings and building recommendation systems using Python and Jupyter Notebooks.
📁 Dataset Description
This project utilizes the MovieLens 100K Dataset, a widely-used benchmark dataset in the field of recommender systems. The dataset comprises 100,000 ratings (ranging from 1 to 5) provided by 943 users for 1,682 movies. Each user has rated at least 20 movies, ensuring a robust dataset for analysis.​
The dataset includes the following files:​

movies.csv: Contains information about movies, including:

movieId: Unique identifier for each movie.

title: Title of the movie.

genres: Genres associated with the movie.​

ratings.csv: Contains user ratings for movies, including:

userId: Unique identifier for each user.

movieId: Identifier for the rated movie.

rating: Rating given by the user (on a scale of 1 to 5).

timestamp: Timestamp of when the rating was given.

## 📊 Project Overview

This project involves:

- **Data Exploration**: Loading and merging movie and rating datasets.
- **Data Cleaning**: Handling duplicates and missing values.
- **Visualization**: Exploring rating distributions and genre popularity.
- **Clustering**: Grouping movies based on genres using KMeans.
- **Recommendation Systems**:
  - Correlation-based recommendations.
  - Matrix Factorization using SVD.

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/alisaidait/Movie_Recommendation.git
   
2. **Navigate to the project directory**:
    ```bash
   cd movie-ratings-analysis
    
3. **Create a virtual environment**:
   ```bash
   python -m venv venv
   venv\\Scripts\\activate  # On MacOS/Linux source venv/bin/activate
4. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   
 


