# Yolo-FaceDetection
## this repo still in preprocessing and waiting for any helping comments.
## WIDERFace Dataset
http://shuoyang1213.me/WIDERFACE/
## Model
### I started with dividing images to 3*3 to detect just 9 faces in each image
### The model consists of Conv layers with max pooling to reduce images res from (500,500) to (3,3)
### Output is 3*3*(x,y,w,h) x,y is the face middel point, w,h are wedith and hight
### I'm using MSE loss and Adm Optimizer 
