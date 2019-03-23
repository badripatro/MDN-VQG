
## MDN-VQG : Multimodal Differential Network for Visual Question Generation

-- [[Project Page](https://badripatro.github.io/MDN-VQG/)]

-- [[Paper](http://aclweb.org/anthology/D18-1434)]




## Introduction

<p align="center">
 <img src="fig/intro.png" width="600">
</p>

<p align="center">
 <img src="fig/mot.png" width="600">
</p>

## Main

<p align="center">
 <img src="fig/model.png" width="600">
</p>

Torch implementation of an "Multimodal Differential Network for Visual Question Generation" .
### Training Step:

    1. Download VQG dataset from MicrosoftVQG site.
    2. Create train,val and test json file.
    3. Preprocess the MSCOCO image file using prepro/prepro_img.lua for joint model and prepro/prepro_img_att.lua for attention model.
    4. Find the exemplar(Supporting and oppsing) Image using /data/knn_image.m
    5. Run : th training.lua







