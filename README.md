# Brain-Tumor-Detection-Using-CNN
This project aims to develop an accurate and efficient system for detecting brain tumors using Convolutional Neural Networks (CNN). Utilizing deep learning techniques, the model is trained on a dataset of brain MRI images, which are categorized into two classes: healthy and tumor. The goal is to enable quick and reliable detection of brain tumors.

# Dataset
The dataset used in this project is organized into two main directories:

Training
Contains images for training the model, with subdirectories for each class (Healthy and Tumor).
Validation
Contains images for validating the model performance, with the same subdirectory structure.
Dataset Structure
brain_tumor_dataset/ │ ├── training/ │ ├── healthy/ │ └── tumor/ │ └── validation/ ├── healthy/ └── tumor/

# Inastallation
To run this project, you need to have Python and the following libraries installed:

TensorFlow,
Keras,
NumPy,
Matplotlib

You can install the required libraries using pip:

pip install tensorflow numpy matplotlib Usage Clone the repository:

Run the training process to train the CNN model using the training dataset.

After training, you can use the model to make predictions on new MRI images.

To predict, upload a random image from the validation set or provide your own image. The model will classify it as either Tumor Detected or No Tumor Detected.

Example Prediction The model provides the following output for predictions:

Prediction: Tumor Detected - If the model predicts a tumor in the MRI scan. Prediction: No Tumor Detected - If the model predicts the absence of a tumor. Results The performance of the model can be evaluated using metrics such as accuracy, loss, and confusion matrix. You can visualize the training history to analyze the model's performance over epochs.

