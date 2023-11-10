# Image and Video Processing with MobileNet SSD

This project performs object detection on images and videos using a MobileNet SSD model trained on the COCO dataset. The model can detect common objects like people, cars, animals etc.

## Usage

The main script is `object_detection_video.py` which takes an input video file, runs object detection on each frame using MobileNet SSD, draws bounding boxes and labels, calculates FPS and writes the output to a video file.

The `ssd_mobilenet` folder contains the pre-trained model files needed:
- `frozen_inference_graph.pb` - Pre-trained weights
- `ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt` - Model configuration
- `coco_names.txt` - Class name labels 

To run on a sample video:

![Sample Video](sample.mp4)
