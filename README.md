# Learning-with-Noisy-Labels

    A curated list of most recent papers & codes in Learning with Noisy Labels
    
    Some recent works about group-distributional robustness, label distribution shifts, are also included.

---

## Tag Legend

### Main Technique
![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
![Theory](https://img.shields.io/badge/Theory-6B7280)

### Task Type
![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)

## 🧰 Public Software
**Docta-AI:** 
An advanced data-centric AI platform that detects and rectifies issues in any data format (i.e., label error detection). [[Website]](https://github.com/Docta-ai/docta)

## 🎓 Tutorial

**1st Learning and Mining with Noisy Labels Challenge** (IJCAI 2023)[[Website]](https://sites.google.com/ucsc.edu/tutorial-noisylabels/home)[[GitHub]](https://github.com/Docta-ai/IJCAI-tutorial)

## 📦 Content
  - [Benchmarks](#benchmarks)
  - [Papers & Code in 2024](#papers--code-in-2024)
    - [NeurIPS 2024](#NeurIPS-2024)
    - [ICML 2024](#ICML-2024)
    - [ICLR 2024](#ICLR-2024)
  - [Papers & Code in 2023](#papers--code-in-2023)
    - [ICCV 2023](#ICCV-2023)
    - [KDD 2023](#KDD-2023)
    - [NeurIPS 2023](#NeurIPS-2023)
    - [ICML 2023](#ICML-2023)
    - [CVPR 2023](#CVPR-2023)
    - [ICLR 2023](#ICLR-2023)
  - [Papers & Code in 2022](#papers--code-in-2022)
    - [NeurIPS 2022](#NeurIPS-2022)
    - [ECCV 2022](#ECCV-2022)
    - [ICML 2022](#ICML-2022)
    - [CVPR 2022](#CVPR-2022)
    - [ICLR 2022](#ICLR-2022)
    - [AISTATS 2022](#AISTATS-2022)
    - [Other Conferences 2022](#Other-Conferences-2022)
    - [ArXiv 2022](#ArXiv-2022)
  - [Papers & Code in 2021](#papers--code-in-2021)
    - [NeurIPS 2021](#NeurIPS-2021)
    - [IJCAI 2021](#IJCAI-2021)
    - [ICML 2021](#ICML-2021)
    - [ICLR 2021](#ICLR-2021)
    - [CVPR 2021](#CVPR-2021)
    - [AISTATS 2021](#AISTATS-2021)
    - [AAAI 2021](#AAAI-2021)
    - [Other Conferences 2021](#Other-Conferences-2021)
    - [ArXiv 2021](#ArXiv-2021)
  - [Papers & Code in 2020](#papers--code-in-2020)
    - [ICML 2020](#ICML-2020)
    - [ICLR 2020](#ICLR-2020)
    - [Nips 2020](#Nips-2020)
    - [AAAI 2020](#AAAI-2020)
    - [CVPR 2020](#CVPR-2020)
    - [ECCV 2020](#ECCV-2020)
    - [ArXiv 2020](#ArXiv-2020)
---

## 📊 Benchmarks
Real-world noisy-label bechmarks:

Dataset | Noise Rate | Website | Paper
--- | --- | --- | ---
CIFAR-10N | ~8%/~20%/~40% (human label noise) | [[Website]](http://noisylabels.com/) | [[Paper]](https://arxiv.org/abs/2110.12088) 
CIFAR-100N | ~40% (human label noise) | [[Website]](http://noisylabels.com/)  | [[Paper]](https://arxiv.org/abs/2110.12088)
Red Stanford Cars | ~40% (synthetic noise) | [[Website]](https://ai.googleblog.com/2020/08/understanding-deep-learning-on.html)  | [[Paper]](http://proceedings.mlr.press/v119/jiang20c/jiang20c.pdf)
Red Mini-ImageNet | ~40% (synthetic noise) | [[Website]](https://ai.googleblog.com/2020/08/understanding-deep-learning-on.html)  | [[Paper]](http://proceedings.mlr.press/v119/jiang20c/jiang20c.pdf)
Animal-10N | ~8% (real-world noise) | [[Website]](https://dm.kaist.ac.kr/datasets/animal-10n/)  | [[Paper]](http://proceedings.mlr.press/v97/song19b.html)
Food-101N | ~20% (human label noise) | [[Website]](https://github.com/kuanghuei/clean-net)  | [[Paper]](https://arxiv.org/pdf/1711.07131.pdf)
Clothing1M  | ~38% (real-world noise) | [[Website]](https://github.com/Cysu/noisy_label)  | [[Paper]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Xiao_Learning_From_Massive_2015_CVPR_paper.pdf)
 
## 🔧 Simulation of Label Noise

### 🧩 Instance-Dependent Noise (IDN)

- **Part-dependent Label Noise: Towards Instance-dependent Label Noise**  
  [[Paper]](https://arxiv.org/abs/2006.07836) [[Code]](https://github.com/xiaoboxia/Part-dependent-label-noise)

- **Beyond Class-Conditional Assumption: A Primary Attempt to Combat Instance-Dependent Label Noise**  
  [[Paper]](https://arxiv.org/abs/2012.05458) [[Code]](https://github.com/chenpf1025/IDN)

- **An Instance-Dependent Simulation Framework for Learning with Label Noise**  
  [[Paper]](https://arxiv.org/abs/2107.11413)


---

### 🔀 Polynomial Margin Diminishing Noise (PMD)

- **Learning with Feature-Dependent Label Noise: A Progressive Approach**  
  [[Paper]](https://openreview.net/pdf?id=ZPa2SyGcbwh) [[Code]](https://github.com/pxiangwu/PLC)


---

> <span style="color:#EF4444"><strong>Note:</strong> This repository mainly focuses on papers published after 2019. For earlier works, please refer to [[this curated list]](https://github.com/subeeshvasu/Awesome-Learning-with-Label-Noise).</span>

## Papers & Code in 2024

-----
### Neurips 2024 
* Learning the Latent Causal Structure for Modeling Label Noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://nips.cc/virtual/2024/poster/93700)

* Entity Alignment with Noisy Annotations from Large Language Models. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://nips.cc/virtual/2024/poster/93478)

* Noisy Label Learning with Instance-Dependent Outliers: Identifiability via Crowd Wisdom. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://nips.cc/virtual/2024/poster/95831)

* Vision-Language Models are Strong Noisy Label Detectors. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://nips.cc/virtual/2024/poster/94056)

* Benchmarking the Reasoning Robustness against Noisy Rationales in Chain-of-thought Prompting. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://nips.cc/virtual/2024/poster/95956)

* Learning from Noisy Labels via Conditional Distributionally Robust Optimization. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://nips.cc/virtual/2024/poster/96820)

* Sample Selection via Contrastive Fragmentation for Noisy Label Regression. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://nips.cc/virtual/2024/poster/95898)

* Label Noise: Ignorance Is Bliss. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://nips.cc/virtual/2024/poster/94205)

* CoSW: Conditional Sample Weighting for Smoke Segmentation with Label Noise. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://nips.cc/virtual/2024/poster/95170)

* Immiscible Diffusion: Accelerating Diffusion Training with Noise Assignment. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://nips.cc/virtual/2024/poster/93906)

* Curriculum Fine-tuning of Vision Foundation Model for Medical Image Classification Under Label Noise. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://nips.cc/virtual/2024/poster/93198)[[Code]](https://github.com/gist-ailab/CUFIT)

* NoisyGL: A Comprehensive Benchmark for Graph Neural Networks under Label Noise. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://nips.cc/virtual/2024/poster/97611)

* Noisy Ostracods: A Fine-Grained, Imbalanced Real-World Dataset for Benchmarking Robust Machine Learning and Label Correction Methods. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://nips.cc/virtual/2024/poster/97733)

* Robust Contrastive Multi-view Clustering against Dual Noisy Correspondence. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://nips.cc/virtual/2024/poster/96528)

* Perplexity-aware Correction for Robust Alignment with Noisy Preferences. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://nips.cc/virtual/2024/poster/95367)

* Information-theoretic Limits of Online Classification with Noisy Labels. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://nips.cc/virtual/2024/poster/95650)

-----
### ICML 2024 
* Pi-DUAL: Using privileged information to distinguish clean from noisy labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://proceedings.mlr.press/v235/wang24bb.html)

* Mitigating Label Noise on Graphs via Topological Sample Selection. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://proceedings.mlr.press/v235/wu24ae.html)

* Self-cognitive Denoising in the Presence of Multiple Noisy Label Sources. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://proceedings.mlr.press/v235/sun24o.html)

* Provably Robust DPO: Aligning Language Models with Noisy Feedback. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://proceedings.mlr.press/v235/ray-chowdhury24a.html)

* Consistent Diffusion Meets Tweedie: Training Exact Ambient Diffusion Models with Noisy Data. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://proceedings.mlr.press/v235/daras24a.html)

* RIME: Robust Preference-based Reinforcement Learning with Noisy Preferences. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://proceedings.mlr.press/v235/cheng24k.html)

* FAFE: Immune Complex Modeling with Geodesic Distance Loss on Noisy Group Frames. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://proceedings.mlr.press/v235/wu24g.html)

-----
### ICLR 2024 
* Understanding and Mitigating the Label Noise in Pre-training on Downstream Tasks. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=TjhUtloBZU)

* Early Stopping Against Label Noise Without Validation Data. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=CMzF2aOfqp)

* Label-Noise Robust Diffusion Models. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=HXWTXXtHNl)

* Why is SAM Robust to Label Noise? 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=3aZCPl3ZvR)

* Local Graph Clustering with Noisy Labels. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=89A5c6enfc)

* Dirichlet-based Per-Sample Weighting by Transition Matrix for Noisy Label Learning. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=A4mJuFRMN8)

* MOFI: Learning Image Representations from Noisy Entity Annotated Images. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=QQYpgReSRk)

* Robust Classification via Regression for Learning with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=wfgZc3IMqo)

* TextField3D: Towards Enhancing Open-Vocabulary 3D Generation with Noisy Text Fields. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=WOiOzHG2zD)

## Papers & Code in 2023

-----
### ICCV 2023 
* PADDLES: Phase-Amplitude Spectrum Disentangled Early Stopping for Learning with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Huang_PADDLES_Phase-Amplitude_Spectrum_Disentangled_Early_Stopping_for_Learning_with_Noisy_ICCV_2023_paper.pdf)[[Code]](https://github.com/CoderHHX/PADDLES)

* Sample-wise Label Confidence Incorporation for Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ahn_Sample-wise_Label_Confidence_Incorporation_for_Learning_with_Noisy_Labels_ICCV_2023_paper.pdf)

* SILT: Shadow-Aware Iterative Label Tuning for Learning to Detect Shadows from Noisy Labels. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_SILT_Shadow-Aware_Iterative_Label_Tuning_for_Learning_to_Detect_Shadows_ICCV_2023_paper.pdf)[[Code]](https://github.com/hanyangclarence/SILT)

* Graph Matching with Bi-level Noisy Correspondence. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Lin_Graph_Matching_with_Bi-level_Noisy_Correspondence_ICCV_2023_paper.pdf)[[Code]](https://github.com/XLearning-SCU/2023-ICCV-COMMON)

* Learning from Noisy Pseudo Labels for Semi-Supervised Temporal Action Localization. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Learning_from_Noisy_Pseudo_Labels_for_Semi-Supervised_Temporal_Action_Localization_ICCV_2023_paper.pdf)[[Code]](https://github.com/kunnxia/NPL)

* Label-Noise Learning with Intrinsically Long-Tailed Data. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Lu_Label-Noise_Learning_with_Intrinsically_Long-Tailed_Data_ICCV_2023_paper.pdf)

* Semi-Supervised Semantic Segmentation under Label Noise via Diverse Learning Groups. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Semi-Supervised_Semantic_Segmentation_under_Label_Noise_via_Diverse_Learning_Groups_ICCV_2023_paper.pdf)

* LA-Net: Landmark-Aware Learning for Reliable Facial Expression Recognition under Label Noise. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_LA-Net_Landmark-Aware_Learning_for_Reliable_Facial_Expression_Recognition_under_Label_ICCV_2023_paper.pdf)

* Holistic Label Correction for Noisy Multi-Label Classification. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Holistic_Label_Correction_for_Noisy_Multi-Label_Classification_ICCV_2023_paper.pdf)[[Code]](https://github.com/xiaoboxia/HLC)

* When Noisy Labels Meet Long Tail Dilemmas: A Representation Calibration Method. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_When_Noisy_Labels_Meet_Long_Tail_Dilemmas_A_Representation_Calibration_ICCV_2023_paper.pdf)

* Combating Noisy Labels with Sample Selection by Mining High-Discrepancy Examples. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Combating_Noisy_Labels_with_Sample_Selection_by_Mining_High-Discrepancy_Examples_ICCV_2023_paper.pdf)[[Code]](https://github.com/xiaoboxia/CoDis)

* Why Is Prompt Tuning for Vision-Language Models Robust to Noisy Labels? 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_Why_Is_Prompt_Tuning_for_Vision-Language_Models_Robust_to_Noisy_ICCV_2023_paper.pdf)[[Code]](https://github.com/CEWu/PTNL)

* RankMatch: Fostering Confidence and Consistency in Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_RankMatch_Fostering_Confidence_and_Consistency_in_Learning_with_Noisy_Labels_ICCV_2023_paper.pdf)

* Learning from Noisy Data for Semi-Supervised 3D Object Detection. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_Learning_from_Noisy_Data_for_Semi-Supervised_3D_Object_Detection_ICCV_2023_paper.pdf)[[Code]](https://github.com/zehuichen123/NoiseDet)

* LNPL-MIL: Learning from Noisy Pseudo Labels for Promoting Multiple Instance Learning in Whole Slide Image. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Shao_LNPL-MIL_Learning_from_Noisy_Pseudo_Labels_for_Promoting_Multiple_Instance_ICCV_2023_paper.pdf)[[Code]](https://github.com/szc19990412/LNPL-MIL)

* BoMD: Bag of Multi-label Descriptors for Noisy Chest X-ray Classification. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_BoMD_Bag_of_Multi-label_Descriptors_for_Noisy_Chest_X-ray_Classification_ICCV_2023_paper.pdf)[[Code]](https://github.com/cyh-0/BoMD)
  
-----
### KDD 2023 
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL)  To Aggregate or Not? Learning with Separate Noisy Labels. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2206.07181)

* DyGen: Learning from Noisy Labels via Dynamics-Enhanced Generative Modeling. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://dl.acm.org/doi/10.1145/3580305.3599318)[[Code]](https://github.com/night-chen/DyGen)

* Robust Positive-Unlabeled Learning via Noise Negative Sample Self-correction. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://dl.acm.org/doi/10.1145/3580305.3599491)

* Neural-Hidden-CRF: A Robust Weakly-Supervised Sequence Labeler. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://browse.arxiv.org/pdf/2309.05086.pdf)[[Code]](https://github.com/junchenzhi/Neural-Hidden-CRF)

* Complementary Classifier Induced Partial Label Learning. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2305.09897)[[Code]](https://github.com/Chongjie-Si/PL-CL)

* Partial-label Learning with Mixed Closed-Set and Open-Set Out-of-Candidate Examples. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2307.00553)

* Weakly Supervised Multi-Label Classification of Full-Text Scientific Papers. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2306.14003)[[Code]](https://github.com/yuzhimanhua/FUTEX)

-----
### NeurIPS 2023 
* The Pursuit of Human Labeling: A New Perspective on Unsupervised Learning. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=3GpIeVYw8X)[[Code]](https://brbiclab.epfl.ch/projects/hume/)

* AQuA: A Benchmarking Tool for Label Quality Assessment. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=dhJ8VbcEtX)

* Efficient Testable Learning of Halfspaces with Adversarial Label Noise. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=mIm0hsUUt1)

* Neural Relation Graph: A Unified Framework for Identifying Label Noise and Outlier Data. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2301.12321)[[Code]](https://github.com/snu-mllab/Neural-Relation-Graph)

* Robust Data Pruning under Label Noise via Maximizing Re-labeling Accuracy. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=xWCp0uLcpG)

* Subclass-Dominant Label Noise: A Counterexample for the Success of Early Stopping. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=kR21XsZeAr)[[Code]](https://github.com/tmllab/2023_NeurIPS_SDN)

* Label Correction of Crowdsourced Noisy Annotations with an Instance-Dependent Noise Transition Model. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=nFEQNYsjQO)

* Scale-teaching: Robust Multi-scale Training for Time Series Classification with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=9D0fELXbrg)[[Code]](https://github.com/qianlima-lab/Scale-teaching)

* SoTTA: Robust Test-Time Adaptation on Noisy Data Streams. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2310.10074)[[Code]](https://github.com/taeckyung/SoTTA)

* Active Negative Loss Functions for Learning with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://neurips.cc/virtual/2023/poster/71501)[[Code]](https://github.com/Virusdoll/Active-Negative-Loss)

* Label-Retrieval-Augmented Diffusion Models for Learning from Noisy Labels. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2305.19518)[[Code]](https://github.com/puar-playground/LRA-diffusion)

* Training shallow ReLU networks on noisy data using hinge loss: when do we overfit and is it benign? 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2306.09955)

* CSOT: Curriculum and Structure-Aware Optimal Transport for Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=y50AnAbKp1)[[Code]](https://github.com/changwxx/CSOT-for-LNL)

* Deep Insights into Noisy Pseudo Labeling on Graph Data. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=XhNlBvb4XV)

* ARTIC3D: Learning Robust Articulated 3D Shapes from Noisy Web Image Collections. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=rJc5Lsn5QU)[[Code]](https://chhankyao.github.io/artic3d/)

* ALIM: Adjusting Label Importance Mechanism for Noisy Partial Label Learning. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=PYSfn5xXEe)[[Code]](https://github.com/zeroQiaoba/ALIM)

* Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2305.11003)[[Code]](https://github.com/ChunmingHe/WS-SAM)

* Label Poisoning is All You Need. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2310.18933)[[Code]](https://github.com/SewoongLab/FLIP)

* SLaM: Student-Label Mixing for Distillation with Unlabeled Examples. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=N7tw0QXx3z)

* IPMix: Label-Preserving Data Augmentation Method for Training Robust Classifiers. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=No52399wXA)

* HQA-Attack: Toward High Quality Black-Box Hard-Label Adversarial Attack on Text. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=IOuuLBrGJR)[[Code]](https://github.com/HQA-Attack/HQAAttack-demo)

-----
### ICML 2023 
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL)  Identifiability of Label Noise Transition Matrix. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://proceedings.mlr.press/v202/liu23g)

* Which is Better for Learning with Noisy Labels: The Semi-supervised Method or Modeling Label Noise? 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://proceedings.mlr.press/v202/yao23a)

* Mitigating Memorization of Noisy Labels by Clipping the Model Prediction. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2212.04055)[[Code]](https://github.com/hongxin001/LogitClip)

* CrossSplit: Mitigating Label Noise Memorization through Data Splitting. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v202/kim23a/kim23a.pdf)[[Code]](https://github.com/SAITPublic/CrossSplit)

* Understanding Self-Distillation in the Presence of Label Noise. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v202/das23d/das23d.pdf)

* RandomClassificationNoisedoesnotdefeatAllConvexPotentialBoosters IrrespectiveofModelChoice. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://proceedings.mlr.press/v202/mansour23a.html)

* Deep Clustering with Incomplete Noisy Pairwise Annotations: A Geometric Regularization Approach. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://proceedings.mlr.press/v202/nguyen23d)

* Delving into Noisy Label Detection with Clean Data. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://proceedings.mlr.press/v202/yu23b.html)

* When does Privileged information Explain Away Label Noise? 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://proceedings.mlr.press/v202/ortiz-jimenez23a)

* Squeeze, Recover and Relabel: Dataset Condensation at ImageNet Scale From A New Perspective. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2306.13092)[[Code]](https://github.com/VILA-Lab/SRe2L)

* Promises and Pitfalls of Threshold-based Auto-labeling. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=RUCFAKNDb2)

* Accelerating Exploration with Unlabeled Prior Data. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=Itorzn4Kwf)
  
-----
### CVPR 2023 
*  Twin Contrastive Learning with Noisy Labels. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2303.06930)[[Code]](https://github.com/Hzzone/TCL)

*  Exploring High-Quality Pseudo Masks for Weakly Supervised Instance Segmentation. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2210.05174)[[Code]](https://github.com/hustvl/BoxTeacher)

*  HandsOff: Labeled Dataset Generation with No Additional Human Annotations. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2212.12645.pdf)[[Code]](https://github.com/austinxu87/handsoff/)

*  Learning from Noisy Labels with Decoupled Meta Label Purifier. 
  ![Meta Learning](https://img.shields.io/badge/Meta%20Learning-EC4899)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2302.06810)[[Code]](https://github.com/yuanpengtu/DMLP)

*  DISC: Learning from Noisy Labels via Dynamic Instance-Specific Selection and Correction. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_DISC_Learning_From_Noisy_Labels_via_Dynamic_Instance-Specific_Selection_and_CVPR_2023_paper.pdf)[[Code]](https://github.com/jackyfl/disc)

*  Leveraging Inter-Rater Agreement for Classification in the Presence of Noisy Labels. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Bucarelli_Leveraging_Inter-Rater_Agreement_for_Classification_in_the_Presence_of_Noisy_CVPR_2023_paper.pdf)

*  Fine-Grained Classification with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wei_Fine-Grained_Classification_With_Noisy_Labels_CVPR_2023_paper.pdf)

*  Collaborative Noisy Label Cleaner: Learning Scene-aware Trailers for Multi-modal Highlight Detection in Movies. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2303.14768)[[Code]](https://github.com/TencentYoutuResearch/HighlightDetection-CLC)

*  MixTeacher: Mining Promising Labels with Mixed Scale Teacher for Semi-supervised Object Detection. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2303.09061)[[Code]](https://github.com/lliuz/MixTeacher)

*  OT-Filter: An Optimal Transport Filter for Learning With Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Feng_OT-Filter_An_Optimal_Transport_Filter_for_Learning_With_Noisy_Labels_CVPR_2023_paper.pdf)

*  Exploiting Completeness and Uncertainty of Pseudo Labels for Weakly Supervised Video Anomaly Detection. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Exploiting_Completeness_and_Uncertainty_of_Pseudo_Labels_for_Weakly_Supervised_CVPR_2023_paper.pdf)[[Code]](https://github.com/ArielZc/CU-Net)

*  Semi-Supervised 2D Human Pose Estimation Driven by Position Inconsistency Pseudo Label Correction Module. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Semi-Supervised_2D_Human_Pose_Estimation_Driven_by_Position_Inconsistency_Pseudo_CVPR_2023_paper.pdf)[[Code]](https://github.com/hlz0606/SSPCM)

*  Learning with Noisy labels via Self-supervised Adversarial Noisy Masking. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Tu_Learning_With_Noisy_Labels_via_Self-Supervised_Adversarial_Noisy_Masking_CVPR_2023_paper.pdf)[[Code]](https://github.com/yuanpengtu/SANM)

*  RONO: Robust Discriminative Learning with Noisy Labels for 2D-3D Cross-Modal Retrieval. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Feng_RONO_Robust_Discriminative_Learning_With_Noisy_Labels_for_2D-3D_Cross-Modal_CVPR_2023_paper.pdf)[[Code]](https://github.com/penghu-cs/RONO)

-----
### ICLR 2023 
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL)  Distributionally Robust Post-hoc Classifiers under Prior Shifts. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=3KUfbI9_DQE)[[Code]](https://github.com/weijiaheng/Drops)

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL)  Mitigating Memorization of Noisy Labels via Regularization between Representations. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=6qcYDVlVLnK)

*  On the Edge of Benign Overfitting: Label Noise and Overparameterization Level. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=UrEwJebCxk)

*  Deep Learning From Crowdsourced Labels: Coupled Cross-Entropy Minimization, Identifiability, and Regularization. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=_qVhsWyWB9)

*  CLIPSep: Learning Text-queried Sound Separation with Noisy Unlabeled Videos. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=H-T3F0dMbyj)

*  Learning to Segment from Noisy Annotations: A Spatial Correction Approach. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=Qc_OopMEBnC)

*  Mutual Partial Label Learning with Competitive Label Noise. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=EUrxG8IBCrC)

*  Memorization-Dilation: Modeling Neural Collapse Under Noise. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=cJWxqmmDL2b)

*  Leveraging Unlabeled Data to Track Memorization . 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=ORp91sAbzI)

*  Quantifying and Mitigating the Impact of Label Errors on Model Disparity Metrics. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=RUzSobdYy0V)

*  When Source-Free Domain Adaptation Meets Learning with Noisy Labels. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=u2Pd6x794I)

*  A law of adversarial risk, interpolation, and label noise. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=0_TxFpAsEI)

*  SoftMatch: Addressing the Quantity-Quality Tradeoff in Semi-supervised Learning. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=ymt1zQXBDiF)

*  CLIPSep: Learning Text-queried Sound Separation with Noisy Unlabeled Videos. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=H-T3F0dMbyj)

*  Does Decentralized Learning with Non-IID Unlabeled Data Benefit from Self Supervision?. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=2L9gzS80tA4)

*  Label Propagation with Weak Supervision . 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=aCuFa-RRqtI)

*  Mitigating Dataset Bias by Using Per-Sample Gradient. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=7mgUec-7GMv)

*  MCAL: Minimum Cost Human-Machine Active Labeling. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=1FxRPKrH8bw)

*  Avoiding spurious correlations via logit correction. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=5BaqCFVh5qL)

*  Bitrate-Constrained DRO: Beyond Worst Case Robustness To Unknown Group Shifts . 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=2QzNuaRHn4Z)

*  Pushing the Accuracy-Group Robustness Frontier with Introspective Self-play. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper \& Code]](https://openreview.net/forum?id=MofT9KEF0kw)

*  Towards Lightweight, Model-Agnostic and Diversity-Aware Active Anomaly Detection. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=-vKlt84fHs)

