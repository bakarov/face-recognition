# Yet another utlity for face recognition 

My implementation of a face recognitor based on Theano+Keras. It also uses Jupyter Notebook.

### Installation

This utility requires Theano, Keras, Jupyter Notebook, scipy and numpy to be installed. 

### Model

First of all, you need to define and train the model. You can train it manually and self-set the hyperparameters:
```sh
model = create_model()
model = train_model(model)
```
Or you can just load the serialized model from .json:
```sh
model = load_model()
```
The traning datasets are stored at /data. Positive and negative images are loaded separately.  

### Executing
To use the model for prediction replace the test image at */data/test/test.png*  with your one and simply run the folliwing method:
```sh
execute()
```
And the utility will print to console 'True', if your image is a face, or 'False' otherwise.

### License

This application is a training work, it is based on open-source software and it does not require any license. 

Thanks for reading this, and if you have any questions you can always contact me:

Amir Bakarov
amirbakarov@ya.ru


