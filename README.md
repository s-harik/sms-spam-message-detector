SMS Spam Message Detector

A machine learning project that classifies SMS messages as spam or legitimate using TF-IDF and Multinomial Naive Bayes.
Technologies Used

* Python
* Pandas
* Scikit-learn
* TF-IDF Vectorization
* Multinomial Naive Bayes
* Google Colab
  
Dataset

The project uses the UCI SMS Spam Collection dataset, containing 5,574 labeled SMS messages.
Dataset: https://archive.ics.uci.edu/dataset/228/sms+spam+collection
Workflow
1. Loaded and explored the dataset.
2. Converted message labels into numerical values.
3. Split the dataset into training and testing sets.
4. Converted text messages into numerical features using TF-IDF.
5. Trained a Multinomial Naive Bayes classifier.
6. Evaluated the model using accuracy, precision, recall, and F1-score.
7. Tested the model on a new SMS message.
 Results
* Accuracy: 96.68%
* Spam Precision: 100%
* Spam Recall: 75.17%
* Spam F1-score: 85.82%

How to Run
Open `sms_spam_detector.ipynb` in Google Colab and run the cells in order.

Limitations
The model may misclassify messages and cannot guarantee that a message is safe.
