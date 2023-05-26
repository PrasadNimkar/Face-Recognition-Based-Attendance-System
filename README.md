# Face Recognition Based Attendance System


# Problem Statement
Traditional student attendance marking technique is often facing a lot of trouble. The face recognition student attendance system emphasizes its simplicity by eliminating classical student attendance marking technique such as calling student names or checking respective identification cards. There are not only disturbing the teaching process but also causes distraction for students during exam sessions. Apart from calling names, attendance sheet is passed around the classroom during the lecture sessions. The lecture class especially the class with a large number of students might find it difficult to have the attendance sheet being passed around the class. Thus, face recognition attendance system is proposed in order to replace the manual signing of the presence of students which are burdensome and causes students get distracted in order to sign for their attendance. Furthermore, the face recognition based automated student attendance system able to overcome the problem of fraudulent approach and lecturers does not have to count the number of students several times to ensure the presence of the students. 

# Project Definition
Design of an automatic class attendance system using face detection algorithm of LabVIEW
software. The system requires a video capture device and the running LabVIEW algorithm to be
implemented successfully. It detects the faces and mark attendance accordingly. This system will
prevent unnecessary wastage of time of classes that is usually wasted in form of class roll calls.

# Project Objectives
1. Reducing time wastage during conventional class attendance.
2. Utilizing latest trends in machine vision to implement a feasible solution for class
attendance system.
3. Automating the whole process so that we have digital environment.
4. Preventing fake roll calls as one to one attendance marking is possible only.
5. Encouraging the use of technology in daily lives.
The objective of this project is to develop face recognition
attendance system. Expected achievements in order to fulfill the
objectives are:
• To detect the face segment from the video frame.
• To extract the useful features from the face detected.
• To classify the features in order to recognize the face
detected.
• To record the attendance of the identified student.

# Code Requirements
Python 3.6+
Opencv (pip install opencv-python)
Tkinter (Available in python)
PIL (pip install Pillow)
Pandas (pip install pandas)
Numpy (pip install numpy)
Pillow (pip install Pillow)

haarcascade_frontalface_default.xml  ->>>> 
haarcascades - the folder contains trained classifiers for detecting objects
               of a particular type, e.g. faces (frontal, profile), pedestrians etc.
               Some of the classifiers have a special license - please,
               look into the files for details.
https://github.com/opencv/opencv/tree/master/data/haarcascades

#Design Requirements
We used some tools to build the HFR system. Without the help of
these tools it would not be possible to make it done. Here we
will discuss about the most important one.

# Software Implementation
1. OpenCV: We used OpenCV 3 dependency for python 3. OpenCV is
library where there are lots of image processing functions
are available. This is very useful library for image
processing. Even one can get expected outcome without writing
a single code. The library is cross-platform and free for
use under the open-source BSD license. Example of some
supported functions are given bellow:
• Derivation: Gradient / laplacian computing, contours
delimitation
• Hough transforms: lines, segments, circles, and
geometrical shapes detection
• Histograms: computing, equalization, and object
localization with back projection algorithm
• Segmentation: thresholding, distance transform, foreground
/ background detection, watershed segmentation
• Filtering: linear and nonlinear filters, morphological
operations
• Cascade detectors: detection of face, eye, car plates
• Interest points: detection and matching
• Video processing: optical flow, background subtraction,
camshaft (object tracking)
• Photography: panoramas realization, high definition
imaging (HDR), image inpainting

# Python IDE
Editor - Visual studio code

# Project flow & explaination
After you run the project you have to register your face so that system can identify you, so click on register new student
After you click a small window will pop up in that you have to enter you ID and name and then click on Take Image button
After clicking Take Image button A camera window will pop up and it will detect your Face and take upto 50 Images(you can change the number of Image it can take) and stored in the folder named TrainingImage. more you give the image to system, the better it will perform while recognising the face.
Then you have to click on Train Image button, It will train the model and convert all the Image into numeric format so that computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.
It will take some time(depends on you system).
After training model click on Automatic Attendance ,you have to enter the subject name and then it can fill attendace by your face using our trained model.
it will create .csv file for every subject you enter and seperate every .csv file accoriding the subject
You can view the attendance after clicking View Attendance button. It will show record in tabular format.

# Flow Chart

![Flow chart Dec](https://github.com/PrasadNimkar/Face-Recognition-Based-Attendance-System/assets/83298007/ad0e986d-eba2-484c-a7a7-acd7f6699997)
![FLow Chart](https://github.com/PrasadNimkar/Face-Recognition-Based-Attendance-System/assets/83298007/33671079-29cf-4552-b2e9-086c1754595f)
![Block Diagram](https://github.com/PrasadNimkar/Face-Recognition-Based-Attendance-System/assets/83298007/81de54d9-8a06-4a70-b3c9-a1a6a4fb2ab5)
![Flow chart basic](https://github.com/PrasadNimkar/Face-Recognition-Based-Attendance-System/assets/83298007/79962ce7-37a5-470b-9aeb-13f413afd652)
