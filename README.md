# Spam-Email-Classification-using-Semi-Supervised-Learning

## Project Overview
This project aims to classify emails as spam or not spam using semi-supervised learning techniques. Semi-supervised learning is particularly useful for this task as it leverages both labeled and unlabeled data, making it ideal for scenarios where labeled data is scarce.

## Dataset Description
The dataset used in this project contains emails with labels indicating whether they are spam or not. 

## Features
The dataset consists of various features extracted from the email content, such as:<br/>
Textual features: Word frequency, presence of certain keywords, etc.

## Semi-Supervised Learning Approach
### Methodology
1. Data Preprocessing: Clean and preprocess the email text, extract relevant features, and split the data into labeled and unlabeled sets.
2. Initial Model Training: Train a classifier using the labeled data.
3. Label Propagation: Use the initial model to predict labels for the unlabeled data.
4. Refinement: Combine the original labeled data with the newly labeled data and retrain the model.
5. Evaluation: Evaluate the model's performance using appropriate metrics.

### Algorithms Used
Initial Classifier: Logistic Regression, Random Forest, or any other suitable classifier.
Label Propagation Techniques: Self-training, co-training, or other semi-supervised learning algorithms.
