# Face_verification
Building a Siamese netural network from scratch with the help of state of art research paper **Siamese Neural Networks for One-shot Image Recognition**
https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf

+ Building Siamese Neural Network from scratch using Tensorflow functional API

+ Generating data for Anchor and Positive images from webcam using OpenCV and LFW Face Database for Negative images( http://vis-www.cs.umass.edu/lfw/ )

+ Scaling and resizing Images, loading and labelling images using the Tensorflow Dataloader and then splitting data pipelines into training and testing partitions

+ Creating an Image Embedding Model, building L1 Distance Layer and combining models to create a Siamese Neural Network

+Setting Up a Loss Function, an Optimizer and building a Custom Training Step to train the Model

+ Making Predictions with a Siamese Neural network and evaluating the model by calculating Precision and Recall, finally saving the model in h5 file. Reloading the model to perform face Verification in real time using OpenCV
