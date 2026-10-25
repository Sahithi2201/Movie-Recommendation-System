# Movie Recommendation System

## Project Overview
A Python-based movie recommendation system that suggests movies with similar genres using text-based similarity techniques.

## Features
- Movie dataset containing titles and genres
- TF-IDF text feature extraction
- Cosine similarity calculation
- Recommendations for a selected movie
- Handles movie titles that are not found

## Technologies Used
- Python
- Pandas
- Scikit-learn

## How It Works
1. Prepare a sample movie dataset.
2. Convert genre descriptions into numerical features using TF-IDF.
3. Calculate similarity scores using cosine similarity.
4. Rank movies by similarity.
5. Display the top recommended movies.

## How to Run
Open `Movie_Recommendation_System.py` in Google Colab or another Python environment with the required libraries installed. Run the code and call:

```python
recommend_movies("The Space Journey")
```

You can replace the movie title with another title from the dataset.

## Dataset and Limitations
This project uses 15 illustrative movie entries. Recommendations are based on genre-text similarity, not real ratings or viewing history. The small sample dataset is intended for demonstration purposes.

## Future Improvements
- Integrate a larger movie dataset
- Include user ratings
- Build a web-based interface
- Explore collaborative filtering

## Author
Sahithi Kancharla
