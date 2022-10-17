INTRODUCTION

The contribution of AI in the field of healthcare cannot be understated. Due to the large amounts of research already done in the field of image recognition through AI,
the applications of AI models in identifying diseases from MRIs, x-rays, and other such organ scans are vast. In a particular study, researchers that trained
a model on 3600 hip fracture images obtained an accuracy of 92%. This was approximately 15% more accurate than radiologists themselves. 

OVERVIEW
In this project I have used a residual neural network already trained on the ImageNet database and added dense trained layers of my own to create a convolutional
neural network. 

FLOW
Firstly, the necessary libraries are imported. Classic python libraries such as pandas, numpy, and matplotlib are imported for data manipulation and visualisation,
along with Tensoflow and Keras libraries as well. Further, a batch of 40 images are imported from the directory and are rescaled, normalised, shuffled, and arranged 
into a one-hot 2D array. Following this, the image labels are assigned to particular disease. 

After this, data is visualized where using matplotlib where each image is treated as a subplot with their corresponding labels. The model is then imported where the 
top layers are excluded (which will further be trained separately). 
