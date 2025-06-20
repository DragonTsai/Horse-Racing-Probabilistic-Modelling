# Horse-Racing-Probabilistic-Modelling

## Overview

This project aims to estimate realistic and interpretable win probabilities for horse races by modelling horse speed as a continuous target, rather than directly predicting race outcomes. It employs a classic Ordinary Least Squares (OLS) regression, chosen for its transparency and robust statistical assumptions, followed by Monte Carlo simulations to convert predicted speeds into valid race-level win probabilities.

The model is particularly useful in settings where market odds are unavailable or unreliable and prioritises interpretability and replicability over black-box complexity.

---

## Project Structure

| File Name                                      | Description                                                                 |
|-----------------------------------------------|-----------------------------------------------------------------------------|
| `trainData.csv`                               | Training dataset containing race features and speed targets.                |
| `testData.csv`                                | Test dataset used for final model evaluation and probabilistic predictions.                      |
| `predicted_probabilities.csv`                 | Model-generated win probabilities for each horse in each test race.                |
| `Horse Racing Probabilistic Modelling Report_Yi-Lung(Dragon) Tsai.pdf` | Detailed technical report explaining methodology, modelling, and evaluation.   |
| `Horse Racing Probabilistic Modeling.ipynb`   | Full Jupyter Notebook including code for data preprocessing, model fitting, and probability generation. |

---



