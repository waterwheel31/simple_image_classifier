# Simple Image Classification

A simple Image Classification using Tensorflow(Keras) with pre-trained model. 

This is read an image and return the name of flower with the probability


### Output Image

![sample](./sample.png)


### How To Run

to run, write a command as following: 

`$ python predict.py ./test_images/orchid.jpg my_h5model.h5 --top_k 3`

Here `--top_k` parameter means number of the top candidates to show. If --top_k is 1, only the top candidate is shown. 


This requires some dependencies, please install them as needed. 



