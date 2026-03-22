# Face-Recognition
Face Recognition with OpenCV and LBPH
This Google Colab notebook demonstrates a basic face recognition system using OpenCV's Local Binary Patterns Histograms (LBPH) algorithm.

Steps Performed:
Install OpenCV: Installs the required opencv-python and opencv-python-headless libraries.
Upload Dataset: Facilitates uploading a dataset (expected as a zip file).
Unzip Dataset: Extracts the uploaded zip file into a 'dataset' directory.
Import Libraries: Imports cv2 (OpenCV) and numpy.
Load & Preprocess Images: Loads grayscale images from specified training folders, associating them with labels based on directory names.
Train Model: Initializes and trains an LBPHFaceRecognizer model using the loaded training images and labels.
Test Model: Evaluates the trained model by predicting faces in images from a separate test dataset and printing the recognized names.
