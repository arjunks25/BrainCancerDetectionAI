# CancerDetectionAI
This project takes in a CT scan of the brain and classifies if it has no tumor, a pituitary tumor, a glioma tumor, or a meningioma tumor.

In this repository there are two files- Project Development and Presentation.

Project Development file-
  This file contains the code that imports the data, creates the CNN, creates the training and testing datasets, trains the CNN, and tests the CNN.
  Taking advantage of Colab's tools I trained a pretrained model called resnet18, which is a small but effective neural network.
  When training on Colab the biggest issue in runtime. The notebook will time out and erase all progress that you had with the model's weights and biases.
  To fix this I saved the trained model to my google drive immediatly after it finished training so that I could access it later.
Presentation file-
  This file imports the model from Google Drive and tests it. It's main funtion though is to present the accuracy by outputting a graph and some images with labels.
  This file was just used to present the final trained model in a more practical way.
