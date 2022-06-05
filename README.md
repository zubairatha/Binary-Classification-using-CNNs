# Football Team Name Binary Classifier

## TensorFlow Binary Image Classification using CNN's
This is a binary image classification project using Convolutional Neural Networks and TensorFlow API on Python 3. It classifies the players into two reputed football teams - Man Utd and Man City

It is a ready-to-run code.
## Dependencies

```pip install -r requirements.txt```

## Notebook

```jupyter lab TeamClassification.ipynb ``` or ```jupyter notebook TeamClassification.ipynb ```

## Data

This is a repository containing datasets of 334 training images and testing images downloaded from Google Images. No problematic image.

Classes are manutd & mancity.


## Architecture

 Layer (type)                Output Shape              Param #   
=================================================================
 conv2d (Conv2D)             (None, 254, 254, 16)      448       
                                                                 
 max_pooling2d (MaxPooling2D  (None, 127, 127, 16)     0         
 )                                                               
                                                                 
 conv2d_1 (Conv2D)           (None, 125, 125, 32)      4640      
                                                                 
 max_pooling2d_1 (MaxPooling  (None, 62, 62, 32)       0         
 2D)                                                             
                                                                 
 conv2d_2 (Conv2D)           (None, 60, 60, 16)        4624      
                                                                 
 max_pooling2d_2 (MaxPooling  (None, 30, 30, 16)       0         
 2D)                                                             
                                                                 
 flatten (Flatten)           (None, 14400)             0         
                                                                 
 dense (Dense)               (None, 256)               3686656   
                                                                 
 dense_1 (Dense)             (None, 1)                 257       

## Flask web-app

Run:
```pip install -r requirements.txt```

## Result

![Web-App Result Image](/result/res1.png)
