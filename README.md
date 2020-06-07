# YOLOv3 Usage Samples with Python
### General
Get more Information to state-of-the-art, real-time object detection system
['You only look once' (YOLO)](https://pjreddie.com/darknet/yolo/).

#### Installation Steps

##### 0. Download YOLOv3 Weights and Config
Download [YOLOv3 Weights](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg), 
[YOLOv3 Config](https://pjreddie.com/media/files/yolov3.weights) and
[COCO names](https://github.com/pjreddie/darknet/blob/master/data/coco.names) and store the file in the `YOLOv3`
folder.

##### 1. Create and activate a new environment.
```
conda create -n yolo python=3.6
source activate yolo 
```
##### 2. Install Dependencies.
```
pip install -r requirements.txt
```

#### 3. Run Notebooks
Start the Jupyter Notebook and follow the instructions.
```
jupyter notebook "YOLOv3 with OpenCV.ipynb"
```


