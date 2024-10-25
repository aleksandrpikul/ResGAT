# Enhancing Explainability in Deepfake Detection with Graph Attention Networks

Official PyTorch Implementation of "Enhancing Explainability in Deepfake Detection with Graph Attention Networks"

## ResGAT

![Диаграмма без названия drawio(10)(1)(1)](https://github.com/user-attachments/assets/443a652f-280c-4991-9345-c5f0e1c6897c)

## Pretrained models
You can choose to download only the weights of the pretrained backbone used for downstream tasks, or the full checkpoint which contains backbone and projection head weights for both student and teacher networks. We also provide the backbone in `onnx` format, as well as detailed arguments and training/evaluation logs. Note that `DeiT-S` and `ViT-S` names refer exactly to the same architecture.

<table>
  <tr>
    <th>Architecture</th>
    <th>Params</th>
    <th colspan="6">Download</th>
  </tr>
  
  <tr>
    <td>ResGATv1 (DFDC)</td>
    <td>21M</td>
    <td><a href="https://dl.fbaipublicfiles.com/dino/dino_deitsmall16_pretrain/dino_deitsmall16_pretrain.pth">model_weights.pth</a></td>
  </tr>
  
  <tr>
    <td>ResGATv1 (FF++)</td>
    <td>21M</td>
    <td><a href="https://dl.fbaipublicfiles.com/dino/dino_deitsmall16_pretrain/dino_deitsmall16_pretrain.pth">model_weights.pth</a></td>
  </tr>

  <tr>
    <td>ResGATv2 (DFDC)</td>
    <td>21M</td>
    <td><a href="https://dl.fbaipublicfiles.com/dino/dino_deitsmall16_pretrain/dino_deitsmall16_pretrain.pth">model_weights.pth</a></td>
  </tr>

  <tr>
    <td>ResGATv2 (FF++)</td>
    <td>21M</td>
    <td><a href="https://dl.fbaipublicfiles.com/dino/dino_deitsmall16_pretrain/dino_deitsmall16_pretrain.pth">model_weights.pth</a></td>
  </tr>

  
</table>

## Getting started
- [ResGATv1 (DFDC)](https://github.com/polimi-ispl/icpr2020dfdc/blob/master/notebook/Image%20prediction.ipynb) <a target="_blank" href="https://colab.research.google.com/drive/1V9-SdjYvzyreN5-VL_l_Q6XWRk189lp1?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg">
</a>

- [ResGATv1 (FF++)](https://github.com/polimi-ispl/icpr2020dfdc/blob/master/notebook/Image%20prediction.ipynb) <a target="_blank" href="https://colab.research.google.com/drive/19oVKlzEr58VZfRnSq-nW8kFYuxkh3GM8?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg">
</a>

- [ResGATv2 (DFDC)](https://github.com/polimi-ispl/icpr2020dfdc/blob/master/notebook/Video%20prediction.ipynb) <a target="_blank" href="https://colab.research.google.com/drive/12WnvmerHBNbJ49HdoH1lli_O8SwaFPjv?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg">
</a>

- [ResGATv2 (FF++)](https://github.com/polimi-ispl/icpr2020dfdc/blob/master/notebook/Image%20prediction.ipynb) <a target="_blank" href="https://colab.research.google.com/drive/19oVKlzEr58VZfRnSq-nW8kFYuxkh3GM8?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg">
</a>

## Datasets

- [The DeepFake Detection Challenge (DFDC) Dataset](https://www.kaggle.com/c/deepfake-detection-challenge/data) | [arXiv paper](https://arxiv.org/abs/2006.07397)
- [FaceForensics++: Learning to Detect Manipulated Facial Images](https://github.com/ondyari/FaceForensics/blob/master/dataset/README.md) | [arXiv paper](https://arxiv.org/abs/1901.08971)

## References
- ResNet
- GAT
