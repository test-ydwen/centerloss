This branch is the implementation of the paper "A Comprehensive Study for Center Loss".

* [Files](#files)
* [Trained_Model](#trained_model)
* [Contact](#contact)

### Files
- caffe
  * caffe.proto
  * center_loss_layer.hpp
  * center_loss_layer.cpp
  * center_loss_layer.cu
  * shared_center_loss_layer.hpp
  * shared_center_loss_layer.cpp
  * shared_center_loss_layer.cu  
- deploy_prototxt
  * resnet4.prototxt
  * resnet10.prototxt
  * resnet20.prototxt
  * resnet36.prototxt
  * resnet64.prototxt
- exp4_2
  * Parameter sharing
  * Loss Weight
  * Radius
  * Training_set
  * Depth
- exp4_3
  * softmax
  * softmax + contrastive
  * normface
  * coco
  * SphereFace
  * softmax + CL
  * softmax + ACL
  * softmax + ACL-γ
  * coco + ACL-γ
  * sphere + ACL-γ
- exp4_4 & exp4_5 & exp4_6
  * softmax
  * softmax + CL
  * softmax+ ACL-γ
  * softmax + CL (ρ=5)
  * softmax+ ACL-γ (ρ=5)
  * sphere+ ACL-γ (ρ=5)
- training_list
  * [link](https://drive.google.com/open?id=1RGchdWY-Yjz4kqB2kqj15jseK90NB3Rn)

### Trained_Model
- exp4_2
  * [link](https://drive.google.com/open?id=1w-Tx-N8jDEXsOi_akPPTN-jZcRC-21FP)
- exp4_3
  * [link](https://drive.google.com/open?id=1WMPbY_dwqs1jeyVu6wy1OqdykfTgkCWw)
- exp4_4 & exp4_5 & exp4_6
  * [link](https://drive.google.com/open?id=1yZdA-CGVgb07brunz8reJVE2jRaKzhIL)

### Contact 
- [Yandong Wen](http://ydwen.github.io/)
- [Kaipeng Zhang](http://kpzhang93.github.io/)


### License
Copyright (c) Yandong Wen, Kaipeng Zhang
All rights reserved.
MIT License
