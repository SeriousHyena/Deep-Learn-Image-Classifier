# Deep-Learn-Image-Classifier
Deep Learning-Image Classifier

Credit for my learning goes mostly to Jeremy Howard at Fastai for actually having an inuition about what I am doing and why. 

This is a binary image classifier that will take an image of a face wearing a mask and a face and not wearing a face mask. The goal is to accurately predict whether or not the person is wearing a face mask or not. 

The workflow goes basically like this:

* Download the images from google images using a java script to save the urls for later download of the actual images.
* Create my lables (classes).
* I obtained the data (images) for my classifier which consisted of people wearing fasks and note wearing face masks.
* Load the data and create folders as required.
* Verify usable images.
* Create an image databunch (tensor) 
* Define a learner method and train the model.
* Save the trained model. Note that I can do multiple models and save as many as I want to.
* Validate the model using 'ClassificationInterpretation' and show the top losses.
* Plot a confusion matrix showing classification errors.
* Fine-tune the ,model using '.lr_find'.
* Plot the learning rates and fine-tune again. Remember to save the model with the best results.
* Clean up the model by removing duplicates and outlier images.
* ...And finally put the model into production using completely new images from outside of my dataset to verify the model's ability top make accurate predictions.
