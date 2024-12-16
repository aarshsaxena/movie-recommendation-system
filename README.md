# Movie Recommendation System

A web application that provides movie recommendations using Natural Language Processing (NLP) techniques and cosine similarity. Built with Python and Streamlit, this project delivers a seamless and user-friendly interface for exploring movies based on user preferences.

## Features

- **Content-Based Filtering:** Recommends movies based on similarity of titles and descriptions.
- **Cosine Similarity:** Measures the similarity between movie descriptions for accurate recommendations.
- **Interactive Interface:** A responsive UI built with Streamlit for easy interaction.
- **Search Functionality:** Users can search for any movie title to get personalized recommendations.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/aarshsaxena/movie-recommendation-system.git
   cd movie-recommendation-system
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   streamlit run app.py
   ```
