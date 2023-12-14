# Projects

## Music Processing and Chord Prediction System
**Technologies Used:** Signal Processing, Python, C++, Raspberry Pi, Arduino<br>
**My Role:** Project Manager, Signal Processing Software Team, Embedded Software Team<br>
**Demo Link:** https://youtu.be/7riGIKL9tzo <br>
**Description:** Created a music processing and chord prediction system. The user would input an MP3 into our web app, and we used audio processing techniques to find the chords that would accompany the audio file best. The audio file and the chords were then sent to a Raspberry Pi and an Arduino so they could be displayed in an LED matrix while the song played.<br>


Figure: System diagram with all the components of the project.


Figure: Images of the embedded systems of the project.

## Autonomous Foosball Goalkeeper
**Technologies Used:** Computer Vision, Python, Image Processing<br>
**My Role:** Software Design Team<br>
**Demo Link:** https://youtu.be/qmzbtvmiw2Q <br>
**Description:** Created an autonomous foosball goalkeeper. Using one camera above the table, we tracked the location of the ball and predicted its movement. We used ArUco tags and homography for calibration, and color recognition for ball identification. Based on the expected end location of the ball, we used a stepper motor controlled by a microcontroller to move the goalkeeper to a location where the shot would be blocked.<br>


Figure: Image captured by camera detecting the corners of the table and the ball.


Figure: System diagram with the components of the project.

## Sarcasm Classifier
**Technologies Used:** Machine Learning, Natural Language Processing<br>
**My Role:** Software Design Team<br>
**Description:** Classified sarcastic and non-sarcastic phrases. Using a self-labeled Reddit comment dataset with 1 million data points, we implemented a classifier using “text-CNN” methods. We tested different learning rates, regularization values, and optimizers. In the end, we achieved an accuracy rate of 74% on the testing dataset given that sarcasm is highly dependent on context.<br>

Figure: Diagram showing the model we used for our sarcasm classifier.


Figure: Loss and accuracy graphs across epochs. Given a lack of access to GPUs, small amounts of data were processed.


## 3D Room Mapping Using Binaural Audio
**Technologies Used:** HRTF, Real-Time Audio Processing, Python, Raspberry Pi<br>
**My Role:** Team Leader<br>
**Description:** Used an ultrasonic sensor on an RPi to detect objects around the user. When an object was found, we convolved audio with HRTF data to let the user know where the object was located. The purpose of this project was to aid the visually impaired through sound.<br>

Figure: Diagram demonstrating the purpose of the project (left) and assembled product (right).


Figure: System diagram with the components of the project.

