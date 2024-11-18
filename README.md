# IMDB Movie Score Analysis and Prediction

This project analyzes factors influencing IMDB movie scores and develops predictive models for improved accuracy using various statistical techniques. The code includes exploratory data analysis, model building, and evaluation using cross-validation techniques.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data](#data)
3. [Requirements](#requirements)


---

## Project Overview

The primary goal of this project is to identify and evaluate predictors for IMDB scores using statistical models. The code incorporates linear regression, polynomial regression, and splines to improve prediction accuracy. It also uses log transformations to address heteroskedasticity in the data.

---

## Data

The project uses two datasets:
- `IMDB_data_Fall_2024.csv` (training data)
- `test_data_IMDB_Fall_2024.csv` (test data for predictions)

Both datasets contain features such as movie budget, duration, number of news articles, star meter ratings, and more.

---

## Requirements

The project relies on the following R packages:
- `psych`: For data exploration and correlation analysis.
- `car`: For residual and heteroskedasticity checks.
- `lmtest`: For robust regression tests.
- `plm`: For advanced panel regression methods.
- `caret`: For cross-validation and model training.
- `splines`: For spline-based non-linear models.

Install the required packages using:
```R
install.packages(c("psych", "car", "lmtest", "plm", "caret", "splines"))
