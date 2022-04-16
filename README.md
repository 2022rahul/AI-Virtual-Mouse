# AI-Virtual-Mouse
Creating a virtual mouse using python, functionality of this mouse is moving the cursor with hand action and clicking by pressing thumb and index finger together.
The Librarby which are uesd : Mediapipe , OpenCV , numpy , win32api , pyautogui.

cv2 is opencv and mediapipe is well mediapipe, mp is the short notation that we are using here for mediapipe so anywhere in this code you see mp it is referring to mediapipe ,landmark_pb2 is special class imported from mediapipe it will help us find landmark coordinates for hand features like thumb tip,index finger bottom etc , math class is used to derive the formula to find the distance between two coordinates, win32api is used for cursor movement and click automation
