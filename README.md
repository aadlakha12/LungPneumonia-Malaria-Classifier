# LungPneumonia-Malaria-Classifier

Disease Classifier is implemented using two datasets from kaggle.
Transfer Learning has been used to implement VGG19, ResNet50, Inception_v3 in Keras.
The program also uses template matching using normalized cross correlation (built from scratch)
to detect whether the uploaded image is a lung image or a malaria parasite image.
The app is developed in Python, Flask, Javascript, HTML, CSS.

It uses two datasets from Kaggle:

Chest X-ray Pneumonia Disease : https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia 

Malaria Parasite Dataset: https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria

To run this project:

Download both the folders.

Download trained models from the drive link. Place these models in the Flask and PneumoniaMalariaClassifier folder.

https://drive.google.com/drive/folders/1mRMTlzWiWNiZJ5r6CsnwHqfPE8QhCQkX?usp=sharing

To run a web app.

Go to Flask folder. Install necessary dependencies.

Run Python app.py from terminal in the Flask folder.

