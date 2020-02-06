# Yolo-FaceDetection
## This repo still in preprocessing.
## WIDERFace Dataset http://shuoyang1213.me/WIDERFACE/
## YOLO V1 
### it divides the input image(224*224) into 9x9 grid cells. Each cell is responsible for detection an object and it's boundary boxes
### Every boundary box has five elements (x, y, w, h, confidence score). 
### X and y are the coordinates of the object in the input image, w and h are the width and height, Confidence score is the probability that cell contains an object.

## Yolo V2
### increase image dim to (448*448)
### divides the image into 13*13 grid cells
### use Batch Normalization
### use Anchor Boxes

## Yolo V3
...

## Ref
* https://medium.com/@jonathan_hui/real-time-object-detection-with-yolo-yolov2-28b1b93e2088
* https://medium.com/@venkatakrishna.jonnalagadda/object-detection-yolo-v1-v2-v3-c3d5eca2312a
