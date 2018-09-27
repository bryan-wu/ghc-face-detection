# Description
This repository is prepared for Grace Hopper Celebration workshop session: Confronting Algorithmic Bias in Artificial Intelligence. The repository contains implementation of mobilenet-ssd for face detection written in keras. The model training portion is borrowed from https://github.com/bruceyang2012/Face-detection-with-mobilenet-ssd

# Required Software
## Mac (macOS 10.12.6 Sierra or above)
# Preferred method
1. Download and install [Python3](https://www.python.org/ftp/python/3.6.5/python-3.6.5-macosx10.9.pkg) from official site.
2. Upgrade pip to the latest

`python3 -m pip install --user --upgrade pip`

3. Install virtualenv

`python3 -m pip install --user virtualenv`

4. Create a virtualenv

`python3 -m virtualenv env`

5. Activating the virtualenv

`source env/bin/activate`

6. Install required python packages

`pip3 install keras tensorflow opencv-python jupyter imutils sklearn pillow beautifulsoup4 matplotlib tqdm`

## Linux (16.04 or above)
1. Install Python 3

`sudo apt update && sudo apt install python3.6`

2. Install required python packages

`pip3 install keras tensorflow opencv-python jupyter imutils sklearn pillow beautifulsoup4 matplotlib tqdm`

# Live Inference
The repository comes with a pre-trained model to detect faces from the webcam video. Follow the steps to run this inference 

1. [Download](https://github.com/vinay-h/ghc-face-detection/archive/master.zip) or clone this repository by clicking the 'clone or download' button on this page. 
2. Unzip the downloaded zip file.
3. Open a terminal and run the following command:

`cd <download directory>`

`jupyter notebook`

4. Jupyter will open a new tab or window on your default browser. Click on 'live.ipynb', and click 'Run' on each cell to execute. Once you reach the last cell, wait a few seconds for a new window to open up. You can see the face detection in action!

5. Press 'p' key on the video window to pause and 'Esc' key to stop the inference.

<!--
Miniconda3
1. [Miniconda3]()

`wget https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh -O ~/miniconda.sh`
`bash ~/miniconda.sh -b -p $HOME/miniconda`
`source $HOME/miniconda/bin/activate`

2.  Install required python packages
`conda install -y python=3.6.5 tensorflow keras jupyter scikit-learn 


1. [Brew](https://brew.sh) - package manager for Mac

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

2. [Python3.6.5](https://www.python.org/download/releases/3.0)

`brew install https://raw.githubusercontent.com/Homebrew/homebrew-core/f2a764ef944b1080be64bd88dca9a1d80130c558/Formula/python.rb`

3. Python packages
* [Keras](https://keras.io) - high-level deep learning library for Python.
* [Tensorflow](https://www.tensorflow.org) - Machine learning framework which serves as backend for Keras.
* [OpenCV](https://opencv.org) - Computer vision library.
* [Jupyter](http://jupyter.org) - Interactive editor to run python code
* [ImUtils](https://github.com/jrosebr1/imutils) - Convenience functions for basic image processing
* sklearn
* matplotlib
* tqdm
* pillow
* beautifulsoup4

`pip3 install keras tensorflow opencv-python jupyter imutils sklearn pillow beautifulsoup4 matplotlib tqdm`

# Troubleshooting steps
1. If Python 3 is installed previously without using brew, then use following command to install python packages

`/usr/local/bin/pip3 install keras tensorflow opencv-python jupyter imutils sklearn pillow beautifulsoup4 matplotlib tqdm`

2. If previous python packages were installed with root permission, and if that is preventing installing above packages, please run the following command

`sudo pip3 install keras tensorflow opencv-python jupyter imutils sklearn pillow beautifulsoup4 matplotlib tqdm`

3. If you see the following error, make sure the OS version is 10.12.6 or above. To check the version, click Apple log in the top left corner and select 'About This Mac'

`ImportError: dlopen(/usr/local/lib/python3.6/site-packages/tensorflow/python/_pywrap_tensorflow_internal.so, 6): Symbol not found: _SecKeyCopyExternalRepresentation
  Referenced from: /usr/local/lib/python3.6/site-packages/tensorflow/python/_pywrap_tensorflow_internal.so (which was built for Mac OS X 10.12)`

# Live Inference
The repository comes with a pre-trained model to detect faces from the webcam video. Follow the steps to run this inference 

1. [Download](https://github.com/vinay-h/ghc-face-detection/archive/master.zip) or clone this repository by clicking the 'clone or download' button on this page. 
2. Unzip the downloaded zip file.
2. Open a terminal and run the following command:

`cd <download directory>`

`jupyter notebook`

3. Jupyter will open a new tab or window on your default browser. Click on 'live.ipynb', and click 'Run' on each cell to execute. Once you reach the last cell, wait a few seconds for a new window to open up. You can see the face detection in action!

4. Press 'p' key on the video window to pause and 'Esc' key to stop the inference.

-->

# Training Model
This is outside the scope of the workshop and is included for the benefit of the audience and for the fullness of the workshop. Please refer to the original GitHub repository for more information on the training: https://github.com/bruceyang2012/Face-detection-with-mobilenet-ssd

# License
MIT LICENSE
