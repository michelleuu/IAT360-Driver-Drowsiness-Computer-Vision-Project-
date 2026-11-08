# IAT360 Driver Drowsiness Detection - Group 19

## Team Members
- Yumin Ni (301416738)
- Nicole Li (301545941)
- Michelle Zhu (301581468)
- Zainab Shakeel (301464171)

## Project
Driver drowsiness detection using YOLOv8 object detection. The model detects six classes: eye_closed, eye_open, head_dropped, head_straight, no_yawn, and yawn.

## Files
- DriverDrowsinessYolo8.ipynb - main notebook with baseline training, hyperparameter tuning, and test evaluation
- dataset/data.yaml - dataset configuration file
- dataset/train/ - training data (3457 images, download from Roboflow link below)
- dataset/valid/ - validation data (384 images, download from Roboflow link below)
- dataset/test/ - test data (122 images collected by group members, labels included, images on Google Drive)

## Dataset Sources
- Training & Validation: [KantukV2 on Roboflow](https://universe.roboflow.com/testproject-8jvqn/kantukv2) (CC BY 4.0)
- Annotation tools: [Roboflow](https://app.roboflow.com), [Makesense.ai](https://www.makesense.ai)
- YOLOv8: [Ultralytics](https://github.com/ultralytics/ultralytics)
