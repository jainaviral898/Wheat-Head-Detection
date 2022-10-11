# Wheat-Head-Detection

This task requires us to detect the head of the wheat in an image. Based on the count we estimate pertinent traits including head population density and head characteristics such as sanitary state, size, maturity stage and the presence of awns.

![alt text](https://i.ytimg.com/vi/yqvMuw-uedU/maxresdefault.jpg)

## Dataset
Global Wheat Head Detection (GWHD) dataset is a large and diverse dataset of high resolution RGB labelled images to develop and benchmark wheat head detection methods.
Several studies developed methods for wheat head detection from high-resolution RGB imagery. They are based on computer vision and machine learning and are generally calibrated and validated on limited datasets.
The data is images of wheat fields, with bounding boxes for each identified wheat head. Not all images include wheat heads / bounding boxes. The images were recorded in many locations around the world.

The CSV data is simple - the image ID matches up with the filename of a given image, and the width and height of the image are included, along with a bounding box. There is a row in 'train.csv' for each bounding box. Not all images have bounding boxes.

More details on the data acquisition and processes are available at: https://arxiv.org/abs/2005.02162

## Methodologies & Results
Approach to image pre-processing, wheat head detection, model benchmarking, and yield estimation is given in detail in [this report](18AG3AI08_End-1_Report.pdf).