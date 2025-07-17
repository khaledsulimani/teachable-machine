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
    ```
## 📸 Project Results

Here are some real-world shots of the project in action:

📷 Photo 1 –![صورة واتساب بتاريخ 1447-01-20 في 13 04 26_786381e3](https://github.com/user-attachments/assets/29f8a63b-d1ec-4b2a-91cd-d035ef787319)
📷 Photo 2 –![صورة واتساب بتاريخ 1447-01-20 في 13 09 16_aec70239](https://github.com/user-attachments/assets/278bc405-96d2-4a20-89dc-4311c4017397)

## 🧑‍💻 Author

- **khaled mahmoud sulaimani** – [@khaledsulimani](https://github.com/khaledsulimani)
