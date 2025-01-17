# Awesome-HDR (in progress)
Collect High Dynamic Range Imaging (especially for **Multi-exposure Fusion** and **High Dynamic Range Imaging**) Related Papers and Codes.


## Deep Learning Based Approaches

### 2022
| Title                   | Model                               | Paper                         | Code                          |     Main Idea or Key Words | Label |
|-------------------------|-------------------------------------|-------------------------------|-------------------------------|----------------------------|-------|
|TransMEF: A Transformer-Based Multi-exposure Image Fusion Framework using self-supervised Multi-Task Learning| TransMEF | [AAAI-2022](https://arxiv.org/pdf/2112.01030) | [TransMEF](https://github.com/miccaiif/TransMEF) | Transformer, Self-supervised learning | Static |
|Dual-Attention-Guided Network for Ghost-Free High Dynamic Range Imaging | DAHDRNet | [IJCV-2022](https://link.springer.com/content/pdf/10.1007/s11263-021-01535-y.pdf) | - | Dual-attention | Dynamic |

### 2021
| Title                   | Model                               | Paper                         | Code                          |     Main Idea or Key Words | Label |
|-------------------------|-------------------------------------|-------------------------------|-------------------------------|----------------------------|-------|
|ADNet: Attention-guided deformable convolutional network for high dynamic range imaging | ADNet | [CVPRW-2021](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Liu_ADNet_Attention-Guided_Deformable_Convolutional_Network_for_High_Dynamic_Range_Imaging_CVPRW_2021_paper.pdf) | [ADNet](https://github.com/Pea-Shooter/ADNet) | Deformable Convolution | Dynamic |
|Deep Coupled Feedback Network for Joint Exposure Fusion and Image Super-Resolution | CF-Net | [TIP-2021](https://www.researchgate.net/profile/Yutong-Zhang-27/publication/349458866_Deep_Coupled_Feedback_Network_for_Joint_Exposure_Fusion_and_Image_Super-Resolution/links/60ab15e2a6fdcc6d626d23f3/Deep-Coupled-Feedback-Network-for-Joint-Exposure-Fusion-and-Image-Super-Resolution.pdf) | [CF-Net](https://github.com/ytZhang99/CF-Net) | Joint MEF and SR, Feedback Mechanism | Static |
|HDR-GAN: HDR Image Reconstruction From Multi-Exposed LDR Images With Large Motions | HDR-GAN | [TIP-2021](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9387148) | [HDR-GAN](https://github.com/nonu116/HDR-GAN) | GAN | Dynamic |
|Labeled from Unlabeled: Exploiting Unlabeled Data for Few-shot Deep HDR Deghosting | FSHDR | [CVPR-2021](https://openaccess.thecvf.com/content/CVPR2021/papers/Prabhakar_Labeled_From_Unlabeled_Exploiting_Unlabeled_Data_for_Few-Shot_Deep_HDR_CVPR_2021_paper.pdf) | [FSHDR](https://github.com/Susmit-A/FSHDR) | Few-shot Learning | Dynamic |
|Hierarchical Fusion for Practical Ghost-free High Dynamic Range Imaging | HFNet | [ACMMM-2021](https://dl.acm.org/doi/pdf/10.1145/3474085.3475260) | - | Mask | Dynamic |
|IFCNN: A general image fusion framework based on convolutional neural network|IFCNN|[Information Fusion-2021](https://reader.elsevier.com/reader/sd/pii/S1566253518305505?token=ACC5F47A0B1290F77201B2C383AA4F6BEEEE32B552BF3D5C661D5EBFC5AD6CA412C410E2782F87424429D79A1BD83374&originRegion=us-east-1&originCreation=20211112091259)| [IFCNN](https://github.com/uzeful/IFCNN) | Salient Features | Static |
|Multi-exposure image fusion via deep perceptual enhancement | DPE-MEF | [Information Fusion-2021](https://reader.elsevier.com/reader/sd/pii/S1566253521002049?token=E024D57C2BEA2F5188A6EE08246A998D95C171B04869B2583650F117B55D88B1C17FE48D20A107FA713C4BEF28635B17&originRegion=us-east-1&originCreation=20211112090811) | [DPE-MEF](https://github.com/dongdong4fei/DPE-MEF) | Perceptual Enhancement | Static |

### 2020
| Title                   | Model                               | Paper                         | Code                          |            Main Idea or Key Words | Label |
|-------------------------|-------------------------------------|-------------------------------|-------------------------------|-----------------------------------|-------|
|Deep Convolutional Neural Network for Multi-modal Image Restoration and Fusion | CU-Net | [TPAMI-2020](https://arxiv.org/pdf/1910.04066) | [CU-Net](https://github.com/cindydeng1991/TPAMI-CU-Net) | Interpretable Network, Multi-modal image processing | Static |
|U2Fusion: A Unified Unsupervised Image Fusion Network | U2Fusion | [TPAMI-2020](https://www.researchgate.net/profile/Jiayi-Ma-2/publication/343218239_U2Fusion_A_Unified_Unsupervised_Image_Fusion_Network/links/5f1fd81645851515ef50431c/U2Fusion-A-Unified-Unsupervised-Image-Fusion-Network.pdf) | [U2Fusion](https://github.com/hanna-xu/U2Fusion) | Unsupervised Learning | Static |
|Deep Guided Learning for Fast Multi-Exposure Image Fusion | MEF-Net | [TIP-2020](https://ece.uwaterloo.ca/~k29ma/papers/19_TIP_MEF-Net.pdf)| [MEF-Net](https://github.com/makedede/MEFNet) | Unsupervised Learning, Guided Filter | Static |
|Deep HDR Imaging via A Non-Local Network| NHDRRnet | [TIP-2020](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8989959) | [NHDRRnet](https://github.com/tuvovan/NHDRRNet) | Non-local | Dynamic |
|Unsupervised Deep Image Fusion With Structure Tensor Representations | DIF-Net | [TIP-2020](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8962327) | [DIF-Net](https://github.com/kimphys/DIFNet.pytorch) | Unsupervised Learning, Structure Tensor Representations | Static |
|MEF-GAN: Multi-Exposure Image Fusion via Generative Adversarial Networks | MEF-GAN | [TIP-2020](https://drive.google.com/file/d/1EHik52It9YJnxb1loSsXrZ168l_Uljnz/view) |[MEF-GAN](https://github.com/jiayi-ma/MEF-GAN) | GAN | Static |


### 2019
| Title                   | Model                               | Paper                         | Code                          |            Main Idea or Key Words | Label |
|-------------------------|-------------------------------------|-------------------------------|-------------------------------|-----------------------------------|-------|
| Attention-guided Network for Ghost-free High Dynamic Range Imaging | AHDRNet | [CVPR-2019](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yan_Attention-Guided_Network_for_Ghost-Free_High_Dynamic_Range_Imaging_CVPR_2019_paper.pdf) | [AHDRNet](https://donggong1.github.io/ahdr) | Attention | Dynamic |

### 2018
| Title                   | Model                               | Paper                         | Code                          |            Main Idea or Key Words | Label |
|-------------------------|-------------------------------------|-------------------------------|-------------------------------|-----------------------------------|-------|
| Deep high dynamic range imaging with large foreground motions | DeepHDR | [ECCV-2018](http://openaccess.thecvf.com/content_ECCV_2018/papers/Shangzhe_Wu_Deep_High_Dynamic_ECCV_2018_paper.pdf) | [DeepHDR](https://github.com/elliottwu/DeepHDR) | First End-to-End, U-Net | Dynamic |

### 2017
| Title                   | Model                               | Paper                         | Code                          |            Main Idea or Key Words | Label |
|-------------------------|-------------------------------------|-------------------------------|-------------------------------|-----------------------------------|-------|
|DeepFuse: A Deep Unsupervised Approach for Exposure Fusion with Extreme Exposure Image Pairs| DeepFuse | [ICCV-2017](http://openaccess.thecvf.com/content_ICCV_2017/papers/Prabhakar_DeepFuse_A_Deep_ICCV_2017_paper.pdf) | - | Extreme Exposure Fusion, Unsupervised | Static |
|Deep High Dynamic Range Imaging of Dynamic Scenes|Kalantari|[ACM-TOG-2017](https://people.engr.tamu.edu/nimak/Data/SIGGRAPH17_HDR_LoRes.pdf) |[Kalantari](https://cseweb.ucsd.edu/~viscomp/projects/SIG17HDR/)|Resgistration, Large Dataset| Dynamic |
|HDR image reconstruction from a single exposure using deep CNNs|HDRCNN|[ACM-TOG-2017](https://arxiv.org/abs/1710.07480)|[HDRCNN](https://github.com/gabrieleilertsen/hdrcnn)|Single Image HDR | Static & Dynamic |

## Traditional Approaches
| Title                   | Model                               | Paper                         | Code                          |            Main Idea or Key Words | Label | Year |
|-------------------------|-------------------------------------|-------------------------------|-------------------------------|-----------------------------------|-------|------|
|Detail-Preserving Multi-Exposure Fusion with Edge-Preserving Structural Patch Decomposition | MSPD-MEF | [TCSVT-2021](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9330785) | [MSPD-MEF](https://github.com/xiaohuiben/MESPD_TCSVT-2021) | Structural Patch Decomposition | Static & Dynamic | 2021 |
|Fast Multi-Scale Structural Patch Decomposition for Multi-Exposure Image Fusion | FMMEF | [TIP-2020](https://ece.uwaterloo.ca/~k29ma/papers/20_TIP_MS-SPF-MEF.pdf) | [FMMEF](https://github.com/xiaohuiben/fmmef-TIP-2020) | Multi-scale, Structural Patch Decomposition | Static & Dynamic |2020|
|Robust Multi-Exposure Image Fusion: A Structural Patch Decomposition Approach| SPD-MEF | [TIP-2017](https://ece.uwaterloo.ca/~k29ma/papers/17_TIP_SPD-MEF.pdf) | [SPD-MEF](https://ece.uwaterloo.ca/~k29ma/codes/SPD-MEF.rar) | Robust, Structural Patch Decomposition | Static & Dynamic | 2017 |
|Robust High Dynamic Range Imaging by Rank Minimization| RHDR | [TPAMI-2015](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6915885) | [RHDR](https://github.com/ytZhang99/Awesome-HDR/blob/master/code/Oh.zip) | Rank Minimization | Dynamic | 2015 |
|HDR Deghosting: How to deal with Saturation? | Hu | [CVPR-2013](http://openaccess.thecvf.com/content_cvpr_2013/papers/Hu_HDR_Deghosting_How_2013_CVPR_paper.pdf) | [Hu](https://junhu-svd.github.io/public_html/CVPR2013/) | Registration | Dynamic | 2013 |
|Robust Patch-Based HDR Reconstruction of Dynamic Scenes | Sen | [ACM-TOG-2012](https://people.engr.tamu.edu/nimak/Data/SIGASIA12_HDR_PatchBasedReconstruction_LoRes.pdf) | [Sen](https://web.ece.ucsb.edu/~psen/hdrvideo) | Patch-Based Registration | Dynamic |2012|


## HDR Image Quality Evaluation Metrics
| Title    |      Metric       |      Paper         | Code        |       Domain & Scene  |       Year   |
|-----------------|------------------|----------------------|-------------------|----------------|----------------------|
| Perceptual Evalutation for Multi-Exposure Image Fusion of Dynamic Scenes | MEF-SSIMd | [TIP-2020](https://ece.uwaterloo.ca/~k29ma/papers/19_TIP_MEF-SSIMd.pdf) | [MEF-SSIMd](https://github.com/h4nwei/MEF-SSIMd) | LDR & dynamic | 2020 |
| Perceptual Quality Assessment for Multi-Exposure Image Fusion | MEF-SSIM | [TIP-2015](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.709.9646&rep=rep1&type=pdf) | [MEF-SSIM](https://ece.uwaterloo.ca/~k29ma/codes/MEF.rar) | LDR & static | 2015 |