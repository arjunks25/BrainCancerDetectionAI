# BrainCancerDetectionAI by Arjun Singh
This project takes in a CT scan of the brain and classifies if it has no tumor, a pituitary tumor, a glioma tumor, or a meningioma tumor.

Here is the Public Domain Kaggle Dataset link- https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?rvi=1

CancerDetectionAI.ipynb File

    Part 1
    This part contains the code that imports the data, creates the CNN, creates the training and
    testing datasets, trains the CNN, and tests the CNN. Taking advantage of Colab's tools I trained 
    a pre-trained model called resnet18, which is a small but effective neural network. When training
    on Colab the biggest issue is runtime. The notebook will time out and erase all progress that you
    had with the model's weights and biases. To fix this I saved the trained model to my Google Drive 
    immediately after it finished training so that I could access it later.

    Part 2
    This part imports the model from Google Drive and tests it. Its main function though is to present the 
    accuracy by outputting a graph and some images with "predicted" and "actual" labels.
    This part was just used to present the final trained model in a more practical way.
    
  
  Here are the output images in the presentation file for easier access-
    
![image](https://github.com/arjunks25/CancerDetectionAI/assets/102838869/38a6ce41-fe7e-4866-9364-f894fa0fe2c2)
    ![image](https://github.com/arjunks25/CancerDetectionAI/assets/102838869/d610504b-0b30-4a3c-ab4b-541b79750c1c)
    ![image](https://github.com/arjunks25/CancerDetectionAI/assets/102838869/f3810386-d31a-4bdd-8158-05f44bf94f1a)
    

  

