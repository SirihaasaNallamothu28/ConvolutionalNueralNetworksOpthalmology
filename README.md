# FoveaConvolutionalNueralNetworksComputerBasedFundoscopy
Convolutional Neural Network code that I created for classification of fundus and trachoma images. 
Only a few models are included in this repository. 

Abstract: 
Retinal and ocular diseases are a prevalent problem in today’s society with ophthalmic care being inaccessible. Over 200 million people worldwide suffer from retinal diseases relating to the fundus, and over 44 countries face the prevalent health problem of Trachoma which causes irreversible blindness. To solve these problems, I created six supervised binary classifications convolutional neural networks to diagnose AMD, Diabetic Retinopathy, Glaucoma, Hypertension, and Cataracts, each upwards of 90% accurate, and utilized model stacking for higher-quality processing and classification of fundus images. I also trained a neural network for the diagnosis of trachoma, via images of the inner surface of the eye-lid. These seven neural networks were trained off of a dataset with over 6,000 fundus images and 1,000 images of trachoma. When testing these neural networks with fundus with diabetic retinopathy, and passing it through the networks, all the networks except the ‘Normal vs. Diabetes’ models returned percentages around 1.9* 10^-5, proving that model stacking returns accurate results. I’m transferring these neural networks to raspberry pi with an Edge TPU for higher computational power, that will be connected to a camera, a touch-screen display [to show percentages], a light source, and a 20D ophthalmic lens, in order to create a cheap fundoscopy device. The device will serve as a cost-effective and accurate way for a user to take an image of the fundus or inner eyelid using the built-in camera and receive confidence percentages from the algorithms in a matter of minutes. View my research and work regarding for my developing prototype, Fovea, below.

Other links: 

Press Release: https://ibio.org/ibio-announces-winner-of-illinois-biogeneius-challenge-student-competition-2/ 

Overview Video: https://www.youtube.com/watch?v=BsjGtkZOfUA 

https://drive.google.com/file/d/12Gcp8-YDSEMbg9ULnCXnmOOHtRckwKdb/view

Overhttps://www.youtube.com/watch?v=0U2_JKBoiG0&t=15s 

