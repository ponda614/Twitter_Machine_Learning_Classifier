# Twitter_Machine_Learning_Classifier

## Table of Contents
- [Project Overview](#project-overview)
- [Libraries](#Libraries)
- [Usage](#usage)
- [Results](#results)


## Project Overview
In this project, the goal is to develop a machine learning classifier that can automatically classify tweets as either "Business" or "Not Business." The dataset provided is in the form of a CSV file and contains tweets that have been manually classified by human editors.

The objective is to create a classifier that can effectively replace the human editors by accurately predicting the category of each tweet. By automating the classification process, this project aims to streamline the analysis of Twitter data and enable faster and more efficient identification of tweets related to business activities.

## Libraries

| Library                                   | Description                                                                                                     |
|-------------------------------------------|-----------------------------------------------------------------------------------------------------------------|
| scikit-learn                              | Machine learning library for data preprocessing, feature extraction, model training, and evaluation.           |
| pandas                                    | Data manipulation and analysis library for working with structured data.                                         |
| numpy                                     | Fundamental library for numerical computing in Python, providing efficient data structures and mathematical functions.  |
| tqdm                                      | Library for creating progress bars to monitor the progress of tasks. (VERY USEFUL)                                           |
| matplotlib                                | Plotting library for creating various types of visualizations.                                                  |
| seaborn                                   | Statistical data visualization library built on top of Matplotlib.                                              |
| nltk                                      | Natural Language Toolkit for tasks such as tokenization, stemming, and part-of-speech tagging.(Mainly Used for Training |
| re                                        | Built-in library for working with regular expressions.                                                          |
| spaCy                                     | Modern NLP library for efficient and scalable natural language processing tasks. (Preferred over nltk)                              |
| sklearn.model_selection/linear_model/feature_extraction.text/pipeline                   | Module for model selection and evaluation, including cross-validation and train-test splitting, linear models, including Logistic Regression, feature extraction from text data, such as TF-IDF vectorization,  constructing pipelines of multiple steps in machine learning workflows.                   |
| WordNet                                   | Lexical database for English language, used for tasks such as synonym extraction and word sense disambiguation. |
| Contradiction                             | Library for contradiction detection in text, used for identifying contradictory statements in textual data.     |
| emoji                                     | Library for handling emojis in Python.                                                                         |
| gensim                                    | Library for topic modeling and document similarity analysis.                                                    |
| wordcloud                                 | Library for generating word clouds from text data.                                                              |
| swifter                                   | Library for speeding up Pandas apply() function.                                                               |
| collections.Counter                       | Built-in library for counting hashable objects in Python.                                                       |
| wordninja                                 | Library for splitting concatenated words into separate words.                                                   |
| num2words                                 | Library for converting numbers to words in various languages.                                                   |

Logistic Regression with TF-IDF Features:
The logistic regression model trained using TF-IDF features achieved the following results:

    Accuracy: 0.7284
    Precision: 0.7462
    Recall: 0.9005
    F1 Score: 0.8161

These results indicate that the logistic regression classifier performed well in classifying the tweets as Business or not Business. It achieved an accuracy of 72.84%, meaning that 72.84% of the tweets were correctly classified. The precision score of 74.62% indicates that out of the tweets predicted as Business, 74.62% were actually correct. The recall score of 90.05% suggests that the classifier was able to correctly identify 90.05% of the actual Business tweets. The F1 score of 81.61% combines precision and recall, providing a balanced measure of the classifier's performance.

Logistic Regression with CountVectorizer Features:
The logistic regression model trained using CountVectorizer features achieved the following results:

    Accuracy: 0.7196
    Precision: 0.7460
    Recall: 0.8809
    F1 Score: 0.8078

These results show that the logistic regression classifier with CountVectorizer features also performed well. It achieved an accuracy of 71.96%, indicating that 71.96% of the tweets were correctly classified. The precision score of 74.60% suggests that out of the tweets predicted as Business, 74.60% were actually correct. The recall score of 88.09% indicates that the classifier was able to correctly identify 88.09% of the actual Business tweets. The F1 score of 80.78% provides a balanced measure of precision and recall.


