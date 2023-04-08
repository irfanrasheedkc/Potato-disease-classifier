# Potato disease classifier
 
This project is a machine learning model that classifies potato leaf diseases based on images of potato leaves. The model is built using the TensorFlow library and is trained on a dataset of labeled images.

The model can currently classify three different types of potato leaf diseases: Early Blight, Late Blight, and Healthy. The accuracy of the model is currently at 95%, as evaluated on a separate test dataset.

To use the model, simply input an image of a potato leaf and the model will output a prediction of the type of disease present in the leaf.

## Dataset
Dataset
The dataset used to train the model is publicly available on Kaggle and can be found [here](https://www.kaggle.com/datasets/arjuntejaswi/plant-village). 
It contains a total of 16,074 labeled images of potato leaves, including 5,376 images of Early Blight, 5,400 images of Late Blight, and 5,298 images of Healthy leaves.

## Dependencies
- TensorFlow 2.4.0
- NumPy 1.19.3
- Matplotlib 3.3.3
