FROM tensorflow/tensorflow:latest-jupyter
RUN apt-get update
RUN apt-get install -y graphviz
RUN pip3 install pandas sklearn graphviz Pillow keras-tuner
RUN mkdir /tf/experiments
