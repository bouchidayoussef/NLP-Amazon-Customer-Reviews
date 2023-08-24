
# Natural Language Processing for Amazon Customer Reviews

## Table of Contents
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Limitations and Future Work](#limitations-and-future-work)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Problem Statement
This project aims to perform Natural Language Processing (NLP) on Amazon customer reviews. Specifically, the goals are:
- To categorize reviews into Positive or Negative based on the text.
- To derive insights on what customers generally appreciate or complain about.

## Dataset
The dataset used is the Amazon reviews polarity dataset from Kaggle. It comprises:
- 1,800,000 training samples
- 200,000 test samples
- Columns: polarity, title, and text
- Polarity: 1 for Negative, 2 for Positive

## Methodology
- Data Preprocessing: Cleaning, tokenization, and stopword removal.
- Exploratory Data Analysis: Visualization of rating distribution and word clouds.
- Feature Engineering: Text vectorization using TF-IDF.
- Model Training: Multinomial Naive Bayes classifier.
- Evaluation: Measuring accuracy and F1-score.
- Fine-Tuning: Hyperparameter tuning using GridSearchCV.
- Deployment: REST API using Flask.

## Installation
```bash
pip install pandas
pip install numpy
pip install nltk
pip install matplotlib
pip install seaborn
pip install wordcloud
pip install scikit-learn
pip install Flask
```

## Usage
To run the project:
- Clone the GitHub repository.
- Navigate to the project directory.
- Run the Jupyter Notebook or Python files.

To use the REST API:
- Run the Flask app.
- Use a tool like Postman or curl to send a POST request to the /predict endpoint.

## Results
- Training Accuracy: 0.82
- F1 Score: 0.82

## Limitations and Future Work
- The model only works for English reviews.
- Future improvements could include other machine learning algorithms and deep learning models.

## Contributing
Feel free to fork the project, open a pull request, or report issues and suggestions.

## License
This project is licensed under the MIT License.

## Acknowledgments
Thanks to Kaggle for providing the dataset.
