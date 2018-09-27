# Description
This repository is prepared for Grace Hopper Celebration workshop session: Confronting Algorithmic Bias in Artificial Intelligence. The repository contains implementation of mobilenet-ssd for face detection written in keras. The model training portion is borrowed from https://github.com/bruceyang2012/Face-detection-with-mobilenet-ssd

# Required Software
## Mac (macOS 10.12.6 Sierra or above)
1. [Brew](https://brew.sh) - package manager for Mac

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

2. [Python3.6.5](https://www.python.org/download/releases/3.0)

`brew install https://raw.githubusercontent.com/Homebrew/homebrew-core/f2a764ef944b1080be64bd88dca9a1d80130c558/Formula/python.rb`

3. [Keras](https://keras.io) - high-level deep learning library for Python.
4. [Tensorflow](https://www.tensorflow.org) - Machine learning framework which serves as backend for Keras.
5. [OpenCV](https://opencv.org) - Computer vision library.
6. [Jupyter](http://jupyter.org) - Interactive editor to run python code
7. [ImUtils](https://github.com/jrosebr1/imutils) - Convenience functions for basic image processing

`pip3 install keras tensorflow opencv-python jupyter imutils`

# Live Inference
The repository comes with a pre-trained model to detect faces from the webcam video. Follow the steps to run this inference 

1. [Download](https://github.com/vinay-h/ghc-face-detection/archive/master.zip) or clone this repository by clicking the 'clone or download' button on this page. 
2. Open a terminal and run the following command:

`cd <download directory>`

`jupyter notebook`

3. Jupyter will open a new tab or window on your default browser. Click on 'live.pynb', and click 'Run' on each cell to execute. Once you reach the last cell, wait a few seconds for a new window to open up. You can see the face detection in action!

# Training Model
This is outside the scope of the workshop and is included for the benefit of the audience and for the fullness of the workshop. Please refer to the original GitHub repository for more information on the training: https://github.com/bruceyang2012/Face-detection-with-mobilenet-ssd

# License
MIT LICENSE
