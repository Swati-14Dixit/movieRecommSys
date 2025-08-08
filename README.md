🎬 Movie Recommendation System

This is a simple content-based Movie Recommendation System built using Python. It recommends similar movies based on your input using machine learning techniques.

🚀 Features
- Upload your own movie dataset (CSV format)
- Uses content-based filtering (cosine similarity)
- ⚙Built with `pandas`, `numpy`, and `scikit-learn`
- Easy to run in Google Colab — no setup needed
- Get movie recommendations by just typing a movie title

🛠️ Tech Stack
- Python 3.x
- pandas
- numpy
- scikit-learn (sklearn)

📊 Dataset
You can use any movie dataset in CSV format that includes:
- `title` column (movie titles)
- `genres`, `keywords`, `overview`, etc. (for content-based filtering)

Sample datasets:
- [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- [IMDb Dataset](https://www.kaggle.com/datasets/stefanoleone992/imdb-extensive-dataset)


💡 How It Works
1. Upload your `dataset.csv` file
2. Preprocesses the data using `pandas`
3. Extracts features and creates vectors
4. Calculates similarity scores using `cosine_similarity`
5. Enter a movie title → get top similar movie recommendations!

▶️ Try it on Google Colab

Click the badge below to open this notebook in Google Colab:

[![Open In Colab]([https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/movie-recommendation-system/blob/main/movie_recommender.ipynb](https://colab.research.google.com/drive/1nLY87RWM0Lee4U6s4Pb2Hfo5HdXie0oI#scrollTo=R2UwxMdFzr2y))


## 🧾 How to Use

1. Clone this repository or open the Colab notebook.
2. Upload your own `dataset.csv` file when prompted. (you can use any name)
3. Run the notebook cells one by one.
4. Type the movie name in the input cell and see your recommendations!

