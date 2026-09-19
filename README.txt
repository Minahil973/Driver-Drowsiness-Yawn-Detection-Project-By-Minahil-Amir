# Driver Drowsiness & Yawn Detection System

The **Driver Drowsiness & Yawn Detection System** is an AI-based computer vision project designed to identify visual signs of driver fatigue using facial features captured through a webcam.

A custom **Convolutional Neural Network (CNN)** is trained to classify images into four categories: **Open, Closed, Yawn, and No Yawn**. OpenCV is used for facial and eye-region detection, while Gradio provides an interactive web interface for webcam-based predictions.

## Key Features

* Eye state classification using a trained CNN
* Yawn and no-yawn classification
* Webcam-based facial monitoring
* Drowsiness status detection based on eye closure
* Prediction confidence display
* Interactive browser-based interface using Gradio

## Dataset

The model is trained on the Drowsiness / Yawn Detection Dataset available on Kaggle. It contains images categorized into four main classes: **Open**, **Closed**, **Yawn**, and **No Yawn**.

* 🔗 **Kaggle Dataset:** (https://www.kaggle.com/datasets/serenaraju/yawn-eye-dataset-new)

## Demo & Deployment

The interactive web interface is built using **Gradio**, allowing real-time prediction through a webcam feed.

* 🚀 **Live Demo:** (https://1598f5b6e6f261368b.gradio.live)

## Technologies Used

* Python
* TensorFlow / Keras
* Convolutional Neural Network (CNN)
* OpenCV
* NumPy
* Scikit-learn
* Gradio
* Google Colab

## Project Workflow

1. The webcam captures the driver's facial image.
2. OpenCV detects and crops the relevant facial region.
3. The trained CNN processes the image to generate a prediction and confidence score.
4. The system displays the detected state and alerts if potential drowsiness is detected.

