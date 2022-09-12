# yolov7-simple-ADAS
Simple Assistance Driving System (ADAS) based on YOLOV7

This app is demonstrate simple Adaptive Detection System (ADAS) to invoke early warning system to driver when driver vehicle too close to another vehicles

This app is based on YOLOV7 object detection library engine from WongKinYiu repository on https://github.com/WongKinYiu/yolov7

Run this command to run the app
python detect_adas.py --weights yolov7-tiny.pt --view-img --nosave --source "dashcam_2.MP4"

Notes:
You can download yolov7-tiny or yolov7 weights from YOLOV7 assets repository https://github.com/WongKinYiu/yolov7/releases

App Demo:
https://youtu.be/ccjNwJsEvw4

Sample Dashcam Video:
https://drive.google.com/file/d/1u9sJlskOg4w2plPAxRgen0JKkTLi3Bbe/view?usp=sharing
