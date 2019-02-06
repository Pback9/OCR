This project is an OCR project that detects text in a scene
and then outputs a prediction of what the text says. It requires
the CV2 and Tesseract libraries to function along with the pre trained
frozen east text detection model.
The image_detection file detects text from a given image from the command line
and the video_detection file detects text from a webcam. Each require python3 to run
and can be run with the following commands:

Python3 image_detection.py [image]
Python3 video_detection.py
