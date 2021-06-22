# iMiGUE

## Paper
### [Videos](link.xlsx) | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_iMiGUE_An_Identity-Free_Video_Dataset_for_Micro-Gesture_Understanding_and_Emotion_CVPR_2021_paper.pdf)
[iMiGUE: An Identity-free Video Dataset for Micro-Gesture Understanding and Emotion Analysis](https://sdolivia.github.io/FineGym/) <br>
 [Xin Liu](http://seea.tju.edu.cn/info/1015/2158.htm)<sup>1</sup>,
 Henglin Shi<sup>2</sup>,
 Haoyu Chen<sup>3</sup>,
 Zitong Yu<sup>4</sup>,
 Xiaobai Li<sup>5</sup>,
 Guoying Zhao<sup>6</sup> <br>
 <sup>1</sup> Center for Machine Vision and Signal Analysis, University of Oulu,Finland <br>
 <sup>2</sup> School of Electrical and Information Engineering, Tianjin University,China

<div align="center">
    <img src="pictures/Fig2.png">
</div>

## Contents
1. [Paper](#Paper) [Information about the paper.]
2. [Method Zoo](#MethodZoo) [Results of different methods on iMiGUE.]
3. [Citation](#Citation)


## MethodZoo
### Comparison of MG recognition accuracy (%) with state-of-the-art algorithms on the iMiGUE dataset.

<center>
  
| Methods | Model+Modality | acc@top1 | acc@top5 |
| :-----: | :-----: | :------: | :------: |
| SVA-E | RNN+Pose | 27.38 | 60.44 |
| LSTM | RNN+Pose | 32.36 | 72.93 |
| BLSTM | RNN+Pose | 32.39 | 71.34 |
| ST-GCN| GCN+Pose | 46.97 | 84.09 |
| 2S-GCN | GCN+Pose | 47.78 | 88.43 |
| Shift-GCN | GCN+Pose | 51.51 | 88.18 |
| GCN-NAS | GCN+Pose | 53.90 | 89.21 |
| MS-G3D | GCN+Pose | 54.91 | 89.98 |
| C3D | 3DCNN+RGB | 20.32 | 55.31 |
| R3D-101 | 3DCNN+RGB | 25.27 | 59.39 |
| I3D | 3DCNN+RGB | 34.96 | 63.69 |
| TSN | 2DCNN+RGB | 51.54 | 85.42 |
| TRN | 2DCNN+RGB | 55.24 | 89.17 |
| TSM | 2DCNN+RGB | 61.10 | 91.24 |
| P&C | Encoder-Decoder+Pose | 31.67 | 64.93 |
| U-S-VAE Z |Encoder-Decoder+Pose| 32.43 | 64.30 |

</center>

### Comparison of emotion understanding accuracy (%) with methods on iMiGUE dataset

<center>

| Methods | Model+Modality | Accuracy |
| :-----: | :-----: | :------: |
| TRN | CNN + RGB | 0.53 |
| TSM | CNN + RGB | 0.53 |
| I3D | CNN + RGB | 0.57 |
| ST-GCN| GCN+Pose | 0.50 |
| MS-G3D | GCN+Pose | 0.55 |
| U-S-VAE + LSTM | RNN + Micro-Gesture | 0.55 |
| TSM + LSTM | RNN + Micro-Gesture | 0.60 |
</center>

## Citation
```
@InProceedings{Liu_2021_CVPR, 
author = {Liu, Xin and Shi, Henglin and Chen, Haoyu and Yu, Zitong and Li, Xiaobai and Zhao, Guoying}, 
title = {iMiGUE: An Identity-Free Video Dataset for Micro-Gesture Understanding and Emotion Analysis}, 
booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)}, 
month = {June}, 
year = {2021}, 
pages = {10631-10642} }
