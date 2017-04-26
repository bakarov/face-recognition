# Implementation of a LeNet for a Face Recognition task

My implementation of a face recognition script based on Theano+Keras. It uses a LeNet architecture.

### Requiriments

* Theano
* Keras
* numpy
* PIL

### Training

First of all, you need to define and train the model. You can train it manually and set the hyperparameters: `create_model()` and `train_model(model)`

The training set with around ~100 training samples is stored at `/data`.

### Executing

To check the model you should replace a test image at */data/test/test.png*  with yours and run `execute_check()`. The code prints 'True' if image is a face, or 'False' otherwise.
