# Training-an-AI-Image-Classifier🖼️

## 💡the Idea
This project demonstrates an image classification system using a pre-trained Keras deep learning model. The model is designed to recognize an input image and classify it into one of three categories: **Humans**, **Animals**, or **Objects**. After analyzing the image, the model predicts the most suitable category and provides a confidence score that indicates how certain it is about the prediction.

---

## 1. Uploading the Image
The image is uploaded to Google Colab and prepared before being processed by the model. During preprocessing, the image undergoes the following steps:
* Converted to RGB format.
* Normalized to match the input format used during model training.
* 
The processed image is then passed to the trained Keras model for classification.

---

## 3: Results

**Prediction Output:**

> **Class:** Object  
> **Confidence Score:** `0.99968755`

The model successfully classified the uploaded image as an **Object** with a confidence score of approximately **99.97%**, indicating a highly accurate prediction.

---

## 💻 Step 4: Google Colab Code Explanation
The code in Google Colab performs the following operations:
1. Loads the trained Keras model (`keras_model.h5`) and the class labels from `labels.txt`.
2. Reads the uploaded image.
3. Resizes, normalizes, and converts the image into the required format.
4. Passes the preprocessed image to the model using the `predict()` function.
5. Displays the predicted class and its confidence score, allowing the user to evaluate the classification result.
