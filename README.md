# FCN
Repository for a Fully Connnected Convolutional Neural Network (FCN) that uses a pretrained ResNet18 with 1 Convolutional Layer and 1 Transposed Convolutional Layer.
The Model will classify each pixel accorcding to one of 20 classes or background (i.e., not classified).

To run the pretrained model, open the fcn_predictions.ipynb notebook and execute the code.
This will prompt the user for a path to an image and will output the semantic segmentation of the input image.


To train a new model from scratch, open the fcn.ipynb notebook and execute the code.
After training a subset of images will be printed out to show the ouput that the neural network produces.
