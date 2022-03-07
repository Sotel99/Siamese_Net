Project: Real-time face recognition using siamese Neural Network

Technologies: Keras and Opencv

Files in project:
1. "haarcascade_frontalface_default"- used for face detection using Haar Cascades.
2. "Face"- contains cropped face obtained during onboard process to which we compare faces which are detected in camera.
3. "Samples"- contain 10 photos of each of 40 persons used as training and validation set.
4. "final.ipynb"- jupyter notebook which contains code.


To start program you need to unzip it and open project in Jupyter Notebook.
Program will make you a photo and cropp your face of it. Later program will ask for your name. Then program will open camera once again and check if face detected on camera is the same face as on the photo.
To stop process press "q"