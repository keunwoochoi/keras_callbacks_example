# keras_callbacks_example

### What is it?
It is just an example code to check out how to define your own keras callback functions.
More details are explained in [my blog post](https://keunwoochoi.wordpress.com/2016/07/16/keras-callbacks/)

### How to run
(after install keras and sklearn)
```
$ python mnist_cnn.py
```
### Result
```
Using Theano backend.
Couldn't import dot_parser, loading of dot files will not be possible.
X_train shape: (60000, 1, 28, 28)
60000 train samples
10000 test samples
Train on 60000 samples, validate on 10000 samples
Epoch 1/4
60000/60000 [==============================] - 2s - loss: 2.3135 - acc: 0.1315 - val_loss: 2.2803 - val_acc: 0.1639
Epoch 2/4
60000/60000 [==============================] - 2s - loss: 2.2552 - acc: 0.1565 - val_loss: 2.2100 - val_acc: 0.1850
Epoch 3/4
60000/60000 [==============================] - 2s - loss: 2.1600 - acc: 0.2012 - val_loss: 2.0870 - val_acc: 0.2216
Epoch 4/4
60000/60000 [==============================] - 3s - loss: 2.0563 - acc: 0.2550 - val_loss: 2.0025 - val_acc: 0.2893
[2.3134536211649577, 2.255207451756795, 2.1600136189778647, 2.0562698792775471]
[0.59195507750334042, 0.62079124344371317, 0.65786632355974606, 0.68406181760941875]
Test score: 2.00254338188
Test accuracy: 0.2893
```
