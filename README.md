# [ICASSP'25] Don't Lose Yourself: Boosting Multimodal Recommendation via Reducing Node-neighbor Discrepancy in Graph Convolutional Network



## Introduction

This is the Pytorch implementation for our RedNnD paper:

>Don't Lose Yourself: Boosting Multimodal Recommendation via Reducing Node-neighbor Discrepancy in Graph Convolutional Network

## Environment Requirement

- python 3.9
- Pytorch 2.1.0

## Dataset

We provide three processed datasets: **Baby, Sports, Office**. These three datasets' contents are in the `data/` folder.

## Training

The model is based on [MMRec](https://github.com/enoche/MMRec) framework, and the code can be directly embedded into the framework to run.

## Performance Comparison

<img src="pic\performance.png"/>

## Citing RedNnD

If you find RedNnD useful in your research, please consider citing our [paper]().

```
@inproceedings{chen2025rednnd,
  title={Don't Lose Yourself: Boosting Multimodal Recommendation via Reducing Node-neighbor Discrepancy in Graph Convolutional Network},
  author={Chen, Zheyu and Xu, Jinfeng and Hu, Haibo},
  booktitle={ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={},
  year={2025},
  organization={IEEE}
}
```

The code is released for academic research use only. For commercial use, please contact [Zheyu Chen](zheyu.chen@connect.polyu.hk).

## Acknowledgement

The structure of this code is  based on [MMRec](https://github.com/enoche/MMRec). Thank for their work.

