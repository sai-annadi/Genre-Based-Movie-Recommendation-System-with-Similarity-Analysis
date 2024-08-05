# Genre-Based Movie Recommendation System with Similarity Analysis

## Overview

This project focuses on developing a genre-based movie recommendation system using similarity analysis. The goal is to recommend movies similar to a given title based on genre information. The system leverages cosine similarity and k-Nearest Neighbors (k-NN) algorithms to provide movie recommendations.

## Key Features
### 1.Genre Distribution Visualization

- Bubble Chart: Visualizes the distribution of different movie genres, with the size of each bubble representing the number of movies in each genre.
- Donut Chart: Provides a proportionate view of genre distribution.

### 2.Similarity Analysis

- Cosine Similarity: Computes the cosine similarity between genre vectors to determine how similar movies are to one another.
- k-Nearest Neighbors (k-NN): Uses the k-NN algorithm to find the nearest neighbors based on genre similarity and recommend similar movies.

### 3.Model Evaluation

- Cross-Validation: Assesses the performance of the k-NN model using cross-validation to ensure robust recommendation results.

### 4.Recommendation Functions

- Functions to get recommendations based on both cosine similarity and k-NN algorithms, providing movie titles and their genres.

## Getting Started

To get started with the Genre-Based Movie Recommendation System, follow these steps:

### Installation

To install the necessary Python libraries, you can use pip. Run the following command:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Usage

### 1.Clone the Project Repository

```bash
git clone https://github.com/sai-annadi/Genre-Based-Movie-Recommendation-System-with-Similarity-Analysis.git
```

### 2.Navigate to the Project Directory

```bash
cd Genre-Based-Movie-Recommendation-System-with-Similarity-Analysis
```

### 3.Run the Project

- Load the dataset and preprocess it, then generate genre visualizations and movie recommendations. Use the provided functions to get recommendations based on cosine similarity and k-NN.
