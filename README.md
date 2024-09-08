# Smart Course Recommendations Leveraging NLP and Clustering Techniques

## Overview

This project involves clustering and recommending courses based on their descriptions. It uses Natural Language Processing (NLP) techniques and machine learning algorithms to process and analyze course data. The key steps include data preprocessing, feature extraction, clustering, and visualization.

## Project Components

1. **Data Preprocessing**
   - Load course data from a CSV file.
   - Clean and preprocess the data by removing duplicates, null values, and applying text normalization (e.g., lowercasing, punctuation removal, and stemming/lemmatization).

2. **Feature Extraction**
   - Convert text descriptions into numerical embeddings using Sentence-BERT (SBERT).

3. **Clustering**
   - Apply K-Means clustering to group similar courses.
   - Use various methods (Elbow Method, Silhouette Score, Davies-Bouldin Score, Calinski-Harabasz Index, and X-Means) to determine the optimal number of clusters.

4. **Visualization**
   - Reduce dimensionality using t-SNE for 2D and 3D visualization.
   - Visualize clusters in 2D and 3D plots using Seaborn and Plotly.
   - Use the NMSLIB library for approximate nearest neighbors to facilitate course recommendations.

5. **Recommendation System**
   - Implement a function to find and recommend courses based on user input using the trained clustering model.

## Setup

### Prerequisites

- Python 3.7 or later
- Required Python packages (install using `pip`):
  - `nltk`
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `sklearn`
  - `sentence-transformers`
  - `yellowbrick`
  - `pyclustering`
  - `plotly`
  - `texthero`
  - `nmslib`

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/course-catalog-clustering.git
   cd course-catalog-clustering
