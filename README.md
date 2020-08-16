## YesProf!:Novel-Based Approach to Facilitate Virtual Learning

This technology consists of two significant entities that include attendence tracking feature using face recognition and pdf-generated engagement session report. It purely fulfills its purpose of providing student data such as attendance and reports to instructors to track their students' progress and drive them in the correct path of achievement. 

### Stage 1: Attendance Tracker 

Once entering into the virtual meeting environment(such as zoom or google meet), this feature enables face recognition of students to track their presence and punctuality. This feature was built using OpenCV and python. The dependencies that were used are listed below:
1. cv2
2. numpy np
3. os
4. face_recognition
5. datetime
6. imutils VideoStream

Once these dependencies are installed using pycharm file settings, they can be imported using the following commands:
```
import cv2
import numpy as np
import os
import face_recognition
from datetime import datetime
from imutils.video import VideoStream
```
Save the images from ImagesAttendance File and use them for the path. Find encodings and mark attendance to connect directly to the csv file (which can be opened as an excel document). 

The boxes are added around the faces and this will be run through the demo video (mp4 file format). This will allow the recognition of faces which is recorded in the tracker for teachers to utilize.


### Stage 2: Session Engagement Reports