*  Weakly Supervised Explainable Phrasal Reasoning with Neural Fuzzy Logic. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=Hu4r-dedqR0)

*  Towards Addressing Label Skews in One-Shot Federated Learning. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=rzrqh85f4Sc)

*  Instance-wise Batch Label Restoration via Gradients in Federated Learning. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=FIrQfNSOoTr)

*  That Label's got Style: Handling Label Style Bias for Uncertain Image Segmentation. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=wZ2SVhOTzBX)

*  Learning Hyper Label Model for Programmatic Weak Supervision. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=aCQt_BrkSjC)

*  Rhino: Deep Causal Temporal Relationship Learning with History-dependent Noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper \& Code]](https://openreview.net/forum?id=i_1rbq8yFWC)


## Papers & Code in 2022

-----
### NeurIPS 2022 
* Estimating Noise Transition Matrix with Label Correlations for Noisy Multi-Label Learning . 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=GwXrGy_vc8m)[[Code]](https://github.com/ShikunLi/Estimating_T_For_Noisy_Mutli-Labels)

* Learning from Label Proportions by Learning with Label Noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper & Code]](https://openreview.net/forum?id=cqyBfRwOTm1)

* Class-Dependent Label-Noise Learning with Cycle-Consistency Regularization. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper & Code]](https://openreview.net/forum?id=IvnoGKQuXi)

* On Image Segmentation With Noisy Labels: Characterization and Volume Properties of the Optimal Solutions to Accuracy and Dice. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper & Code]](https://openreview.net/forum?id=WDS1M0gsfXk)

* Robustness to Label Noise Depends on the Shape of the Noise Distribution. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper & Code]](https://openreview.net/forum?id=AlpR6dzKjfy)

* Label Noise in Adversarial Training: A Novel Perspective to Study Robust Overfitting. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper & Code]](https://openreview.net/forum?id=9_O9mTLYJQp)

* SoftPatch: Unsupervised Anomaly Detection with Noisy Data. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper & Code]](https://openreview.net/forum?id=pIYYJflkhZ)

-----
### ECCV 2022 
* Neighborhood Collective Estimation for Noisy Label Identification and Correction. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2208.03207)[[Code]](https://github.com/lijichang/LNL-NCE)

* Teaching with Soft Label Smoothing for Mitigating Noisy Labels in Facial Expressions. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720639.pdf)[[Code]](https://github.com/toharl/soft)

* Learning from Multiple Annotator Noisy Labels via Sample-wise Label Fusion. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136840402.pdf)[[Code]](https://github.com/zhengqigao/Learning-from-Multiple-Annotator-Noisy-Labels)

* Learn From All: Erasing Attention Consistency for Noisy Label Facial Expression Recognition. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2207.10299)[[Code]](https://github.com/zyh-uaiaaaa/Erasing-Attention-Consistency)

* Centrality and Consistency: Two-Stage Clean Samples Identification for Learning with Instance-Dependent Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2207.14476)[[Code]](https://github.com/uitrbn/TSCSI_IDN)

* Learning with Noisy Labels by Efficient Transition Matrix Estimation to Combat Label Miscorrection. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2111.14932)[[Code]](https://github.com/hyperconnect/FasTEN)

* Identifying Hard Noise in Long-Tailed Sample Distribution. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2207.13378)[[Code]](https://github.com/yxymessi/H2E-Framework)

* Self-Filtering: A Noise-Aware Sample Selection for Label Noise with Confidence Penalization. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2208.11351)

