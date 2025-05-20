# AI-POWERED-QUALITY-CONTROL-IN-MANUFACTURING
This is a NAAN MUDHALVAN-IBM-AI-EBPL final phase (phase 5) project on the topic of AI-POWERED QUALITY CONTROL IN MANUFACTURING
 # 🖼️ Image Classification with CNN for Defective Product Detection

## 🛠️ 1. Technology Used

* 🐍 Python
* 🔥 TensorFlow
* 🧠 Keras
* 🔢 NumPy
* 📊 Matplotlib
* 🌈 Seaborn
* 📈 Scikit-learn

## 🌟 2. Features

* ✅ Binary classification to identify defective products based on image data.
* 🧩 Uses a Convolutional Neural Network (CNN) for accurate image classification.
* 📊 Visualizes the confusion matrix for performance analysis.
* 🔍 Displays sample predictions for validation.

## 📝 3. How It Works

1. 📂 The model uses the CIFAR-10 dataset, which contains 60,000 images categorized into 10 classes.
2. 🔍 Classes are grouped as follows:

   * ✅ Good: Airplane (0), Automobile (1)
   * ❌ Defective: Bird (2), Cat (3)
   * 🚫 All other classes are ignored.
3. 🌐 The images are normalized to improve training efficiency.
4. 🧠 A CNN model with convolutional and max-pooling layers extracts features.
5. 🔑 Binary classification is performed with a sigmoid activation function.

## 📂 4. Data Collection

* 📁 Dataset: CIFAR-10
* 🌐 Access the dataset [here](https://www.cs.toronto.edu/~kriz/cifar.html)
* 🗃️ Download as CSV file [here](https://www.kaggle.com/datasets/sarabirk/cifar-10-csv)

## 🎯 5. Objective

The project aims to classify product images into "Good" and "Defective" categories to automate quality control processes, reducing manual inspection time and improving accuracy.

## 🧩 6. Control

* 📝 The model is trained on the filtered CIFAR-10 dataset.
* ⚙️ The training process includes normalization and binary labeling.
* 📉 Loss: Binary Crossentropy
* 🚀 Optimizer: Adam
* 📊 Accuracy as the performance metric.

## 🤖 7. ML Techniques Used

* 🧠 Convolutional Neural Network (CNN)
* 🔑 Binary classification using sigmoid activation.
* 📊 Performance evaluation using classification reports and confusion matrices.

## 🏋️‍♂️ 8. Model Training

* 🔁 The CNN model is trained for 5 epochs with the Adam optimizer.
* ✅ Validation is performed using a separate test set.
* 🗃️ The model outputs training accuracy, loss, and a visual confusion matrix.

## 📊 9. Output Explanation

* 📌 The model predicts whether an image belongs to the "Good" or "Defective" category.
* 🗺️ The confusion matrix shows the number of true positives, true negatives, false positives, and false negatives.
* 📷 Sample predictions are displayed with images for visual verification.
