<h1>Real-Time-Object-Detection-using-yolo<h1>

# Performance on the COCO Dataset
We Need only three files
- yolov3.weights
- colo-name
- yolov3.cfg


## Download the coco-name and colo-name file here Or Just run this

$ git clone https://github.com/pjreddie/darknet

- coco-name location:- darknet/data/coco.names
- yolov3.cfg location:- darknet/cfg/yolov3.cfg

## For Download the pre-trained weight
$ wget https://pjreddie.com/media/files/yolov3.weights

# For Webcam Just use this  0
   
# If you want to Change confidence and threshold value 

$ python3 yolo_video.py -i o -c 0.6 -t 0.4

-  -c for confidence
-  -t for threshold
# For other Media file and live stream Just run this 
```sh
$ python3 yolo_video.py -i rtsp://192.168.43.102:7878/h264_ulaw.sdp (use your own ip)
```
# For live stream by url Just run this
```sh
$ python3 yolo_video.py -i http://192.168.43.102:7878/video?x.mjpg #(use your own ip)
```
### output

# For Video file
```sh
$ python3 yolo_video.py -i video_file_name
```
