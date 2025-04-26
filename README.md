# Character-Level Language Model

This project implements a character-level language model to generate names using a neural network. The model is trained on a dataset of names and learns to predict the next character based on a given sequence of previous characters.

## Features
- **Data Preprocessing**: Reads names from a file and creates training, validation, and test datasets.
- **Model Architecture**: A simple neural network with embedding, hidden, and output layers.
- **Training**: Implements a training loop with loss calculation and parameter updates.
- **Evaluation**: Evaluates the model on training and validation datasets.
- **Name Generation**: Generates new names using the trained model through a sampling process.

## Requirements
- Python 3.x
- PyTorch
- NumPy
- scikit-learn

## Data
- The model is trained on a dataset of names (`names.txt`). You can replace this file with your own dataset of names to train the model on different data.

## Usage
After training, you can generate names by sampling from the trained model.
