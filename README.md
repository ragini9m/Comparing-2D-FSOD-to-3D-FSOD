# Comparing-2D-FSOD-to-3D-FSOD

### Dataset Preparation
```
cd $DATA_ROOT
wget https://pjreddie.com/media/files/VOCtrainval_11-May-2012.tar
wget https://pjreddie.com/media/files/VOCtrainval_06-Nov-2007.tar
wget https://pjreddie.com/media/files/VOCtest_06-Nov-2007.tar
tar xf VOCtrainval_11-May-2012.tar
tar xf VOCtrainval_06-Nov-2007.tar
tar xf VOCtest_06-Nov-2007.tar
```

|Dataset||
| --- |--- |
|cocosplit|[download_link](https://drive.google.com/file/d/1T_cYLxNqYlbnFNJt8IVvT7ZkWb5c0esj/view?usp=sharing)|
|vocsplit|[download_link](https://drive.google.com/file/d/1BpDDqJ0p-fQAFN_pthn2gqiK5nWGJ-1a/view?usp=sharing)|

|Papers| | |
| --- | --- | --- | 
| Few-Shot Object Detection via Variational Feature Aggregation (VFA) | [PAPER](https://arxiv.org/pdf/2301.13411.pdf) | [CODE](https://github.com/csuhan/VFA) | 
| DeFRCN: Decoupled Faster R-CNN for Few-Shot Object Detection (DeFRCN)| [PAPER](https://arxiv.org/pdf/2108.09017.pdf)| [CODE](https://github.com/er-muyue/DeFRCN)|


conda env 
install detectron in conda env
```
python3 -m pip install detectron2==0.3 -f https://dl.fbaipublicfiles.com/detectron2/wheels/cu101/torch1.6/index.html
```
