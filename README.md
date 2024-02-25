# Language-Detection-Model-
The language detection model begins with the preprocessing of text data, aiming to enhance the quality of the dataset for subsequent machine learning tasks. This preprocessing involves the removal of special characters, symbols, numbers, URLs, mentions, and extra whitespaces. The text is also converted to lowercase to ensure uniformity.

A new column called 'cleaned_Text' is added to the DataFrame, containing the preprocessed text. This step is crucial for creating a reliable feature set for language detection.

Next, label encoding is applied to convert the categorical labels in the 'Language' column into numerical values. This step is essential for training machine learning models, as algorithms typically require numerical input.

Several machine learning models, including K-Nearest Neighbors (KNN), Random Forest, and Multinomial Naive Bayes (MNB), are trained on the preprocessed data. The accuracy of each model is evaluated, and metrics such as confusion matrices are used to assess their performance.

The Multinomial Naive Bayes model emerges as the most accurate among the models tested. It is then selected as the final language detection model, showcasing the highest accuracy. The final model is capable of predicting the language of a given text with high reliability, making it suitable for language identification tasks.
