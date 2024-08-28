# Potato Disease Classifier Using CNN

# Project Overview
Potato farming is crucial for food production worldwide, but it is also vulnerable to various diseases that can devastate crops and cause significant economic losses for farmers. Two of the most common and destructive potato diseases are Early Blight and Late Blight. Early detection of these diseases is essential for applying timely treatments, reducing crop waste, and ensuring better yields.

This project aims to develop a deep learning model using Convolutional Neural Networks (CNN) to accurately classify potato leaf diseases. By leveraging this model, farmers can quickly identify signs of Early Blight or Late Blight and take necessary actions to protect their crops.

# Dataset
The project uses the Plant Village dataset, specifically the subset of images related to potato leaf diseases. This dataset contains labeled images of healthy and diseased potato leaves, which were used to train and validate the CNN model.

# How It Works
1. Data Preprocessing: Images from the dataset are resized, normalized, and augmented to improve the model's generalization.
2. Model Training: The CNN model is trained on the preprocessed dataset using a supervised learning approach. The model learns to recognize patterns associated with healthy and diseased leaves.
3. Prediction: Once trained, the model can classify new potato leaf images as Healthy, Early Blight, or Late Blight.
4. Deployment: The trained model can be integrated into a web or mobile application, providing farmers with easy access to the disease detection tool.

# Usage
1. Clone the Repository: git clone https://github.com/yourusername/potato-disease-classifier.git
2. Run the Model: Open the project in Google Colab and run the cells to train the model and make predictions.

# Results
The CNN model achieved an accuracy of 100% on the test set, demonstrating its effectiveness in identifying potato leaf diseases. This tool can potentially save farmers time and resources by enabling early detection and treatment of diseases.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
