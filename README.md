# Riyadhvision 
Realtime pothole severity classifier powered by Deep Learning  

## Installation Instructions

0.U  need  `Python 3`, `python-3-devel`, `gcc`, `virtualenv`, and `pip` installed.     
1. Clone the repository

    ```bash
        $ git clone https://github.com/Allujain/Riyadhvision.git
        $ cd Riyadhvision
    ```  
2. Create a python 3 virtualenv, activate the environment and Install the project dependencies.   

    a. Linux Users:
  
    ```bash  
        $ virtualenv vir
        $ source vir/bin/activate
        $ pip3 install -r requirements.txt 
    ```  

    b. Windows Users:  

    ```bash
        $ virtualenv vir
        $ vir\Scripts\Activate
        $ pip3 install -r requirements.txt
    ```   

You have now successfully set up the project on your environment.  

## Tech Stack  
1) TensorFlow
2) Python
3) OpenCV
4) Tkinter  

## Usage  
a) Command line mode:  
```
  python3 classifier.py --inputvideo="path/to/video.mp4"
```
b) Simple GUI:  
```
  python3 GUI.py
```  
