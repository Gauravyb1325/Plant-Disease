🌿 Plant Disease Detection Using Leaf Images
📋 Project Overview
This project focuses on detecting plant diseases by analyzing images of plant leaves. Using a Convolutional Neural Network (CNN), the model is trained to classify whether a plant leaf is healthy or diseased.
The model achieves an accuracy of 88% on the test set.

🛠️ Technologies Used
Python

TensorFlow / Keras (for building CNN)

NumPy, Pandas (for data handling)

Matplotlib, Seaborn (for visualization)

OpenCV (for image processing)

📈 Model Summary
Model Type: Convolutional Neural Network (CNN)

Accuracy Achieved: 88%

Loss Function: categorical_crossentropy

Optimizer: Adam

Evaluation Metrics: Accuracy

🖼️ Result
Here is an image showing the model's accuracy and loss over the epochs:

Example:

![Screenshot 2025-04-18 224112](https://github.com/user-attachments/assets/5bcb02f6-f19e-42c7-a8bd-c9c606d77797)

![Screenshot 2025-04-18 224125](https://github.com/user-attachments/assets/b3e0a7b0-8587-4397-90b0-65c84b171ae5)

![Screenshot 2025-04-18 224144](https://github.com/user-attachments/assets/2b5c4651-a349-4ac3-acdc-fd682f0bbf13)



🧠 How It Works
Load and preprocess the leaf images.

Train a CNN model on the preprocessed data.

Evaluate the model performance on the test set.

Predict plant health based on new input images.
