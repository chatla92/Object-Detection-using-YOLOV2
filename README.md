### Car Detection
Object detection using YoloV2
The follwoing work is an implementation of Redmon et al., 2016 (https://arxiv.org/abs/1506.02640.pdf) and Redmon and Farhadi, 2016 (https://arxiv.org/abs/1612.08242.pdf)

### Required packages
* Pythonv3
* Keras

### Required downloads
* Pretrained Keras Yolo model https://pjreddie.com/media/files/yolov2.weights and convert using script https://github.com/allanzelener/YAD2K/blob/master/yad2k.py  by Allen Zelener. Copy the yolo.h5 file produced to model_data folder
* Download and copy images into images folder

### Sample Output 
The follwoing the result for the test image

Found 7 boxes for test.jpg <br>
car 0.60 (925, 285) (1045, 374) <br>
car 0.66 (706, 279) (786, 350) <br>
bus 0.67 (5, 266) (220, 407) <br>
car 0.70 (947, 324) (1280, 705) <br>
car 0.74 (159, 303) (346, 440) <br>
car 0.80 (761, 282) (942, 412) <br>
car 0.89 (367, 300) (745, 648) <br>
![test-image](test.jpg)


