# diabetic-retinopathy-classification
🩺 Diabetic Retinopathy Detection Using Deep Learning (Binary Classification)

This project focuses on the automated detection of Diabetic Retinopathy (DR) from retinal fundus images using a deep learning-based image classification approach. Diabetic Retinopathy is one of the leading causes of vision impairment and blindness among diabetic patients worldwide, making early detection crucial for preventing severe complications.

The model in this study was developed using the Diagnosis of Diabetic Retinopathy dataset obtained from Kaggle:
📂 https://www.kaggle.com/datasets/pkdarabi/diagnosis-of-diabetic-retinopathy

🎯 Objective

To develop a deep learning model capable of classifying retinal fundus images into two categories:

- No DR : No indication of Diabetic Retinopathy
- DR : Presence of Diabetic Retinopathy

This binary classification approach simplifies the detection task into a clinically relevant screening system that can assist in early diagnosis.

🧠 Methodology

The proposed system utilizes a Convolutional Neural Network (CNN) architecture for image classification. The classification pipeline consists of:

- Image preprocessing and resizing to 224 × 224 pixels
- Feature extraction using a CNN-based backbone (Using Transfer Learning -> DenseNet121)

Binary classification using:

- Sigmoid activation function
- Binary Crossentropy loss function

The output layer produces a probability score between 0 and 1 indicating the likelihood of Diabetic Retinopathy presence in a given retinal image.
