# Training-an-AI-Image-Classifier🖼️

## 💡the Idea
This project demonstrates an image classification system using a pre-trained Keras deep learning model. The model is designed to recognize an input image and classify it into one of three categories: **Humans**, **Animals**, or **Objects**. After analyzing the image, the model predicts the most suitable category and provides a confidence score that indicates how certain it is about the prediction.

---

## 1. Uploading the Image
The input image is loaded into the (Teachable Machine) and prepared before being processed by the model. The preprocessing steps include:

*Format Conversion: Converted to RGB format.

*Normalization: Normalized to match the input format used during model training.

The processed image is then passed directly to the trained Keras model for classification.

---

## 3. Results(Teachable Machine)
![image alt](https://github.com/jumanah2004/Training-an-AI-Image-Classifier/blob/65a922bfddc51a7d0871ff2d0f41b95ff6ed8c1d/Training-Al..png.jpeg)

---

## 4. Google Colab Code Explanation
The code in Google Colab performs the following operations:
1. Loads the trained Keras model (`keras_model.h5`) and the class labels from `labels.txt`.
2. Reads the uploaded image.
3. Resizes, normalizes, and converts the image into the required format.
4. Passes the preprocessed image to the model using the `predict()` function.
5. Displays the predicted class and its confidence score, allowing the user to evaluate the classification result.
   
---

## 3. Results( Google Colab)
