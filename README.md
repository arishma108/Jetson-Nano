# Jetson-Nano
Using the new and powerful Jetson Nano developer kit and run multiple neural networks in parallel for applications like image classification, object detection, segmentation, and speech processing. Building my own small low power IoT application.

 #Installing TensorFlow-GPU on the Jetson Board
1. Open the terminal on the device and type the following commands:

       sudo apt-get update
       sudo apt-get upgrade
       sudo apt-get install python3-pip libhdf5-serial-dev hdf5-tool
       sudo pip3 install --pre --extra-index-url https://developer.download.nvidia.com/compute/redist/jp/v42 tensorflow-gpu 
       
2. In case of errors like HTTP 404 Not found use the following command:

pip3 install — pre — extra-index-url https://developer.download.nvidia.com/compute/redist/jp/v42 tensorflow
