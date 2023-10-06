# In this project, I use two stage object detection:

# Firstly, I get traffic sign images cropped from normal images. I will take features from it by using histrogram of oriented gradient and then feed them to SVM to classify into four classes: Stop, CrossWalk, SpeedLimit,Trafficlight

# Secondly, To take the proper bounding boxes traffic sign, I will use image pyramid and multiscale sliding windows. And them I take them to non-maximum suppression to remove redundant bounding boxes. Finally I feed them to trained SVM to predict.
