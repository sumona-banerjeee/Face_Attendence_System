# Face_Attendence_System_STAR

This project works on face recognition and provide a automate the process of recording attendance in the csv file by using face recognition technology and machine learning algorithms. Through the various libraries like Opencv, Numpy, face recognition. This project can be helpful for the capturing the face and marking their attendance in the csv file and logs attendance into a CSV file with timestamps.

## Features
- Real-time face detection, recognition from webcam feed & Marking attendance of individual.
- Attendance logging with individual names and timestamps noted in the CSV file with proper date and time.
- Simple and easy-to-understand code structure of the python.
- Should install libraries by using command "pip install package_name".

## Command

- pip install face_recognition
- pip install opencv-python
- pip install numpy

## Requirements
- Python 3.x
- Anaconda
- Jupyter Notebook
- Libraries:
  - face_recognition
  - OpenCV (cv2)
  - NumPy
  - datetime
  - csv

## Installation
1. Install Python if not already installed or Anaconda from their official websites.
Python: https://www.python.org/downloads/
Anaconda: https://docs.anaconda.com/free/anaconda/install/windows/ 
2. Install required libraries using pip in the terminal.
3. Note: If you are facing any problem related to the Installation of face_recognition or Dlib installation problem then follow several steps given below and download the attach file for linking by following steps.


1. Open terminal: python --version
2. pip install file_name (Choose from Dlib-library-Installation-main as per version with full link)
3. pip install cmake
4. pip install face-recognition

## Usage
1. Place images of known individuals in the same directory as the script within the same file.
2. Update the file names in the script to match the images of known individuals.
3. Run the script
4. Press the 'a' or any provided key to exit the program and save the attendance records.

## Notes
- Ensure your webcam is connected and properly configured.
- This script is a basic implementation and may require further customization for specific use cases.
- The attendance records are saved in a CSV file with the date as the filename.

## Credits
This script utilizes the following libraries:
- [face_recognition](https://github.com/ageitgey/face_recognition): For face detection and recognition.
- [OpenCV (cv2)](https://opencv.org/): For video capture and image processing.
- [NumPy](https://numpy.org/): For array manipulation and mathematical operations.
- [datetime](https://docs.python.org/3/library/datetime.html): For handling date and time.
- [csv](https://docs.python.org/3/library/csv.html): For reading and writing CSV files.

### Acknowledgments

Thanks to Adam Geitgey and contributors for the face_recognition Developed, Open Source Computer Vision Library (Opencv),NumPy developed by Travis Oliphant, Python Standard Library for datetime and csv libraries.

### Author

Sumona Banerjee

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.