# Text Classification using ML

This project demonstrates a simple machine learning pipeline for sentiment analysis using the IMDB movie reviews dataset. The notebook loads review text, cleans it, converts it into numerical features, and trains a model to classify each review as either positive or negative.

## Project Goal

The goal is to build a text classification model that can predict the sentiment of a movie review based on its content.

## Dataset

This project uses the IMDB dataset (`IMDB Dataset.csv`), which contains movie reviews with sentiment labels:

- positive
- negative

The notebook samples the first 10,000 rows for faster execution and experimentation.

## Workflow

The notebook includes the following steps:

- Importing required libraries
- Loading the dataset with pandas
- Checking data size and class distribution
- Handling missing values and duplicate rows
- Removing HTML tags from review text
- Converting text to lowercase
- Applying basic text preprocessing
- Splitting the data into train/test sets
- Converting text to features using TF-IDF / CountVectorizer
- Training a machine learning classifier
- Evaluating results using confusion matrix and classification metrics

## Libraries Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- scikit-learn

## Requirements

Install the required dependencies using:

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn
```

## How to Run

Open the notebook in Jupyter Notebook or Google Colab and run all cells in sequence:

```bash
Text_Classification_using_ML.ipynb
```

## Notes

- The project uses basic natural language preprocessing for sentiment classification.
- Stopwords are downloaded from NLTK during execution.
- The implementation is beginner-friendly and suitable for learning text classification and sentiment analysis.

## Author

Dhruvpalsinh

## License

This project is intended for educational and learning purposes.
