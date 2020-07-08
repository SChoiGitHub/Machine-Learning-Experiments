# Machine Learning Experiments

These are my personal experiments with TensorFlow and python Machine Learning related things.

Most (if not all) of the data sets come from the [UCI Machine Learning](https://archive.ics.uci.edu/ml/index.php). They must be downloaded as needed because they are not included in this repository.

The "Open_Images_Dataset" is an experiment that uses the [Open Images Dataset](https://storage.googleapis.com/openimages/web/index.html) to obtain images. At the moment, the folder contains code to train data on big cats like lions and tigers. Due to lack of access to sufficiently powerful software, I am unable to fully train the neural network; there was an attempt to do so on Google Colab, but there was not enough RAM to allow for a high enough quality image. This project may be re-explored now that I know about CNNs.

Flower Classification was done entirely on Google Colab. Data comes from the Tensorflow Team; more details on in the notebook files there.

Topics:

- Supervised Learning
  - Iris
  - Adult
  - Breast Cancer
  - Bike Sharing
  - Open Images Dataset (WARNING: Unable to properly train and test.)
  - Weather Prediction (First Use of RNNs and LSTMs are here)
  - Flower Classification (First Use of Keras-Tuner's Hyperband and CNNs are here)
- Unsupervised Learning
  - TF-Agents

The "Setup" folder contains the Dockerfile I used to start the developer enviroment. Docker-compose does expect that this folder is to be renamed to "~/tfDir" so that it can mount this directory into the container. Some of the juypter journals assume a Google Colab enviroment
since Google is able to provide better hardware.

Much of this work was done with the help of Google's TensorFlow guides.

Portions of this page are modifications based on work created and [shared by Google](https://developers.google.com/readme/policies) and used according to terms described in the [Creative Commons 4.0 Attribution License](https://creativecommons.org/licenses/by/4.0/).