# EE604_Course_Project

The deepfake detection model proposed in
this study is a dual-branch neural network architecture that
combines EfficientNet (a pre-trained convolutional neural
network) with a handcrafted feature extraction branch. This
dual-branch structure aims to enhance detection performance by leveraging both high-level feature representations
from a deep learning model and specific handcrafted statistical features, creating a more comprehensive approach
to identify deepfake images. 
Our model was trained and
evaluated on a comprehensive kaggle dataset of 10,000+ real and deepfake
photos

We experimented with various architechtures such as MobileNetV3, ResNet50, etc., but chose 
EfficientNetB0 for the final implementation.
