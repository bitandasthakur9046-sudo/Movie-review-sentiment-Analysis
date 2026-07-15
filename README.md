# 🎬 Movie Review Sentiment Analysis

A Machine Learning project that classifies movie reviews as **Positive**
or **Negative** using **Natural Language Processing (NLP)** and
**Multinomial Naive Bayes**. The project uses the **NLTK Movie Reviews**
dataset and **TF-IDF Vectorization**.

## Features

-   Uses the NLTK Movie Reviews dataset
-   TF-IDF text vectorization
-   Multinomial Naive Bayes classifier
-   Accuracy and classification report
-   Predicts custom movie reviews
-   Saves trained model (`movie_model.pkl`) and vectorizer
    (`vectorizer.pkl`)

## Technologies

-   Python
-   NLTK
-   Pandas
-   Scikit-learn
-   Pickle

## Installation

``` bash
git clone https://github.com/your-username/movie-review-sentiment-analysis.git
cd movie-review-sentiment-analysis
pip install nltk pandas scikit-learn
```

## Run

``` bash
python movie_review_sentiment.py
```

## Workflow

1.  Load NLTK Movie Reviews dataset
2.  Convert reviews into a DataFrame
3.  Apply TF-IDF Vectorization
4.  Split training and testing data
5.  Train Multinomial Naive Bayes
6.  Evaluate the model
7.  Predict sentiment for new reviews
8.  Save the trained model

## Project Structure

``` text
Movie-Review-Sentiment-Analysis/
├── movie_review_sentiment.py
├── movie_model.pkl
├── vectorizer.pkl
├── README.md
└── requirements.txt
```

## License

MIT License

## Author

**Ayan Pal**

⭐ Star this repository if you found it useful!
