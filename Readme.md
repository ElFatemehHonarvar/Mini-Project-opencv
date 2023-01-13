# Facial Recignition on Video

Face recognition system is used in order to automatically identify a person from an image or a video source. The recognition task is performed by obtaining facial features from an image of the subject's face.
Here I used opecv and face-recognition to identify some artists on a video.


### Required libraries

> import cv2
> import face_recognition
> import os
> import numpy as np

Note : To install face-recognition library, you must install dlib at first.

How this program works ?
Initially,  known images are fetched and encoded as a trainset. After receiving a video each frame of the camera is compared with known images in terms of 128 measurements for each face. The result of face recognition will be shown as the movie broadcasts.
