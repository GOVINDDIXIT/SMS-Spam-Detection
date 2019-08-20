# SMS Spam Detection

Author: [Govind Dixit](https://github.com/GOVINDDIXIT)

*Federated Learning is a machine learning setting where the goal is to train a high-quality centralized model with training data distributed over a large number of clients each with unreliable and relatively slow network connections.*

*In this project I have used Federated Learning with the PyTorch extension of PySyft for a classification task with a simple 1-layer GRU.* 

**Dataset:**
[Link](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)

**Dataset Description:**
The data used for this project was the SMS Spam Collection Data Set available on the UCI Machine Learning Repository. The dataset consists of 5500 SMS messages, of which around 13% are spam messages.

*The objective here is to simulate two remote machines (that we will call Bob and Anne), where each machine have a similar number of labeled data points (SMS labeled as spam or not).*
