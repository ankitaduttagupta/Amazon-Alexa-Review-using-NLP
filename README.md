# ANALYSIS OF AMAZON ALEXA REVIEW USING NLP TECHNIQUE

About the dataset:

- contains  customer rating(scale of 1 to 5), verified textual reviews , variation of product(16 variations) and feedback (1 or 0)
- Performed some EDA on the data to understand the trends between product variant with its rating and feedback
- Textual pre-processing of the Reviews using NLTK and visualisation using **WordCloud** .

- Predicted the feedback rating on test data , model used: **Random Forest Classifier**
  test measures used: precision and accuracy scores.
- Improved precision of model by **SMOTE technique for class imbalance treatment.**

-  Performed Sentiment analysis for all reviews ( polarity and subjectivity).
