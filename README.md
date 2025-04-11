# 🎵 Creating Cohorts of Songs using Clustering (Spotify - Rolling Stones)

This project applies **unsupervised machine learning (clustering)** techniques to create **cohorts of songs** based on their audio features from Spotify's API. By identifying patterns in musical attributes like energy, danceability, valence, and more, the project groups songs into meaningful clusters that can be used for recommendation systems.

---

## 📁 Project Structure

📦 spotify-song-clustering/ │ ├── 📊 EDA_and_Clustering.ipynb # Jupyter notebook with complete code and analysis ├── 📁 spotify_data/ # Contains the extracted CSV file from the Rolling Stones dataset ├── 📄 README.md # Project overview and instructions ├── 📄 requirements.txt # Required packages └── 📄 rolling_stones_spotify.csv

---

## 🎯 Problem Statement

Spotify wants to personalize music recommendations using **cohorts of songs**. This project clusters the songs from the **Rolling Stones albums** to identify similar tracks based on their audio characteristics.

### Objectives:
- Perform **data cleaning and EDA**
- Analyze patterns in features like **popularity, energy, danceability**
- Apply **dimensionality reduction**
- Use **KMeans clustering** to create song cohorts
- Recommend albums based on popular tracks

---

## 🧠 Techniques Used

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Data Preprocessing & Cleaning
- Exploratory Data Analysis (EDA)
- Standardization using `StandardScaler`
- PCA (Principal Component Analysis) for 2D visualization
- KMeans Clustering & Elbow Method

---

## 📊 Key Features Used for Clustering

- `acousticness`
- `danceability`
- `energy`
- `instrumentalness`
- `liveness`
- `loudness`
- `speechiness`
- `tempo`
- `valence`
- `popularity`
- `duration_ms`

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/spotify-song-clustering.git
cd spotify-song-clustering

