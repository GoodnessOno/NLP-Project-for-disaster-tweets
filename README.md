**Twitter Disaster Prediction NLP Project**

## Overview

Welcome to my Twitter Disaster Prediction NLP Project repository! In this project, I developed machine learning models to predict whether tweets are related to real disasters or not. The project involves both a baseline logistic regression model and an advanced LSTM neural network.

## Project Structure

- `train.csv/test.csv`: Contains the dataset used for training and evaluation.
- `notebooks/`: Jupyter Notebooks used for data exploration, preprocessing, and model development.
- `models/`: Saved model files.
- `scripts/`: Any additional scripts used in the project.

## Files

- `train.csv`: The original dataset containing labeled tweets.
- `README.md`: This file, providing an overview of the project.

## Models

1. **Baseline Model: Logistic Regression**
   - A simple logistic regression model using TF-IDF vectorization for feature extraction.

2. **Advanced Model: LSTM Neural Network**
   - A more complex model leveraging an LSTM architecture for sequence processing.

## Usage

### Training the Models

To train the models, run the Jupyter Notebooks in the `notebooks/` directory. These notebooks cover data exploration, preprocessing, model development, and evaluation.

### Dependencies

- Python 3.11
- Jupyter Notebook
- Required libraries (e.g. tensorflow, keras, numpy, pandas, matplotlib etc) can be installed using the following:
  ```bash
  pip install -r requirements.txt
  ```

### Evaluation

Evaluate the model's performance using the provided evaluation scripts in the notebooks.

### Prediction

Make predictions on new data using the trained models. Example scripts are available in the `scripts/` directory.

## Acknowledgments

- This project is part of the "Getting Started" competition on Kaggle.
- Special thanks to the Kaggle community for valuable insights and discussions.

## Author

- Goodness Ononogbu
- LinkedIn - https://www.linkedin.com/in/goodness-ononogbu-aicmc/
- Email: ononogbugoodness@gmail.com

Feel free to reach out for any questions or collaboration opportunities.
