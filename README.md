# Social Distancing Detection using Python
Analyze and detect Social Distancing between people to avoid the spread of the pandemic Corona Disease
## Getting Started with Python
- Install the latest version of Python from here https://www.python.org/downloads/
- Make sure to check ADD TO PATH checkbox while installing python
- Check if python is installed and is in the Path by executing the below command on Command Prompt
```
python --version
```
## Installation of Packages
Install the below packages using Command Prompt
- Numpy
```
pip install numpy
```
- imutils
```
pip install imutils
```
- OpenCV
```
pip install opencv-python
```
- Scipy
```
pip install scipy
```
## Models used for Object Detection
### Caffe Model
- This Model has more than 20 classes
- It provides Moderate FPS( Frames Per Second ) without GPU

### YOLOv3 Model
- This Model has more than 80 classes
- It provides less FPS without GPU and provides Moderate FPS with GPU
- It is more accurate than Caffe Model

### Key Points to Remember
- Google colab provides 1 GB free GPU (So, we can use YOLOv3 in Google colab for best results)
- You can install YOLOv3 weights on Google colab from the link below https://pjreddie.com/media/files/yolov3.weights

## Entire Flow
![alt text](https://github.com/MohammedaijazS-Hexaware/corona-social-distancing/blob/master/Screenshot%20(158).png)
