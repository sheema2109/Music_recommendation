🎵 LyricWave – Content-Based Music Recommendation System

Welcome to LyricWave, a powerful content-based music recommendation system that analyzes song lyrics to recommend similar songs. Whether you're looking to explore new music or build a lyrics-driven playlist, LyricWave helps you discover songs based on their **semantic similarity**.

 🌟 Key Features

- 🔍 Content-Based Recommendation using TF-IDF and Cosine Similarity
- 🎨 **User-Friendly GUI** built with Tkinter (Light/Dark mode)
- 📊 **Pie Chart Visualization** of lyrical similarity scores
- 📁 **Export Recommendations** to `.txt` playlists
- 📚 Supports over 3000 songs from real-world data

 📁 Dataset Information

The dataset used in this project is `songdata.csv` and contains:

| Column   | Description                        |
|----------|------------------------------------|
| `song`   | Name of the song                   |
| `artist` | Artist who performed the song      |
| `text`   | Full lyrics of the song            |
| `link`   | URL to the original lyrics source *(removed)* |

 The project samples 3000 random records from the dataset to improve performance.

⚙️ How It Works

1. Text Preprocessing
- Removes newline characters from lyrics
- Applies TF-IDF vectorization with English stop words removed

 2. Similarity Matrix
- Uses Cosine Similarity to compute a matrix of pairwise song similarity
- Stores the top 50 similar songs for each track in a dictionary

 3. Tkinter GUI
- Song selection dropdown
- “✨ Recommend” button shows top 5 similar songs with scores & lyrics preview
- “📊 Pie Chart” is displayed for visual comparison
- “🌓 Theme Toggle” for dark/light mode
- “💾 Export” to save recommendations as `.txt`


 




