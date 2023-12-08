
# Custom Object Detection with YOLOv5

## Overview

The key steps are:

### 1. Clone the YOLOv5 repository
### 2. Install dependencies 
### 3. Download custom dataset from Roboflow
### 4. Train YOLOv5 model on custom dataset
### 5. Evaluate trained model on test images

## Usage 

To use this notebook:

1. Run the cells to install YOLOv5 and dependencies
2. Update the Roboflow API key to access your dataset
3. Run the training cell to train a model on your custom dataset
4. Run the detection cell to run inference on test images 
5. View and evaluate detection results

The trained model and inference results are saved to the `runs` folder.

## Customization

- Update Roboflow dataset ID to use your own custom dataset
- Adjust training parameters like IMG SIZE, BATCH SIZE, EPOCHS etc  
- Pass additional `--hyp` parameter for hyperparameter tuning
- Use a different YOLOv5 model size instead of `yolov5s`

## References

- [YOLOv5 Docs](https://docs.ultralytics.com)
- [Roboflow Docs](https://docs.roboflow.com)

