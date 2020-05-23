# Capstone1_Readmission_Rate_Predictor
This is the first Capstone Project for the Data Science Career Track Program at Springboard. The goal of this project is to build a model that predicts whether a patient is going to be readmitted within 30 days of discharge. This information aims to help hospitals make better decisions in managing resources as well as patient outcome. 

[Presentation Slides](https://docs.google.com/presentation/d/1VksqgZgzRRvDBYz7ajUYl9BLyZyff0Dtz14YiOQdq_0/edit?usp=sharing)
[Final Report](https://docs.google.com/document/d/1dsYO3RixDwN-B5tQCjo7ckMlaFsTLXWTbYowZzEJOw8/edit?usp=sharing)

# Notebooks
1. Data Wrangling & Feature Engineering - code for cleaning, merging, scaling and feature engineering.
2. Story Telling - code for data visualization and statistical inference showing relationships between features and target variables.
3. Machine Learning DischargeNotes - code for building a model using word features from Discharge Notes only.
4. Machine Learning Overall - code for building data pipeline (task in pipeline: feature transformation and merge all features), tuning model parameters using GridSearch, finding important feature set, finding best model and evaluating model performance.   
5. functions: code for functions being called by the notebooks above.

# Project Setup

Setup python for xgboost
```sh
brew install cmake
brew install libomp
brew install python
```

Setup project
```sh
python -m venv .venv
source .venv/bin/activate
pip install -U pip
pip install -r requirements.txt
```
