# Awesome Industrial Anomaly Detection

We discuss public datasets and related studies in detail. Welcome to read our paper and make comments. 

[Deep Industrial Image Anomaly Detection: A Survey](https://arxiv.org/abs/2301.11514)

We will keep focusing on this field and update relevant information.

(Keywords: anomaly detection, anomaly segmentation, industrial image, defect detection.)

# Recent research
+ DiffusionAD: Denoising Diffusion for Anomaly Detection [[2023]](https://arxiv.org/abs/2303.08730)
+ SSGD: A smartphone screen glass dataset for defect detection [[2023]](https://arxiv.org/abs/2303.06673)[[dataset is coming soon]](https://github.com/Yangr116/SSGDataset)
+ In-painting Radiography Images for Unsupervised Anomaly Detection [[CVPR 2023]](https://arxiv.org/abs/2111.13495)
+ Diversity-Measurable Anomaly Detection [[CVPR 2023]](https://arxiv.org/abs/2303.05047)
+ PyramidFlow: High-Resolution Defect Contrastive Localization using Pyramid Normalizing Flow [[CVPR 2023]](https://arxiv.org/abs/2303.02595)
+ Multimodal Industrial Anomaly Detection via Hybrid Fusion [[CVPR 2023]](https://arxiv.org/abs/2303.00601)[[code is coming soon]](https://github.com/nomewang/M3DM)
+ Pushing the Limits of Fewshot Anomaly Detection in Industry Vision: Graphcore [[ICLR 2023]](https://arxiv.org/abs/2301.12082)
+ RGI: robust GAN-inversion for mask-free image inpainting and unsupervised pixel-wise anomaly detection [[ICLR 2023]](https://openreview.net/pdf?id=1UbNwQC89a)
+ Collaborative Discrepancy Optimization for Reliable Image Anomaly Localization [[TII 2023]](https://ieeexplore.ieee.org/document/10034849)[[code]](https://github.com/caoyunkang/CDO)
+ CVPR 1st workshop on Vision-based InduStrial InspectiON[[homepage]](https://vision-based-industrial-inspection.github.io/cvpr-2023/)[[data link]](https://drive.google.com/drive/folders/1TVp_UXJuXudqhC2L3ZKyIDcmQ_2O3JVi)
# Paper Tree (Classification of representative methods)
![](https://github.com/M-3LAB/awesome-industrial-anomaly-detection/blob/main/paper_tree.png)
# Timeline
![](https://github.com/M-3LAB/awesome-industrial-anomaly-detection/blob/main/timeline.png)

# Paper list for industrial image anomaly detection

# Related Survey, Benchmark and Framework
+ A review on computer vision based defect detection and condition assessment of concrete and asphalt civil infrastructure [[2015]](https://www.sciencedirect.com/science/article/abs/pii/S1474034615000208)
+ (czimmermann2020visual)Visual-based defect detection and classification approaches for industrial applications: a survey [[2020]](https://pdfs.semanticscholar.org/1dfc/080a5f26b5ce78f9ce3e9f106bf7e8124f74.pdf)
+ (tao2022deep)Deep Learning for Unsupervised Anomaly Localization in Industrial Images: A Survey [[TIM 2022]](http://arxiv.org/pdf/2207.10298)
+ (cui2022survey)A Survey on Unsupervised Industrial Anomaly Detection Algorithms [[2022]](https://arxiv.org/abs/2204.11161)
+ Benchmarking Unsupervised Anomaly Detection and Localization [[2022]](https://arxiv.org/abs/2205.14852)
+ IM-IAD: Industrial Image Anomaly Detection Benchmark in Manufacturing [[2023]](https://arxiv.org/abs/2301.13359)
+ A Deep Learning-based Software for Manufacturing Defect Inspection[[TII 2017]](https://ieeexplore.ieee.org/document/9795891)[[code]](https://github.com/sundyCoder/DEye)
+ Anomalib: A Deep Learning Library for Anomaly Detection [[code]](https://github.com/openvinotoolkit/anomalib)

# 2 Unsupervised AD

## 2.1 Feature-Embedding-based Methods

### 2.1.1 Teacher-Student
+ Uninformed students: Student-teacher anomaly detection with discriminative latent embeddings [[CVPR 2020]](http://arxiv.org/pdf/1911.02357)
+ Student-Teacher Feature Pyramid Matching for Anomaly Detection [[2021]](https://arxiv.org/pdf/2103.04257.pdf)
+ Multiresolution knowledge distillation for anomaly detection [[CVPR 2021]](https://arxiv.org/pdf/2011.11108)
+ Reconstruction Student with Attention for Student-Teacher Pyramid Matching [[2021]](https://arxiv.org/pdf/2111.15376.pdf)
+ Reconstructed Student-Teacher and Discriminative Networks for Anomaly Detection [[2022]](https://arxiv.org/pdf/2210.07548.pdf)
+ Anomaly Detection via Reverse Distillation from One-Class Embedding [[CVPR 2022]](http://arxiv.org/pdf/2201.10703)[[code]](https://github.com/hq-deng/RD4AD)
+ Asymmetric Student-Teacher Networks for Industrial Anomaly Detection [[WACV 2022]](https://arxiv.org/pdf/2210.07829.pdf)[[code]](https://github.com/marco-rudolph/AST)
+ Informative knowledge distillation for image anomaly segmentation [[2022]](https://www.sciencedirect.com/science/article/pii/S0950705122004038/pdfft?md5=758c327dd4d1d052b61a19882f957123&pid=1-s2.0-S0950705122004038-main.pdf)

### 2.1.2 One-Class Classification (OCC)
+ Patch svdd: Patch-level svdd for anomaly detection and segmentation [[ACCV 2020]](https://arxiv.org/pdf/2006.16067.pdf)
+ Anomaly detection using improved deep SVDD model with data structure preservation [[2021]](https://www.sciencedirect.com/science/article/am/pii/S0167865521001598)
+ A Semantic-Enhanced Method Based On Deep SVDD for Pixel-Wise Anomaly Detection [[2021]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9428370)
+ MOCCA: Multilayer One-Class Classification for Anomaly Detection [[2021]](http://arxiv.org/pdf/2012.12111)
+ Defect Detection of Metal Nuts Applying Convolutional Neural Networks [[2021]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9529439)
+ Panda: Adapting pretrained features for anomaly detection and segmentation [[2021]](http://arxiv.org/pdf/2010.05903)
+ Mean-shifted contrastive loss for anomaly detection [[2021]](https://arxiv.org/pdf/2106.03844.pdf)
+ Learning and Evaluating Representations for Deep One-Class Classification [[2020]](https://arxiv.org/pdf/2011.02578.pdf)
+ Self-supervised learning for anomaly detection with dynamic local augmentation [[2021]](https://ieeexplore.ieee.org/ielx7/6287639/6514899/09597511.pdf)
+ Contrastive Predictive Coding for Anomaly Detection [[2021]](https://arxiv.org/pdf/2107.07820.pdf)
+ Cutpaste: Self-supervised learning for anomaly detection and localization [[ICCV 2021]](http://arxiv.org/pdf/2104.04015)[[unofficial code]](https://github.com/Runinho/pytorch-cutpaste)
+ Consistent estimation of the max-flow problem: Towards unsupervised image segmentation [[2020]](http://arxiv.org/pdf/1811.00220)
+ MemSeg: A semi-supervised method for image surface defect detection using differences and commonalities [[2022]](https://arxiv.org/pdf/2205.00908.pdf)[[unofficial code]](https://github.com/TooTouch/MemSeg)

### 2.1.3 Distribution-Map
+ A Multi-Scale A Contrario method for Unsupervised Image Anomaly Detection [[2021]](http://arxiv.org/pdf/2110.02407)
+ Modeling the distribution of normal data in pre-trained deep features for anomaly detection [[2021]](http://arxiv.org/pdf/2005.14140)
+ Transfer Learning Gaussian Anomaly Detection by Fine-Tuning Representations [[2021]](https://arxiv.org/pdf/2108.04116.pdf)
+ PEDENet: Image anomaly localization via patch embedding and density estimation [[2022]](https://arxiv.org/pdf/2110.15525.pdf)
+ Unsupervised image anomaly detection and segmentation based on pre-trained feature mapping [[2022]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9795121)
+ Position Encoding Enhanced Feature Mapping for Image Anomaly Detection [[2022]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9926547)[[code]](https://github.com/smiler96/PFM-and-PEFM-for-Image-Anomaly-Detection-and-Segmentation)
+ Focus your distribution: Coarse-to-fine non-contrastive learning for anomaly detection and localization [[ICME 2022]](http://arxiv.org/pdf/2110.04538)
+ Anomaly Detection of Defect using Energy of Point Pattern Features within Random Finite Set Framework [[2021]](https://arxiv.org/abs/2108.12159)[[code]](https://github.com/AmmarKamoona/RFS-Energy-Anomaly-Detection-of-Defect)
+ Fastflow: Unsupervised anomaly detection and localization via 2d normalizing flows [[2021]](https://arxiv.org/pdf/2111.07677.pdf)[[unofficial code]](https://github.com/gathierry/FastFlow)
+ Same same but differnet: Semi-supervised defect detection with normalizing flows [[WACV 2021]](http://arxiv.org/pdf/2008.12577)[[code]](https://github.com/marco-rudolph/differnet)
+ Fully convolutional cross-scale-flows for image-based defect detection [[WACV 2022]](http://arxiv.org/pdf/2110.02855)[[code]](https://github.com/marco-rudolph/cs-flow)
+ Cflow-ad: Real-time unsupervised anomaly detection with localization via conditional normalizing flows [[WACV 2022]](http://arxiv.org/pdf/2107.12571)[[code]](https://github.com/gudovskiy/cflow-ad)
+ CAINNFlow: Convolutional block Attention modules and Invertible Neural Networks Flow for anomaly detection and localization tasks [[2022]](https://arxiv.org/pdf/2206.01992.pdf)
+ AltUB: Alternating Training Method to Update Base Distribution of Normalizing Flow for Anomaly Detection [[2022]](https://arxiv.org/pdf/2210.14913.pdf)
+ Collaborative Discrepancy Optimization for Reliable Image Anomaly Localization [[TII 2023]](https://ieeexplore.ieee.org/document/10034849)[[code]](https://github.com/caoyunkang/CDO)
+ PyramidFlow: High-Resolution Defect Contrastive Localization using Pyramid Normalizing Flow [[CVPR 2023]](https://arxiv.org/abs/2303.02595)

### 2.1.4 Memory Bank
 <!-- + (eskin2002geometric) A geometric framework for unsupervised anomaly detection [[2002]](https://www.researchgate.net/publication/242620986_A_Geometric_Framework_for_Unsupervised_Anomaly_Detection_Detecting_Intrusions_in_Unlabeled_Data#read) -->
 + Sub-image anomaly detection with deep pyramid correspondences [[2020]](https://arxiv.org/pdf/2005.02357.pdf)
 + Semi-orthogonal embedding for efficient unsupervised anomaly segmentation [[2021]](https://arxiv.org/pdf/2105.14737.pdf)
 + Anomaly Detection Via Self-Organizing Map [[2021]](http://arxiv.org/pdf/2107.09903)
 + PaDiM: A Patch Distribution Modeling Framework for Anomaly Detection and Localization [[ICPR 2021]](https://link.springer.com/chapter/10.1007/978-3-030-68799-1_35)[[unofficial code]](https://github.com/xiahaifeng1995/PaDiM-Anomaly-Detection-Localization-master)
 + Industrial Image Anomaly Localization Based on Gaussian Clustering of Pretrained Feature [[2021]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9479740)
 + Towards total recall in industrial anomaly detection[[CVPR 2022]](http://arxiv.org/pdf/2106.08265)[[code]](https://github.com/amazon-science/patchcore-inspection)
 + CFA: Coupled-Hypersphere-Based Feature Adaptation for Target-Oriented Anomaly Localization[[2022]](https://arxiv.org/pdf/2206.04325.pdf)[[code]](https://github.com/sungwool/CFA_for_anomaly_localization)
 + FAPM: Fast Adaptive Patch Memory for Real-time Industrial Anomaly Detection[[2022]](https://arxiv.org/pdf/2211.07381.pdf)
 + N-pad: Neighboring Pixel-based Industrial Anomaly Detection [[2022]](https://arxiv.org/pdf/2210.08768.pdf)
 + Image Anomaly Detection and Localization with Position and Neighborhood Information [[2022]](https://arxiv.org/pdf/2211.12634.pdf)
 + Multi-scale patch-based representation learning for image anomaly detection and segmentation [[2022]](https://openaccess.thecvf.com/content/WACV2022/papers/Tsai_Multi-Scale_Patch-Based_Representation_Learning_for_Image_Anomaly_Detection_and_Segmentation_WACV_2022_paper.pdf)
 + SPot-the-Difference Self-supervised Pre-training for Anomaly Detection and Segmentation [[ECCV 2022]](https://arxiv.org/pdf/2207.14315.pdf)
 + Diversity-Measurable Anomaly Detection [[CVPR 2023]](https://arxiv.org/abs/2303.05047)

## 2.2 Reconstruction-Based Methods

### 2.2.1 Autoencoder (AE)
 + Improving unsupervised defect segmentation by applying structural similarity to autoencoders [[2018]](https://arxiv.org/pdf/1807.02011.pdf)
 + Unsupervised anomaly detection using style distillation [[2020]](https://ieeexplore.ieee.org/ielx7/6287639/6514899/09288772.pdf)
 + Unsupervised two-stage anomaly detection [[2021]](https://arxiv.org/pdf/2103.11671.pdf)
 + Dfr: Deep feature reconstruction for unsupervised anomaly segmentation [[Neurocomputing 2020]](https://arxiv.org/pdf/2012.07122.pdf)
 + Unsupervised anomaly segmentation via multilevel image reconstruction and adaptive attention-level transition [[2021]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9521893)
 + Encoding structure-texture relation with p-net for anomaly detection in retinal images [[2020]](http://arxiv.org/pdf/2008.03632)
 + Improved anomaly detection by training an autoencoder with skip connections on images corrupted with stain-shaped noise [[2021]](http://arxiv.org/pdf/2008.12977)
 + Unsupervised anomaly detection for surface defects with dual-siamese network [[2022]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9681338)
 + Divide-and-assemble: Learning block-wise memory for unsupervised anomaly detection [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Hou_Divide-and-Assemble_Learning_Block-Wise_Memory_for_Unsupervised_Anomaly_Detection_ICCV_2021_paper.pdf)
 + Reconstruction from edge image combined with color and gradient difference for industrial surface anomaly detection [[2022]](http://arxiv.org/pdf/2210.14485)[[code]](https://github.com/liutongkun/edgrec)
 + Spatial Contrastive Learning for Anomaly Detection and Localization [[2022]](https://ieeexplore.ieee.org/ielx7/6287639/9668973/09709224.pdf)
 + Superpixel masking and inpainting for self-supervised anomaly detection [[BMVC 2020]](https://www.bmvc2020-conference.com/assets/papers/0275.pdf)
 + Iterative image inpainting with structural similarity mask for anomaly detection [[2020]](https://openreview.net/pdf?id=b4ach0lGuYO)
 + Self-Supervised Masking for Unsupervised Anomaly Detection and Localization [[2022]](https://arxiv.org/pdf/2205.06568.pdf)
 + Reconstruction by inpainting for visual anomaly detection [[PR 2021]](https://www.sciencedirect.com/science/article/pii/S0031320320305094/pdfft?md5=9bbe942017de1acd3a97034bc2d4a8fb&pid=1-s2.0-S0031320320305094-main.pdf)
 + Draem-a discriminatively trained reconstruction embedding for surface anomaly detection [[ICCV 2021]](http://arxiv.org/pdf/2108.07610)[[code]](https://github.com/vitjanz/draem)
 + DSR: A dual subspace re-projection network for surface anomaly detection [[ECCV 2022]](https://arxiv.org/pdf/2208.01521.pdf)[[code]](https://github.com/VitjanZ/DSR_anomaly_detection)
 + Natural Synthetic Anomalies for Self-supervised Anomaly Detection and Localization [[ECCV 2022]](https://arxiv.org/pdf/2109.15222.pdf)[[code]](https://github.com/hmsch/natural-synthetic-anomalies)
 + Self-Supervised Training with Autoencoders for Visual Anomaly Detection [[2022]](https://arxiv.org/pdf/2206.11723.pdf)
 + Self-supervised predictive convolutional attentive block for anomaly detection [[CVPR 2022 oral]](http://arxiv.org/pdf/2111.09099)[[code]](https://github.com/ristea/sspcab)
 + Self-Supervised Masked Convolutional Transformer Block for Anomaly Detection [[TPAMI 2022]](https://arxiv.org/pdf/2209.12148.pdf)[[code]](https://github.com/ristea/ssmctb)
 + Iterative energy-based projection on a normal data manifold for anomaly localization [[2019]](https://arxiv.org/pdf/2002.03734.pdf)
 + Towards visually explaining variational autoencoders [[2020]](http://arxiv.org/pdf/1911.07389)
 + Deep generative model using unregularized score for anomaly detection with heterogeneous complexity [[2020]](http://arxiv.org/pdf/1807.05800)
 + Anomaly localization by modeling perceptual features [[2020]](https://arxiv.org/pdf/2008.05369.pdf)
 + Image anomaly detection using normal data only by latent space resampling [[2020]](https://pdfs.semanticscholar.org/cb59/dab0a725c0b511f3140ea47ea0967f3643bf.pdf)
 + In-painting Radiography Images for Unsupervised Anomaly Detection [[CVPR 2023]](https://arxiv.org/abs/2111.13495)
 
### 2.2.2 Generative Adversarial Networks (GANs)
 + Learning semantic context from normal samples for unsupervised anomaly detection [[AAAI 2021]](https://ojs.aaai.org/index.php/AAAI/article/download/16420/16227)
 + Anoseg: Anomaly segmentation network using self-supervised learning [[2021]](https://arxiv.org/pdf/2110.03396.pdf)
 + Omni-frequency Channel-selection Representations for Unsupervised Anomaly Detection [[2022]](https://arxiv.org/pdf/2203.00259.pdf)[[code]](https://github.com/zhangzjn/ocr-gan)

### 2.2.3 Transformer
 + VT-ADL: A vision transformer network for image anomaly detection and localization [[ISIE 2021]](http://arxiv.org/pdf/2104.10036)
 + ADTR: Anomaly Detection Transformer with Feature Reconstruction [[2022]](https://arxiv.org/pdf/2209.01816.pdf)
 + AnoViT: Unsupervised Anomaly Detection and Localization With Vision Transformer-Based Encoder-Decoder [[2022]](https://ieeexplore.ieee.org/ielx7/6287639/6514899/09765986.pdf)
 + HaloAE: An HaloNet based Local Transformer Auto-Encoder for Anomaly Detection and Localization [[2022]](https://arxiv.org/pdf/2208.03486.pdf)
 + Inpainting transformer for anomaly detection [[ICIAP 2022]](https://arxiv.org/pdf/2104.13897.pdf)
 + Masked Swin Transformer Unet for Industrial Anomaly Detection [[2022]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9858596)
 + Masked Transformer for image Anomaly Localization [[TII 2022]](http://arxiv.org/pdf/2210.15540)

### 2.2.4 Diffusion Model
 + Denoising diffusion probabilistic models [[2020]](https://arxiv.org/pdf/2006.11239.pdf)
 + AnoDDPM: Anomaly Detection With Denoising Diffusion Probabilistic Models Using Simplex Noise [[CVPR Workshop 2022]](http://dro.dur.ac.uk/36134/1/36134.pdf)
 + Unsupervised Visual Defect Detection with Score-Based Generative Model[[2022]](https://arxiv.org/pdf/2211.16092.pdf)
 + DiffusionAD: Denoising Diffusion for Anomaly Detection [[2023]](https://arxiv.org/abs/2303.08730)
 
 # 2.3 Supervised AD
 + Neural batch sampling with reinforcement learning for semi-supervised anomaly detection [[ECCV 2020]](https://www.ri.cmu.edu/wp-content/uploads/2020/05/WenHsuan_MSR_Thesis-1.pdf)
 + Explainable Deep One-Class Classification [[ICLR 2020]](https://arxiv.org/pdf/2007.01760.pdf)
 + Attention guided anomaly localization in images [[ECCV 2020]](http://arxiv.org/pdf/1911.08616)
 + Mixed supervision for surface-defect detection: From weakly to fully supervised learning [[2021]](https://arxiv.org/pdf/2104.06064.pdf)
 + Explainable deep few-shot anomaly detection with deviation networks [[2021]](https://arxiv.org/pdf/2108.00462.pdf)
 + Logit Inducing With Abnormality Capturing for Semi-Supervised Image Anomaly Detection [2022]
 + Catching Both Gray and Black Swans: Open-set Supervised Anomaly Detection [[CVPR 2022]](http://arxiv.org/pdf/2203.14506)
 + Domain adaptation for automatic OLED panel defect detection using adaptive support vector data description [[IJCV 2017]](https://link.springer.com/article/10.1007/s11263-016-0953-y)
 + An effective framework of automated visual surface defect detection for metal parts [[2021]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9475966)
 + Interleaved Deep Artifacts-Aware Attention Mechanism for Concrete Structural Defect Classification [[TIP 2021]](https://eprints.keele.ac.uk/10031/1/TIP24Jul2021.pdf)
 + Reference-based defect detection network [[TIP 2021]](http://arxiv.org/pdf/2108.04456)
 + Fabric defect detection using tactile information [[ICRA 2021]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9561092)
 + A lightweight spatial and temporal multi-feature fusion network for defect detection [[TIP 2020]](http://nrl.northumbria.ac.uk/id/eprint/48908/1/ALightweightSpatialandTemporalMulti-featureFusionNetworkforDefectDetection.pdf)
 + Detection and segmentation of manufacturing defects with convolutional neural networks and transfer learning [[2018]](https://europepmc.org/articles/pmc6512995?pdf=render)

# 3 Other Research Direction

## 3.1 Few-Shot AD
 + Learning unsupervised metaformer for anomaly detection [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wu_Learning_Unsupervised_Metaformer_for_Anomaly_Detection_ICCV_2021_paper.pdf)
 + Registration based few-shot anomaly detection [[ECCV 2022 oral]](https://arxiv.org/pdf/2207.07361.pdf)[[code]](https://github.com/MediaBrain-SJTU/RegAD)
 + Same same but differnet: Semi-supervised defect detection with normalizing flows [[(Distribution)WACV 2021]](http://arxiv.org/pdf/2008.12577)
 + Towards total recall in industrial anomaly detection [[(Memory bank)CVPR 2022]](http://arxiv.org/pdf/2106.08265)
 + A hierarchical transformation-discriminating generative model for few shot anomaly detection [[ICCV 2021]](http://arxiv.org/pdf/2104.14535)
 + Anomaly detection of defect using energy of point pattern features within random finite set framework [[2021]](https://arxiv.org/pdf/2108.12159.pdf)
 + MAEDAY: MAE for few and zero shot AnomalY-Detection [[2022]](https://arxiv.org/pdf/2211.14307.pdf)
  <!-- + (he2022masked)Masked autoencoders are scalable vision learners [[2022]](http://arxiv.org/pdf/2111.06377) -->

## 3.2 Noisy AD
 + Trustmae: A noise-resilient defect classification framework using memory-augmented auto-encoders with trust regions [[WACV 2021]](http://arxiv.org/pdf/2012.14629)
 + Self-Supervise, Refine, Repeat: Improving Unsupervised Anomaly Detection [[TMLR 2021]](https://arxiv.org/pdf/2106.06115.pdf)
 + Data refinement for fully unsupervised visual inspection using pre-trained networks [[2022]](https://arxiv.org/pdf/2202.12759.pdf)
 + Latent Outlier Exposure for Anomaly Detection with Contaminated Data [[ICML 2022]](https://arxiv.org/pdf/2202.08088.pdf)
 + Deep one-class classification via interpolated gaussian descriptor [[AAAI 2022 oral]](https://arxiv.org/pdf/2101.10043.pdf)[[code]](https://github.com/tianyu0207/IGD)
 + SoftPatch: Unsupervised Anomaly Detection with Noisy Data [[NIPS 2020]](http://arxiv.org/pdf/2009.09443)[[code is coming soon]](https://github.com/TencentYoutuResearch/AnomalyDetection-SoftPatch)

## 3.3 Anomaly Synthetic
 + Cutpaste: Self-supervised learning for anomaly detection and localization [[(OCC)ICCV 2021]](http://arxiv.org/pdf/2104.04015)[[unofficial code]](https://github.com/Runinho/pytorch-cutpaste)
 + Draem-a discriminatively trained reconstruction embedding for surface anomaly detection [[(Reconstruction AE)ICCV 2021]](http://arxiv.org/pdf/2108.07610)[[code]](https://github.com/vitjanz/draem)
 + MemSeg: A semi-supervised method for image surface defect detection using differences and commonalities [[(OCC)2022]](https://arxiv.org/pdf/2205.00908.pdf)[[unofficial code]](https://github.com/TooTouch/MemSeg)
 + Multistage GAN for fabric defect detection [[2019]](https://pubmed.ncbi.nlm.nih.gov/31870985/)
 + Gan-based defect synthesis for anomaly detection in fabrics [[2020]](https://www.lfb.rwth-aachen.de/bibtexupload/pdf/RIP20c.pdf)
 + Defect image sample generation with GAN for improving defect recognition [[2020]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9000806)
 + Defective samples simulation through neural style transfer for automatic surface defect segment [[2020]](http://arxiv.org/pdf/1910.03334)
 + A simulation-based few samples learning method for surface defect segmentation [[2020]](https://www.sciencedirect.com/science/article/pii/S0925231220310791/pdfft?md5=f3f72bc8687c8f9968d4a2a1bd3ea17e&pid=1-s2.0-S0925231220310791-main.pdf)
 + Synthetic data augmentation for surface defect detection and classification using deep learning [[2020]](https://link.springer.com/article/10.1007/s10845-020-01710-x)
 + Defect Transfer GAN: Diverse Defect Synthesis for Data Augmentation [[BMVC 2022]](https://openreview.net/pdf?id=2hMEdc35xZ6)
 + Defect-GAN: High-fidelity defect synthesis for automated defect inspectio [[2021]](https://dr.ntu.edu.sg/bitstream/10356/146285/2/WACV_2021_Defect_GAN__Camera_Ready_.pdf)
 + EID-GAN: Generative Adversarial Nets for Extremely Imbalanced Data Augmentation[[TII 2022]](https://ieeexplore.ieee.org/document/9795891)
 
## 3.4 3D AD
 + Anomaly detection in 3d point clouds using deep geometric descriptors [[WACV 2022]](https://arxiv.org/pdf/2202.11660.pdf)
 + Back to the feature: classical 3d features are (almost) all you need for 3D anomaly detection [[2022]](https://arxiv.org/pdf/2203.05550.pdf)[[code]](https://github.com/eliahuhorwitz/3D-ADS)
 + Anomaly Detection Requires Better Representations [[2022]](https://arxiv.org/pdf/2210.10773.pdf)
 + Asymmetric Student-Teacher Networks for Industrial Anomaly Detection [[WACV 2022]](https://arxiv.org/pdf/2210.07829.pdf)
 + Multimodal Industrial Anomaly Detection via Hybrid Fusion [[CVPR 2023]](https://arxiv.org/abs/2303.00601)
 
## 3.5 Continual AD
 + Towards Continual Adaptation in Industrial Anomaly Detection [[ACM MM 2022]](https://dl.acm.org/doi/abs/10.1145/3503161.3548232)

## 3.6 Uniform AD
 + A Unified Model for Multi-class Anomaly Detection [[NIPS 2022]](https://arxiv.org/pdf/2206.03687.pdf)
## 3.7 Logical AD
 + Beyond Dents and Scratches: Logical Constraints in Unsupervised Anomaly Detection and Localization [[IJCV 2022]](https://link.springer.com/content/pdf/10.1007/s11263-022-01578-9.pdf)
 
# 4 Dataset
 + A noise robust method based on completed local binary patterns for hot-rolled steel strip surface defects [[2013]](https://www.sciencedirect.com/science/article/pii/S0169433213016437/pdfft?md5=478bf7f07bbf551a5d991048f9bc16e4&pid=1-s2.0-S0169433213016437-main.pdf)
 + Deep learning based steel pipe weld defect detection [[2021]](https://www.tandfonline.com/doi/pdf/10.1080/08839514.2021.1975391?needAccess=true)
 + (SDD)Severstal: Steel Defect Detection [[2019]]()
 + (carrera2016defect)Defect detection in SEM images of nanofibrous materials [[2016]](https://re.public.polimi.it/bitstream/11311/1024586/1/anomaly_detection_sem.pdf)
 + (GDXray)GDXray: The database of X-ray images for nondestructive testing [[2015]](http://dmery.sitios.ing.uc.cl/Prints/ISI-Journals/2015-JNDE-GDXray.pdf)
 + Online PCB defect detector on a new PCB defect dataset [[2019]](https://arxiv.org/pdf/1902.06197.pdf)
 + Fabric inspection based on the Elo rating method [[2016]](http://hub.hku.hk/bitstream/10722/229176/1/content.pdf)
 + (KolektorSDD)Segmentation-based deep-learning approach for surface-defect detection [[Journal of Intelligent Manufacturing]](http://arxiv.org/pdf/1903.08536)
 + (KolektorSDD2)Mixed supervision for surface-defect detection: From weakly to fully supervised learning [[Computers in Industry 2021]](https://arxiv.org/pdf/2104.06064.pdf)
 + (RSDD)A hierarchical extractor-based visual rail surface inspection system [[2017]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8063875)
 + (Eyecandies)The Eyecandies Dataset for Unsupervised Multimodal Anomaly Detection and Localization [[ACCV 2022]](https://arxiv.org/pdf/2210.04570.pdf)
 + (MVTec AD)MVTec AD: A comprehensive real-world dataset for unsupervised anomaly detection [[CVPR 2019]](https://www.mvtec.com/fileadmin/Redaktion/mvtec.com/company/research/mvtec_ad.pdf)
 + (MVTec 3D-AD)The mvtec 3d-ad dataset for unsupervised 3d anomaly detection and localization [[VISAPP 2021]](https://arxiv.org/pdf/2112.09045.pdf)
 + (MVTec LOCO-AD)Beyond Dents and Scratches: Logical Constraints in Unsupervised Anomaly Detection and Localization [[IJCV 2022]](https://link.springer.com/content/pdf/10.1007/s11263-022-01578-9.pdf)
 + (MPDD)Deep learning-based defect detection of metal parts: evaluating current methods in complex conditions [[2021]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9631567)
 + (BTAD)VT-ADL: A vision transformer network for image anomaly detection and localization [[2021]](http://arxiv.org/pdf/2104.10036)
 + (VisA)SPot-the-Difference Self-supervised Pre-training for Anomaly Detection and Segmentation [[ECCV 2022]](https://arxiv.org/pdf/2207.14315.pdf)
 + (MTD)Surface defect saliency of magnetic tile [[2020]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8560423)
 + (DAGM)DAGM dataset [[2007]](https://www.kaggle.com/datasets/mhskjelvareid/dagm-2007-competition-dataset-optical-inspection)
 + CVPR 1st workshop on Vision-based InduStrial InspectiON[[homepage]](https://vision-based-industrial-inspection.github.io/cvpr-2023/)[[data link]](https://drive.google.com/drive/folders/1TVp_UXJuXudqhC2L3ZKyIDcmQ_2O3JVi)
 + SSGD: A smartphone screen glass dataset for defect detection [[2023]](https://arxiv.org/abs/2303.06673)[[dataset is coming soon]](https://github.com/Yangr116/SSGDataset)

## BibTex Citation

If you find this paper and repository useful, please cite our paper.

```
@article{liu2023deep,
  title={Deep Industrial Image Anomaly Detection: A Survey},
  author={Liu, Jiaqi and Xie, Guoyang and Wang, Jingbao and Li, Shangnian and Wang, Chengjie and Zheng, Feng and Jin, Yaochu},
  journal={arXiv e-prints},
  pages={arXiv--2301},
  year={2023}
}
```
