# AlexNet4KidneyMRI
The repository contains my scripts written for Bachelor thesis

The main part usues Keras Tensorflow (which I installed on the GPU) to implement AlexNet.
For augmentation is used the Albumentations library.

The files includes:
  1. Albumentations-Every-Transformation.ipynb
          This Notebook contains visualization of every transformation from Albumentations library for input pair (image-mask)
          
  2. 35-image.jpg and 35-mask.png 
          A pair of image-mask used in the file number one
          
  3. Image augmentation for BS thesis.ipynb
          A file that was used to augment the training images (during the development I also recieved an enlarged dataset from my supervisor which was containing already extracted ROIs from the mask-image pairs)
          
  4. AlexNet in kidney disease classification.ipynb
          A notebook file that contains input preprocessing after the augmentations and the model development.
