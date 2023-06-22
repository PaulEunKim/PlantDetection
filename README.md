# Plant Detection with ArcGIS + Python
![Alt text](Becks_AdobeExpress.gif)
## Background

There are four popular computer vision tasks that are used commonly and relevant to our project (inspired by huggingface.co)
- Image classification
- Image segmentation
- Zero-shot classification
- Object detection
Each one of these techniques has their advantages and disadvantages.

There are also a few very similar papers that uses semantic segmentation, instance segmentation, and object detection to identify plants.
Instance Segmentation
- Mask R-CNN Refitting Strategy for Plant Counting and Sizing in UAV Imagery
Semantic Segmentation
- Corn Plant Counting Using Deep Learning and UAV Images
Object Detection
- Plant detection and counting from high-resolution RGB images acquired from UAVs: comparison between deep-learning and handcrafted methods with application to maize, sugar beet, and sunflower
- A Convolutional Neural Network-Based Method for Corn Stand Counting in the Field

## Tooling

Requirements for running Machine Learning models in ArcGIS Pro
- ArcGIS Pro 
    - Free license for Purdue students: https://www.rcac.purdue.edu/downloads/geospatial/arcgis/arcgis_pro
    - Free license for ASU students: https://libguides.asu.edu/esrisoftware/arcgispro
    - CUDA-enabled GPU
o	A list of CUDA compatible GPU’s is listed here: https://en.wikipedia.org/wiki/CUDA#GPUs_supported
•	CUDA
•	Deep Learning Framework for ArcGIS Pro
o	This can be downloaded following this guide: https://www.esri.com/arcgis-blog/products/arcgis-pro/imagery/deep-learning-with-arcgis-pro-tips-tricks/
-   ArcGIS Python API
     - A tutorial on how to use the Python API: https://www.youtube.com/watch?v=xxHKCTnZ9c8

Some other labeling software we discovered along the way are (these do not appear to be compatible with the ArcGIS Pro workflow):
- LabelStudio
- LabelMe
