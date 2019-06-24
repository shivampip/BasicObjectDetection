# BasicObjectDetection
Implementing object detection while learning

## Preparation

### Download Weights and cnf files

Download any Darknet model cfg and weights from the [official YOLO website](https://pjreddie.com/darknet/yolo/).

### Generate `yolo.h5`

* Clone keras-yolo3 repo
```
git clone https://github.com/qqwweee/keras-yolo3.git
cd keras-yolo3
```

* Copy downloaded weight and cfg file in cloned repo folder


* Generate `yolo.h5`
```
python convert.py yolov3.cfg yolov3.weights model_data/yolo.h5
```



### Note

* Push large file `yolo.h5` with [Git Large File Storege](https://git-lfs.github.com/)



