# MovieFrameStack

Inspired by https://thecolorsofmotion.com/ I tried to display the gradient of a movie frame by frame. 
The program is written in Python. The result looks like this.

![result](/img/br2049.jpg "Movie Frames")

## Requirement
* JupyterLab > 1.0.2
* Python 3 

## Input

```movie= "TITLE"
filetype= "mp4"
spf = 30
width = 10 
height = 1000
rot= 0 
```

* A video in mp4 format is required as input. 
* ```spf``` (Seconds per Frame) sets the time between frame extraction
* ```width and ```height specifies the output dimension of each frame
* ```rot ``` changes the image orientation, where ```rot=0``` is a rotation 90 degrees to the right. 
