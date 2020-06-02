## maskRCNN = istance segmentation = objection detection(faster RCNN) + semantic segmentation (fully convolutional network)
* Faster RCNN use selective search to grow bounding box based on similarity of neighbouring pixels(texture,etc)
* Pass images on bounding box to pre-trained AlexNet
* use ROI pooling to prevent recomputation of overlapping bounding box regions
* slide anchor boxes across the image and give a score and pass image in bounding box to classifier

* ROI align is essential for pixel segmentation
