# Movie_Recommendation_System

## Overview
This project is a **Movie Recommender System** built using **Python** and **Streamlit**. It recommends movies based on content similarity by leveraging data from **The Movie Database (TMDb)**. The system employs a **cosine similarity algorithm** to suggest movies similar to a user-selected movie and displays their titles and posters.

## Features
- **Movie Selection**: Users can select a movie from a dropdown list.
- **Recommendations**: Displays up to 5 recommended movies with their posters.
- **Error Handling**: Handles cases where movie posters are unavailable or the server is busy.
- **Interactive UI**: Built with **Streamlit** for a user-friendly web experience.
- **External API Integration**: Fetches movie posters from the **TMDb API**.

## Prerequisites
To run this project, ensure you have the following:
1. **Python 3.8+** installed.
2. Required Python libraries (listed in `requirements.txt`):
   - `pandas`
   - `streamlit`
   - `requests`
   - `scikit-learn`
3. **TMDb API key** (Replace the demo key in the code with your own for production).
4. Precomputed data files:
   - `movie_list.pkl`: Contains the movie dataset.
   - `similarity.pkl`: Contains the precomputed similarity matrix.

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Parth8155/Movie_Recommendation_System.git
   cd Movie_Recommendation_System

   Movie_Recommendation_System/

## DataSet Link 
[TMDb Movie Metadata Dataset on Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## file structure  
   ```bash
├── app2.py                       # Main application script for Streamlit
├── movie-recommender-system.ipynb # Jupyter notebook for data preprocessing
├── movie_list.pkl                # Processed movie dataset (Pickle file)
├── similarity.pkl                # Cosine similarity matrix (Pickle file)
├── README.md                     # Project documentation
