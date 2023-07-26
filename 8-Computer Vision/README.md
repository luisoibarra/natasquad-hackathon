# Fresh or Rotten Fruits Classification

## Dataset preparation

1. Download the dataset from [here](https://share.natasquad.com/index.php/s/D2BHJSt5nY3idPd).

2. Copy the **Test** and **Train** folders into a the **data/dataset** folder.

## Pretrained weights download

This project uses the pretrained weights of ResNet50V2 and Xception for fine tuning.
These weights can be downloaded from:

- [ResNet50V2](https://storage.googleapis.com/tensorflow/keras-applications/resnet/resnet50v2_weights_tf_dim_ordering_tf_kernels_notop.h5)
- [Xception](https://storage.googleapis.com/tensorflow/keras-applications/xception/xception_weights_tf_dim_ordering_tf_kernels_notop.h5)

The downloaded files must be copied to `data/resnet_base` in case of ResNet50V2 weights and to `data/xception_base` for Xception model weights.

## Preprocess, training and evaluation

Run the cells in `computer_vision.ipynb` once the steps above are completed. This should run the complete pipeline for all models and create the used models and metrics.

## Detailed explanation of the process

The `presentation.ipynb`'s cells will contain a detailed explanation of all the problem processes.  
