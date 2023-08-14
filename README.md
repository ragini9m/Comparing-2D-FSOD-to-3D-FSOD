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
|kitti|[download_link](https://www.cvlibs.net/datasets/kitti/eval_object.php)|


2D-FSOD
|repo-name| | |
| --- | --- | --- | 
|TFA (FSDet)|[PAPER]()|[CODE](https://github.com/ucbdrive/few-shot-object-detection)|
| VFA | [PAPER](https://arxiv.org/pdf/2301.13411.pdf) | [CODE](https://github.com/csuhan/VFA) | 
| DeFRCN| [PAPER](https://arxiv.org/pdf/2108.09017.pdf)| [CODE](https://github.com/er-muyue/DeFRCN)|
|Dual-awareness Attention for Few-shot Object Detection|[PAPER]()|[CODE](https://github.com/Tung-I/Dual-awareness-Attention-for-Few-shot-Object-Detection)|
|OS2D|[PAPER]()|[CODE](https://github.com/aosokin/os2d/tree/master)|
|Sylph|[PAPER]()|[CODE](https://github.com/facebookresearch/sylph-few-shot-detection)|
|ICPE|[PAPER]()|[CODE](https://github.com/lxn96/ICPE/tree/main)|
|Dynamic Relevance Learning for Few-Shot Object Detection|[PAPER]()|[CODE](https://github.com/liuweijie19980216/DRL-for-FSOD)|
|VizWiz-FewShot|[PAPER]()|[CODE](https://github.com/alec-bell/vizwiz-fewshot/tree/master)|
|DandR|[PAPER]()|[CODE](https://github.com/ZYN-1101/DandR/tree/main)|
|AirDet|[PAPER]()|[CODE](https://github.com/Jaraxxus-Me/AirDet)|
|MFDC|[PAPER]()|[CODE](https://github.com/WuShuang1998/MFDC)|
|FewX|[PAPER]()|[CODE](https://github.com/fanq15/FewX)|
|Counting-DETR|[PAPER]()|[CODE](https://github.com/VinAIResearch/Counting-DETR)|
|MRSN(Classification)|[PAPER]()|[CODE](https://github.com/MMatx/MRSN)|
|AcroFOD|[PAPER]()|[CODE](https://github.com/Hlings/AcroFOD)|
|KFSOD|[PAPER]()|[CODE](https://github.com/ZS123-lang/KFSOD)|
|lvc|[PAPER]()|[CODE](https://github.com/prannaykaul/lvc)|
|Meta-Faster-R-CNN|[PAPER]()|[CODE](https://github.com/GuangxingHan/Meta-Faster-R-CNN)|
|HallucFsDet(no code)|[PAPER]()|[CODE]()|
|QA-FewDet|[PAPER]()|[CODE](https://github.com/GuangxingHan/QA-FewDet)|
|UP-FSOD|[PAPER]()|[CODE](https://github.com/AmingWu/UP-FSOD)|
|Meta-DETR|[PAPER]()|[CODE](https://github.com/ZhangGongjie/Meta-DETR)|
|SVD-Dictionary-Enhancement(no code)|[PAPER]()|[CODE](https://github.com/AmingWu/SVD-Dictionary-Enhancement)|
|FADI|[PAPER]()|[CODE](https://github.com/yhcao6/FADI)|
|AIT|[PAPER]()|[CODE](https://github.com/CAIVIAC/AIT)|
|DCNet|[PAPER]()|[CODE](https://github.com/hzhupku/DCNet)|
|GFSD|[PAPER]()|[CODE](https://github.com/Megvii-BaseDetection/GFSD)|
|CME|[PAPER]()|[CODE](https://github.com/Bohao-Lee/CME)|
|UniT(L/C)|[PAPER]()|[CODE](https://github.com/ubc-vision/UniT)|
|FAPIS(SS)|[PAPER]()|[CODE](https://github.com/ducminhkhoi/FAPIS)|
|FSCE|[PAPER]()|[CODE](https://github.com/megvii-research/FSCE)|




3D-FSOD

|repo-name| | |
| --- | --- | --- | 
|Few-Shot Viewpoint Estimation (OD)|[PAPER]()|[CODE](https://github.com/YoungXIAO13/FewShotViewpoint)|
|FS3D (PC-OD)|[PAPER]()|[CODE](https://github.com/CVMI-Lab/FS3D)|
|MetaDetect3D|[PAPER]()|[CODE](https://github.com/JanMarcelKezmann/MetaDetect3D)|
|3D-Few-Shot|[PAPER]()|[CODE](https://github.com/yuchenlichuck/3D-Few-Shot)|
|Few-Shot-3D-Object-Detection-of-LiDAR-Point-Cloud-for-Autonomous-Driving|[PAPER]()|[CODE](https://github.com/Garvey98/Few-Shot-3D-Object-Detection-of-LiDAR-Point-Cloud-for-Autonomous-Driving)|
|UVStyle-Net|[PAPER]()|[CODE](https://github.com/AutodeskAILab/UVStyle-Net)|
|FSCIL-3D (Learning)|[PAPER]()|[CODE](https://github.com/townim-faisal/FSCIL-3D)|
|NeuralVS|[PAPER]()|[CODE](https://github.com/Angtian/NeuralVS)|
|Few-Shot-3D-Point-Cloud-Classification|[PAPER]()|[CODE](https://github.com/PeiZhou26/Few-Shot-3D-Point-Cloud-Classification)|
|FewShot_3D|[PAPER]()|[CODE](https://github.com/rishabhdotgupta/FewShot_3D)|
|fewshot-3d|[PAPER]()| [CODE](https://github.com/YWQQQQQQ/fewshot-3d)|
|attMPTI (PC-SS)|[PAPER]()|[CODE](https://github.com/Na-Z/attMPTI)|
|FewShot_GAN-Unet3D (SS-L)|[PAPER]()|[CODE](https://github.com/arnab39/FewShot_GAN-Unet3D)|
|GeoFormer(PC-SS-OD)|[PAPER]()|[CODE](https://github.com/VinAIResearch/GeoFormer)|
|few_shot_3dr (PC-SS)|[PAPER]()|[CODE](https://github.com/JeremyFisher/few_shot_3dr)|
|iccv_2019_few_shot_3d_wallace (Recon)|[PAPER]()|[CODE](https://github.com/BramSW/iccv_2019_few_shot_3d_wallace)|
|PAP-FZS3D (PC-SS)|[PAPER]()|[CODE](https://github.com/heshuting555/PAP-FZS3D)|
|Few-Shot-Learning-of-Part-Specific-Probability-Space-for-3D-Shape-Segmentation|[PAPER]()|[CODE](https://github.com/Lingjing324/Few-Shot-Learning-of-Part-Specific-Probability-Space-for-3D-Shape-Segmentation)|
|Few-shot_3D_Geometric_DeepLearning|[PAPER]()|[CODE](https://github.com/Mzunoven/Few-shot_3D_Geometric_DeepLearning)|
|H3D-Net-new|[PAPER]()|[CODE](https://github.com/MaxPolak97/H3D-Net-new)|
|PADMix|[PAPER]()|[CODE](https://github.com/ttchengab/PADMix)|
|BFG_FewShot3D|[PAPER]()|[CODE](https://github.com/Mostapha0A/BFG_FewShot3D)|
|3D_Medical_FewShot|[PAPER]()|[CODE](https://github.com/Rituraj-commits/3D_Medical_FewShot)|
|SCAT|[PAPER]()|[CODE](https://github.com/czzhang179/SCAT)|
|JRSS|[PAPER]()|[CODE](https://github.com/AIforMS/JRSS)|
|analogicalnets|[PAPER]()|[CODE](https://github.com/nickgkan/analogicalnets)|
|SST|[PAPER]()|[CODE](https://github.com/tusen-ai/SST)|
|SFA3D|[PAPER]()|[CODE](https://github.com/maudzung/SFA3D)|
|XrayDet|[PAPER]()|[CODE]([https://github.com/DIG-Beihang/XrayDetection](https://github.com/DIG-Beihang/XrayDetection))|
