# SC1015-Group-5-Data-Science-Project
# Fake News Classifier
## About
This is a mini-project for SC1015, which focuses on identifying fake news, using the dataset from [Fake News Corpus](https://github.com/several27/FakeNewsCorpus).

Project datasets: rawData.zip and cleanedData.csv

https://drive.google.com/drive/folders/1_ur9kd5K8U-56ETi_ibqcttyWXi90Fum?usp=sharing

## Contributors
- Nicky - Data cleaning and preprocessing and Neural Network
- Jin Kai - Logistic Regression and EDA
- Meng Kiat - Naive Bayes Classifier, Binary Classification Tree and Ensemble

## Problem Definition
- Are we able to predict whether a news article is fake based on its attributes?
- Which model would be the best to predict?

## Models Used
- Logistic Regression
- Naive Bayes Classifier
- Binary Classification Tree
- Ensemble Model
- Recurrent Neural Network (LSTM)

## Conclusion
- Fake news articles tend to have:
  - stronger sentiment 
  - higher usage of first-person pronouns
  - lower usage of third-person pronouns
  - greater number of sentences
- Some words are more prevalent in fake news articles and thus, can be used to determine the credibility of fake news via vectorization
- Combination of a few machine learning models via ensemble can produce a better model

## What did we learn from this project
- Machine Learning Models
  - Recurrent Neural Network, Naive Bayes Classifier, Logistic Regression and Ensemble Model
- Using GitHub
- Packages
  - Tensorflow, nltk, sklearn
- EDA
  - Lexical score, vader score and vectorization 
- F-Score

## References
- https://machinelearningmastery.com/develop-bidirectional-lstm-sequence-classification-python-keras/
- https://towardsdatascience.com/predicting-fake-news-using-nlp-and-machine-learning-scikit-learn-glove-keras-lstm-7bbd557c3443
- https://towardsdatascience.com/building-classification-models-with-sklearn-6a8fd107f0c1
- https://github.com/several27/FakeNewsCorpus
- https://github.com/AIRLegend/fakenews/blob/master/notebooks/GettingRealAboutFake.ipynb
- https://github.com/AIRLegend/fakenews/blob/master/notebooks/data_analysis/Data_analysis-GettingReal.ipynb
- https://towardsdatascience.com/fake-news-detection-with-machine-learning-using-python-3347d9899ad1
- https://medium.com/geekculture/detecting-fake-news-using-supervised-learning-8abf09b9bf1d
- https://analyticsindiamag.com/a-hands-on-guide-to-hybrid-ensemble-learning-models-with-python-code/
- https://github.com/krishnaik06/Fake-New-LSTM

