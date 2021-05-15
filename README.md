# FoveaConvolutionalNueralNetworksComputerBasedFundoscopy
Convolutional Neural Network code that I created for classification of fundus and trachoma images. 
Only a few models are included in this repository. 

Abstract: 
Retinal and ocular diseases are a prevalent problem in today’s society with ophthalmic care being inaccessible. Over 200 million people worldwide suffer from retinal diseases relating to the fundus, and over 44 countries face the prevalent health problem of Trachoma which causes irreversible blindness. To solve these problems, I created six supervised binary classifications convolutional neural networks to diagnose AMD, Diabetic Retinopathy, Glaucoma, Hypertension, and Cataracts, each upwards of 90% accurate, and utilized model stacking for higher-quality processing and classification of fundus images. I also trained a neural network for the diagnosis of trachoma, via images of the inner surface of the eye-lid. These seven neural networks were trained off of a dataset with over 6,000 fundus images and 1,000 images of trachoma. When testing these neural networks with fundus with diabetic retinopathy, and passing it through the networks, all the networks except the ‘Normal vs. Diabetes’ models returned percentages around 1.9* 10^-5, proving that model stacking returns accurate results. I’m transferring these neural networks to raspberry pi with an Edge TPU for higher computational power, that will be connected to a camera, a touch-screen display [to show percentages], a light source, and a 20D ophthalmic lens, in order to create a cheap fundoscopy device. The device will serve as a cost-effective and accurate way for a user to take an image of the fundus or inner eyelid using the built-in camera and receive confidence percentages from the algorithms in a matter of minutes. View my research and work regarding for my developing prototype, Fovea, below.

Please note that I did not include the processed data set in this repository. I processed and orgnized the kaggle data set through the funding I recived. View the video below as well. 
I also included the script I utlized to sort the data in a seperate respository: Fovea-DataSetSortingScript
I included the tensorflow lite compressed models as well. 
I was unable to add my normal vs amd model. 

Diseases I chose to diagnose: 
Retinal Diseases:
-Medical Description
“Diabetic retinopathy is caused by damage to the blood vessels in the tissue at the back of the eye (retina). Poorly controlled blood sugar is a risk factor.”


Age-Related Macular Degeneration 
-Medical Description
“Macular degeneration causes loss in the center of the field of vision. In dry macular degeneration, the center of the retina deteriorates. With wet macular degeneration, leaky blood vessels grow under the retina. Blurred vision is a key symptom.”


Myopia
-Medical Description
“A condition in which close objects appear clearly, but far ones don't.
Nearsightedness tends to run in families.Faraway objects appear blurry. The condition may develop gradually or rapidly.”


Glaucoma
-Medical Description:
“A group of eye conditions that can cause blindness. With all types of glaucoma, the nerve connecting the eye to the brain is damaged, usually due to high eye pressure. The most common type of glaucoma (open-angle glaucoma) often has no symptoms other than slow vision loss.”


Ocular Hypertension
-Medical Description:
“Ocular hypertension is the result of poor drainage of the aqueous humor (fluid inside the eye). Essentially, this means that too much fluid enters the eye without being drained, causing high amounts of pressure to build up. Can be diagnosed and visualized via the Retina”. 


Cataract
-Medical Description:
“Clouding of the normally clear lens of the eye. Most cataracts develop slowly over the course of years. The main symptom is blurry vision. Having cataracts can be like looking through a cloudy window.” Can be diagnosed and visualized via the Retina. This can make my model more versatile. 

Healthy
-Medical Description:
“Health Retina warrants a clear and cohesive vision.”
-In my model, I will utilize the healthy retina dataset as a baseline and a comparison. If no retinal disease features are detected this will be the default image. 



Retinal Disease Diagnosis [Process and Information]:
-Fluorescein Angiography Equipment or Highly Advanced [costly] Fundus Cameras are utilized to image the Retina and the Fundus. 

Other links: 

Press Release: https://ibio.org/ibio-announces-winner-of-illinois-biogeneius-challenge-student-competition-2/ 

Overview Video: https://www.youtube.com/watch?v=BsjGtkZOfUA 

Research Poster: https://drive.google.com/file/d/12Gcp8-YDSEMbg9ULnCXnmOOHtRckwKdb/view

Funding and Data Processing video: https://www.youtube.com/watch?v=0U2_JKBoiG0&t=15s 

