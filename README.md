 # Batch A1 
 # Virtual Mouse 
 ## About the project
Virtual Mouse makes human computer interaction simple by making use of Hand Gestures and Voice Commands. The computer requires almost no direct contact. All I/O operations can be virtually controlled by using static and dynamic hand gestures along with a voice assistant. This project makes use of the state-of-art Machine Learning and Computer Vision algorithms to recognize hand gestures and voice commands, which works smoothly without any additional hardware requirements. It leverages models such as CNN implemented by MediaPipe  

## Prerequisites 
 Hardware requirements
 ```
 Processor - i3
 RAM - 4GB
 Webcam
 Speakers
 Microphone
 ```
 Software Requirements
 ```
 OS - Windows
 IDE - PyCharm
 Python
 Anaconda Distribution
 ```
 ## Features  
 
 ## Virtual Mouse  
 
 * Neutral Gesture
 * Move Cursor
 * Left Click
 * Right Click
 * Double Click
 * Scrolling
 * Drag and Drop
 * Multiple Item Selection
 * Volume Control
 * Brightness Control  
 ## Voice Assistant (Proton)  
 * Launch/Stop Virtual mouse
 * Google Search
 * Finding location on google maps  
 * File Navigation
 * Current Date/Time
 * Copy and Paste
 * Sleep/ Wake Proton
 * Exit  
 
 ## Installation
 
 Step 1 : Extract the files  
 
 Step 2 :
  ```bash
  conda create --name gest python=3.8.5
  ```
  
  Step 2:
  ```bash
  conda activate gest
  ```
  
  Step 3:
  ```bash
  pip install -r requirements.txt
  ```
  
  Step 4:
  ```bash 
  conda install PyAudio
  ```
  ```bash 
  conda install pywin32
  ```
  
  Step 5:
  ``` 
  cd to the GitHub Repo till src folder
  ```
  Command may look like: `cd C:\Users\.....\Gesture-Controlled-Virtual-Mouse\src`
  
  Step 6:
  
  For running Voice Assistant:
  ```bash 
  python Proton.py
  ```
  ( You can enable Gesture Recognition by using the command "Proton Launch Gesture Recognition" )  
  
  For running Virtual Mouse:
  ```bash
  python Gesture_Controller.py
  ```  
  ## Project Developers  
  
  * Deepika P
  * Janani N
  * Janet Jessica R
  
  
  
         
       
