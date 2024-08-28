## Minute Theft Detection
This project is a Python-based application that uses OpenCV for real-time motion detection and comparison to identify minute theft activities. It leverages structural similarity to spot differences between frames captured from a webcam, alerting the user if any discrepancies are detected.

Features
Real-Time Motion Detection: Continuously monitors the environment using a webcam.
Motion Analysis: Compares current frames to previous ones to detect motion.
Difference Spotting: Utilizes structural similarity to find differences between frames.
Alerts: Provides visual feedback on the detection window and saves images of suspected theft.

Requirements
Python 3.x
OpenCV
NumPy
Scikit-Image

Acknowledgments
OpenCV: For providing powerful tools for image processing.
Scikit-Image: For enabling structural similarity calculations.
