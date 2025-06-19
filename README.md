# Movie Recommendation System

This project implements a movie recommendation system from scratch using two different deep learning models: Restricted Boltzmann Machines (RBMs) and Stacked Autoencoders (SAEs). The goal is to predict movie ratings for users and recommend movies they might like.

## Features

*   **Movie Recommendation:** Predicts user ratings for movies they haven't seen.
*   **Two Models:** Implements both RBM and SAE models for comparison.
*   **Training and Evaluation:** Includes scripts for training the models and evaluating their performance.

## Technologies Used

*   **Python:** The primary programming language for the project.
*   **PyTorch:** The deep learning framework used to build the RBM and SAE models.
*   **NumPy:** For numerical operations and data manipulation.
*   **Pandas:** For data loading and preprocessing.

## Project Structure

The repository is organized as follows:

```
.
├── AutoEncoders (AE)/
│   └── ae.py
├── Boltzmann Machines (BM)/
│   └── rbm.py
├── README.md
```

*   `AutoEncoders (AE)/ae.py`: Contains the implementation of the Stacked Autoencoder model.
*   `Boltzmann Machines (BM)/rbm.py`: Contains the implementation of the Restricted Boltzmann Machine model.

## Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/satyansh-mittal/Movie-Recommendation-System.git
    ```
2.  Install the required dependencies:
    ```bash
    pip install torch numpy pandas
    ```
