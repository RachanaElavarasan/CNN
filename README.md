# 🐱🐶 Dog and Cat Image Classification Using CNN

### Deep Learning Mini Project

A Convolutional Neural Network (CNN) based image classification project that identifies whether an image contains a dog or a cat using deep learning techniques.

---

## 📌 Project Overview

This project focuses on developing a CNN model for binary image classification using a dataset containing dog and cat images. The model learns visual features from images through three convolutional layers and predicts the corresponding category.

The project is implemented using Python, TensorFlow, and Keras. Model performance is evaluated using Accuracy, Precision, Recall, and F1-score, with the results visualized using a bar graph.

## 🎯 Objectives

- Develop a CNN model for dog and cat image classification.
- Understand image preprocessing and feature extraction.
- Implement three convolutional layers.
- Train the model using a labeled image dataset.
- Evaluate classification performance using standard metrics.
- Visualize the evaluation results using a bar chart.

## ✨ Key Features

- **Image Classification:** Classifies images into dog and cat categories.
- **Three Convolutional Layers:** Extracts visual features from input images.
- **Image Normalization:** Rescales pixel values to improve model training.
- **Max Pooling:** Reduces feature-map dimensions.
- **Model Training:** Trains the CNN for 10 epochs.
- **Performance Evaluation:** Calculates Accuracy, Precision, Recall, and F1-score.
- **Metric Visualization:** Displays the evaluation scores in a bar graph.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| TensorFlow | Deep learning framework |
| Keras | CNN model development |
| NumPy | Numerical operations |
| Matplotlib | Graph visualization |
| Scikit-learn | Performance evaluation metrics |
| Google Colab | Development and execution environment |

## 🧠 CNN Architecture

The CNN model contains the following layers:

1. **Input Layer:** Accepts RGB images of size 64 × 64 pixels.
2. **Rescaling Layer:** Normalizes pixel values between 0 and 1.
3. **Convolutional Layer 1:** Extracts basic image features using 16 filters.
4. **Max-Pooling Layer 1:** Reduces spatial dimensions.
5. **Convolutional Layer 2:** Learns more detailed visual patterns using 32 filters.
6. **Max-Pooling Layer 2:** Further reduces feature-map dimensions.
7. **Convolutional Layer 3:** Extracts higher-level features using 64 filters.
8. **Max-Pooling Layer 3:** Reduces the feature dimensions.
9. **Flatten Layer:** Converts feature maps into a one-dimensional representation.
10. **Dense Layer:** Learns patterns for classification.
11. **Output Layer:** Uses a sigmoid activation function to predict one of two classes.

**Optimizer:** Adam  
**Loss Function:** Binary Cross-Entropy  
**Training Epochs:** 10  
**Batch Size:** 32

## 📊 Evaluation Metrics

The model is evaluated using four classification metrics:

- **Accuracy:** Measures the proportion of correctly classified images.
- **Precision:** Measures how many images predicted as the positive class are actually positive.
- **Recall:** Measures how many actual positive-class images are correctly identified.
- **F1-score:** Combines precision and recall into a single metric.

The scores are printed after evaluation and displayed in a bar graph for easy interpretation.

## 🚀 How to Run the Project

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the `CNN.ipynb` notebook.
3. Ensure that an internet connection is available to download the dataset.
4. Run the notebook cells in order.
5. Allow the CNN model to train for 10 epochs.
6. View the evaluation metrics and bar graph.

### Required Libraries

```python
tensorflow
numpy
matplotlib
scikit-learn
```

These libraries are commonly available in Google Colab. Install any missing libraries if required.

## 📁 Project Structure

```text
CNN-Dog-Cat-Classification/
│
├── CNN.ipynb
└── README.md
```

The dataset is downloaded and extracted automatically when the notebook runs successfully.

## 📈 Expected Results

After training, the notebook displays:

- Model training progress for each epoch.
- Accuracy score.
- Precision score.
- Recall score.
- F1-score.
- A bar graph representing all four evaluation metrics.

Actual results may vary depending on training conditions and the dataset.

## 🎓 Learning Outcomes

Through this project, we learn how to:

- Build a CNN using TensorFlow and Keras.
- Process and classify image data.
- Extract features using convolutional layers.
- Train a deep learning model.
- Evaluate binary classification performance.
- Visualize model evaluation results.

## 🔮 Future Enhancements

- Improve classification accuracy through data augmentation.
- Experiment with additional training epochs and hyperparameters.
- Add image upload functionality for individual predictions.
- Explore transfer learning using pretrained CNN models.
- Develop a simple web interface for image classification.

## 👩‍💻 Project Information

**Project Title:** Development of a Convolutional Neural Network (CNN) for Dog–Cat Image Classification Using Three Convolutional Layers

**Project Type:** Deep Learning Mini Project

**Domain:** Artificial Intelligence and Deep Learning

**Environment:** Google Colab / Jupyter Notebook

---

⭐ *This project demonstrates the practical application of Convolutional Neural Networks in image recognition and binary classification.*

