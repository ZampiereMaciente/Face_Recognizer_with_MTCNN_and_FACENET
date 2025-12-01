# Face Recognizer with MTCNN and FACENET

### Description

Simple real-time facial recognition project that uses MTCNN for face detection and the FaceNet model (via keras-facenet) to extract embeddings and compare faces.

### Features

Face capture via webcam and saving to disk (press r to capture and register a person).
Real-time facial recognition comparing embeddings with saved faces.
Dynamic margin adjustment around the face for good captures.

### Project Structure

- recognize_faces/: main source code.
  - recognize_faces/recognize_faces.py: implements detection, capture, embedding removal, and recognition.
  - recognize_faces/capture.py: (invokes) function to capture faces.
  - recognize_faces/detect.py: (invokes) function for real-time recognition.

### Libraries used
>[Opencv](https://opencv.org/ "https://opencv.org/")

>[MTCNN](https://github.com/ipazc/mtcnn "https://github.com/ipazc/mtcnn")

>[Keras](https://pypi.org/project/keras-facenet/ "https://pypi.org/project/keras-facenet/")

>[Numpy](https://pypi.org/project/numpy/ "https://pypi.org/project/numpy/")

>[OS](https://docs.python.org/pt-br/3/library/os.html "https://docs.python.org/pt-br/3/library/os.html")
