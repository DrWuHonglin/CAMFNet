# CAMFNet
CAMFNet: A Cross-Modal Attention and Mamba Fusion Network for Multimodal Semantic Segmentation

![Uploading image.png…]()


The main contributions of this work are summarized as follows:
1) We propose a novel multimodal semantic segmentation network, CAMFNet, which adopts a dual-encoder and single-decoder architecture combined with a multi-level feature fusion strategy. Validation on the ISPRS Vaihingen and Potsdam datasets reveals that CAMFNet outperforms other methods in terms of segmentation accuracy.

2) We designed the CAMF module to selectively aggregate complementary cross-modal information while enhancing the discriminative power of fused features. The further proposed GCMI module enables fusion features to more effectively absorb complementary information from different modalities.

3) Additionally, we designed the MCMB module to synergistically enhance multiscale contextual understanding and long-range dependencies during the advanced semantic stage, thereby achieving superior segmentation performance.

## Results

1. CAMFNet achieves competitive results on the following datasets:
- Vaihingen: 84.04% mIoU
- Potsdam: 86.04% mIoU
2. We provide visualizations of our results on the Vaihingen and Potsdam datasets:
<img width="909" height="345" alt="image" src="https://github.com/user-attachments/assets/5910d2b1-47da-44bc-9ded-cce0210f5bb9" />


## Installation
1. Requirements
   
- Python 3.10.15	
- CUDA 12.1
- torch==1.13.0+cu117
- torchvision==0.14.0+cu117
- tqdm==4.66.4
- numpy==1.23.5
- pandas==2.0.1
- ipython==8.12.3


## Datasets
All datasets including ISPRS Potsdam, ISPRS Vaihingen can be downloaded [here](https://github.com/open-mmlab/mmsegmentation/blob/main/docs/en/user_guides/2_dataset_prepare.md#prepare-datasets).
