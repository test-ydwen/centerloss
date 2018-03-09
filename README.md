# centerloss

This branch is the implementation of the paper "A Comprehensive Study for Center Loss".
    

* [Files](#files)
* [Trained_Model](#trained_model)
* [Contact](#contact)

### Files
- Original Caffe library
- Center Loss
  * src/caffe/proto/caffe.proto
  * include/caffe/layers/center_loss_layer.hpp
  * src/caffe/layers/center_loss_layer.cpp
  * src/caffe/layers/center_loss_layer.cu
- face_example
  * face_example/data/
  * face_example/face_snapshot/
  * face_example/face_train_test.prototxt
  * face_example/face_solver.prototxt
  * face_example/face_deploy.prototxt
  * face_example/extractDeepFeature.m
- mnist_example
  * mnist_example/data/
  * mnist_example/face_snapshot/
  * mnist_example/mnist_train_test.prototxt
  * mnist_example/mnist_solver.prototxt
  * mnist_example/mnist_deploy.prototxt

### Trained_Model
- Exp4_2
- Exp4_3
  * src/caffe/proto/caffe.proto
  * include/caffe/layers/center_loss_layer.hpp
  * src/caffe/layers/center_loss_layer.cpp
  * src/caffe/layers/center_loss_layer.cu
- Exp4_4
  * face_example/data/
  * face_example/face_snapshot/
  * face_example/face_train_test.prototxt
  * face_example/face_solver.prototxt
  * face_example/face_deploy.prototxt
  * face_example/extractDeepFeature.m
- mnist_example


### Contact 
- [Yandong Wen](http://ydwen.github.io/)
- [Kaipeng Zhang](http://kpzhang93.github.io/)

### Citation
You are encouraged to cite the following paper if it helps your research. 

    @inproceedings{wen2016discriminative,
      title={A Discriminative Feature Learning Approach for Deep Face Recognition},
      author={Wen, Yandong and Zhang, Kaipeng and Li, Zhifeng and Qiao, Yu},
      booktitle={European Conference on Computer Vision},
      pages={499--515},
      year={2016},
      organization={Springer}
    }

### License
Copyright (c) Yandong Wen
All rights reserved.

MIT License
