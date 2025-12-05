# Korean Drama Recommendation System 🎬

A deep learning-based recommendation system that predicts user ratings for Korean dramas and generates personalized recommendations using collaborative filtering.

## 🎯 Overview

This system predicts ratings for unwatched Korean dramas, recommends personalized content, and finds similar dramas based on user preferences and genre analysis.

**Key Features:**
- Predicts user ratings with 0.0885 test loss
- Recommends dramas based on viewing history
- Handles cold-start problem using genre preferences
- Analyzes 30+ genres across 1,400+ dramas

## 🛠️ Tech Stack

**Core:** Python, TensorFlow, Pandas, Scikit-learn  
**Scraping:** BeautifulSoup, Requests  
**Environment:** Jupyter Notebook

## 📊 Dataset

- **1,400+ Korean dramas** scraped from MyDramaList, IMDb, and KAGGLE
- **9,700+ user ratings**
- **30+ genres** (Romance, Action, Comedy, Thriller, etc.)




## 🏗️ Model

**Collaborative Filtering** with:
- User and drama embeddings
- Dot product similarity
- Genre-based feature engineering
- One-hot encoded genre vectors

## 📈 Results

- **Test Loss:** 0.0885
- Successfully generates accurate personalized recommendations
- Handles both existing users and cold-start scenarios

## 🚧 Key Challenges Solved

1. **Web scraping blocks** → Rotating user agents + delays
2. **Missing genre data** → Multi-source cross-referencing
3. **Cold-start problem** → Genre-based user profiling
4. **Sparse data** → Feature engineering with user-genre aggregation



⭐ Star this repo if you found it helpful!