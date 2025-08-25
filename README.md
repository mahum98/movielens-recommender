# Movie Recommendation System

## Overview
This project implements a movie recommendation system using the MovieLens 100K dataset. I built a system that recommends movies based on user similarity, evaluated its performance with precision and recall, and added bonus features like item-based collaborative filtering and matrix factorization (SVD).

## Features
- **User-Based Collaborative Filtering**: Recommends movies based on similarity between users.
- **Item-Based Collaborative Filtering**: Suggests movies based on similarity between items.
- **Matrix Factorization (SVD)**: Uses latent factors to enhance recommendations.
- **Evaluation Metrics**: Calculates precision@K and recall@K for performance assessment.

## Requirements
- Python 3.12+
- Libraries:
    `pandas`, `numpy`, `scikit-learn`
- Dataset: MovieLens 100K (download from the link below)

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd movie-recommendation-system
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn
   ```
3. Download the MovieLens 100K dataset from [https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset) and extract the `ml-100k` folder containing `u.data` and `u.item` into the project directory.

## Usage
1. Run the Jupyter Notebook `movie_recommendation.ipynb`:
   ```bash
   jupyter notebook movie_recommendation.ipynb
   ```
2. Execute cells in order to load data, build the model, and generate recommendations.
3. Check the output of the evaluation and bonus methods (user-based, item-based, SVD).

## File Structure
- `movie_recommendation.ipynb`: Main notebook with code and descriptions.
- `ml-100k/`: Directory for the MovieLens 100K dataset files (`u.data`, `u.item`) after download.
- `README.md`: This file.

## Results
  **Evaluation**: Mean Precision@5 and Recall@5 are computed for a subset of users.
  **Recommendations**: Sample outputs from user-based, item-based, and SVD methods are printed for user_id=1.
