# Cricket Ball-by-Ball Prediction

## Overview

This project explores the use of machine learning to predict outcomes in cricket using historical ball-by-ball match data from [Cricsheet](https://cricsheet.org/).

The project develops two predictive models using XGBoost:

- **Run prediction (regression):** Predicting the number of runs scored from an individual delivery.
- **Wicket prediction (classification):** Predicting the probability of a wicket occurring on an individual delivery.

The analysis involves processing raw match data, engineering cricket-specific features, training models and evaluating their predictive performance.

## Project Background

This project was originally put together relatively quickly in a Google Colab notebook as an opportunity to experiment with machine learning techniques on cricket data.

It has since been migrated to a local Python development environment in VS Code and published to GitHub. As a result, the project is still primarily contained within a Jupyter notebook rather than being organised as a fully modular Python application.

The intention is to continue developing the project, improving the modelling approach and gradually refactoring the code into reusable Python modules.

## Data

The project uses publicly available ball-by-ball cricket data from [Cricsheet](https://cricsheet.org/), supplemented by venue reference data.

The raw Cricsheet dataset is not included in this repository due to its size. The notebook contains code to download and extract the data automatically.

## Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- XGBoost
- Jupyter Notebook / VS Code

## Running the Project

1. Clone the repository.
2. Create and activate a Python virtual environment.
3. Install dependencies using `pip install -r requirements.txt`.
4. Open the notebook in the `notebooks/` directory.
5. Run the notebook cells in order. The required Cricsheet data will be downloaded if it is not already available locally.

## Future Improvements

- Refactor data processing, feature engineering and modelling into reusable Python modules.
- Further develop and evaluate the predictive models.
- Explore additional cricket-specific features and modelling techniques.
- Improve visualisation and interpretation of model predictions.
