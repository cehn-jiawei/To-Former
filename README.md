# To-Former

# Running environment
Pytorch 1.23 with cuda 11.6  in an Ubuntu 20.04 system

# Dataset
We use the Pascal VOC2012 and Trans10k-v2.

# Data Preparation
1. create dirs './Data/Trans10K-v2'
2. put the ImageSets/JPEGImages/SegmentationClass data under './Data/Trans10K-v2'. Data Structure is shown below.
3. Trans10K_v2
├── ImageSets
│   ├── train.txt
│   ├── test.txt
│   └── val.txt
├── JPEGImages
└── SegmentationClass
  