* BoundaryFace: A mining framework with noise label self-correction for Face Recognition. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730092.pdf)[[Code]](https://gitee.com/swjtugx/classmate/tree/master/OurGroup/BoundaryFace)

* Embedding contrastive unsupervised features to cluster in- and out-of-distribution noise in corrupted image datasets. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2207.01573)[[Code]](https://github.com/PaulAlbert31/SNCF)

* WeLSA: Learning To Predict 6D Pose From Weakly Labeled Data Using Shape Alignment. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680633.pdf)

* Joint-Modal Label Denoising for Weakly-Supervised Audio-Visual Video Parsing. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2204.11573)[[Code]](https://github.com/MCG-NJU/JoMoLD)

* PseCo: Pseudo Labeling and Consistency Training for Semi-Supervised Object Detection. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2203.16317)[[Code]](https://github.com/ligang-cs/PseCo)

* Active label correction using robust parameter update and entropy propagation. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136810001.pdf)

* A data-centric approach for improving ambiguous labels with combined semi-supervised classification and clustering. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2106.16209)[[Code]](https://github.com/Emprime/dc3)

-----
### ICML 2022 
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) To Smooth or Not? When Label Smoothing Meets Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2106.04149)[[Code]](https://github.com/UCSC-REAL/negative-label-smoothing)

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Detecting Corrupted Labels Without Training a Model to Predict. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2110.06283)[[Code]](https://github.com/UCSC-REAL/SimiFeat)

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Beyond Images: Label Noise Transition Matrix Estimation for Tasks with Lower-Quality Features. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2202.01273)

