# Malaria_Classifier_CNN
Detection of Malaria Infected Disease cells using cell images, deployed using Flask.

Dataset is downloaded from kaggle (https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria). Since I'm training the model on my personal laptop, I have trained 3000 images only from Parasite & Uninfected classes.

Under the 'Training' folder, one file has a model created using CNN, and the second one has a model created using Transfer learning VGG19 Model. The folder 'Models' contain the .h5 model file created using the CNN model. The model for VGG19 was too large to upload. The model was deployed using Flask.

Run the app.py file to initiate the model deployment in the web browser.
