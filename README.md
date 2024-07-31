# Plant-disease-prediction

This project aims to predict plant diseases using a dataset from Kaggle, which contains images of plant leaves. The dataset is categorized into three classes: healthy, powdery mildew, and rust, each contributing equally. During preprocessing, the images were rescaled and normalized to ensure consistent input sizes and pixel values. The dataset was then split into training and testing sets to facilitate model development and evaluation.

The training set was used to build a neural network model comprising convolutional layers, max pooling layers, and dense layers. These layers were designed to extract features and classify the images effectively. After training the model over sufficient epochs, it was saved for future use. The model's performance was tested using images that were not part of the training set, demonstrating its ability to accurately predict plant health and identify diseases from new data.
