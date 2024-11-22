# sms_spam_detector
This notebook demonstrates an SMS classification task to distinguish between spam and non-spam (ham) messages. Here's a summary of its key components:

Libraries Imported:

Data processing: pandas.
Machine learning: scikit-learn for train-test splitting, TF-IDF vectorization, and LinearSVC for classification.
Frontend: Gradio for creating an interactive interface.
Dataset:

The dataset is loaded from a CSV file (Resources/SMSSpamCollection.csv) into a pandas DataFrame with columns label (spam or ham) and text_message (SMS content).
Model Training:

A pipeline is created using TF-IDF vectorization for text transformation and Linear Support Vector Classification (LinearSVC) for predicting labels.
The data is split into training and testing sets (33% test size).
The model is trained on the training data and saved for future predictions.
Prediction Function:

A function (sms_prediction) takes an SMS message as input and predicts whether it is spam or ham using the trained model.
The output indicates whether the message is classified as spam or not.
Interactive Gradio Interface (presumably later):

The notebook likely ends by creating an interface to allow users to input SMS messages and see the classification results interactively.
Let me know if you'd like further details or an exploration of specific sections!