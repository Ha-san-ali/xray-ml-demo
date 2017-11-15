## Intro
The purpose of this repo is to showcase my learning experience with tensorflow following the image classification retraining tutorial found here https://www.tensorflow.org/tutorials/image_retraining.
I attempted to retrain the final layer of the Inception v3 model against images of chest xrays classified as either abnormal or normal and then test the newly retrained model.

## Installation
Follow the installation guide for tensorflow based on your operating system here https://www.tensorflow.org/install/install_sources. I cloned the tensorflow repository like this 
`$ git clone https://github.com/tensorflow/tensorflow` 

You'll also need to install python, bazel, and other dependencies using pip. 
`$ sudo pip install six numpy wheel`

In order for bazel to work properly you will need to configure your project like this 
`cd tensorflow`
`$ ./configure`


