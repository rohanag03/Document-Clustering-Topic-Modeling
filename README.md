# Document Clustering for Topic Modeling

## Overview

This project demonstrates document clustering and topic modeling techniques on the Twenty Newsgroups dataset. The objective is to apply clustering algorithms like K-means and Latent Dirichlet Allocation (LDA) to group similar documents and discover underlying topics within a large text corpus.

The analysis includes:
- **Document Clustering**: Using K-means to partition the dataset into clusters.
- **Topic Modeling**: Using LDA to uncover topics from the document corpus.
- **Visualization**: Dimensionality reduction using PCA to visualize the clusters.

## Table of Contents

- [Overview](#overview)
- [Project Components](#project-components)
- [Installation](#installation)
- [Key Features](#key-features)
- [Contributing](#contributing)
- [License](#license)

## Project Components

### Data

- **Dataset**: [Twenty Newsgroups](http://archive.ics.uci.edu/ml/datasets/Twenty+Newsgroups) dataset containing approximately 20,000 newsgroup documents organized into 20 different categories.

### Techniques Used

- **K-means Clustering**: A popular unsupervised learning algorithm for partitioning data into clusters based on similarity.
- **Latent Dirichlet Allocation (LDA)**: A statistical model for topic modeling that discovers the hidden thematic structure in a collection of documents.

## Installation

To get started with this project, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/rohanag03/Document-Clustering-Topic-Modeling.git
   cd Document-Clustering-Topic-Modeling
   ```
2. **Install Required Packages**

    ```bash
    pip install -r requirements.txt
    ```

## Key Features

- Data Preprocessing: Includes text tokenization, stopword removal, and stemming.
- Feature Extraction: Uses TF-IDF vectorization for document representation.
- Clustering: Implements K-means to group documents into clusters.
- Topic Modeling: Applies LDA to extract topics from the document corpus.
- Visualization: Uses PCA for dimensionality reduction to visualize document clusters.

## Contributing
Contributions are welcome! If you have suggestions for improvements or would like to add new features, please follow these steps:

- Fork the repository.
- Create a new branch for your changes.
- Commit your changes and push to your forked repository.
- Open a pull request with a description of the changes you made.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


