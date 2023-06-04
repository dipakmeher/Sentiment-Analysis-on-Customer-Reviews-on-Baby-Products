# Sentiment-Analysis-on-Customer-Reviews-on-Baby-Products

I am thrilled to share that I successfully implemented sentiment analysis on a dataset of 18,506 customer reviews for baby products. My goal was to predict sentiment using a logistic regression classifier, with positive sentiment represented by a review rating of +1 and negative sentiment represented by a review rating of -1.

To ensure accurate predictions, I utilized various preprocessing techniques. This involved removing irrelevant words such as stop words, punctuation, and HTML tags using the NLTK and re libraries. Additionally, I applied stemming to reduce words to their base form, thereby ensuring consistency and enhancing the sentiment analysis algorithm's ability to extract relevant information.

Next, I explored different methods for converting the textual data into numerical representations. I experimented with bag of words, n-grams, and TF-IDF weighting to capture the essence of the reviews. Three models were implemented, and after careful evaluation, I selected Model_2, which combined bag of words and bigram, as it achieved an impressive accuracy of 87%.

To assess the accuracy of the chosen model, I split the training data into a 80:20 ratio for training and testing, respectively. By leveraging the CountVectorizer from the scikit-learn library, I transformed the data into a numerical representation, allowing for seamless integration with the logistic regression classifier. The model achieved an accuracy of 87% on the test data, as evidenced by the confusion matrix and classification report.

Buoyed by these results, I decided to train the Model_2 on the entire training dataset of 18,506 records. Subsequently, I applied the same preprocessing steps to the test data, ensuring consistency in the analysis. The sentiment predictions for the test data were stored in a file and uploaded for evaluation, yielding an impressive accuracy of 88%!

This project not only allowed me to deepen my understanding of sentiment analysis and logistic regression but also honed my skills in data preprocessing and model evaluation. I am proud to have accomplished these results and eagerly look forward to applying my newfound expertise to future projects.