* From Noisy Prediction to True Label: Noisy Prediction Calibration via Generative Model 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2205.00690)[[Code]](https://github.com/BaeHeeSun/NPC)

* Robust Training under Label Noise by Over-parameterization. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2202.14026)[[Code]](https://github.com/shengliu66/SOP)

* Estimating Instance-dependent Label-noise Transition Matrix using DNNs. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2105.13001)

* Transfer and Marginalize: Explaining Away Label Noise with Privileged Information. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2202.09244)

* Guaranteed Robust Deep Learning against Extreme Label Noise using Self-supervised Learning.  
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)

* Robust Meta-learning with Sampling Noise and Label Noise via Eigen-Reptile. 
  ![Meta Learning](https://img.shields.io/badge/Meta%20Learning-EC4899)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2206.01944v1.pdf)[[Code]](https://github.com/anfeather/eigen-reptile)

* Learning General Halfspaces with Adversarial Label Noise via Online Gradient Descent. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://proceedings.mlr.press/v162/diakonikolas22b.html)

* Guaranteed Robust Deep Learning against Extreme Label Noise using Self-supervised Learning.  
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)

-----
### CVPR 2022
* Selective-Supervised Contrastive Learning with Noisy Labels. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2203.04181)[[Code]](https://github.com/ShikunLi/Sel-CL)

* Scalable Penalized Regression for Noise Detection in Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2203.07788)[[Code]](https://github.com/Yikai-Wang/SPR-LNL)

* Large-Scale Pre-training for Person Re-identification with Noisy Labels. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](http://arxiv.org/pdf/2203.16533)[[Code]](https://github.com/dengpanfu/luperson-nl)

* Adaptive Early-Learning Correction for Segmentation from Noisy Annotations. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2110.03740)[[Code]](https://github.com/Kangningthu/ADELE)

-----
### ICLR 2022
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Learning with Noisy Labels Revisited: A Study Using Real-World Human Annotations. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=TBWA6PLJZQm&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICLR.cc%2F2022%2FConference%2FAuthors%23your-submissions))[[Code]](https://github.com/zwzhu-d/cifar-10-100n)

* Resolving Training Biases via Influence-based Data Relabeling. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper and Code]](https://openreview.net/forum?id=EskfH0bwNVn)

* Contrastive Label Disambiguation for Partial Label Learning. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper and Code]](https://openreview.net/forum?id=EhYjZy6e1gJ)

* Sample Selection with Uncertainty of Losses for Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper and Code]](https://openreview.net/forum?id=xENf4QUL4LW)

* An Information Fusion Approach to Learning with Instance-Dependent Label Noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper and Code]](https://openreview.net/forum?id=ecH2FKaARUp)

* Meta Discovery: Learning to Discover Novel Classes given Very Limited Data. 
  ![Meta Learning](https://img.shields.io/badge/Meta%20Learning-EC4899)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper and Code]](https://openreview.net/forum?id=MEpKGLsY8f)


-----
### ArXiv 2022
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) To Aggregate or Not? Learning with Separate Noisy Labels. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2206.07181)

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Identifiability of Label Noise Transition Matrix. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2202.02016)

* Constrained Instance and Class Reweighting for Robust Learning under Label Noise. 
  ![Reweighting](https://img.shields.io/badge/Reweighting-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2111.05428)

* AUGLOSS: A Learning Methodology for Real-World Dataset Corruption. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2206.02286.pdf)

* Do We Need to Penalize Variance of Losses for Learning with Label Noise?. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2201.12739)

* Robust Training under Label Noise by Over-parameterization. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2202.14026)[[Code]](https://github.com/shengliu66/SOP)

* On Learning Contrastive Representations for Learning with Noisy Labels. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2203.01785)

* Learning from Label Proportions by Learning with Label Noise. 
  ![Weak Supervision](https://img.shields.io/badge/Weak%20Supervision-0EA5E9)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2203.02496)

* Benign Overfitting without Linearity: Neural Network Classifiers Trained by Gradient Descent for Noisy Linear Data. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2202.05928#:~:text=11%20Feb%202022%5D-,Benign%20Overfitting%20without%20Linearity%3A%20Neural%20Network%20Classifiers%20Trained%20by,Descent%20for%20Noisy%20Linear%20Data&text=Abstract%3A%20Benign%20overfitting%2C%20the%20phenomenon,models%20trained%20with%20gradient%20descent.)

* Synergistic Network Learning and Label Correction for Noise-robust Image Classification. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2202.13472)

* Transfer and Marginalize: Explaining Away Label Noise with Privileged Information. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2202.09244)

* Convolutional Network Fabric Pruning With Label Noise. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2202.07268)

* Learning to Bootstrap for Combating Label Noise. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2202.04291)

* Learning with Neighbor Consistency for Noisy Labels. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2202.02200)

* Investigating Why Contrastive Learning Benefits Robustness Against Label Noise. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2201.12498)

* PARS: Pseudo-Label Aware Robust Sample Selection for Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2201.10836)

* GMM Discriminant Analysis with Noisy Label for Each Class. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2201.10242)

* Learning with Label Noise for Image Retrieval by Selecting Interactions. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2112.10453)

* Two Wrongs Don't Make a Right: Combating Confirmation Bias in Learning with Label Noise. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2112.02960)

-----

## Papers & Code in 2021

### NeurIPS 2021 
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Can Less be More? When Increasing-to-Balancing Label Noise Rates Considered Beneficial. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2107.05913#:~:text=We%20are%20primarily%20inspired%20by,fairness%20guarantees%20against%20label%20bias.)[[Code]](https://github.com/UCSC-REAL/CanLessBeMore)

