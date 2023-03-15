# Lab-5_202001098

# **Software Engineering: IT 314**

# Parth Agarwal
# 202001098


Date: March 15th  2023

Lab-Group:2
Lab Assignment: **5**   
  
  





*** 
*** 

# STATIC ANALYSIS

Github Repo Link: https://github.com/CT83/SmoothStream

**About Project:**
SmoothStream is a Python Application which makes streaming video from webcams over the network a breeze.
Streaming images from your Webcam over the network should be easy, right?




**Code file: Test.py**
No config file found, using default configuration
Module test_local_streaming
C0111: 1,0: : Missing module docstring
C0111: 11,0: TestLocalStreaming: Missing class docstring
W0108: 21,22: TestLocalStreaming.setUpClass.<lambda>: Lambda may not be necessary
C0111: 25,4: TestLocalStreaming.test_camera_image: Missing method docstring
C0111: 28,4: TestLocalStreaming.test_camera_image_not_null: Missing method docstring

Your code has been rated at **7.92/10**  
  
  

**Code file: constants.py**

No config file found, using default configuration
Module constants
C0111: 1,0: : Missing module docstring

Your code has been rated at **8.75/10**  
  
  

**Code file: StreamerViewer.py**

No config file found, using default configuration
Module StreamViewer
C0301: 28,0: : Line too long (128/100)
C0111: 1,0: : Missing module docstring
E0401: 3,0: : Unable to import 'cv2'
C0111: 11,0: StreamViewer: Missing class docstring
E1101: 19,45: StreamViewer.__init__: Module 'zmq' has no 'SUB' member
E1101: 21,46: StreamViewer.__init__: Module 'zmq' has no 'SUBSCRIBE' member
C0111: 54,0: main: Missing function docstring

Your code has been rated at **5.25/10 (previous run: 5.25/10, +0.00)**  
  
  
**Code file: Streamer.py**

No config file found, using default configuration
odule Streamer
C0301: 15,0: : Line too long (110/100)
C0301: 17,0: : Line too long (115/100)
C0301: 30,0: : Line too long (114/100)
C0111: 1,0: : Missing module docstring
E0401: 3,0: : Unable to import 'cv2'
C0111: 11,0: Streamer: Missing class docstring
E1101: 23,45: Streamer.__init__: Module 'zmq' has no 'PUB' member
C0111: 58,0: main: Missing function docstring

Your code has been rated at **6.44/10 (previous run: 6.44/10, +0.00)**
   
  
