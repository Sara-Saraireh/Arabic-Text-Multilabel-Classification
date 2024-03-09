# Arabic-Text-Multilabel-Classification

This repository contains code for a multilabel classification system designed to classify Arabic text documents into multiple categories simultaneously. The system utilizes machine learning algorithms and natural language processing (NLP) techniques to analyze Arabic text and predict the relevant categories.

Features:
Multilabel Classification: The system is capable of assigning multiple labels to each text document, allowing for nuanced categorization.
TF-IDF Vectorization: Text data is transformed into numerical feature vectors using the Term Frequency-Inverse Document Frequency (TF-IDF) technique, capturing important information about word occurrences and frequencies.
Machine Learning Models: Various classifiers including SGDClassifier, LogisticRegression, and LinearSVC are trained and evaluated using the One-vs-Rest strategy to handle multilabel classification tasks.
Evaluation Metrics: The system evaluates model performance using Jaccard score and generates a classification report to assess precision, recall, and F1-score for each label.
Usage:
Clone the repository to your local machine.
Ensure you have the necessary dependencies installed (Pandas, NumPy, scikit-learn).
Prepare your Arabic text dataset in an Excel file format.
Run the provided notebook or Python script to preprocess the data, train the models, and evaluate performance.
Explore the classification results and fine-tune the system as needed for your specific application.
Contributions:
Contributions to improve model performance, add new features, or enhance code quality are welcome. Please submit pull requests or open issues for any suggestions, bug fixes, or enhancements.

License:
This project is licensed under the MIT License - see the LICENSE file for details.

