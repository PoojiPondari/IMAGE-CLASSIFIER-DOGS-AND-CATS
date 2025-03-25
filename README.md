# Cat and Dog Image Classifier

This project uses **TensorFlow 2.0** and **Keras** to build a **Convolutional Neural Network (CNN)** that classifies images of cats and dogs.

### Project Overview:
- **Goal**: Create a model to classify images of cats and dogs with at least 63% accuracy (70% for extra credit).
- **Dataset**: The dataset consists of images in the `train`, `validation`, and `test` directories, each containing subdirectories for cats and dogs.
- **Tools Used**: 
  - **ImageDataGenerator** for image preprocessing and augmentation.
  - **CNN** with **Conv2D**, **MaxPooling2D**, and **Dense** layers for model creation.

### Steps:
1. **Data Preprocessing**: Load and preprocess the images using **ImageDataGenerator**.
2. **Data Augmentation**: Apply transformations like rotation and zoom to prevent overfitting.
3. **Model Creation**: Build the CNN using Keras and compile it.
4. **Training**: Train the model using the training and validation datasets.
5. **Prediction**: Use the model to classify images from the test set.
6. **Evaluation**: Ensure the model achieves at least 63% accuracy.

### Instructions:
1. Clone this repository.
2. Open the notebook and follow the instructions in each code cell.
3. Train the model and evaluate its performance.

### License:
MIT License.
