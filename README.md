### FaceMask-Detection
This Project is implemented by using Keras-tensorflow,opencv and python.It contains 3 parts

1. Data Preprocessing
2. Training the CNN
3. Detecting Mask

# Data Processing
Firstly I took this DataSet from [Prajna bhandary](#) and available at [github](https://github.com/prajnasb/observations/tree/master/experiements/data).
The dataset Contains 1376 images,690 face images with masks and 686 without masks.
Asuming Colour is not a Critical Feature in detecting Mask, Converted all the Images present in the dataset into grayScale and Resized the image into 100*100,since we need all the images should be of same size before passing them into Convolution Neural network(CNN).
