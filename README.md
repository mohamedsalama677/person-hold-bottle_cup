# Object Detection: Person Holding Bottle or Cup

## Task Description

This project applies a pre-trained object detection model to identify and detect instances where a person is holding a bottle or a cup. The objective is to present the results through annotated images and videos.

## Approach

- A pre-trained YOLOv5 model was used due to its efficiency and accuracy in real-time object detection.
- Detection logic filters for instances where a person is holding either a bottle or a cup based on overlapping bounding boxes.
- The output includes both annotated images and videos to demonstrate the model’s performance.

## Files

- `The_main_notebook.ipynb`: Contains the full implementation of the detection pipeline and result visualization.


## Sample Outputs

- Annotated image with bounding boxes showing persons holding bottles or cups.
- Annotated video displaying continuous detection across frames.

## Installation

The environment setup is included within the notebook using the following commands:

```python
pip install opencv-python
```

```python
%%cmd
git clone https://github.com/ultralytics/yolov5
cd yolov5
pip install -r requirements.txt
```

These commands will install OpenCV and clone the YOLOv5 repository, along with all required dependencies.

## How to Run

1. Open the notebook `The_main_notebook.ipynb` in Jupyter Notebook.
2. Run the installation cells to set up the environment.
3. Follow the execution steps in the notebook to perform object detection and generate annotated outputs.

