## Pure Evaluation version of MegaDepth

* original repo: [MegaDepth](https://github.com/lixx2938/MegaDepth.git)

This repo is intended to use the well-trained MegaDepth model to predict depth from single image w/o any training scripts.

Acoording to MegaDepth, It has better generalization ability to completely unknown scenes.

## Usage

* downloads [best_generalization_net_G.pth](http://www.cs.cornell.edu/projects/megadepth/dataset/models/best_generalization_net_G.pth) into ```checkpoints/test_local/best_generalization_net_G.pth```

* ```python demo.py```

## Results

![](https://raw.githubusercontent.com/yunlongdong/MegaDepthEval/master/test_color.jpg)

![](https://raw.githubusercontent.com/yunlongdong/MegaDepthEval/master/test_depth.png)

## Tested Platform

* ubuntu 14.04, pytorch 0.4.0, cuda 9.0, GTX1080, about 1GB gpu memory to use (I optimized some code, original needs above 3GB)
* win10, pytorch 0.4.0, cuda 9.0, GTX750ti, GTX1050ti