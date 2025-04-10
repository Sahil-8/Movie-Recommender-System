# 🎬 Movie Recommender System

This project is a **content-based movie recommender system** built with Python. It suggests movies similar to a selected title using cosine similarity and preprocessed data.

## 📁 Project Structure

```
movies-recommender-system/
├── README.md               # Project documentation
├── app.py                  # Streamlit or Flask app to run the recommender system
├── movie_dict.pkl          # Pickled dictionary containing movie data
├── movie_list.pkl          # Pickled list of movies used in the app
├── project.ipynb           # Notebook for model building and analysis
├── Movie recommender.ipynb # Final version or UI integration notebook
```

## 🚀 Features

- Recommend similar movies based on a selected title.
- Web interface using Streamlit or Flask (via `app.py`).
- Lightweight and easy to run locally.
- Uses precomputed similarity for fast results.

## 🛠️ Requirements

Make sure you have Python installed, then install the required packages:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available, you can manually install:

```bash
pip install pandas numpy scikit-learn streamlit
```

## ▶️ How to Run

### Option 1: Run the Web App (Streamlit)

```bash
streamlit run app.py
```

### Option 2: Explore in Jupyter

Open `project.ipynb` or `Movie recommender.ipynb` in Jupyter Notebook to understand the logic and play with the data manually.

```bash
jupyter notebook
```

## 🧠 How It Works

- The system uses a content-based filtering method.
- It relies on text features (e.g., genres, tags, overview) to compute cosine similarity between movies.
- `movie_dict.pkl` and `movie_list.pkl` are used to quickly fetch movie info and recommendations.

## 📦 Data Files

- `movie_dict.pkl`: Dictionary of all movies with metadata used in recommendation logic.
- `movie_list.pkl`: Cleaned and indexed list of movies used for UI dropdowns and selection.

## ✍️ Author
Sahil Samal
Sahil-8
sahilsamal91@gmail.com
