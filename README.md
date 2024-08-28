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
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/minute-theft-detection.git
Navigate to the project directory:
bash
Copy code
cd minute-theft-detection
Install the required packages:
bash
Copy code
pip install -r requirements.txt
How to Use
Run the main application:

bash
Copy code
python main.py
UI Interaction:

The application window will display a simple interface with buttons to start the motion detection (Spot Diff) or exit the application.
Upon detecting motion, the program will analyze for differences and notify the user.
Output:

If theft is detected, images highlighting the differences will be saved in the stolen/ directory.
Project Structure
find_motion.py: Handles motion detection and triggers the difference spotting process.
spot_diff.py: Analyzes frames to detect differences and generates alerts.
main.py: Provides a simple Tkinter GUI for user interaction.
Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue if you have any suggestions or improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
OpenCV: For providing powerful tools for image processing.
Scikit-Image: For enabling structural similarity calculations.
