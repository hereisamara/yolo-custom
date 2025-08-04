# Customize YOLO with Attention
### Custom Higher Dimension Head inside PAN for small/far objects
- ECA Attention
- Bi-level Routing Attention
  - https://github.com/rayleizhu/BiFormer/blob/public_release/models/biformer.py

### Install
```
pip install ultralytics
```

### Run
```
yolo detect train data=coco8.yaml model=./cfg/models/11/yolo11-custom.yaml epochs=100 imgsz=640
```
