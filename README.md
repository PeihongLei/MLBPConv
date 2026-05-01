# Rotation-Equivariant Multi-Scale Convolution via Adaptive Magnitude LBP

**Peihong Lei**†, Yuying Ren‡, Siqi Chen‡, Fan Bai‡, Hanlin Mo†,\*

† Xidian University, China  
‡ Northwestern Polytechnical University, China

*Accepted to IEEE International Conference on Image Processing (ICIP), 2026*

[[Paper]]() [[Project Page]](https://peihonglei.github.io/MLBPConv/)

## Abstract

Rotation equivariance is a key challenge for deep neural networks, as standard convolutions are sensitive to input orientation and often rely on extensive data augmentation. We introduce MLBPConv, a novel rotation-equivariant convolution based on a locally magnitude-thresholded Local Binary Pattern (LBP). We first identify that the instability of prior LBP-based methods stems from the intrinsic periodicity of LBP codes, which can cause errors in orientation alignment, and show that MLBPConv effectively resolves this issue. To further enrich feature representation, we design a lightweight multi-scale fusion strategy that aggregates multireceptive-field features without increasing the number of parameters. Experiments on MNIST-Rot, Outex 00012, and MTARSI demonstrate that our methods outperform standard CNNs and classical rotation-equivariant networks, and integrating MLBPConv into ResNet architectures substantially
enhances rotation robustness. This approach provides an efficient, lightweight, and plug-and-play solution for learning stable rotation-equivariant features.

## Key Findings
 
- **Rotation-equivariant representation**: The proposed method improves robustness to image rotations by incorporating adaptive magnitude-based LBP information into convolutional feature extraction. 
- **Multi-scale feature modeling**: The method captures local structural patterns at multiple scales, improving representation capacity for complex visual patterns. 
- **Adaptive magnitude LBP**: Compared with traditional LBP-style descriptors, the adaptive magnitude formulation provides more flexible and discriminative local texture encoding. 
- **CNN-compatible module**: The proposed convolution can be integrated into deep neural networks as a feature extraction component.

## Citation
 
If you find this work useful, please cite:
 
```bibtex
@inproceedings{lei2026rotation,
  title={Rotation-Equivariant Multi-Scale Convolution via Adaptive Magnitude LBP},
  author={Lei, Peihong and Ren, Yuying and Chen, Siqi and Bai, Fan and Mo, Hanlin},
  booktitle={Proceedings of the IEEE International Conference on Image Processing (ICIP)},
  year={2026}
}
```

## Copyright

*Copyright 2026 IEEE. Published in 2026 IEEE International Conference on Image Processing (ICIP), scheduled for 13-17 September 2026 in Tampere, Finland. Personal use of this material is permitted. Permission from IEEE must be obtained for all other uses, in any current or future media, including reprinting/republishing this material for advertising or promotional purposes, creating new collective works, for resale or redistribution to servers or lists, or reuse of any copyrighted component of this work in other works.*

