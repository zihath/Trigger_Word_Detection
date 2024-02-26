# How to do Real Time Trigger Word Detection with Keras.

Trigger word detection, aka. wake/hot word detection. Like Amazon's "Alexa" or Google Home's "OK, Google" to wake them up.
Will it be cool to build one yourself and run it in **Real-time**?

In this post, I am going to show you exactly how to build a Keras model to do the same thing from scratch. No third party voice API or network connection required to make it functional.

Background information is shown in my blog post.

## How to Run
Require [Python 3.5+](https://www.python.org/ftp/python/3.6.4/python-3.6.4.exe) and [Jupyter notebook](https://jupyter.readthedocs.io/en/latest/install.html) installed
### Clone or download this repo
```
git clone https://github.com/zihath/trigger_word_detection
```
### Install required libraries
`pip3 install -r requirements.txt`


### Real-time demo

In the project directory start a command line, then run command
```
jupyter notebook
```
If you want to learn about data preparation and model training. In the opened browser window choose this notebook.
```
Trigger word detection - v2.ipynb
```
Download the train/dev Data from the releases if you want to follow along the notebook. Extract `XY_dev` and `XY_train` folders to the root of the project directory.
##Results
You can result in the chime_output.wav file. 
Happy coding! 
