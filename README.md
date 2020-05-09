# object_detection


##  Software setup
## 1. Install Python and Anaconda

Download Anaconda for windows
python 3.7 version or above
https://www.anaconda.com/products/individual

Attention: check ‘Add Anaconda to my PATH environment variable'

## 2. Create virtual environment

In command line console, input the following command: 


    conda create --name ocv4 python=3.7
    activate ocv4

on Ubuntu:

    conda create --name ocv4 python=3.7
    conda activate ocv4
    

### 2.3 Install cmake ,numpy, and opencv
In command line console, input the following command: 

    pip install cmake
    pip install numpy
    pip install opencv-contrib-python==4.0.1.24
    conda install -c conda-forge dlib

## 3. Install a text editor (optional)
You can use your own IDE for python. We will use atom for this course.
Down load atom from https://atom.io/

After installation, please import python packages:
From atom menu:
Packages->settings view->Install packages/Themes
Then, please input:

    autocomplete-python




