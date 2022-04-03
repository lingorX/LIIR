# LIIR (CVPR'22)
[Liulei Li](https://scholar.google.com/citations?user=eCrBWngAAAAJ&hl=en), [Tianfei Zhou](https://www.tfzhou.com/), [Wenguan Wang](https://sites.google.com/view/wenguanwang/)&dagger;, [Lu Yang](https://scholar.google.com/citations?user=V-6H56AAAAAJ&hl=en), [Jianwu Li](https://scholar.google.com/citations?hl=en&user=rWIZNIwAAAAJ), [Yi Yang](https://scholar.google.com/citations?user=RMSuNFwAAAAJ&hl=en)

[[`arXiv`](https://arxiv.org/abs/2203.14333)] [[`BibTeX`](#CitingLIIR)]

## Updates
* This repo will release an official PaddlePaddle implementation for paper: Locality-Aware Inter-and Intra-Video Reconstruction for Self-Supervised Correspondence Learning.

## Abstract
Our target is to learn visual correspondence from unlabeled videos. We develop LIIR, a locality-aware inter-and intra-video reconstruction framework that fills in three missing pieces, i.e., instance discrimination, location awareness, and spatial compactness, of self-supervised correspondence learning puzzle. First, instead of most existing efforts focusing on intra-video self-supervision only, we exploit cross video affinities as extra negative samples within a unified, inter-and intra-video reconstruction scheme. This enables instance discriminative representation learning by contrasting desired intra-video pixel association against negative inter-video correspondence. Second, we merge position information into correspondence matching, and design a position shifting strategy to remove the side-effect of position encoding during inter-video affinity computation, making our LIIR location-sensitive. Third, to make full use of the spatial continuity nature of video data, we impose a compactness-based constraint on correspondence matching, yielding more sparse and reliable solutions. The learned representation surpasses self-supervised state-of-the-arts on label propagation tasks including objects, semantic parts, and keypoints.
<p align="center">
<img src="https://github.com/0liliulei/LIIR/blob/main/fig.png" width="1000">
</p>

## Other Related Work
[Learning Video Object Segmentation from Unlabeled Videos (CVPR20)](https://github.com/carrierlxk/MuG)

## <a name="CitingLIIR"></a>Citing LIIR
```BibTeX
@inproceedings{li2022locality,
  title={Locality-Aware Inter-and Intra-Video Reconstruction for Self-Supervised Correspondence Learning},
  author={Li, Liulei and Zhou, Tianfei and Wang, Wenguan and Yang, Lu and Li, Jianwu and Yang, Yi},
  booktitle={CVPR},
  year={2022}
}
```
