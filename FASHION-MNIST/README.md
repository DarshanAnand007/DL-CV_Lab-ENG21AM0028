CNN Performance Analysis on Fashion MNIST Dataset
Overview
This repository contains code for analyzing the performance of a Convolutional Neural Network (CNN) on the Fashion MNIST dataset. The code is implemented in Python using TensorFlow/Keras, a popular deep learning library.

Key Components
CNN Model: The CNN model is constructed using TensorFlow/Keras. It consists of two convolutional layers followed by max-pooling layers, a flattening layer, and fully connected layers.

Data Preprocessing: The dataset, Fashion MNIST, is loaded and preprocessed. Pixel values are normalized to the range [0, 1].

Training: The model is trained on the training set using the Adam optimizer and sparse categorical cross-entropy loss function.

Evaluation: The trained model's performance is evaluated on the test set, and accuracy metrics are calculated.
![Screenshot 2024-03-28 143341](https://github.com/DarshanAnand007/DL-CV_Lab-ENG21AM0028/assets/93935699/f1fb7f8c-cdbe-4033-ae09-ba8fac8fb5a6)


Visualization: The training history (accuracy and loss) is visualized using matplotlib. Additionally, predictions are made on test images, and one example prediction is displayed.

Instructions
Dependencies
Python 3.x
TensorFlow
Keras
NumPy
Matplotlib
Running the Code
Clone this repository to your local machine:

bash
Copy code
git clone <repository_url>
Navigate to the repository directory:

bash
Copy code
cd <repository_directory>
Run the Python script:

bash
Copy code
python cnn_fashion_mnist.py
Monitor the training progress and view the evaluation results.

Results
After running the code, you will observe:
![shoe](https://github.com/DarshanAnand007/DL-CV_Lab-ENG21AM0028/assets/93935699/5c0665bb-977d-4c7b-ba17-334b5fa74a83)

![Uploading Screenshot 2024-03-28 143209.png…]()
![pullover](https://github.com/DarshanAnand007/DL-CV_Lab-ENG21AM0028/assets/93935699/05469efb-1014-4464-ab48-bbd99d6ec88f)

![Screenshot 2024-03-28 143226](https://github.com/DarshanAnand007/DL-CV_Lab-ENG21AM0028/assets/93935699/70139179-93cf-4968-a58c-cc42c25991c0)


Training progress displayed in the console, including accuracy and loss metrics.
Evaluation results on the test set, including accuracy.
Visualization of training history (accuracy and loss) using matplotlib.
Display of one example prediction with the corresponding true label and predicted label.
Further Customization
You can customize the CNN model architecture and hyperparameters to experiment with different configurations. Additionally, you can explore other performance metrics and visualization techniques to gain further insights into the model's behavior.

References
Fashion MNIST Dataset - https://www.kaggle.com/datasets/zalando-research/fashionmnist/data
