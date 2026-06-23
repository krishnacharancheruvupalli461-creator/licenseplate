### License Plate Detection Using OpenCV – Theory (15 Lines)

1. This project performs real-time license plate detection using OpenCV and a webcam.
2. It uses a Haar Cascade Classifier to identify license plates in video frames.
3. The OpenCV library is imported using `import cv2`.
4. The pre-trained license plate detection model is loaded from an XML file.
5. The webcam is accessed using `cv2.VideoCapture(0)`.
6. A message is displayed indicating that detection has started.
7. The program continuously captures frames using a `while True` loop.
8. Each frame is converted to grayscale for faster processing.
9. The `detectMultiScale()` function detects license plates in the image.
10. Parameters like `scaleFactor` and `minNeighbors` improve detection accuracy.
11. The coordinates of detected plates are stored as `(x, y, w, h)`.
12. A green rectangle is drawn around each detected plate.
13. The label "Plate" is displayed above the detected region.
14. The processed video is shown in a window using `cv2.imshow()`.
15. Pressing **'q'** exits the program, releases the webcam, and closes all windows.
