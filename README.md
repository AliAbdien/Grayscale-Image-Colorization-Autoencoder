# Grayscale Image Colorization Autoencoder
Project Overview
This project involves the development of an Autoencoder model using TensorFlow and Keras to colorize grayscale images. The primary goal is to teach the model how to add color to black and white images, enhancing the perception of originally monochromatic photos. We leverage the CelebA dataset, a rich collection of celebrity images, which is ideal for training and testing deep learning models in facial attribute recognition and image colorization tasks.

Dataset
The CelebA dataset, hosted on Kaggle, is utilized for this project. It is a large-scale face attributes dataset with more than 200,000 celebrity images, each with 40 attribute annotations. The dataset can be found here: CelebA Dataset on Kaggle.

About the Dataset:
Context: This dataset is widely used in computer vision for applications like face recognition and facial attribute detection. The images in the dataset include a wide range of pose variations and backgrounds, making it a comprehensive dataset for facial analysis tasks.
Content: The dataset contains 202,599 images of various celebrities with 10,177 unique identities. While the names of the identities are not provided, each image comes with 40 binary attribute annotations and 5 landmark locations.
Model Description
The Autoencoder model consists of two main parts: an Encoder and a Decoder. The Encoder reduces the dimensions and extracts features from grayscale images, while the Decoder reconstructs the colored image from these features. Advanced techniques like Batch Normalization and Dropout are used to improve training stability and prevent overfitting.

Implementation
Data Preparation: Images from the CelebA dataset are loaded, converted to grayscale, and then split into training and testing sets.
Model Building: The model is built using TensorFlow and Keras, incorporating layers for both the encoding and decoding processes.
Training: The model is trained using grayscale images as inputs and the original colored images as targets.
Results: The trained model is used to colorize grayscale images, and the results are displayed using matplotlib.
Usage
The project can be cloned from this repository. Ensure you have TensorFlow installed in your environment, and download the CelebA dataset from Kaggle to run the project.
