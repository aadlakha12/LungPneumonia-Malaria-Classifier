# LungPneumonia-Malaria-Classifier

Disease Classifier is implemented using two datasets from kaggle.
Transfer Learning has been used to implement VGG19, ResNet50, Inception_v3 in Keras.
The program also uses template matching using normalized cross correlation (built from scratch)
to detect whether the uploaded image is a lung image or a malaria parasite image.
The app is developed in Python, Flask, Javascript, HTML, CSS.

It uses two datasets from Kaggle:

Chest X-ray Pneumonia Disease : https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia 

Malaria Parasite Dataset: https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria

Watch video from Demo-video folder for walk through of web application.

To run this project:

- Download both the folders.

- Download trained models from the drive link. Place these models in the Flask and PneumoniaMalariaClassifier folder.

https://drive.google.com/drive/folders/1mRMTlzWiWNiZJ5r6CsnwHqfPE8QhCQkX?usp=sharing

To run a web app.

- Go to Flask folder. Install necessary dependencies.

- Run Python app.py from terminal in the Flask folder.

## Results

##### Main Page:

![alt text](https://github.com/aadlakha12/LungPneumonia-Malaria-Classifier/blob/master/Images/Main-Landing.png?raw=true)

##### Lung X-ray Pneumonia result:

![alt text](https://github.com/aadlakha12/LungPneumonia-Malaria-Classifier/blob/master/Images/Pneumonia.png?raw=true)

##### Malaria Parasite result:

![alt text](https://github.com/aadlakha12/LungPneumonia-Malaria-Classifier/blob/master/Images/Malaria.png?raw=true)

### Template Matching

- Error on choosing Malaria Dataset and uploading lung x-ray image:

![alt text](https://github.com/aadlakha12/LungPneumonia-Malaria-Classifier/blob/master/Images/Error_lung.png?raw=true)

- Error on choosing Lung Dataset and uploading malaria image:

![alt text](https://github.com/aadlakha12/LungPneumonia-Malaria-Classifier/blob/master/Images/Error_malaria.png?raw=true)

- Error on choosing Lung/Malaria Dataset and uploading any unknown image:

![alt text](https://github.com/aadlakha12/LungPneumonia-Malaria-Classifier/blob/master/Images/Error_unknown.png?raw=true)



