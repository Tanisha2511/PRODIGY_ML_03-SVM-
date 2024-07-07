# Cat vs Dog Image Classification using SVM

## Project Overview
This project aims to develop a Support Vector Machine (SVM) model to classify images of cats and dogs from the Kaggle dataset. The project explores the application of SVMs in handling high-dimensional image data, emphasizing feature extraction, model training, evaluation, and parameter optimization.

## Dataset
The dataset used in this project is the Cat vs Dog dataset from Kaggle, which consists of 25,000 images of cats and dogs.

## Project Structure
Dataset/: contains the dataset files
train.zip: the training dataset
test1.zip: the testing dataset
svm_model.pkl: the trained SVM model
confusion_matrix.png: the confusion matrix of the model
classification_report.txt: the classification report of the model
README.md: this file

## Requirements
Python 3.10 or higher
scikit-learn 1.0 or higher
OpenCV 4.5 or higher
NumPy 1.23 or higher
Matplotlib 3.5 or higher
Seaborn 0.11 or higher

## How to Run
Extract the dataset files from train.zip and test1.zip.
Run the svm_model.py file to train the SVM model.
The trained model will be saved as svm_model.pkl.
Run the evaluation.py file to evaluate the model and generate the confusion matrix and classification report.

## Results
The optimized SVM model achieved an accuracy score of approximately 67.62%, indicating its ability to correctly classify images of cats and dogs.

## License
This project is licensed under the MIT License. See LICENSE for details.

## Acknowledgments
This project was inspired by the Kaggle dataset and the scikit-learn library.
