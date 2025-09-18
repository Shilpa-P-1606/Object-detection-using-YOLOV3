# Object-detection-using-YOLOV3

# YOLOv3 Object Detection (OpenCV)

Python implementation of YOLOv3 object detection using OpenCV.  
Detects objects in images and videos, with configurable model weights, class labels, and visualization outputs.

---

## Setup

1. Download the required YOLOv3 files:
   - [yolov3.weights](https://www.kaggle.com/datasets/shivam316/yolov3-weights)  
   - [yolov3.cfg](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)  
   - [yolov3-labels - coco.names (class labels)](https://github.com/pjreddie/darknet/blob/master/data/coco.names)  

   Save them in the project directory.

2. Install dependencies:
   ```bash
   pip install opencv-python
   pip install numpy

  ## Usage

- **yolo.py**  
  Main script to run YOLOv3 object detection.  
  - `detectFromImage`: runs detection on a single image (e.g., `test.png`).  
  - `detectFromVideo`: runs detection on a video file (e.g., `video5.mp4`).  

- **yoloDetection.py**  
  Provides helper functions to process images/videos: builds input blobs, runs forward passes through the CNN, filters bounding boxes, and draws predictions.

  # Example Commands
  
  ## Detect objects in an image
  - python yolo.py image test.png
    
  ## Detect objects in a video
  - python yolo.py video video5.mp4
 
  # Results Preview
  
  ## Image Detection & Accuracy detection:
  ![Detected Image](https://github.com/user-attachments/assets/eafc5ff9-9fb2-4a48-8c4d-0849f128b0cf)
  
  ![image](https://github.com/user-attachments/assets/827edd78-bf17-4493-a7bc-20e6069be06c)
  
  ## Video Detection:
  ![image](https://github.com/user-attachments/assets/661aeb1c-b5b3-4400-b597-593e685614e6)

  ## Contributing
  Contributions are welcome!  
  Feel free to open issues or submit pull requests if you’d like to improve detection accuracy, add new features, or test on more datasets.
