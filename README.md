# 🎮 ML LAB Project - Steam Game Recommendation System

## 📌 Project Overview

This project focuses on building a **Steam game recommendation system** using user ratings and game metadata. It aims to analyze user preferences and game attributes to generate **personalized game suggestions**.

## 👥 Team Members

- 22k4102  
- 22k8709  
- 22k4066  

## 📂 Datasets

The project utilizes two main datasets:

### `user_ratings.csv`
Contains user ratings for various games.

- `user_id`: Unique identifier for users  
- `user_rating`: Rating given by the user (1–5 scale)  
- `appid`: Unique game identifier  

### `steam.csv`
Contains detailed metadata about Steam games.

- `appid`, `name`, `release_date`, `genres`, `developer`, `publisher`, etc.  
- `positive_ratings`, `negative_ratings`, `average_playtime`, etc.

## 🌟 Key Features

- Data loading and exploratory data analysis (EDA)
- Visualization of rating distributions
- Data cleaning and preprocessing
- Analysis of game genres and metadata
- Preparation for implementing recommendation algorithms

## 🧠 Project Structure

The Jupyter notebook follows this sequence:

1. Dataset loading and initial exploration  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Visualization of key insights  
5. Preparation for recommendation system implementation  

## 🛠️ Requirements

- Python 3.x  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn` (for recommendation models)

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/steam-game-recommendation.git
   cd steam-game-recommendation
