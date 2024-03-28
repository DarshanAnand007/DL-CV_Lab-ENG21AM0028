Experiment 3: Text Classification using LSTM model
Overview
In this experiment, we perform text classification using a Long Short-Term Memory (LSTM) neural network model. The goal is to classify text data into two categories: spam or ham (non-spam). We utilize the IMDB movie review dataset as a sample dataset for this experiment.

Code Description
The code consists of the following components:

Data Loading and Preprocessing: The dataset (spam.csv) is loaded using pandas. Text preprocessing steps such as tokenization, padding, and label encoding are performed.
Model Architecture: An LSTM model is constructed using Keras with TensorFlow backend. The model consists of embedding, LSTM, and dense layers with dropout for regularization.
Model Training: The model is compiled with appropriate loss function and optimizer. It is trained on the training data with a validation split of 20% for a specified number of epochs.
Model Evaluation: The trained model is evaluated on the test dataset to measure its performance in terms of loss and accuracy.
Visualization: Training history (accuracy and loss over epochs) and a confusion matrix are generated for visual analysis of model performance.
Requirements
pandas
numpy
matplotlib
seaborn
scikit-learn
TensorFlow
Keras
Usage
Ensure all dependencies are installed (pip install -r requirements.txt).
Download the dataset (spam.csv) and place it in the project directory.
Execute the provided Python script (text_classification_lstm.py).
View the generated visualizations and model evaluation metrics.

![Screenshot 2024-03-28 151641](https://github.com/DarshanAnand007/DL-CV_Lab-ENG21AM0028/assets/93935699/1195457c-04bc-4b31-a0c0-3d24d8e2110e)

Results
![Screenshot 2024-03-28 151657](https://github.com/DarshanAnand007/DL-CV_Lab-ENG21AM0028/assets/93935699/f1fb6df7-a7f4-4140-ae08-ab5b82191c2a)

The LSTM model achieves a test accuracy of X.XX% on the IMDB movie review dataset.
![Screenshot 2024-03-28 151724](https://github.com/DarshanAnand007/DL-CV_Lab-ENG21AM0028/assets/93935699/d8d689e7-c3c2-4cbd-8486-55b40053a824)

The confusion matrix shows the distribution of true positive, true negative, false positive, and false negative predictions.

Conclusion
The LSTM model demonstrates promising performance in classifying text data into spam and ham categories. Further experimentation and fine-tuning may be necessary to improve model accuracy and generalization.

This README report provides an overview of the experiment, describes the code components, outlines requirements and usage instructions, presents results, and concludes with insights and potential areas for further exploration. Adjustments can be made to tailor the report to specific needs or preferences.
