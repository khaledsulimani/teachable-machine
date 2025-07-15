# teachable-machine
# 🍌🍅🥒 AI Fruit & Vegetable Classifier

This is a simple AI project built using [Teachable Machine](https://teachablemachine.withgoogle.com/) by Google.  
The model was trained to classify **banana**, **tomato**, and **cucumber** using image data.

## 🔧 Technologies Used

- **Teachable Machine** – for training the image classification model  
- **Python** – to run the model  
- **TensorFlow / Keras** – to load and use the trained model  
- **OpenCV** (optional) – for camera input and image handling

## 📁 Project Structure

```plaintext
project/
│
├── model/
│   ├── keras_model.h5        # Trained AI model exported from Teachable Machine
│
├── from_keras.py             # Python code to load and run the model
├── label.txt                 # Text file containing labels (e.g., banana, tomato, etc.)
├── single_banana.jpg         # Example input image of a banana
└── README.md                 # This documentation file
```

## 🚀 How to Run

1. Export your model from Teachable Machine in **Keras (.h5)** format and place it in the `model/` folder.
2. Install dependencies:
   ```bash
   pip install tensorflow opencv-python
