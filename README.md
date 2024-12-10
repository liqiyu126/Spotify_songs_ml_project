# Music Classification Using Audio Attributes 🎵

This project uses machine learning models to classify songs based on their audio attributes, leveraging data from the Spotify API. The dataset contains approximately 30,000 songs with various features like **track popularity**, **danceability**, **energy**, and **tempo**. The primary goal is to explore relationships between these features and genres.

---

## 📂 Dataset  
**Source:** [30000 Spotify Songs Dataset](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs)  
The dataset includes detailed metadata about songs, such as:  
- **Track Popularity**  
- **Danceability**  
- **Energy**  
- **Acousticness**  
- **Instrumentalness**  
- **Mode**
- **Tempo**  

---

## 🎯 Objectives  
1. Clean and preprocess the dataset for machine learning.  
2. Engineer features and select relevant attributes.  
3. Implement and evaluate multiple machine learning models to classify songs into genres.  

---

## 🤖 Machine Learning Models  
We experimented with the following models:  
1. **Naive Bayes**  
2. **K-Nearest Neighbors (KNN)**  
3. **Random Forest**  
4. **Support Vector Machine (SVM)**  

### 🏆 Best Model: **Random Forest**  
- **Accuracy:** 57.6%  
- **Baseline (Random Guess):** 16.7%  

---

## 🧪 Results  
- **Baseline Accuracy (Random Guess):** 16.7% (1/6 classes)  
- **Best Model Accuracy (Random Forest):** 57.6%  
- Significant improvement achieved by leveraging detailed audio attributes and feature selection.  
