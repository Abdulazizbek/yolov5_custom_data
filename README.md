# YOLO custom data

Code is used from Ultralytics [YOLO](https://github.com/ultralytics/yolov5) implementation

### Multi-GPU training

`python3 -m torch.distributed.launch --nproc_per_node 4 train.py --device 0,1,2,3`

### More details
tutorial, data-preparation, requirements, model statistics, ... : https://github.com/ultralytics/yolov5
