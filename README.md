# Handwritten Digit Recognition using CNN

This project is a Handwritten Digit Recognition system using Convolutional Neural Networks (CNNs), trained on the MNIST dataset. It includes a Streamlit web application that allows users to draw digits and get real-time predictions using a trained deep learning model.

Features
✅ CNN-based digit recognition trained on the MNIST dataset
✅ Interactive web app built using Streamlit
✅ Drawing canvas for users to input handwritten digits
✅ Real-time prediction with a pre-trained model
✅ Model saving & loading for deployment

Project Structure
train_mnist.py: Contains the CNN model architecture and training script
app.py: Streamlit application script
mnist_cnn_model.h5: Pre-trained model saved in HDF5 format
requirements.txt: List of dependencies
Dataset
The model is trained on the MNIST dataset, which consists of 60,000 training and 10,000 test grayscale images of handwritten digits (0-9), each of size 28x28 pixels.
## Requirements
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

## How to Run
1. Download saved model and app.py  in Google Colab to same folder:
   - open cmd navigat ti that foler (cd %UserProfile%\Desktop\HR).
   
   - Run thi code in cmd (streamlit run app.py)
2. Alternatively, install dependencies and run locally:
   ```bash
   pip install -r requirements.txt
   jupyter notebook
