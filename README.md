# Intelligent-School-Attendance-System-with-AI-and-IoT-Technology

This project proposes to develop a smart surveillance camera using a Raspberry Pi 4 (model B) and camera module (V2). The camera will be used to detect the presence of students in a classroom and to generate an automatic attendance list. The camera will be connected to a web-site, which will be managed by a Flask server. 

The camera will be used to detect the presence of students in a classroom by checking the time to see if a course is taking place in the room where it is positioned or not. If a course is in progress then students will be registered in a list and at the end of the course the number of minutes in which they were attended in the classroom will be established. At the end of the course the presence of a student will be established depending on the number of minutes in which he was detected in the classroom.

The users who will have access to the attendance data are the Administrator, Teacher, Parent and Guardian. The Administrator will have access to the attendance data of all students and the ability to add, modify or delete student information. The Teacher will have access to the attendance data of their classroom and the ability to add, modify or delete student information. The Parent and Guardian will be able to view the attendance data of their student.

The first step in this project is to set up the Raspberry Pi 4 and camera module. The Raspberry Pi 4 is a small, single-board computer which can be used to run a variety of operating systems. The camera module, which is included in the Raspberry Pi 4, is a 5 megapixel camera which can capture still images and video. 

Once the Raspberry Pi 4 and camera module are set up, the next step is to install the software needed for the project. The software that will be used is the open-source software OpenCV. OpenCV is a library of computer vision algorithms which can be used for facial recognition and tracking. 

Once the software is installed, the next step is to configure the camera. This involves setting the resolution of the camera, the frame rate and the exposure settings. Additionally, the camera must be calibrated so that it is able to detect faces accurately. Once the camera is configured, the software can be used to detect faces in the video feed from the camera. 

The final step is to create a web-site which will be used for the project. This web-site will be used to display the attendance data and to provide access to the users. The web-site will be managed by a Flask server and will use HTML, CSS and JavaScript for the design and functionality. 

Once the web-site is created, the project is complete. The smart surveillance camera can now be used to detect the presence of students in the classroom and to generate an automatic attendance list. The users can access the attendance data through the web-site. 

This project could be easily adapted to other uses. For example, it could be used to detect the presence of employees in an office or to monitor the attendance of students in a school. Additionally, the software could be used to detect other objects such as vehicles or animals. The possibilities are endless.

![raspberry-pi-camera-pinout-camera-2](https://user-images.githubusercontent.com/56380723/208130340-a3b88771-53ab-4dd4-9fea-653f476a7d5d.png)

# Specification

- The "data" folder is an empty folder used to save images (used to train the neural network for facial recognition)

- To take the necessary images, the user must run the script "training.py" in the Raspberry Pi terminal for the facial scanning of students .

- In the "em2.py" file is the main project with all the features and functions .

# Requirements

- Python 3.x

- Flask

- TensorFlow

- OpenCV

- SHA256

- SQLite 3

- SQLAlchemy

# Wath I Learned

- Encrypting data using hash function

- Computer Vision (facial detection)

- Machine Learning (facial recognition)

- Internet of Things (remote controling the Raspberry Pi via client-server services)

- Web site desing using CSS and FlaskForm
