# Binary Classification with Neural Network

This project demonstrates binary classification using a neural network model built with TensorFlow and Keras. It incorporates **Batch Normalization** and **L2 Regularization** to mitigate overfitting.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Model Architecture](#model-architecture)
- [Performance](#performance)
- [How to Run](#how-to-run)
- [Known Issues](#known-issues)
- [Future Enhancements](#future-enhancements)

---

## Introduction

The goal of this project is to build and evaluate a binary classification model using a dataset with 10 numerical features and a binary target. The model uses techniques like **Batch Normalization** and **L2 Regularization** to stabilize training and prevent overfitting.

---

## Dataset

The dataset contains 3000 rows with the following:
- **Features:** 10 numerical features (e.g., `feature_1`, `feature_2`, ..., `feature_10`)
- **Target:** A binary target variable (`0` or `1`)

---

## Dependencies

Install the required Python libraries before running the project:

```bash
pip install pandas scikit-learn tensorflow
