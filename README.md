# Hand-Gesture-Recognition
This project demonstrates a hand gesture recognition model using a Convolutional Neural Network (CNN) with a pretrained VGG16 model as the base for feature extraction. The model accurately identifies and classifies different hand gestures from image data, enabling intuitive human–computer interaction and gesture-based control systems.

# Dataset
The dataset used in this project is LeapGestRecog, which consists of images of 10 different hand gestures performed by 10 different subjects. The gestures included in the dataset are:
Palm (01_palm)
L (02_l)
Fist (03_fist)
Fist Moved (04_fist_moved)
Thumb (05_thumb)
Index (06_index)
OK (07_ok)
Palm Moved (08_palm_moved)
C (09_c)
Down (10_down)

# Steps Involved
The project involves the following steps:
Data Loading and Preprocessing: Images are loaded, resized, and normalized to match the input requirements of the VGG16 model.
Data Augmentation: Applied to increase the diversity of the training data and improve model generalization.
Model Creation: A pretrained VGG16 model is used for feature extraction, with additional custom dense layers added for gesture classification.
Model Training: The model is trained on the dataset for a specified number of epochs.
Evaluation: Model performance is evaluated using validation accuracy and loss metrics.
Prediction: The trained model predicts hand gestures for unseen input images.
Visualization: Predictions are visualized alongside the corresponding input images.

# Result Analysis
The final model achieved an impressive ~99% validation accuracy on the test dataset. The model demonstrates high reliability in classifying hand gestures using a CNN with a pretrained VGG16 backbone and can be confidently applied in real-world applications such as gesture-controlled systems, virtual reality environments, and assistive technologies.
