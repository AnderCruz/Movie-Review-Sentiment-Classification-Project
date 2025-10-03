# Movie Review Sentiment Classification Project

## Project Description

This project implements a sentiment classification system (positive/negative) for movie reviews in Portuguese. Using Natural Language Processing (NLP) techniques and Machine Learning, the model can analyze review texts and determine whether the expressed opinion is positive or negative.

## Objective

Develop a sentiment classifier that can be applied to analyze user opinions about movies, using a dataset of IMDB reviews translated into Portuguese.

## Dataset

The project uses the **"IMDB Reviews in Portuguese"** dataset available on Kaggle, containing:
- 49,459 movie reviews
- Texts in Portuguese and English
- Sentiment classifications (positive/negative)
- Balanced distribution between positive and negative classes

## Technologies Used

- **Python 3**
- **Pandas** - Data manipulation
- **Scikit-learn** - Machine Learning
- **NLTK** - Natural language processing
- **TF-IDF** - Text vectorization
- **Logistic Regression** - Classification model

## Methodology

### 1. Pre-processing
- Dataset download and loading
- Train-test split
- Removal of Portuguese stopwords
- TF-IDF vectorization with 5,000 features

### 2. Modeling
- **Algorithm**: Logistic Regression
- **Data split**: 80% training, 20% testing
- **Validation**: Train-Test Split with random_state=42

### 3. Evaluation
- **Main metric**: Accuracy
- **Result**: 88.17% accuracy on test set

## Results

The model achieved an accuracy of **88.17%** in sentiment classification, demonstrating good performance in distinguishing between positive and negative reviews.

## How to Run

### Prerequisites
```bash
pip install pandas scikit-learn nltk kagglehub
```

### Execution
1. Clone the repository
2. Run the `LLM_Project.ipynb` notebook
3. The dataset will be automatically downloaded via Kagglehub

## Project Structure

```
LLM_Project/
├── LLM_Project.ipynb          # Main notebook
├── requirements.txt           # Project dependencies
└── README.md                 # Documentation
```

## Features

- **Exploratory Analysis**: Sentiment distribution visualization
- **Pre-processing**: Text cleaning and preparation
- **Training**: Classification model development
- **Evaluation**: Model performance metrics
- **Visualization**: WordCloud for frequent words analysis

## Dataset Insights

- Balanced distribution: 24,765 negative vs 24,694 positive
- Portuguese texts with consistent translations
- Rich and diverse vocabulary for training

## Applications

- Opinion analysis on streaming platforms
- Sentiment monitoring on social media
- Market research for film industry
- Review-based recommendation systems

## Next Steps

- Experiment with other algorithms (Random Forest, SVM, Neural Networks)
- Implement deep learning techniques (BERT in Portuguese)
- Develop web interface for demonstration
- Expand to other domains (product analysis, news)

## Developed by

**Nowa Analytics** - Data Science and Machine Learning Consulting

---

*This project demonstrates the practical application of NLP and Machine Learning for solving real-world sentiment analysis problems.*
