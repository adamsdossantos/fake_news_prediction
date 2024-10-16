# Logistic Regression NLP Project with NLTK - Fake News Detection

## 1. Project Overview

This project implements a Logistic Regression model for fake news detection using NLTK for text preprocessing. Logistic Regression is commonly used for classification tasks and is a good baseline for text classification problems.

## 2. Dataset Source

https://www.kaggle.com/c/fake-news/data?select=train.csv


## 3. Features
- **Data Preprocessing**: Text cleaning, tokenization, stop word removal, and feature extraction using NLTK.
- **Model Training**: Training a Logistic Regression model using scikit-learn.
- **Model Evaluation**: Evaluating the performance of the model using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.
- **Visualization**: Visualization of feature importance and performance metrics.


## 4. Project Structure
    ├── train.csv                   # Dataset file 
    ├── fake_news_prediction.ipynb  # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 5. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- NLTK
- pandas
- matplotlib
- numpy
- seaborn

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/fake_news_prediction.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook fake_news_prediction.ipynb
```
## 6. Usage

Open the fake_news_prediction.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- **Data Loading and Preprocessing**: Load data from the train.csv and perform text cleaning, tokenization, lemmatization, and feature extraction using NLTK.
- **Model Training**: Train a Logistic Regression model with adjustable hyperparameters.
- **Model Evaluation**: Evaluate the model using metrics like accuracy, precision, recall, F1-score, and visualize the confusion matrix.
- **Visualization**: Visualize the top features contributing to classification decisions and the confusion matrix for model evaluation.


## 7. Results in Test
| Metric    |  Value |
|-----------|--------|
| Accuracy  |  98%   |
| Precision |  97%   |
| Recall    |  99%   |
| F1 Score  |  98%   |

## 8. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 9. License

This project is licensed under the MIT License - see the LICENSE file for details.







