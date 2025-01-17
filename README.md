# The source repository is located [in nyoki-mtl/keras-facenet](https://github.com/nyoki-mtl/keras-facenet) if you wish to contribute to that project.

## This project has been forked from the Original Repository and all credit goes to its authors and owner as well as all contributing developers and sources for their great work.
## The original code will be used for reference and modification to integrate with I.o.T. devices.

# keras-facenet
Facenet implementation by Keras2

## Pretrained model
You can quickly start facenet with pretrained Keras model (trained by MS-Celeb-1M dataset).
- Download model from [here](https://drive.google.com/open?id=1pwQ3H4aJ8a6yyJHZkTwtjcL4wYWQb7bn) and save it in model/keras/


You can also create Keras model from pretrained tensorflow model.
- Download model from [here](https://github.com/davidsandberg/facenet) and save it in model/tf/
- Convert model for Keras in [tf_to_keras.ipynb](https://github.com/nyoki-mtl/keras-facenet/blob/master/notebook/tf_to_keras.ipynb)


## Demo
- [Face vector calculation](https://github.com/nyoki-mtl/keras-facenet/blob/master/notebook/demo-images.ipynb)
- [Classification with SVM](https://github.com/nyoki-mtl/keras-facenet/blob/master/notebook/demo-svm.ipynb)
- [Web camera demo](https://github.com/nyoki-mtl/keras-facenet/blob/master/notebook/demo-webcam.ipynb)

## Environments
Ubuntu16.04 or Windows10  
python3.6.2  
tensorflow: 1.3.0  
keras: 2.1.2  
