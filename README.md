
Language Identification in South African Texts
This Python notebook aims to develop a language classification model capable of identifying one of the 11 official languages of South Africa present in a given text. The dataset consists of texts labeled with their respective language IDs.

Overview
Contents:
Introduction: Overview of the project and its objectives.
Exploratory Data Analysis (EDA): Understanding the dataset's structure and initial insights.
Preprocessing: Cleaning and preparing the textual data for model training.
Vectorization: Transforming text data into numerical form for model compatibility.
Modeling: Training various machine learning models to identify languages.
Findings: Observations on model performance, including training time, prediction time, and accuracy.
Saving the Model: Code snippet to save the best-performing model for future use.
Recommendations and Conclusion: Insights on model deployment and further improvements.
Key Points
Data Exploration: The dataset contains equal observations for each language, totaling 33,000 in the training set and 5,682 in the test set.
Preprocessing: Textual data undergoes tokenization, stop words removal, and stemming to enhance uniformity.
Modeling: Multiple classifiers are trained, evaluated, and compared based on training time, prediction time, and accuracy.
Best Model: Multinomial Naive Bayes performed exceptionally well in terms of accuracy and computational speed.
Recommendations: Considerations for optimizing prediction speed, further analysis for model enhancement, and potential deployment scenarios.
This notebook provides an outline for training and evaluating language identification models. One of the best performing models, SVC, is saved for future use.
