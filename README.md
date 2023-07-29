# Fire_Detection_System_Using_Yolov8
This is a fire detection alarm system with an accuracy between 80-85% made using Yolov8(a convulational neural network model) and OpenCV  where we can detect any type of fire with camera or from any source.

First create a  virtual enviornment with python or install all the packages into your system directly with these steps-:

1) open any CLI navigate to this folder

2) type this command ->    pip install -r requirement.txt

3) This will install all the dependencies required to run this thing

4) Now you can either run this command to launch the fire detection system using your web cam -> python detect.py

5) or we can use yolo command to detect the fire from a video or picture using this CLI Command -> yolo task=detect mode=predict model=best.pt source="Your_file_source_here"

6) And then click enter now the result will be saved in runs/detect folder you'll get a directory link as well from your CLI to navigate to that folder and check the results.

7) if you are using multiple webcams then change OpenCV VideoCapturing to 0 to N (0 is for web cam and 1 for web cam and so on)

8) we can also add ip cameras over here with ip and username password in the same field

This is my first ever repo in GitHub so please excue for any inconvenience :)
