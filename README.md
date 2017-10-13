# YOLOobjectDetection-SanFranciscoSunset
This repository is a YOLO object detection project, using the dash camera videoes taken from streets of the Sunset District in 
San Francisco. The object detection algorithm is YOLO. The YOLO model weights file is 'yolo-tiny.weights'.   The object detection is 
similiar to SSD, which has weights for object detection. The ipython script, is YOLOobjectDetectionVideoProc.ipynb. This script detects
objects such persons, cars, and trucks. This script processes each frame in the input video by detecting 
objects, using openCV to detect traffic light color specifically for traffic lights. Then, it passes the processed image in each frame 
into a stream output video with YOLO object detection and openCV traffic light color detection.

Instruction on how to run the ipython script:
1)  Open the Anaconda prompt
2)  Type "jupyter notebook" will open up an internet browser
3)  From your internet browser, click on icons up to the directory where the "trafficLightColorDetectionOpenCV.ipynb" ipython script is 
    located.
4)  Double click on this file to run the openCV traffic light color classification.
5)  Double click on the run button in Anaconda to run the script.
6)  Once this ipython is completed, from your internet browser, double click on another file to run the YOLO object detection
    script, "YoloPedestrianCarDetection.ipynb".
7)  Once this file is opened up in your browser, double click on the run button will produce the output videoes where the output 
    videos are located in the test_videos directory.