* Open-set Label Noise Can Improve Robustness Against Inherent Label Noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2106.10891)[[Code]](https://github.com/hongxin001/ODNL)

* Generalized Jensen-Shannon Divergence Loss for Learning with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2105.04522)[[Code]](https://github.com/ErikEnglesson/GJS)

* Understanding and Improving Early Stopping for Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2106.15853)[[Code]](https://github.com/tmllab/PES)

* How does a Neural Network's Architecture Impact its Robustness to Noisy Labels? 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=Ir-WwGboFN-)[[Code]](https://github.com/jinglingli/alignment_noisy_label)

* FINE Samples for Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2102.11628v3.pdf)[[Code]](https://github.com/Kthyeon/FINE_official)

* Label Noise SGD Provably Prefers Flat Global Minimizers. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2106.06530)[[Code]](https://github.com/adamian98/LabelNoiseFlatMinimizers)

* Improved Regularization and Robustness for Fine-tuning in Neural Networks. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=QX32YlxrQJc)[[Code]](https://github.com/NEU-StatsML-Research/Regularized-Self-Labeling)

* Instance-dependent Label-noise Learning under a Structural Causal Model. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2109.02986)

* Combating Noise: Semi-supervised Learning by Region Uncertainty Quantification. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2111.00928)

* DP-SSL: Towards Robust Semi-supervised Learning with A Few Labeled Samples. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2110.13740)

* Corruption Robust Active Learning. 
  ![Active Learning](https://img.shields.io/badge/Active%20Learning-6366F1)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=Ruw3MHL9jAO)

-----

### IJCAI 2021 

* Learning Implicitly with Noisy Data in Linear Arithmetic. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://www.ijcai.org/proceedings/2021/0195.pdf)

* Towards Understanding Deep Learning from Noisy Labels with Small-Loss Criterion. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://www.ijcai.org/proceedings/2021/0340.pdf)

* Modeling Noisy Hierarchical Types in Fine-Grained Entity Typing: A Content-Based Weighting Approach. 
  ![Reweighting](https://img.shields.io/badge/Reweighting-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://www.ijcai.org/proceedings/2019/0731.pdf) 

* Multi-level Generative Models for Partial Label Learning with Non-random Label Noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://www.ijcai.org/proceedings/2021/0449.pdf)
-----

### ICML 2021

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) The importance of understanding instance-level noisy labels. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2102.05336.pdf)

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Clusterability as an Alternative to Anchor Points When Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2102.05291.pdf)[[Code]](https://github.com/zwzhu-d/HOC)

* Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2102.05918v2.pdf)[[Code]](https://github.com/MicPie/clasp)

* Learning Noise Transition Matrix from Only Noisy Labels via Total Variation Regularization. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2102.02414v2.pdf)[[Code]](https://github.com/YivanZhang/lio)

* Class2Simi: A Noise Reduction Perspective on Learning with Noisy Labels. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2006.07831)

* Provably End-to-end Label-noise Learning without Anchor Points. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2102.02400.pdf)

* Asymmetric Loss Functions for Learning with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2106.03110v1.pdf)[[Code]](https://github.com/hitcszx/ALFs)

* Confidence Scores Make Instance-dependent Label-noise Learning Possible. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2001.03772) 

* Provable Generalization of SGD-trained Neural Networks of Any Width in the Presence of Adversarial Label Noise. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2101.01152)

* Wasserstein Distributional Normalization For Robust Distributional Certification of Noisy Labeled Data. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v139/park21a/park21a.pdf)

* Learning from Noisy Labels with No Change to the Training Process. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v139/zhang21k/zhang21k.pdf)
-----
### ICLR 2021

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) When Optimizing f-Divergence is Robust with Label Noise. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/pdf?id=WesiCoRVQ15)[[Code]](https://github.com/weijiaheng/Robust-f-divergence-measures) 

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Learning with Instance-Dependent Label Noise: A Sample Sieve Approach. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/pdf?id=2VXyy9mIyU3)[[Code]](https://github.com/haochenglouis/cores) 

* Noise against noise: stochastic label noise helps combat inherent label noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/pdf?id=80FMcTSZ6J0)[[Code]](https://github.com/chenpf1025/SLN)

* Learning with Feature-Dependent Label Noise: A Progressive Approach. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/pdf?id=ZPa2SyGcbwh)[[Code]](https://github.com/pxiangwu/PLC)

* Robust early-learning: Hindering the memorization of noisy labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/pdf?id=Eql5b1_hTE4)[[Code]](https://github.com/xiaoboxia/CDR)

* MoPro: Webly Supervised Learning with Momentum Prototypes. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=0-EYBhgw80y) [[Code]](https://github.com/salesforce/MoPro) 

* Robust Curriculum Learning: from clean label detection to noisy label self-correction. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/pdf?id=lmTWnm3coJJ)

* How Does Mixup Help With Robustness and Generalization? 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/pdf?id=8yKEo06dKNo)

* Theoretical Analysis of Self-Training with Deep Networks on Unlabeled Data. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/pdf?id=rC8sJ4i6kaH)
-----
### CVPR 2021

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) A Second-Order Approach to Learning with Instance-Dependent Label Noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2012.11854)[[Code]](https://github.com/UCSC-REAL/CAL)

* Improving Unsupervised Image Clustering With Robust Learning. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2012.11150)

* Multi-Objective Interpolation Training for Robustness to Label Noise. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2012.04462)[[Code]](https://git.io/JI40X)

* Noise-resistant Deep Metric Learning with Ranking-based Instance Selection. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2103.16047)[[Code]](https://github.com/alibaba-edu/Ranking-based-Instance-Selection)

* Augmentation Strategies for Learning with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2103.02130)[[Code]](https://github.com/KentoNishi/Augmentation-for-LNL)

* Jo-SRC: A Contrastive Approach for Combating Noisy Labels. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2103.13029.pdf)[[Code]](https://github.com/NUST-Machine-Intelligence-Laboratory/Jo-SRC)

* Multi-Objective Interpolation Training for Robustness to Label Noise. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2012.04462)[[Code]](https://github.com/DiegoOrtego/LabelNoiseMOIT)

* Partially View-aligned Representation Learning with Noise-robust Contrastive Loss. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Partially_View-Aligned_Representation_Learning_With_Noise-Robust_Contrastive_Loss_CVPR_2021_paper.pdf)[[Code]](https://github.com/XLearning-SCU/2021-CVPR-MvCLN)

* Correlated Input-Dependent Label Noise in Large-Scale Image Classification. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2105.10305)

* DAT: Training Deep Networks Robust To Label-Noise by Matching the Feature Distributions. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Qu_DAT_Training_Deep_Networks_Robust_To_Label-Noise_by_Matching_the_CVPR_2021_paper.pdf)

* Faster Meta Update Strategy for Noise-Robust Deep Learning. 
  ![Meta Learning](https://img.shields.io/badge/Meta%20Learning-EC4899)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://github.com/youjiangxu/FaMUS/tree/main/paper)[[Code]](https://github.com/youjiangxu/FaMUS)

* DualGraph: A graph-based method for reasoning about label noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_DualGraph_A_Graph-Based_Method_for_Reasoning_About_Label_Noise_CVPR_2021_paper.pdf)

* Background-Aware Pooling and Noise-Aware Loss for Weakly-Supervised Semantic Segmentation. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2104.00905)

* Joint Negative and Positive Learning for Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2104.06574)

* Faster Meta Update Strategy for Noise-Robust Deep Learning. 
  ![Meta Learning](https://img.shields.io/badge/Meta%20Learning-EC4899)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2104.15092)

* AutoDO: Robust AutoAugment for Biased Data with Label Noise via Scalable Probabilistic Implicit Differentiation. 
  ![Meta Learning](https://img.shields.io/badge/Meta%20Learning-EC4899)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2103.05863)[[Code]](https://github.com/gudovskiy/autodo)

* Meta Pseudo Labels. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2003.10580.pdf)[[Code]](https://github.com/google-research/google-research/tree/master/meta_pseudo_labels)

* All Labels Are Not Created Equal: Enhancing Semi-supervision via Label Grouping and Co-training. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2104.05248)[[Code]](https://github.com/islam-nassar/semco)

* SimPLE: Similar Pseudo Label Exploitation for Semi-Supervised Classification. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2103.16725)[[Code]](https://github.com/zijian-hu/SimPLE)
-----
### AAAI 2021
* Beyond Class-Conditional Assumption: A Primary Attempt to Combat Instance-Dependent Label Noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2012.05458)[[Code]](https://github.com/chenpf1025/IDN)

* Learning to Purify Noisy Labels via Meta Soft Label Corrector. 
  ![Meta Learning](https://img.shields.io/badge/Meta%20Learning-EC4899)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2008.00627)[[Code]](https://github.com/WuYichen-97/Learning-to-Purify-Noisy-Labels-via-Meta-Soft-Label-Corrector)

* Robustness of Accuracy Metric and its Inspirations in Learning with Noisy Labels. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2012.04193)[[Code]](https://github.com/chenpf1025/RobustnessAccuracy)

* Learning from Noisy Labels with Complementary Loss Functions. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://palm.seu.edu.cn/zhangml/files/AAAI'21a.pdf)[[Code]](https://github.com/dengbaowang/CompLossForNoisyLabels)

* Analysing the Noise Model Error for Realistic Noisy Label Data. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2101.09763)[[Code]](https://github.com/uds-lsv/noise-estimation)

* Tackling Instance-Dependent Label Noise via a Universal Probabilistic Model. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://niug1984.github.io/paper/wang_aaai21.pdf)

* Learning with Group Noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://gcatnjust.github.io/ChenGong/paper/wang_aaai21_2.pdf)

* Meta Label Correction for Noisy Label Learning. 
  ![Meta Learning](https://img.shields.io/badge/Meta%20Learning-EC4899)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://www.microsoft.com/en-us/research/publication/meta-label-correction-for-noisy-label-learning/)
-----
### Other Conferences 2021
* (ICCV 2021) Learning with Noisy Labels for Robust Point Cloud Segmentation. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://shuquanye.com/PNAL_website/)[[Code]](https://github.com/pleaseconnectwifi/PNAL)

* (ICCV 2021) Learning with Noisy Labels via Sparse Regularization. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2108.00192)

* (WACV 2022) Towards a Robust Differentiable Architecture Search under Label Noise. 
  ![Meta Learning](https://img.shields.io/badge/Meta%20Learning-EC4899)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2110.12197)

* (WACV 2022) Addressing out-of-distribution label noise in webly-labelled data. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2110.13699)[[Code]](https://github.com/PaulAlbert31/DSOS)

* (BMVC 2021) PropMix: Hard Sample Filtering and Proportional MixUp for Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2110.11809)[[Code]](https://github.com/filipe-research/PropMix.)

* (IJCAI2021 Workshop) An Ensemble Noise-Robust K-fold Cross-Validation Selection Method for Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2107.02347)
-----
### ArXiv 2021

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Understanding Generalized Label Smoothing when Learning with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2106.04149)

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) A Good Representation Detects Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2110.06283.pdf)

* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Demystifying How Self-Supervised Features Improve Training from Noisy Labels. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2110.09022.pdf)[[code]](https://github.com/UCSC-REAL/SelfSup_NoisyLabel)

* Pervasive Label Errors in Test Sets Destabilize Machine Learning Benchmarks. 
  ![Noise Analysis](https://img.shields.io/badge/Noise%20Analysis-6B7280)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2103.14749)[[Code]](https://github.com/cgnorthcutt/label-errors)

* Double Descent in Adversarial Training: An Implicit Label Noise Perspective. 
  ![Theory](https://img.shields.io/badge/Theory-9CA3AF)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2110.03135.pdf)

* Estimating Instance-dependent Label-noise Transition Matrix using DNNs. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2105.13001)

* A Theoretical Analysis of Learning with Noisily Labeled Data. 
  ![Theory](https://img.shields.io/badge/Theory-9CA3AF)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2104.04114)

* Learning from Multiple Annotators by Incorporating Instance Features. 
  ![Label Fusion](https://img.shields.io/badge/Label%20Fusion-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2106.15146)

* Learning from Multiple Noisy Partial Labelers. 
  ![Partial Label](https://img.shields.io/badge/Partial%20Label-6366F1)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2106.04530)

* Instance Correction for Learning with Open-set Noisy Labels. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2106.00455)

* Sample Selection with Uncertainty of Losses for Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2106.00445)

* Analysis of classifiers robust to noisy labels. 
  ![Theory](https://img.shields.io/badge/Theory-9CA3AF)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2106.00274)

* NoiLIn: Do Noisy Labels Always Hurt Adversarial Training? 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2105.14676)

* Alleviating Noisy-label Effects in Image Classification via Probability Transition Matrix. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2110.08866)

* Learning with Noisy Labels by Targeted Relabeling. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2110.08355)

* Simple Attention Module based Speaker Verification with Iterative noisy label detection. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2110.06534)

* Adaptive Early-Learning Correction for Segmentation from Noisy Annotations. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2110.03740)

* Robust Deep Learning from Crowds with Belief Propagation. 
  ![Label Fusion](https://img.shields.io/badge/Label%20Fusion-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2111.00734)

* Adaptive Hierarchical Similarity Metric Learning with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2111.00006)

* Prototypical Classifier for Robust Class-Imbalanced Learning. 
  ![Reweighting](https://img.shields.io/badge/Reweighting-F97316)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2110.11553)

* A Survey of Label-noise Representation Learning: Past, Present and Future. 
  ![Survey](https://img.shields.io/badge/Survey-111827)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2011.04406.pdf)

* Noisy-Labeled NER with Confidence Estimation. 
  ![Reweighting](https://img.shields.io/badge/Reweighting-F97316)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2104.04318.pdf)[[Code]](https://github.com/liukun95/Noisy-NER-Confidence-Estimation)

* Study Group Learning: Improving Retinal Vessel Segmentation Trained with Noisy Labels. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2103.03451.pdf)[[Code]](https://github.com/SHI-Labs/SGL-Retinal-Vessel-Segmentation)

* Contrast to Divide: Self-Supervised Pre-Training for Learning with Noisy Labels. 
  ![Self-supervised](https://img.shields.io/badge/Self--supervised-059669)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2103.13646.pdf)[[Code]](https://github.com/ContrastToDivide/C2D)

* Exponentiated Gradient Reweighting for Robust Training Under Label Noise and Beyond. 
  ![Reweighting](https://img.shields.io/badge/Reweighting-F97316)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2104.01493.pdf)

* Understanding the Interaction of Adversarial Training with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2102.03482.pdf)

* Learning from Noisy Labels via Dynamic Loss Thresholding. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2104.02570.pdf)

* Evaluating Multi-label Classifiers with Noisy Labels. 
  ![Evaluation](https://img.shields.io/badge/Evaluation-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2102.08427.pdf)

* Self-Supervised Noisy Label Learning for Source-Free Unsupervised Domain Adaptation. 
  ![Self-supervised](https://img.shields.io/badge/Self--supervised-059669)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2102.11614.pdf)

* Transform consistency for learning with noisy labels. 
  ![Consistency Regularization](https://img.shields.io/badge/Consistency-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2103.13872.pdf)

* Learning to Combat Noisy Labels via Classification Margins. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2102.00751.pdf)

* Joint Negative and Positive Learning for Noisy Labels. 
  ![Loss Design](https://img.shields.io/badge/Loss%20Design-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2104.06574.pdf)

* Robust Classification from Noisy Labels: Integrating Additional Knowledge for Chest Radiography Abnormality Assessment. 
  ![Knowledge Integration](https://img.shields.io/badge/Knowledge-0EA5E9)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2104.05261.pdf)

* DST: Data Selection and joint Training for Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2103.00813.pdf)

* LongReMix: Robust Learning with High Confidence Samples in a Noisy Label Environment. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2103.04173.pdf)

* A Novel Perspective for Positive-Unlabeled Learning via Noisy Labels. 
  ![PU Learning](https://img.shields.io/badge/PU%20Learning-6366F1)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2103.04685.pdf)

* Ensemble Learning with Manifold-Based Data Splitting for Noisy Label Correction. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2103.07641.pdf)

* MetaLabelNet: Learning to Generate Soft-Labels from Noisy-Labels. 
  ![Meta Learning](https://img.shields.io/badge/Meta%20Learning-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2103.10869.pdf)

* On the Robustness of Monte Carlo Dropout Trained with Noisy Labels. 
  ![Uncertainty](https://img.shields.io/badge/Uncertainty-06B6D4)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2103.12002.pdf)
*  Co-matching: Combating Noisy Labels by Augmentation Anchoring. 
  ![Consistency Regularization](https://img.shields.io/badge/Consistency-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2103.12814.pdf)

* Pathological Image Segmentation with Noisy Labels. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2104.02602.pdf)

* CrowdTeacher: Robust Co-teaching with Noisy Answers & Sample-specific Perturbations for Tabular Data. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2103.17144.pdf)

* Approximating Instance-Dependent Noise via Instance-Confidence Embedding. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2103.13569)

* Rethinking Noisy Label Models: Labeler-Dependent Noise with Adversarial Awareness. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2105.14083)

* ScanMix: Learning from Severe Label Noise viaSemantic Clustering and Semi-Supervised Learning. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2103.11395)

* Friends and Foes in Learning from Noisy Labels. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2103.15055.pdf)

* Learning from Noisy Labels for Entity-Centric Information Extraction. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2104.08656.pdf)

* A Fremework Using Contrastive Learning for Classification with Noisy Labels. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2104.09563.pdf)

* Contrastive Learning Improves Model Robustness Under Label Noise. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2104.08984.pdf)[[Code]](https://github.com/arghosh/noisy_label_pretrain)

* Noise-Resistant Deep Metric Learning with Probabilistic Instance Filtering. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2108.01431.pdf)

* Compensation Learning. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2107.11921.pdf)

* kNet: A Deep kNN Network To Handle Label Noise. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2107.09735.pdf)

* Temporal-aware Language Representation Learning From Crowdsourced Labels. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2107.07958.pdf)

* Memorization in Deep Neural Networks: Does the Loss Function matter?. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2107.09957.pdf)

* Mitigating Memorization in Sample Selection for Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2107.07041.pdf)

* P-DIFF: Learning Classifier with Noisy Labels based on Probability Difference Distributions. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2009.06382)[[Code]](https://github.com/fistyee/P-DIFF)

* Decoupling Representation and Classifier for Noisy Label Learning. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2011.08145.pdf)

* Contrastive Representations for Label Noise Require Fine-Tuning. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2108.09154.pdf)

* NGC: A Unified Framework for Learning with Open-World Noisy Data. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2108.11035.pdf)

* Learning From Long-Tailed Data With Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2108.11096.pdf)

* Robust Long-Tailed Learning Under Label Noise. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2108.11569.pdf)

