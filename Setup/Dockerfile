FROM tensorflow/tensorflow:latest-jupyter
RUN apt-get update
RUN apt-get install -y graphviz
RUN pip3 install pandas sklearn graphviz Pillow keras-tuner tf-agents
RUN pip3 install cloudpickle==1.4.1
RUN mkdir /tf/experiments
