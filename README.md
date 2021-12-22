# Dog-Breed-Classification
The objective of this project was to create a classifier using Convolutional Neural Network which could differentiate between human and dog images. For detecting human faces, I reused OpenCV's implementation of human face detector. This is the first step in the pipeline. After detecting whether the image is human or dogs or something else, then I built a Convolutional Neural Network to identify the species of dogs and also to find the closest species of dogs for human images. 
For building Convolutional Neural Network, used two techniques -
- Created own CNN model from scratch and then built and optimized it for performance
- Used Transfer Learning using models like VGG16, ResNet50 which conveniently outperformed basic CNN model

Code for these steps is present in 'dog_app.ipynb' file.
