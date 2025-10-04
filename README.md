

-----

# Movie Recommendation System

A content-based movie recommendation system that suggests movies to users based on their similarity to a movie they have already watched. This project uses machine learning techniques to analyze movie data and provide personalized recommendations.

## Project Description

This project aims to build a recommendation system that can suggest movies to users based on their preferences. The recommendation engine is built using a content-based filtering approach, where the similarity between movies is calculated based on their genres, keywords, cast, and crew. The system takes a movie title as input and outputs a list of similar movies. The project includes a Jupyter Notebook for the model development process and a web application to showcase the recommendation system in action.

## Key Features

  * **Content-Based Filtering:** Recommends movies based on the similarity of their content (genres, keywords, cast, crew).
  * **Vector Space Model:** Uses the count vectorizer technique to convert text data into a vector space model.
  * **Cosine Similarity:** Calculates the similarity between movies using the cosine similarity metric.
  * **Interactive Web Interface:** A user-friendly web application built with Streamlit/Flask to provide movie recommendations.
  * **Scalable and Efficient:** The recommendation algorithm is optimized for performance and can handle a large dataset of movies.

## Technologies and Tools

  * **Programming Language:** Python
  * **Libraries:**
      * **Pandas:** For data manipulation and analysis.
      * **NumPy:** For numerical operations.
      * **Scikit-learn:** For implementing the Count Vectorizer and Cosine Similarity.
      * **Streamlit / Flask:** For creating the web application.
      * **Jupyter Notebook:** For model development and experimentation.

## Installation and Setup

To run this project locally, please follow these steps:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/harsh-07-byte/Movie-Recommendation-System.git
    cd Movie-Recommendation-System
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Run the web application:**

    ```bash
    streamlit run app.py  # Or `python app.py` if you are using Flask
    ```

2.  **Open your web browser and navigate to the local URL provided by Streamlit/Flask.**

3.  **Enter a movie title in the input field and get a list of recommended movies.**

## Dataset

The dataset used in this project is the "TMDB 5000 Movie Dataset" from Kaggle, which contains information about 5000 movies, including their genres, keywords, cast, and crew.

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
