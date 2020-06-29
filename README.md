# Machine Learning Experiments

These are my personal experiments with TensorFlow and python Machine Learning related things.

Most (if not all) of the data sets come from the [UCI Machine Learning](https://archive.ics.uci.edu/ml/index.php). They must be downloaded as needed because they are not included in this repository.

The "Open_Images_Dataset" is an experiment that uses the [Open Images Dataset](https://storage.googleapis.com/openimages/web/index.html) to obtain images. At the moment, the folder contains code to train data on big cats like lions and tigers. Due to lack of access to sufficiently powerful software, I am unable to fully train the neural network; there was an attempt to do so on Google Colab, but there was not enough RAM to allow for a high enough quality image.

The "Setup" folder contains the Dockerfile I used to start the developer enviroment. Docker-compose does expect that this folder is to be renamed to "~/tfDir" so that it can mount this directory into the container.
