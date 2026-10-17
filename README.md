# Reddit and Financial Data Analysis

Coursework exploring Reddit discussion data and financial features with machine-learning classification and regression models. The repository contains research notebooks and preprocessing scripts.

## Repository map

- `Webscrape_351.ipynb`: Reddit data collection using PRAW and Pushshift APIs.
- `Preprocessing/`: submission and comment filtering, text cleaning, ticker extraction, financial-data collection, sentiment scores, and trustworthiness calculations.
- `Models/`: Random Forest and LightGBM classifiers/regressors, an MLP classifier, and a feed-forward neural-network regressor.
- `Metrics/results.ipynb`: percent-change regression results.
- `Metrics/classification_results.ipynb`: maximum adjusted closing-price classification results.
- `Metrics/MaxDay_Regression Results.ipynb`: maximum adjusted closing-price regression results.

## Working with the notebooks

Use a Python/Jupyter environment and inspect each notebook's imports, input paths, and execution order before running it. Some notebooks use Google Colab and Google Drive authentication.

A reproducible environment specification and the input datasets are not supplied at the repository root. For example, `Models/NN_Predictor.ipynb` expects `10dayWindow_original_no_duplicates_date_tick.csv`, while preprocessing scripts reference a `Data/` directory. Historical data-access integrations may also need updating.

## Scope and limitations

Reproducing the experiments requires the original data, environment, and preprocessing choices. There is no consolidated environment specification or end-to-end execution guide.

## Attribution

`Models/NN_Predictor.ipynb` credits Jordan Posen. Preserve the authorship information in individual files; this repository should not be read as a claim of sole authorship of every notebook.
