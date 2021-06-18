# Instance-based Vision Transformer for Subtyping of Papillary Renal Cell Carcinoma in Histopathological Image

![ViT](./I-ViT/static/model.jpeg)

The instance-based Vision Transformer (i-ViT) for learning robust representations of histopathological images for the pRCC subtyping task by extracting finer features from instance patches (by cropping around segmented nuclei and assigning predicted grades). 
The i-ViT takes top-K instances as input and aggregates them for capturing both the cellular and cell-layer level patterns by a position-embedding layer, a grade-embedding layer, and a multi-head multi-layer self-attention module. 

[Link]() to MICCAI 2021 paper.

## Set Up Environment

Our framework is composed by two parts, Please set up two environemnts based on:
-[`./nuclei_seg_cls_infer`](./nuclei_seg_cls_infer)
-[`./I-ViT`](./I-ViT)