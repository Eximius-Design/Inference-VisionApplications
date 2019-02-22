# NCS_MNIST
MNIST implementation using Intel neural compute stick and ncsdk v2.0

Train a CNN for MNIST using Keras

`$ python3 train_mnist.py`

Convert Keras model to tensorflow

`$ python3 convert-mnist.py`

Compile MNIST model using mvNC Toolkit

`$ mvNCCompile TF_Model/tf_model.meta -in=conv2d_1_input -on=dense_2/Softmax`

Inference: predict using NCSDK v2.0

`$ python3 predict-mnist-ncs2.py`
