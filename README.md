#  Traffic Signs YOLO3 pytorch
YOLO3 to detect the traffic sign in pytoch. I used the Traffic Signs dataset and convert the given annoations into YOLO fromat.
Traffic Signs is the dataset of German Traffic Sign Detection Benchmark datset http://benchmark.ini.rub.de 
It contains 900 image files with natural pictures 00000.ppm - 00899.ppm. Dataset contains the images files and gt.txt to define define the ImageID, XMin, YMin, XMax, YMax with calls numbers as annotation file.

# Default Label
Dataset has annotated with following labels 
* 0 = speed limit 20 (prohibitory) 
* 1 = speed limit 30 (prohibitory) 
* 2 = speed limit 50 (prohibitory) 
* 3 = speed limit 60 (prohibitory)
* 4 = speed limit 70 (prohibitory)
* 5 = speed limit 80 (prohibitory)
* 6 = restriction ends 80 (other)
* 7 = speed limit 100 (prohibitory)
* 8 = speed limit 120 (prohibitory)
* 9 = no overtaking (prohibitory)
* 10 = no overtaking (trucks) (prohibitory)
* 11 = priority at next intersection (danger)
* 12 = priority road (other)
* 13 = give way (other)
* 14 = stop (other)
* 15 = no traffic both ways (prohibitory)
* 16 = no trucks (prohibitory)
* 17 = no entry (other)
* 18 = danger (danger)
* 19 = bend left (danger)
* 20 = bend right (danger)
* 21 = bend (danger)
* 22 = uneven road (danger)
* 23 = slippery road (danger)
* 24 = road narrows (danger)
* 25 = construction (danger)
* 26 = traffic signal (danger)
* 27 = pedestrian crossing (danger)
* 28 = school crossing (danger)
* 29 = cycles crossing (danger)
* 30 = snow (danger)
* 31 = animals (danger)
* 32 = restriction ends (other)
* 33 = go right (mandatory)
* 34 = go left (mandatory)
* 35 = go straight (mandatory)
* 36 = go right or straight (mandatory)
* 37 = go left or straight (mandatory)
* 38 = keep right (mandatory)
* 39 = keep left (mandatory)
* 40 = roundabout (mandatory)
* 41 = restriction ends (overtaking) (other)
* 42 = restriction ends (overtaking (trucks)) (other)

# Modified Label
Among of 42 labels of annotation i have make it folling lables
* 1 = prohibitory
* 2 = danger
* 3 = mandatory
* 4 = other

# Reference
Udemy.com
Instructor :  **Valentyn Sichkar**
            Computer Vision, Machine Learning, Image Processing

