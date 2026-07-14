# Gaussian Naive Bayes vs Bernoulli Naive Bayes on Iris Dataset

## Overview

This project compares the performance of **Gaussian Naive Bayes** and **Bernoulli Naive Bayes** classifiers using the famous **Iris dataset** from Scikit-learn. The models are trained and evaluated using training and testing accuracy to determine which algorithm performs better on continuous-valued data.

## Dataset

- Dataset: Iris Dataset
- Source: Scikit-learn
- Number of Samples: 150
- Number of Features: 4
- Number of Classes: 3

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Technologies Used

- Python
- Pandas
- Scikit-learn

## Libraries

```python
pandas
scikit-learn
```

## Algorithms Used

### Gaussian Naive Bayes
- Suitable for continuous numerical data.
- Assumes features follow a Gaussian (Normal) distribution.

### Bernoulli Naive Bayes
- Suitable for binary (0/1) features.
- Continuous features are converted into binary values using a threshold before training.

## Workflow

1. Load the Iris dataset.
2. Split the dataset into training and testing sets.
3. Train a Gaussian Naive Bayes classifier.
4. Evaluate training and testing accuracy.
5. Convert numerical features into binary values using `Binarizer`.
6. Train a Bernoulli Naive Bayes classifier.
7. Compare the performance of both models.

## Results

| Model | Training Accuracy | Testing Accuracy |
|--------|------------------:|-----------------:|
| Gaussian Naive Bayes | 94.3% | 97.8% |
| Bernoulli Naive Bayes | 64.8% | 71.1% |

## Conclusion

Gaussian Naive Bayes performs significantly better than Bernoulli Naive Bayes on the Iris dataset because the dataset contains continuous numerical features. Bernoulli Naive Bayes is designed for binary data, and converting continuous values into binary causes information loss, reducing classification accuracy.

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/repository-name.git
```

2. Install the required libraries.

```bash
pip install pandas scikit-learn
```

3. Run the Python file.

```bash
python filename.py
```

## Learning Outcomes

- Understanding the Naive Bayes algorithm.
- Difference between Gaussian and Bernoulli Naive Bayes.
- Data preprocessing using Binarizer.
- Model evaluation using training and testing accuracy.
- Choosing the appropriate classifier based on data type.

## Author

Mohammad Uruj Faizan
