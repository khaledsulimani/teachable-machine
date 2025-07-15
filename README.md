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

project-folder/
├── model/           # Contains the trained model files (e.g. .h5 or model.json + weights)
├── main.py          # Python script to run the model
└── README.md        # Project documentation

## 🚀 How to Run

1. Export your model from Teachable Machine in **Keras (.h5)** format and place it in the `model/` folder.
2. Install dependencies:
   ```bash
   pip install tensorflow opencv-python