* Instance-dependent Label-noise Learning under a Structural Causal Model. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2109.02986.pdf)

* Assessing the Quality of the Datasets by Identifying Mislabeled Samples. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2109.05000.pdf)

* Learning to Aggregate and Refine Noisy Labels for Visual Sentiment Analysis. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/2109.07509)

* Robust Temporal Ensembling for Learning with Noisy Labels. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2109.14563.pdf)

* Knowledge Distillation with Noisy Labels for Natural Language Understanding. 
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2109.10147.pdf)

* Robustness and reliability when training with noisy labels. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2110.03321.pdf)

* Noisy Annotations Robust Consensual Collaborative Affect Expression Recognition. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021W/ABAW/papers/Gera_Noisy_Annotations_Robust_Consensual_Collaborative_Affect_Expression_Recognition_ICCVW_2021_paper.pdf)

* Consistency Regularization Can Improve Robustness to Label Noise. 
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2110.01242.pdf)
-----
## Papers & Code in 2020
-----
### ICML 2020
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Peer Loss Functions: Learning from Noisy Labels without Knowing Noise Rates. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v119/liu20e)[[Code 1]](https://github.com/weijiaheng/Multi-class-Peer-Loss-functions) [[Code 2]](https://github.com/gohsyi/PeerLoss)

* Normalized Loss Functions for Deep Learning with Noisy Labels. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2006.13554)[[Code]](https://github.com/HanxunH/Active-Passive-Losses)

* SIGUA: Forgetting May Make Learning with Noisy Labels More Robust. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v119/han20c.html)[[Code]](https://github.com/bhanML/SIGUA)

* Error-Bounded Correction of Noisy Labels. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v119/zheng20c.html)[[Code]](https://github.com/pingqingsheng/LRT)

* Training Binary Neural Networks through Learning with Noisy Supervision. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](http://proceedings.mlr.press/v119/han20d.html)[[Code]](https://github.com/zhaohui-yang/Binary-Neural-Networks)

* Improving generalization by controlling label-noise information in neural network weights. 
  ![Regularization](https://img.shields.io/badge/Regularization-84CC16)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v119/harutyunyan20a.html)[[Code]](https://github.com/hrayrhar/limit-label-memorization)

* Self-PU: Self Boosted and Calibrated Positive-Unlabeled Training. 
  ![PU Learning](https://img.shields.io/badge/PU%20Learning-6366F1)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/2006.11280)[[Code]](https://github.com/VITA-Group/Self-PU)

* Searching to Exploit Memorization Effect in Learning with Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v119/yao20b.html)[[Code]](https://github.com/jerermyyoung/rtlearning)

* Learning with Bounded Instance and Label-dependent Label Noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v119/cheng20c.html)

* Label-Noise Robust Domain Adaptation. 
  ![Domain Adaptation](https://img.shields.io/badge/Domain%20Adaptation-0EA5E9)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](http://proceedings.mlr.press/v119/yu20c.html)

* Beyond Synthetic Noise: Deep Learning on Controlled Noisy Labels. 
  ![Noise Analysis](https://img.shields.io/badge/Noise%20Analysis-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v119/jiang20c)

* Does label smoothing mitigate label noise?. 
  ![Regularization](https://img.shields.io/badge/Regularization-84CC16)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v119/lukasik20a.html)

* Learning with Multiple Complementary Labels. 
  ![Partial Label](https://img.shields.io/badge/Partial%20Label-6366F1)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v119/feng20a.html)

* Deep k-NN for Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v119/bahri20a.html)

* Extreme Multi-label Classification from Aggregated Labels. 
  ![Label Fusion](https://img.shields.io/badge/Label%20Fusion-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://proceedings.mlr.press/v119/shen20f.html)
-----
### ICLR 2020
* DivideMix: Learning with Noisy Labels as Semi-supervised Learning. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=HJgExaVtwr)[[Code]](https://github.com/LiJunnan1992/DivideMix)

* Learning from Rules Generalizing Labeled Exemplars. 
  ![Weak Supervision](https://img.shields.io/badge/Weak%20Supervision-0EA5E9)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/pdf?id=SkeuexBtDr) [[Code]](https://github.com/awasthiabhijeet/Learning-From-Rules)

* Robust training with ensemble consensus. 
  ![Ensemble](https://img.shields.io/badge/Ensemble-14B8A6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=ryxOUTVYDH)[[Code]](https://github.com/jisoolee0123/Robust-training-with-ensemble-consensus)

* Self-labelling via simultaneous clustering and representation learning. 
  ![Self-supervised](https://img.shields.io/badge/Self--supervised-22C55E)
  ![Clustering](https://img.shields.io/badge/Clustering-06B6D4)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=Hyx-jyBFPr)[[Code]](https://github.com/yukimasano/self-label)

* Can gradient clipping mitigate label noise? 
  ![Optimization](https://img.shields.io/badge/Optimization-84CC16)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=rklB76EKPr)[[Code]](https://github.com/dmizr/phuber)

* Mutual Mean-Teaching: Pseudo Label Refinery for Unsupervised Domain Adaptation on Person Re-identification. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openreview.net/forum?id=rJlnOhVYPS)[[Code]](https://github.com/yxgeee/MMT)

* Curriculum Loss: Robust Learning and Generalization against Label Corruption. 
  ![Curriculum Learning](https://img.shields.io/badge/Curriculum%20Learning-F97316)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=rkgt0REKwS)

* Simple and Effective Regularization Methods for Training on Noisily Labeled Data with Generalization Guarantee. 
  ![Regularization](https://img.shields.io/badge/Regularization-84CC16)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=Hke3gyHYwH)

* SELF: Learning to Filter Noisy Labels with Self-Ensembling. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Ensemble](https://img.shields.io/badge/Ensemble-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openreview.net/forum?id=HkgsPhNYPS)
-----
### NIPS 2020
* Part-dependent Label Noise: Towards Instance-dependent Label Noise. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/5607fe8879e4fd269e88387e8cb30b7e-Abstract.html)[[Code]](https://github.com/xiaoboxia/Part-dependent-label-noise)

* Identifying Mislabeled Data using the Area Under the Margin Ranking. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/c6102b3727b2a7d8b1bb6981147081ef-Abstract.html)[[Code]](https://github.com/asappresearch/aum)

* Dual T: Reducing Estimation Error for Transition Matrix in Label-noise Learning. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/512c5cad6c37edb98ae91c8a76c3a291-Abstract.html)

* Early-Learning Regularization Prevents Memorization of Noisy Labels. 
  ![Regularization](https://img.shields.io/badge/Regularization-84CC16)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/ea89621bee7c88b2c5be6681c8ef4906-Abstract.html)[[Code]](https://github.com/shengliu66/ELR)

* Coresets for Robust Training of Deep Neural Networks against Noisy Labels. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/8493eeaccb772c0878f99d60a0bd2bb3-Abstract.html)[[Code]](https://github.com/snap-stanford/crust)

* Modeling Noisy Annotations for Crowd Counting. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/22bb543b251c39ccdad8063d486987bb-Abstract.html)[[Code]](https://github.com/jia-wan/NoisyCC-pytorch)

* Robust Optimization for Fairness with Noisy Protected Groups. 
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/37d097caf1299d9aa79c2c2b843d2d78-Abstract.html)[[Code]](https://github.com/wenshuoguo/robust-fairness-code)

* Stochastic Optimization with Heavy-Tailed Noise via Accelerated Gradient Clipping. 
  ![Optimization](https://img.shields.io/badge/Optimization-84CC16)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/abd1c782880cc59759f4112fda0b8f98-Abstract.html)[[Code]](https://github.com/eduardgorbunov/accelerated_clipping)

* A Topological Filter for Learning with Label Noise. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/f4e3ce3e7b581ff32e40968298ba013d-Abstract.html)[[Code]](https://github.com/pxiangwu/TopoFilter)

* Self-Adaptive Training: beyond Empirical Risk Minimization. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://proceedings.neurips.cc//paper/2020/hash/e0ab531ec312161511493b002f9be2ee-Abstract.html)[[Code]](https://github.com/LayneH/self-adaptive-training)

* Disentangling Human Error from the Ground Truth in Segmentation of Medical Images. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://proceedings.neurips.cc//paper/2020/file/b5d17ed2b502da15aa727af0d51508d6-Paper.pdf)[[Code]](https://github.com/moucheng2017/Learn_Noisy_Labels_Medical_Images)

* Non-Convex SGD Learns Halfspaces with Adversarial Label Noise. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/d785bf9067f8af9e078b93cf26de2b54-Abstract.html)

* Efficient active learning of sparse halfspaces with arbitrary bounded noise. 
  ![Active Learning](https://img.shields.io/badge/Active%20Learning-6366F1)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/5034a5d62f91942d2a7aeaf527dfe111-Abstract.html)

* Semi-Supervised Partial Label Learning via Confidence-Rated Margin Maximization. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/4dea382d82666332fb564f2e711cbc71-Abstract.html)

* Labelling unlabelled videos from scratch with multi-modal self-supervision. 
  ![Self-supervised](https://img.shields.io/badge/Self--supervised-22C55E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/31fefc0e570cb3860f2a6d4b38c6490d-Abstract.html)[[Code]](https://github.com/facebookresearch/selavi)

* Distribution Aligning Refinery of Pseudo-label for Imbalanced Semi-supervised Learning. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/a7968b4339a1b85b7dbdb362dc44f9c4-Abstract.html)[[Code]](https://github.com/bbuing9/DARP)

* MetaPoison: Practical General-purpose Clean-label Data Poisoning. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/8ce6fc704072e351679ac97d4a985574-Abstract.html)[[Code 1]](https://github.com/wronnyhuang/metapoison)[[Code]](https://github.com/JonasGeiping/poisoning-gradient-matching)

* Provably Consistent Partial-Label Learning. 
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/7bd28f15a49d5e5848d6ec70e584e625-Abstract.html)

* A Variational Approach for Learning from Positive and Unlabeled Data. 
  ![PU Learning](https://img.shields.io/badge/PU%20Learning-6366F1)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/aa0d2a804a3510442f2fd40f2100b054-Abstract.html)[[Code]](https://github.com/HC-Feynman/vpu)
-----
### AAAI 2020
* [[**UCSC REAL Lab**]](https://github.com/UCSC-REAL) Reinforcement Learning with Perturbed Rewards. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/abs/1810.01032) [[Code]](https://github.com/wangjksjtu/rl-perturbed-reward)

* Less Is Better: Unweighted Data Subsampling via Influence Function. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/abs/1912.01321) [[Code]](https://github.com/RyanWangZf/Influence_Subsampling)

* Weakly Supervised Sequence Tagging from Noisy Rules. 
  ![Weak Supervision](https://img.shields.io/badge/Weak%20Supervision-0EA5E9)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/6009)[[Code]](https://github.com/BatsResearch/wiser)

* Coupled-View Deep Classifier Learning from Multiple Noisy Annotators. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5898)

* Partial multi-label learning with noisy label identification. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://www.xiemk.pro/publication/aaai20-pml-ni.pdf)

* Self-Paced Robust Learning for Leveraging Clean Labels in Noisy Data. 
  ![Curriculum Learning](https://img.shields.io/badge/Curriculum%20Learning-F97316)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://xuczhang.github.io/papers/aaai20_sprl.pdf)

* Label Error Correction and Generation Through Label Relationships. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5778)
-----
### CVPR 2020
* Combating noisy labels by agreement: A joint training method with co-regularization. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Ensemble](https://img.shields.io/badge/Ensemble-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Wei_Combating_Noisy_Labels_by_Agreement_A_Joint_Training_Method_with_CVPR_2020_paper.html)[[Code]](https://github.com/hongxin001/JoCoR)

* Distilling Effective Supervision From Severe Label Noise. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Knowledge Distillation](https://img.shields.io/badge/Knowledge%20Distillation-6366F1)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Distilling_Effective_Supervision_From_Severe_Label_Noise_CVPR_2020_paper.html)[[Code]](https://github.com/google-research/google-research/tree/master/ieg)

* Self-Training With Noisy Student Improves ImageNet Classification. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Self-training](https://img.shields.io/badge/Self--training-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Xie_Self-Training_With_Noisy_Student_Improves_ImageNet_Classification_CVPR_2020_paper.html)[[Code]](https://github.com/google-research/noisystudent)

* Noise Robust Generative Adversarial Networks. 
  ![Generative Model](https://img.shields.io/badge/Generative%20Model-EC4899)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Kaneko_Noise_Robust_Generative_Adversarial_Networks_CVPR_2020_paper.html)[[Code]](https://github.com/takuhirok/NR-GAN/)

* Global-Local GCN: Large-Scale Label Noise Cleansing for Face Recognition. 
  ![Graph-based](https://img.shields.io/badge/Graph-based-06B6D4)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Global-Local_GCN_Large-Scale_Label_Noise_Cleansing_for_Face_Recognition_CVPR_2020_paper.html)

* DLWL: Improving Detection for Lowshot Classes With Weakly Labelled Data. 
  ![Weak Supervision](https://img.shields.io/badge/Weak%20Supervision-0EA5E9)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Ramanathan_DLWL_Improving_Detection_for_Lowshot_Classes_With_Weakly_Labelled_Data_CVPR_2020_paper.html)

* Spherical Space Domain Adaptation With Robust Pseudo-Label Loss. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.html)[[Code]](https://github.com/XJTU-XGU/RSDA)

* Training Noise-Robust Deep Neural Networks via Meta-Learning. 
  ![Meta-learning](https://img.shields.io/badge/Meta--learning-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Training_Noise-Robust_Deep_Neural_Networks_via_Meta-Learning_CVPR_2020_paper.html)[[Code]](https://github.com/ZhenWang-PhD/Training-Noise-Robust-Deep-Neural-Networks-via-Meta-Learning)

* Shoestring: Graph-Based Semi-Supervised Classification With Severely Limited Labeled Data. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Graph-based](https://img.shields.io/badge/Graph-based-06B6D4)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lin_Shoestring_Graph-Based_Semi-Supervised_Classification_With_Severely_Limited_Labeled_Data_CVPR_2020_paper.html)[[Code]](https://github.com/iQua/CVPR2020-Shoestring)

* Noise-Aware Fully Webly Supervised Object Detection. 
  ![Weak Supervision](https://img.shields.io/badge/Weak%20Supervision-0EA5E9)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Shen_Noise-Aware_Fully_Webly_Supervised_Object_Detection_CVPR_2020_paper.html)[[Code]](https://github.com/shenyunhang/NA-fWebSOD)

* Learning From Noisy Anchors for One-Stage Object Detection. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_Learning_From_Noisy_Anchors_for_One-Stage_Object_Detection_CVPR_2020_paper.html)[[Code]](https://github.com/henrylee2570/NoisyAnchor)

* Generating Accurate Pseudo-Labels in Semi-Supervised Learning and Avoiding Overconfident Predictions via Hermite Polynomial Activations. 
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lokhande_Generating_Accurate_Pseudo-Labels_in_Semi-Supervised_Learning_and_Avoiding_Overconfident_Predictions_CVPR_2020_paper.html)[[Code]](https://github.com/lokhande-vishnu/DeepHermites)

* Revisiting Knowledge Distillation via Label Smoothing Regularization. 
  ![Knowledge Distillation](https://img.shields.io/badge/Knowledge%20Distillation-6366F1)
  ![Regularization](https://img.shields.io/badge/Regularization-84CC16)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Yuan_Revisiting_Knowledge_Distillation_via_Label_Smoothing_Regularization_CVPR_2020_paper.html)[[Code]](https://github.com/yuanli2333/Teacher-free-Knowledge-Distillation)
-----
### ECCV 2020
* 2020-ECCV - Learning with Noisy Class Labels for Instance Segmentation. 
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2062_ECCV_2020_paper.php)[[Code]](https://github.com/longrongyang/LNCIS)

* 2020-ECCV - Suppressing Mislabeled Data via Grouping and Self-Attention. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2633_ECCV_2020_paper.php)[[Code]](https://github.com/kaiwang960112/AFM)

* 2020-ECCV - NoiseRank: Unsupervised Label Noise Reduction with Dependence Models. 
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Unsupervised](https://img.shields.io/badge/Unsupervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/5921_ECCV_2020_paper.php)

* 2020-ECCV - Weakly Supervised Learning with Side Information for Noisy Labeled Images. 
  ![Weak Supervision](https://img.shields.io/badge/Weak%20Supervision-0EA5E9)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/7467_ECCV_2020_paper.php)

* 2020-ECCV - Learning Noise-Aware Encoder-Decoder from Noisy Labels by Alternating Back-Propagation for Saliency Detection. 
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2760_ECCV_2020_paper.php)

* 2020-ECCV - Graph convolutional networks for learning with few clean and many noisy labels. 
  ![Graph-based](https://img.shields.io/badge/Graph-based-06B6D4)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-10B981)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1060_ECCV_2020_paper.php)
-----
### ArXiv 2020
* No Regret Sample Selection with Noisy Labels. (Published on Machine Learning)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2003.03179.pdf)[[Code]](https://github.com/songheony/TAkS)

* Meta Soft Label Generation for Noisy Labels. (Published on ICPR 2020)
  ![Meta-learning](https://img.shields.io/badge/Meta--learning-F43F5E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2007.05836.pdf)[[Code]](https://github.com/gorkemalgan/MSLG_noisy_label)

* Learning from Noisy Labels with Deep Neural Networks: A Survey. 
  ![Survey](https://img.shields.io/badge/Survey-6B7280)
  ![Classification LNL](https://img.shields.io/badge/Classification%20LNL-16A34A)
  [[Paper]](https://arxiv.org/pdf/2007.08199.pdf)

* RAR-U-Net: a Residual Encoder to Attention Decoder by Residual Connections Framework for Spine Segmentation under Noisy Labels. (Published on ICIP 2021)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2009.12873.pdf)

* Learning from Small Amount of Medical Data with Noisy Labels: A Meta-Learning Approach. (Published on ICRPOA 2021)
  ![Meta-learning](https://img.shields.io/badge/Meta--learning-F43F5E)
  ![Cross-domain LNL](https://img.shields.io/badge/Cross--domain%20LNL-4B5563)
  [[Paper]](https://arxiv.org/pdf/2010.06939.pdf)
-----

## Acknowledgements

This repository is partially based on and inspired by the following project:

- https://github.com/weijiaheng/Advances-in-Label-Noise-Learning
