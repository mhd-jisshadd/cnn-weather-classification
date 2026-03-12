# Weather Image Classification Using Deep Learning (CNN)

## 1. Project Description

The Weather Image Classification System is a deep learning-based project designed to classify weather conditions from images. The system uses a Convolutional Neural Network (CNN) model to identify different types of weather such as cloudy, rain, shine, and sunrise.

The model is trained on a labeled dataset of weather images. After training, the CNN model can analyze new images and predict the corresponding weather category.

This project demonstrates how deep learning can be used for image recognition and classification tasks using convolutional neural networks.

---

## 2. Features

- Weather image classification using deep learning
- Convolutional Neural Network (CNN) model
- Classification of weather conditions:
  - Cloudy
  - Rain
  - Shine
  - Sunrise
- Image preprocessing and resizing
- Model training and evaluation
- Prediction on new images

---

## 3. Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Deep Learning (CNN)

---

## 4. Dataset

The dataset used in this project is the Weather Image Dataset available on Kaggle.

Dataset link:
https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset

The dataset contains images grouped into four weather categories:

- Cloudy
- Rain
- Shine
- Sunrise

Dataset Structure:

dataset/

│
├── Cloudy/  
├── Rain/  
├── Shine/  
└── Sunrise/  

All images were resized and preprocessed before training the CNN model.

---

## 5. Project Structure

Weather-Image-Classification/

│
├── dataset/
│   ├── Cloudy/
│   ├── Rain/
│   ├── Shine/
│   └── Sunrise/
│
├── CNN_WEATHER_CLASSIFICATION.ipynb
├── weather_model.h5
├── outputs/
│   └── prediction_result.png
│
├── requirements.txt
└── README.md

---

## 6. Installation

1. Clone the repository

git clone https://github.com/mhd-jisshadd/weather-image-classification.git

2. Navigate to the project folder

cd weather-image-classification

3. Install the required dependencies

pip install -r requirements.txt

---

## 7. How to Run

Open Jupyter Notebook:

jupyter notebook

Then open:

CNN_WEATHER_CLASSIFICATION.ipynb

Run all cells to train the CNN model and test predictions.

---

## 8. Output

The trained CNN model predicts the weather condition from an input image.

Possible predictions:

- Cloudy
- Rain
- Shine
- Sunrise

The prediction result will be displayed after processing the input image.

---

## 9. Future Improvements

- Improve model accuracy using transfer learning
- Add more weather categories
- Deploy the model as a web application
- Implement real-time weather detection
- Optimize the model for mobile applications

---

## Author

Jishad  
AI / Machine Learning Enthusiast
