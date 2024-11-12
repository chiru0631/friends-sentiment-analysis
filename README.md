# friends-sentiment-analysis
This project aims to perform sentiment analysis on dialogues from the popular TV show Friends. The goal is to classify each utterance as either positive, negative, or neutral sentiment.

# Approach

## The main steps in this project are:

Data Preprocessing: Load the training and testing datasets, and create video file paths for each utterance.

Feature Extraction: Extract text-based features using TF-IDF and video-based features by processing the video clips.

Model Training: Combine the text and video features, and train a RandomForestClassifier model on the training data.

Model Evaluation: Evaluate the model's performance on the validation set and report classification metrics.

Inference on Test Data: Generate predictions for the test set, create a submission CSV file, and save it.
