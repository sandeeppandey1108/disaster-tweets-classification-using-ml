
# Disaster Tweets Classification using Machine Learning

This project focuses on classifying disaster-related tweets using various machine learning models. The primary objective is to develop a model capable of accurately identifying whether a tweet pertains to a real disaster.

## Project Overview

- **Data**: The dataset utilized in this project comprises tweets labeled as either disaster-related or not.
- **Models Used**: This project explores multiple machine learning models, including Logistic Regression, Multinomial Naive Bayes, Random Forest, XGBoost, CatBoost, and SVM.
- **Goal**: To accurately classify tweets as either disaster-related or non-disaster-related.

## Project Structure

- `disaster-tweets-classification-using-ml.ipynb`: Jupyter notebook containing the project's code and analysis.
- `DataSet/`: Directory containing the dataset files:
  - `train.csv`: Training dataset.
  - `test.csv`: Test dataset.
  - `submission.csv`: Sample submission file.
- `catboost_info/`: Directory containing CatBoost model training information.
- `.venv/`: Virtual environment for the project (not included in the repository).

## Objectives

The primary objectives of this project are as follows:

- Perform exploratory data analysis to understand the distribution and characteristics of the dataset.
- Analyze the relationships between various factors (such as text features) and the target variable (disaster-related or not).
- Visualize the data to gain insights into patterns and trends.
- Create predictive models to classify tweets as disaster-related or non-disaster-related.

## Tools and Libraries

The analysis and modeling were conducted using the following libraries:

- `pandas`: For data manipulation.
- `numpy`: For numerical operations.
- `scikit-learn`: For machine learning algorithms and evaluation.
- `catboost`: For the CatBoost model.
- `xgboost`: For the XGBoost model.
- `tensorflow`: For neural networks and deep learning.
- `nltk`: For natural language processing tasks.
- `plotly`: For interactive visualizations.
- `wordcloud`: For generating word clouds.
- `matplotlib`: For static visualizations.

## How to Run

1. **Clone the repository**:
   ```sh
   git clone https://github.com/sandeeppandey1108/disaster-tweets-classification-using-ml.git
   ```

2. **Navigate to the project directory**:
   ```sh
   cd disaster-tweets-classification-using-ml
   ```

3. **Set up the virtual environment**:
   ```sh
   python -m venv .venv
   source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
   ```

4. **Install the required dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

5. **Run the Jupyter notebook**:
   ```sh
   jupyter notebook disaster-tweets-classification-using-ml.ipynb
   ```

## Analysis and Results

### Data Import and Preprocessing

- Imported the dataset and checked its structure and summary statistics.
- Preprocessed the text data, including tokenization and vectorization.
- Split the dataset into training and testing sets.

### Exploratory Data Analysis

- **Word Clouds**: Created word clouds to visualize the most common words in disaster-related and non-disaster-related tweets.
- **Bar Charts**: Analyzed the distribution of tweet lengths and other features.

### Model Building

- **Logistic Regression**: Built and evaluated models using different n-grams and TF-IDF approaches.
- **Multinomial Naive Bayes**: Built and evaluated models using TF-IDF approaches.
- **Random Forest**: Built and evaluated models using TF-IDF approaches.
- **XGBoost**: Built and evaluated models using TF-IDF approaches.
- **CatBoost**: Built and evaluated models using TF-IDF approaches.
- **SVM**: Built and evaluated models using TF-IDF approaches.
- **Voting Classifier**: Combined multiple models using a voting classifier for improved accuracy.

### Model Evaluation

- Evaluated model performance using accuracy, precision, recall, and F1-score.
- Visualized the confusion matrix to understand the model's classification performance.

## Results

- **Logistic Regression**: Achieved high accuracy with n-grams=1.
- **Random Forest**: Provided robust performance with TF-IDF.
- **Voting Classifier**: Combined multiple models for the best performance.

## Conclusions

The project successfully classified tweets as disaster-related or non-disaster-related using various machine learning models. The Voting Classifier provided the best overall performance.

## Acknowledgments

- The dataset is provided by [Kaggle](https://www.kaggle.com/c/nlp-getting-started).
- Special thanks to all contributors to the machine learning libraries used in this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
