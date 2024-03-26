# Movie Recommendation System

This project implements a Movie Recommendation System using Python and Streamlit. It utilizes collaborative filtering to suggest movies based on user preferences.

## Features

- **Collaborative Filtering:** Recommends movies by analyzing similarities between user-selected movies and others in the dataset.
- **Real-time Recommendations:** Offers suggestions in real-time upon user interaction.
- **User-friendly Interface:** Simple dropdown menu and button interface for easy navigation.
- **Data-driven:** Leverages a pre-trained model and dataset containing movie information.

## How to Use

1. **Clone the repository:** `git clone https://github.com/your_username/movie-recommendation-system.git`
2. **Install dependencies:** `pip install -r requirements.txt`
3. **Run the Streamlit app:** `streamlit run app.py`
4. **Select a movie:** Choose a movie from the dropdown menu.
5. **Get recommendations:** Click the "Recommend" button to view movie suggestions.

## File Structure

- `app.py`: Main Python script implementing the Streamlit application.
- `movie_dict.pkl`: Pickled file containing movie data.
- `similarity.pkl`: Pickled file containing similarity scores between movies.
- `requirements.txt`: File listing required Python dependencies.

## Dependencies

- Python 3.x
- Streamlit
- pandas

**Note:** Ensure that you have Python and the required dependencies installed on your system before running the application.

## Author

[Your Name](https://github.com/your_username)

## Acknowledgements

This project is inspired by the tutorials and guides available online for building recommendation systems using Python and Streamlit. Special thanks to the open-source community for their contributions.
