# Variable-size-adaptive-block-matching-motion-estimation
The source code for the two published papers on adaptive block matching motion estimation with variable size blocks

## Description
Using Python, I Created a method for block matching motion estimation (ME), with a focus on variablesize blocks. First, I designed a fast and efficient way to automatically generate blocks with different
shapes and sizes according to the identified location and direction of movement. Next, by utilizing
adaptive search tools, (e.g. the search window size selection, global motion compensation, changing
reference frame), I attempted to decrease the computation load while maintaining the quality of ME.

## Requirements
```
$ pip install PyQt5
$ pip install opencv-python
$ pip install numpy
$ pip install pandas (For analyzing data)

To use this code, please ensure that you have placed the sample video sequences inside the "resources" folder.

If you need to download video sequences, you can check the following links:
http://trace.eas.asu.edu/yuv/
https://media.xiph.org/video/derf/

```
![block1](https://user-images.githubusercontent.com/131509932/233799434-ef7b0fd7-58be-40da-aa63-ddbce6c91a72.png)
