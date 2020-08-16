# Research on lung segmentation for COVID19 patients in CXR
This source code is for sharing deep learning-based detection model for carina and left hilium in CXR. It has been validated for COVID19 patients as well.

[Lung segmentation](https://github.com/younggon2/Research-Segmentation-Lung-CXR-COVID19) in CXR is followed by this detection model for dividing the whole lung into four regions.

# Pre-requisities
* Python == 3.5
* Keras >= 2.0
* Tensorflow >= 1.11
* Scipy
* OpenCV
* [keras-retinanet](https://github.com/fizyr/keras-retinanet)

# Detection result and segmentation for four regions (mAP: 0.69 for a private dataset)

![Detection](/img/DetectionResult.png)

# Reference (Github)

1. https://github.com/qubvel/segmentation_models
2. https://github.com/fizyr/keras-retinanet
