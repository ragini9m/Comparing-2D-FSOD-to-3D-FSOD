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


2D-FSOD
|Papers| | |
| --- | --- | --- | 
| Few-Shot Object Detection via Variational Feature Aggregation (VFA) | [PAPER](https://arxiv.org/pdf/2301.13411.pdf) | [VFA](https://github.com/csuhan/VFA) | 
| DeFRCN: Decoupled Faster R-CNN for Few-Shot Object Detection (DeFRCN)| [PAPER](https://arxiv.org/pdf/2108.09017.pdf)| [defrcn](https://github.com/er-muyue/DeFRCN)|
|Dual-awareness Attention for Few-shot Object Detection|[PAPER]()|[CODE](https://github.com/Tung-I/Dual-awareness-Attention-for-Few-shot-Object-Detection)|
|OS2D: One-Stage One-Shot Object Detection by Matching Anchor Features|[PAPER]()|[os2d](https://github.com/aosokin/os2d/tree/master)|
|Sylph: A Hypernetwork Framework for Incremental Few-shot Object Detection|[PAPER]()|[ICPE](https://github.com/facebookresearch/sylph-few-shot-detection)|
|ICPE|[PAPER]()|[CODE](https://github.com/lxn96/ICPE/tree/main)|
|Dynamic Relevance Learning for Few-Shot Object Detection|[PAPER]()|[CODE](https://github.com/liuweijie19980216/DRL-for-FSOD)|
|VizWiz-FewShot|[PAPER]()|[vizwiz](https://github.com/alec-bell/vizwiz-fewshot/tree/master)|
|DandR|[PAPER]()|[DandR](https://github.com/ZYN-1101/DandR/tree/main)|
||[PAPER]()|[CODE]()|



3D-FSOD

|Papers| | |
| --- | --- | --- | 
|Few-Shot Viewpoint Estimation|[PAPER]()|[CODE](https://github.com/YoungXIAO13/FewShotViewpoint)|
|SST|[PAPER]()|[SST](https://github.com/tusen-ai/SST)|
|FS3D|[PAPER]()|[FS3D]()|
||[PAPER]()|[CODE](https://github.com/CVMI-Lab/FS3D)|
|SFA3D|[PAPER]()|[SFA3D](https://github.com/maudzung/SFA3D)|
|XrayDet|[PAPER]()|[CODE](https://github.com/DIG-Beihang/XrayDetection)|
|attMPTI|[PAPER]()|[attMPTI](https://github.com/Na-Z/attMPTI)|
|FSCIL-3D|[PAPER]()|[FSCIL-3D](https://github.com/townim-faisal/FSCIL-3D)|
|FewShot_GAN-Unet3D|[PAPER]()|[CODE](https://github.com/arnab39/FewShot_GAN-Unet3D)|
|GeoFormer|[PAPER]()|[GeoFormer](https://github.com/VinAIResearch/GeoFormer)|
|few_shot_3dr|[PAPER]()|[few_shot_3dr](https://github.com/JeremyFisher/few_shot_3dr)|
||[PAPER]()|[CODE]()|
||[PAPER]()|[CODE]()|
||[PAPER]()|[CODE]()|
||[PAPER]()|[CODE]()|


conda env 
install detectron in conda env
```
python3 -m pip install detectron2==0.3 -f https://dl.fbaipublicfiles.com/detectron2/wheels/cu101/torch1.6/index.html
```
