# Intuitive-Deep-Learning
Jupyter Notebooks

1. Image Classification using CNN

  a. Download dataset and visualize the images
  
  b. Change the label to one-hot encodings
  
  c. Scale the image pixel values to take between 0 and 1
  
  d. After downloading the  Image data set, its pixelated to 32 * 32 pixels. 
  
  e. The trained data used to train the model. Conv2D with relu activation is used. 
  
  f. Appropriate graphs are plotted for model accuracy. model is saved as cifar10_model.h5
  
  The model can be used to test with our own images after activating environment and resizing the image to 32 * 32. predict the model using 
  > index = np.argsort(probabilities[0,:])
