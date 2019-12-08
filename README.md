## AI-Powered-Detection
Object detcetion & Facial emotion recognition

- Find directory structures and weights files [here](http://bit.ly/keras-detection-practice)

- Facial emotion training : [Emotion/README.md](https://github.com/jinhojang6/ai-detection-practice/blob/master/Emotion/README.md)
    - [fer2013 dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data), Tensorflow and Keras

- Object detection & Facial Emotion processing: [Video-object-detection/README.md](https://github.com/jinhojang6/ai-detection-practice/blob/master/Video-object-detection/README.md)
    - Object detection: [COCO dataset](http://cocodataset.org/#home) and yolov3
        - download [yolov3-spp.weights](https://pjreddie.com/media/files/yolov3-spp.weights) and move the weights file to /Video-object-detection/yolov3-coco
        - yolov3-spp.weights is stronger in detection but slower in processing than [yolov3.weights](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg) 
    - Facial expression: follow the comments in yolo.py