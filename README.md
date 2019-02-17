# Yolov3-implementation-using-OpenCV
Implementing Yolov3 algorithm using OpenCV to detect different objects<br><br>


| `Input` | `Output` |
| --- | --- |
| <img src="https://github.com/pranavmicro7/Yolov3-implementation-using-OpenCV/blob/master/images/input-1.jpeg"> | <img src="https://github.com/pranavmicro7/Yolov3-implementation-using-OpenCV/blob/master/images/output-1.jpg" >|<br>
| <img src="https://github.com/pranavmicro7/Yolov3-implementation-using-OpenCV/blob/master/images/input-3.jpeg"> | <img src="https://github.com/pranavmicro7/Yolov3-implementation-using-OpenCV/blob/master/images/output-3.jpg">|<br>
| <img src="https://github.com/pranavmicro7/Yolov3-implementation-using-OpenCV/blob/master/images/input-2.jpeg"> | <img src="https://github.com/pranavmicro7/Yolov3-implementation-using-OpenCV/blob/master/images/output-2.jpg" >|<br>


# Steps of implementation
1-Firstly <i>`run download_models.sh`</i>. This will download following three files:-
<ul style="list-style-type:disc;">
  <li>coco.names (contains the names of all the detection objects)</li>
  <li>yolov3.weights (pretrained weights for the model)</li>
  <li>yolov3.cfg (configuration file of yolov3 algorithm)</li>
</ul>  


2-Then run <i>`yolov3_run.py`</i>. The output will be stored in the format of "<i>video_name</i>_yolo_out_py.avi" for videos and "<i>image_name</i>_yolo_out_py.jpg" for images.<br><br>
3-For running through command lines:-
<ul style="list-style-type:disc;">
  <li>python3 yolov3_run.py --video=video_name.mp4</li>
  <li>python3 yolov3_run.py --image=image_name.mp4</li>
  
</ul> 
