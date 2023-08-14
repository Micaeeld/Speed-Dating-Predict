##### Use https://nbviewer.org to upload the file in case of errors
---

# Dating compatibility prediction

This notebook contains exploratory data analysis and a predictive model to predict compatibility between two people on a romantic date. The data was taken from the "Speed Dating" dataset available on Kaggle, which contains information about participants in speed dating events, as well as each couple's mutual estimates.

The goal of this project is to build a predictive model that can predict whether two individuals will be compatible based on their responses to a dialogue and their mutual estimates.

## Data set
The dataset contains information about 8378 participants of speed dating events, including their demographic characteristics, their personal interests and emotions, as well as their mutual estimates of other participants. The dataset is divided into two parts: a dataset with information about participants and a dataset with information about mutual estimates.

## Exploratory data analysis
An exploratory data analysis was performed to better understand participant characteristics and identify patterns and trends in the data. Some of the questions that were explored during the analysis include:

What are the demographic characteristics of the participants?
What are the interests and personal stimuli of the participants?
What is the distribution of mutual estimates among the participants?
Is there any psychology between participant characteristics and compatibility between couples?

## Data preparation
Before creating the predictive model, the data was pre-processed and prepared for training. Some of the data preparation steps include:

- Cleaning of missing data and outliers
- Coding of categorical features
- Selection of features relevant to the model
- Predictive model
To predict compatibility between participants, a binary classification model was trained using the GradientBoostingClassifier algorithm. The dataset was split into a training set and a test set to assess the model's accuracy.

Several model evaluation techniques such as the confusion matrix, the ROC curve and the F1 evaluation were used to evaluate the performance of the model against the test data.

## Conclusion
This notebook featured exploratory data analysis and a predictive model to predict compatibility between participants in speed dating events. The model was trained on a dataset of over 8000 participants and achieved reasonable accuracy in predicting compatibility between couples.
While there are many factors that go into satisfying compatibility between couples, this model can be useful as a preliminary tool to help screen potential compatible matches at speed dating events or other similar situations.

## Contribution
Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue in the repository or submit a pull request.
a pull request.
