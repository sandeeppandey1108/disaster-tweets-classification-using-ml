# Disaster Tweets Classification using Machine Learning

This project focuses on classifying disaster-related tweets using various machine learning models. The primary objective is to develop a model capable of accurately identifying whether a tweet pertains to a real disaster.

## Project Overview

- Data: The dataset utilized in this project comprises tweets labeled as either disaster-related or not.
- Models Used: This project explores multiple machine learning models, including CatBoost.
- Goal: To accurately classify tweets as either disaster-related or non-disaster-related.

## Project Structure

- `disaster-tweets-classification-using-ml.ipynb`: Jupyter notebook containing the project's code and analysis.
- `DataSet/`: Directory containing the dataset files:
  - `train.csv`: Training dataset.
  - `test.csv`: Test dataset.
  - `submission.csv`: Sample submission file.
- `catboost_info/`: Directory containing CatBoost model training information.
- `.venv/`: Virtual environment for the project (not included in the repository).

## How to Run

1. Clone the repository:
  
   git clone https://github.com/sandeeppandey1108/disaster-tweets-classification-using-ml.git

2. Navigate to the project directory:

    cd disaster-tweets-classification-using-ml
   
3.  python -m venv .venv

   source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`

4.  Install the required dependencies:

   pip install -r requirements.txt

5. jupyter notebook disaster-tweets-classification-using-ml.ipynb
   
