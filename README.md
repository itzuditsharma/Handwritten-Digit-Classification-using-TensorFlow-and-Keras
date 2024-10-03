# Handwritten-Digit-Classification-using-TensorFlow-and-Keras
This project implements a handwritten digit classification model using the MNIST dataset. The model is built using TensorFlow and Keras, and it achieves digit classification through a simple neural network architecture. The MNIST dataset consists of 28x28 grayscale images of handwritten digits, labeled from 0 to 9.


# Features
- **Preprocessing:** The images are scaled and reshaped to be suitable for the neural network.
  
- **Model Architecture:** A sequential model is constructed with three layers:
  
  - A Flatten layer to convert the 28x28 image into a 1D vector.
  - Two Dense layers with 50 neurons each, activated by ReLU.
  - An output Dense layer with 10 neurons, activated by sigmoid for multi-class classification.
    
- **Training and Evaluation:** The model is trained for 10 epochs using the Adam optimizer and sparse categorical crossentropy loss. Accuracy is used as a performance metric.
- **Confusion Matrix Visualization:** After testing, a confusion matrix is generated using Seaborn to visualize model performance across the 10 classes.
- **Real-time Prediction:** The model can predict digits from custom image inputs by preprocessing and reshaping them to match the input format.
  
# Dataset
- The MNIST dataset contains 60,000 training images and 10,000 test images.
- The dataset is pre-loaded with Keras, so no manual download is required.

# Libraries Used
- Numpy for numerical operations.
- Matplotlib and Seaborn for plotting and visualizing the confusion matrix.
- OpenCV for image preprocessing (reading, resizing, and converting images to grayscale).
- TensorFlow/Keras for constructing and training the neural network model.

# Output: 
![image](https://github.com/user-attachments/assets/02e7c6bf-a38b-4d85-8a27-b3dd2b1e6b95)
