# Intelligent-School-Attendance-System-with-AI-and-IoT-Technology

This project use a Raspberry Pi 4 (model B) and camera module (V2) for creating a "smart surveillance camera" . The surveillance camera will use facial recognition to achieve automatic generation of the attendance in the classroom. 
The interaction with the user is done through a  web-site, behind which is a Flask server. The camera will check the time to see if a course is taking place in the room where it is positioned  or not . If a course is in progress  then students will be registered in a list  and at the end of the course the number of minutes in which they were attended in the classroom will be established . At the end of the course  the presence of a student will be established depending on the number of minutes in which he was detected in the classroom. 
This project allows access to the following users: Administrator , Teacher , Parent and Guardian . 

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
