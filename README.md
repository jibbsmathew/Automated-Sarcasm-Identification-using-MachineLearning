# Sarcasm Detection using Machine Learning

Sarcasm, a linguistic staple for ages, involves saying the opposite of what's meant, often playfully, with a distinct tone. Contrary to belief, not everyone grasps sarcasm; it hinges on language skills and understanding others' perspectives. But can a computer decode sarcasm? Absolutely! Training a machine learning model to discern sarcastic sentences is indeed possible. Curious to explore how? Dive into this article to unravel the art of Sarcasm Detection using Machine Learning and Python.

## Installation Requirements

Ensure you have the necessary libraries installed:
```bash
pip install numpy seaborn pandas plotly statsmodels matplotlib scikit-learn
```

## Dataset Overview

The provided dataset includes headlines with binary labels denoting sarcasm. Columns include `article_link`, `headline`, and `is_sarcastic`, where 1 signifies sarcasm and 0 denotes non-sarcastic headlines.

## Preparing the Data

The process involves preparing features and labels using CountVectorizer and splitting the data into training and test sets.

## Building the Model

A Bernoulli Naive Bayes algorithm is employed to train the model for sarcasm detection, achieving an accuracy score of 84.48%.

## Model Testing

A sample sarcastic text is inputted into the trained model, demonstrating its ability to detect sarcasm accurately.

## Conclusion

This project showcases how machine learning techniques, implemented using Python, can discern sarcasm in text. Sarcasm, an integral part of language, is deciphered through the lens of technology, offering a fascinating insight into NLP applications. If you're curious about sarcasm detection using machine learning, this article serves as an excellent guide.
