# Garbage Profiling
## About Garbage_profiling: I had recommended 6 classes namely plastic, paper, cardboard, metal, other non biodegradable and biodegradeable. 
## As this model has ability to detect garbage by input image or in real-time.

### Dataset --> [kaggle](https://www.kaggle.com/techsash/waste-classification-data)

### Following are steps I'm going to discuss how to run this project on your local machine.



#### To install YOLOv3 on your local machine follow this [repo](https://github.com/AlexeyAB/darknet) or use this youtube [video](https://www.youtube.com/watch?v=DjO9UtSON6U&t=1189s)

#### After installing darknet/yolov3 install packages:

1. For opencv ---> pip install opencv-python

2. For numpy ---> pip install numpy

3. For argparse ---> pip install argparse

#### You have to place the file in respective directory:

1. move obj.data file to cfg folder of darknet (example ---> C:\darknet\darknet-master\build\darknet\x64\cfg)

2. move obj.names to data folder of darknet (example ---> C:\darknet\darknet-master\build\darknet\x64\data)

3. Download weights file from this [link](https://drive.google.com/file/d/1ngpL0ZAPcJ4WkTEgfUuUDbRzn-Whq8JQ/view?usp=sharing)

4. move weights file to x64 of darknet (example ---> C:\darknet\darknet-master\build\darknet\x64)

5. move yolo-garbage1.cfg to cfg folder of darknet (example ---> C:\darknet\darknet-master\build\darknet\x64\cfg)

#### After installing packages and place file in respective directory run garbage_profiling.py file

- If it throws error you can Google or reach me.

- Important Note: This project can run without garbage_profiling.py by following commands:

1. To run using input image: darknet detector test cfg/obj.data cfg/yolo-garbage1.cfg yolo-garbage1_last.weights data/plastic_1.jpg

2. To run using webcam.real-time: darknet.exe detector demo cfg/obj.data cfg/yolo-garbage1.cfg yolo-garbage1_last.weights

##### If you find any difficulty or error you can reach me by email --> gupta29470@gmail.com

##### Thankyou, 
*Valar Dohaeris!*