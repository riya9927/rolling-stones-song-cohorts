# 🎵 Creating Cohorts of Songs using Clustering 

This project applies **unsupervised machine learning (clustering)** techniques to create **cohorts of songs** based on their audio features from Spotify's API. By identifying patterns in musical attributes like energy, danceability, valence, and more, the project groups songs into meaningful clusters that can be used for recommendation systems.

---

## 📁 Project Structure

```
📦 spotify-song-clustering/
│
├── 📊 CohortsofSongs.ipynb          # Jupyter notebook with complete code and analysis
├── 📄 1688641626_data_dictionary.xlsx  # Blueprint for understanding the dataset
├── 📄 README.md                      # Project overview and instructions
├── 📄 requirements.txt               # Required packages
└── 📄 1689942861_rolling_stones_spotify.zip    # Original dataset
```

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
git clone https://github.com/riya9927/rolling-stones-song-cohorts.git
cd spotify-song-clustering
```

2. Create a virtual environment and install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook EDA_and_Clustering.ipynb
```

---

## 📷 Visual Insights

- 📈 Correlation Matrix of song attributes  
- 🎨 PCA 2D visualization of clusters  
- 🌀 Cluster-wise interpretation of musical traits  
- 📀 Top Albums by Popular Songs  

---

## 📌 Results

- Songs were grouped into **4 clusters** with distinct acoustic/mood characteristics.
- Identified albums with **highest popular songs** for recommendation.
- Provided **cluster-wise interpretation** for better recommendation logic.

---

## ✨ Future Work

- Incorporate user listening data for personalized recommendations
- Use advanced models like DBSCAN or Gaussian Mixture Models
- Integrate with a web app for real-time recommendations
