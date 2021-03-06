# Drone-and-Robotics
Gachon University 2020 Fall semester

* Introduction : 2020 Fall semester Drone and Robotics Midterm Project
* Concept : Smart Selfi-Rone
* Member : Park Seong Won
* Task : Take a selfi through the Smart Drone

# Algorithm
1. Receive mode input from user's keyboard
2. Recognize the Face
3. The drone's position is adjusted until it reaches the face area that matches the input mode.
4. When the face area reaches the specified value, pictures are taken 5 times at 1 second intervals.
5. After taking a picture, flip it.
6. Repeat until "q" is entered from the user's keyboard.

# Mode
* Selfi Mode
* Half Mode
* Full Mode

# Proposal Presentation
* Selfie Rone Proposal: [[PPTX](https://drive.google.com/file/d/1SmKBYX_LeN28cn0YOfvayCcQzonjKj5m/view?usp=sharing)]

# Demo video (2020/11/06 Fri.)
* Introduction: [[Video1](https://drive.google.com/file/d/1uPZNUORh5YrPnLT0MgBV4J3P_IPJl68n/view?usp=sharing)]
* Execution: [[Video2](https://drive.google.com/file/d/1x7Fmtb-u_2XtLRN8AWnngtexW7QYhhUR/view?usp=sharing)]

# Result Image
* Selfi Mode
![ScreenShot](Selfi_Mode/Selfi_Mode_img_5.jpg)

* Half Mode
![ScreenShot](Half_Mode/Half_Mode_img_5.jpg)

* Full Mode
![ScreenShot](Full_Mode/Full_Mode_img_5.jpg)

# Environment
* OS: Windows 10 (Boot Camp)
* Drone Model: Tello EDU

# Problem Solving
* I need to recognize the body in full mode, but it was not well recognized unlike the face. 
  
  -> Instead, I took a picture by bypassing the method of taking a picture by recognizing a small face.
