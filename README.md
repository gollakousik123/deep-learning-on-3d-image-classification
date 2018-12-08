# deep-learning-on-3d-image-classification

Install <a href="https://www.tensorflow.org/get_started/os_setup" target="_blank">TensorFlow</a>.
 The code has been tested with TensorFlow 0.12.1, CUDA 8.0 and cuDNN 5.1 on Ubuntu 14.04.
#usage
To train a model to classify
    python train.py
To see HELP for the training script:
     python train.py -h
     
fter the above training, we can evaluate the model and output some visualizations of the error cases.
 	python evaluate.py --visu True

