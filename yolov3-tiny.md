##YOLOv3-tiny is the compressed version of YOLOv3 designed to train on machines that have less computing power.

#YOLOv3-Tiny Architecture

YOLOv3-Tiny utilizes a couple of different changes from the original YOLOv3 network to help it achieve these fast speeds. First and foremost, The number of convolutional layers in the CSP backbone are compressed with a total of 29 pretrained convolutional layers. Additionally, the number of YOLO layers has been reduced to two instead of three and there are fewer anchor boxes for prediction.

#Size: YOLOv3-tiny is about 42 MB in size

#SPEED: YOLOv3-tiny performs batch inference at about 10 and 13 FPS respectively on jetson nano and tx2 by default. It performs at 18 and 35 FPS respectively on jetson nano and tx2 after optimization.

#ACCURACY: YOLOv3-tiny gives roughly 0.785 mAP