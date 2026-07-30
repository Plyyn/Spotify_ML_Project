# Spotify Genre Classification using Machine Learning

## About the Project

This project explores a dataset of Spotify tracks and applies machine learning techniques to classify songs by genre based on their audio features.

The project covers the complete machine learning pipeline: data preprocessing, exploratory data analysis, dimensionality reduction, clustering, model training, and performance evaluation.

## Objectives

- Analyze Spotify audio features
- Explore relationships between musical characteristics and genres
- Reduce feature dimensionality using PCA
- Cluster similar tracks with K-Means
- Compare different machine learning algorithms for genre classification
- Evaluate model performance using classification metrics

## Dataset

The project uses the **Spotify Tracks Dataset**, which contains over 100,000 tracks with numerical audio features, including:

- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo
- Duration
- Popularity
- Genre

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

### 1. Data Preprocessing

- Missing value analysis
- Feature selection
- Encoding categorical variables
- Feature scaling using StandardScaler

### 2. Exploratory Data Analysis

- Distribution analysis
- Correlation matrix
- Feature visualization
- Genre distribution

### 3. Dimensionality Reduction

Principal Component Analysis (PCA) was applied to reduce the number of features while preserving most of the variance.

### 4. Clustering

K-Means clustering was used to identify groups of tracks with similar musical characteristics.

### 5. Machine Learning Models

The following classification algorithms were trained and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Gradient Boosting

### 6. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The best results were achieved using ensemble methods, particularly **Random Forest**, which demonstrated the highest classification performance on the Spotify dataset.

## Repository Structure

```
.
├── Spotify_ML_Project.ipynb
├── spotify_dataset.csv
├── README.md
└── requirements.txt
```

## Installation

Clone the repository

```bash
git clone https://github.com/your_username/spotify-genre-classification.git
cd spotify-genre-classification
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Spotify_ML_Project.ipynb
```

## Results

The project demonstrates how audio characteristics can be used to classify music genres. Different machine learning algorithms were compared, showing the strengths of ensemble methods for this task. In addition to supervised learning, clustering and PCA provided valuable insights into the structure of the dataset.

## Skills Demonstrated

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Dimensionality reduction (PCA)
- Clustering (K-Means)
- Supervised Machine Learning
- Model evaluation
- Data visualization
