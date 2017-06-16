# FaceAnalyzing
Face analyzing by caffe for gender and age predict

## Introduction

This repository contains a pyCaffe-based implementation of face analyzing such as age, gender and emotion etc...

You can read the paper in following link:

Age & Gender
http://www.openu.ac.il/home/hassner/projects/cnn_agegender/

Emotion
http://www.openu.ac.il/home/hassner/projects/cnn_emotions/


the model above are all available in caffe model zoo

according my test, only gender predict is reliable...


## Requirements

 - Python >= 2.7
 - CUDA >= 6.5 (highly recommended)
 - Caffe

CUDA will enable GPU-based computation in Caffe.

## example usage.

```
python FaceAnalyzing.py -i <input_image>
```

if you do not input image name it will use default image for demo.