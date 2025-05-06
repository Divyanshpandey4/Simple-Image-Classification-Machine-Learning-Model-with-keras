# 🧠 Handwritten Digit Recognition with CNN

This project demonstrates a simple yet effective Convolutional Neural Network (CNN) model built using TensorFlow/Keras to recognize handwritten digits from the MNIST dataset. The model is trained to classify grayscale images (28x28 pixels) of digits (0 through 9) with high accuracy.



## 📁 Project Structure


## 🧰 Technologies Used

- Python 3.x
- Jupyter Notebook
- TensorFlow & Keras
- NumPy
- Matplotlib

## 📊 Dataset

The [MNIST dataset](http://yann.lecun.com/exdb/mnist/) consists of 70,000 grayscale images of handwritten digits (60,000 for training and 10,000 for testing). Each image is 28x28 pixels.

## 🧪 How It Works

1. **Data Loading**  
   Loads the MNIST dataset using TensorFlow's built-in dataset loader.

2. **Preprocessing**  
   - Normalizes pixel values between 0 and 1.
   - Reshapes the data for compatibility with the CNN.

3. **Model Building**  
   Constructs a simple CNN with:
   - 2 Convolutional layers
   - MaxPooling
   - Flatten + Dense layers
   - Output layer with `softmax` activation

4. **Training**  
   - Model is compiled with Adam optimizer and categorical crossentropy loss.
   - Trained over a few epochs with validation data.

5. **Prediction**  
   - Predicts single digits using reshaped input images.
   - Displays the digit image alongside the predicted class.

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/imageclassification.git
   cd imageclassification
