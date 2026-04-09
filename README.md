# Entertainment-Media-Project

A comprehensive data science project for movie analysis, recommendation system, and sentiment analysis.

## Project Overview

This project involves data preprocessing, exploratory data analysis (EDA), and machine learning models to:
- Analyze movie data from TMDB and other sources
- Build a movie recommender system
- Predict movie popularity
- Perform sentiment analysis on movie-related content

## Project Structure

```
├── App/                          # Streamlit applications
│   └── streamlit_app.py         # Main Streamlit application
├── Data/                        # Dataset directory
│   ├── Raw/                     # Original datasets
│   │   ├── movies.csv
│   │   ├── ratings.csv
│   │   ├── tmdb_5000_credits.csv
│   │   └── tmdb_5000_movies.csv
│   └── Processed/               # Cleaned and processed data
│       ├── movies_clean.csv
│       ├── ratings_clean.csv
│       ├── movie_data_merged.csv
│       └── movie_data_filtered.csv
├── Models/                      # Trained models (pickle files)
│   ├── recommender_model.pkl
│   ├── popularity_model_tmdb.pkl
│   └── sentiment_model.pkl
├── Notebook/                    # Jupyter notebooks
│   ├── Data_Preprocessing.ipynb
│   └── EDA.ipynb
├── Src/                         # Source code
│   ├── Data_Preprocessing.py
│   ├── train_popularity.py
│   ├── train_recommender.py
│   └── train_sentiment.py
└── requirements.txt             # Project dependencies
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Devvvv15/Entertainment-Media-Project.git
cd Entertainment-Media-Project
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Run the Streamlit App
```bash
streamlit run App/streamlit_app.py
```

### Data Preprocessing
```bash
python Src/Data_Preprocessing.py
```

### Train Models
```bash
python Src/train_recommender.py
python Src/train_popularity.py
python Src/train_sentiment.py
```

## Key Features

- **Data Preprocessing**: Clean and merge multiple data sources
- **Exploratory Data Analysis**: Visualize and analyze movie trends
- **Recommender System**: Content-based movie recommendations
- **Popularity Prediction**: ML model to predict movie popularity
- **Sentiment Analysis**: Analyze sentiment from movie-related text

## Technologies Used

- Python 3.x
- Streamlit
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Pickle (model serialization)

## Author

Devvvv15

## License

This project is open source and available under the MIT License.
