# Learning-with-Noisy-Labels

A curated list of most recent papers & codes in Learning with Noisy Labels.
---------------------------------------------------------------------------

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
![Datasets](https://img.shields.io/badge/Datasets-0F766E)

### Task Type

![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
![Multimodal](https://img.shields.io/badge/task-Multimodal-0F766E?style=flat-square)
![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
![General Cross-domain](https://img.shields.io/badge/task-General%20Cross--domain-475569?style=flat-square)

<!-- TASK_TYPE_INDEX_START -->
## Task Type Quick Index

> Each task lists up to 5 recent representative entries; the full paper list remains organized by venue below.

### Classification LNL (298)
![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)

- **ICLR 2026** - Enhancing Learning with Noisy Labels via Rockafellian Relaxation [[Paper]](https://openreview.net/forum?id=g4EpGiN5X3)
- **ICLR 2026** - TrainRef: Curating Data with Label Distribution and Minimal Reference for Accurate Prediction and Reliable Confidence [[Paper]](https://openreview.net/forum?id=jSs8CDsF0A)
- **ICLR 2026** - Resurfacing the Instance-only Dependent Label Noise Model through Loss Correction [[Paper]](https://openreview.net/forum?id=tuvkrivvbG)
- **AAAI 2026** - Jump-teaching: Combating Sample Selection Bias via Temporal Disagreement [[Paper]](https://doi.org/10.1609/aaai.v40i26.39375)
- **AAAI 2026** - On the Learning Dynamics of Two-layer Linear Networks with Label Noise SGD [[Paper]](https://doi.org/10.1609/aaai.v40i33.40069)

### Long-tailed Learning (12)
![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)

- **Top Journals 2026** - **Sxu** Class-Aware Multi-Granularity Co-Diffusion Models for Learning With Noisy Labels on Imbalanced Datasets. (Published on TKDE) [[Paper]](https://doi.org/10.1109/TKDE.2026.3650911)
- **ICCV 2025** - Boosting Class Representation via Semantically Related Instances for Robust Long-Tailed Learning with Noisy Labels [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Li_Boosting_Class_Representation_via_Semantically_Related_Instances_for_Robust_Long-Tailed_ICCV_2025_paper.html)
- **AAAI 2025** - Robust Logit Adjustment for Learning with Long-Tailed Noisy Data [[Paper]](https://doi.org/10.1609/aaai.v39i15.33738)
- **Neurips 2024** - Noisy Ostracods: A Fine-Grained, Imbalanced Real-World Dataset for Benchmarking Robust Machine Learning and Label Correction Methods [[Paper]](https://nips.cc/virtual/2024/poster/97733)
- **ICCV 2023** - Label-Noise Learning with Intrinsically Long-Tailed Data [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Lu_Label-Noise_Learning_with_Intrinsically_Long-Tailed_Data_ICCV_2023_paper.pdf)

### Multi-Label (10)
![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)

- **NeurIPS 2025** - **Sxu** Noisy Multi-Label Learning through Co-Occurrence-Aware Diffusion [[Paper]](https://neurips.cc/virtual/2025/poster/115033)
- **CVPR 2025** - Theory-Inspired Deep Multi-View Multi-Label Learning with Incomplete Views and Noisy Labels [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Li_Theory-Inspired_Deep_Multi-View_Multi-Label_Learning_with_Incomplete_Views_and_Noisy_CVPR_2025_paper.html)
- **ICCV 2023** - Holistic Label Correction for Noisy Multi-Label Classification [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Holistic_Label_Correction_for_Noisy_Multi-Label_Classification_ICCV_2023_paper.pdf)
- **ICCV 2023** - BoMD: Bag of Multi-label Descriptors for Noisy Chest X-ray Classification [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_BoMD_Bag_of_Multi-label_Descriptors_for_Noisy_Chest_X-ray_Classification_ICCV_2023_paper.pdf)
- **KDD 2023** - Weakly Supervised Multi-Label Classification of Full-Text Scientific Papers [[Paper]](https://arxiv.org/abs/2306.14003)

### Graph Data (12)
![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)

- **NeurIPS 2025** - GD$^2$: Robust Graph Learning under Label Noise via Dual-View Prediction Discrepancy [[Paper]](https://neurips.cc/virtual/2025/poster/115580)
- **Other Conferences 2025** - (IJCAI 2025) Leveraging Peer-Informed Label Consistency for Robust Graph Neural Networks with Noisy Labels [[Paper]](https://www.ijcai.org/proceedings/2025/623)
- **Neurips 2024** - NoisyGL: A Comprehensive Benchmark for Graph Neural Networks under Label Noise [[Paper]](https://nips.cc/virtual/2024/poster/97611)
- **ICML 2024** - Mitigating Label Noise on Graphs via Topological Sample Selection [[Paper]](https://proceedings.mlr.press/v235/wu24ae.html)
- **ICLR 2024** - Local Graph Clustering with Noisy Labels [[Paper]](https://openreview.net/forum?id=89A5c6enfc)

### Object Detection (6)
![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)

- **NeurIPS 2025** - ELDET: Early-Learning Distillation with Noisy Labels for Object Detection [[Paper]](https://neurips.cc/virtual/2025/poster/118794)
- **ICCV 2023** - Learning from Noisy Data for Semi-Supervised 3D Object Detection [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_Learning_from_Noisy_Data_for_Semi-Supervised_3D_Object_Detection_ICCV_2023_paper.pdf)
- **CVPR 2023** - MixTeacher: Mining Promising Labels with Mixed Scale Teacher for Semi-supervised Object Detection [[Paper]](https://arxiv.org/abs/2303.09061)
- **ECCV 2022** - PseCo: Pseudo Labeling and Consistency Training for Semi-Supervised Object Detection [[Paper]](https://arxiv.org/abs/2203.16317)
- **CVPR 2020** - Noise-Aware Fully Webly Supervised Object Detection [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Shen_Noise-Aware_Fully_Webly_Supervised_Object_Detection_CVPR_2020_paper.html)

### Segmentation (24)
![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)

- **ICCV 2025** - Images as Noisy Labels: Unleashing the Potential of the Diffusion Model for Open-Vocabulary Semantic Segmentation [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Li_Images_as_Noisy_Labels_Unleashing_the_Potential_of_the_Diffusion_ICCV_2025_paper.html)
- **CVPR 2025** - Minding Fuzzy Regions: A Data-driven Alternating Learning Paradigm for Stable Lesion Segmentation [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Fang_Minding_Fuzzy_Regions_A_Data-driven_Alternating_Learning_Paradigm_for_Stable_CVPR_2025_paper.html)
- **Neurips 2024** - CoSW: Conditional Sample Weighting for Smoke Segmentation with Label Noise [[Paper]](https://nips.cc/virtual/2024/poster/95170)
- **ICCV 2023** - SILT: Shadow-Aware Iterative Label Tuning for Learning to Detect Shadows from Noisy Labels [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_SILT_Shadow-Aware_Iterative_Label_Tuning_for_Learning_to_Detect_Shadows_ICCV_2023_paper.pdf)
- **ICCV 2023** - Semi-Supervised Semantic Segmentation under Label Noise via Diverse Learning Groups [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Semi-Supervised_Semantic_Segmentation_under_Label_Noise_via_Diverse_Learning_Groups_ICCV_2023_paper.pdf)

### NLP/Text (9)
![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)

- **ICLR 2026** - LANE: Label-Aware Noise Elimination for Fine-Grained Text Classification [[Paper]](https://openreview.net/forum?id=PuayLKdrFz)
- **Other Conferences 2025** - (AISTATS 2025) AlleNoise - Large-scale Text Classification Benchmark Dataset with Real-world Label Noise [[Paper]](https://proceedings.mlr.press/v258/raczkowska25a.html)
- **Top Journals 2025** - A Survey on Learning with Noisy Labels in Natural Language Processing: How to Train Models with Label Noise. (Published on Engineering Applications of Artificial Intelligence) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0952197625001575)
- **ICLR 2024** - MOFI: Learning Image Representations from Noisy Entity Annotated Images [[Paper]](https://openreview.net/forum?id=QQYpgReSRk)
- **KDD 2024** - Divide and Denoise: Learning from Noisy Labels in Fine-Grained Entity Typing with Cluster-Wise Loss Correction [[Paper]](https://doi.org/10.1145/3637528.3671834)

### Vision-Language (10)
![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)

- **AAAI 2026** - Mitigating Endogenous Confirmation Bias in Noisy Label Learning for Vision-Language Models [[Paper]](https://doi.org/10.1609/aaai.v40i29.39641)
- **CVPR 2025** - NLPrompt: Noise-Label Prompt Learning for Vision-Language Models [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Pan_NLPrompt_Noise-Label_Prompt_Learning_for_Vision-Language_Models_CVPR_2025_paper.html)
- **CVPR 2025** - DiN: Diffusion Model for Robust Medical VQA with Semantic Noisy Labels [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Guo_DiN_Diffusion_Model_for_Robust_Medical_VQA_with_Semantic_Noisy_CVPR_2025_paper.html)
- **Neurips 2024** - Vision-Language Models are Strong Noisy Label Detectors [[Paper]](https://nips.cc/virtual/2024/poster/94056)
- **ICLR 2024** - TextField3D: Towards Enhancing Open-Vocabulary 3D Generation with Noisy Text Fields [[Paper]](https://openreview.net/forum?id=WOiOzHG2zD)

### Multimodal (1)
![Multimodal](https://img.shields.io/badge/task-Multimodal-0F766E?style=flat-square)

- **ACM MM 2023** - Adaptive Contrastive Learning on Multimodal Transformer for Review Helpfulness Predictions with Multimodal Noisy Labels [[Paper]](https://doi.org/10.1145/3581783.3612405)

### LLM Alignment (8)
![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)

- **ICLR 2026** - RE-PO: Robust Enhanced Policy Optimization as a General Framework for LLM Alignment [[Paper]](https://openreview.net/forum?id=jDKpOvTCM8)
- **ICML 2025** - A Unified Theoretical Analysis of Private and Robust Offline Alignment: from RLHF to DPO [[Paper]](https://proceedings.mlr.press/v267/zhou25ac.html)
- **Neurips 2024** - Entity Alignment with Noisy Annotations from Large Language Models [[Paper]](https://nips.cc/virtual/2024/poster/93478)
- **Neurips 2024** - Benchmarking the Reasoning Robustness against Noisy Rationales in Chain-of-thought Prompting [[Paper]](https://nips.cc/virtual/2024/poster/95956)
- **Neurips 2024** - Perplexity-aware Correction for Robust Alignment with Noisy Preferences [[Paper]](https://nips.cc/virtual/2024/poster/95367)

### Medical Imaging (5)
![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)

- **ICLR 2025** - Regretful Decisions under Label Noise [[Paper]](https://openreview.net/forum?id=7B9FCDoUzB)
- **Neurips 2024** - Curriculum Fine-tuning of Vision Foundation Model for Medical Image Classification Under Label Noise [[Paper]](https://nips.cc/virtual/2024/poster/93198)
- **ICML 2024** - FAFE: Immune Complex Modeling with Geodesic Distance Loss on Noisy Group Frames [[Paper]](https://proceedings.mlr.press/v235/wu24g.html)
- **ArXiv 2021** - Robust Classification from Noisy Labels: Integrating Additional Knowledge for Chest Radiography Abnormality Assessment [[Paper]](https://arxiv.org/pdf/2104.05261.pdf)
- **ArXiv 2020** - Learning from Small Amount of Medical Data with Noisy Labels: A Meta-Learning Approach. (Published on ICRPOA 2021) [[Paper]](https://arxiv.org/pdf/2010.06939.pdf)

### Federated Learning (8)
![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)

- **WACV 2026** - FedEFC: Federated Learning Using Enhanced Forward Correction Against Noisy Labels [[Paper]](https://openaccess.thecvf.com/content/WACV2026/html/Yu_FedEFC_Federated_Learning_Using_Enhanced_Forward_Correction_Against_Noisy_Labels_WACV_2026_paper.html)
- **Top Journals 2026** - Federated Learning with Noisy Labels: A Comprehensive and Concise Review of Current Methodologies and Future Directions. (Published on Neural Networks) [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0893608026003503)
- **ICML 2025** - FedClean: A General Robust Label Noise Correction for Federated Learning [[Paper]](https://proceedings.mlr.press/v267/jiang25m.html)
- **Top Journals 2025** - FedELR: When Federated Learning Meets Learning with Noisy Labels. (Published on Neural Networks) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0893608025001546)
- **AAAI 2024** - FedDiv: Collaborative Noise Filtering for Federated Learning with Noisy Labels [[Paper]](https://doi.org/10.1609/aaai.v38i4.28153)

### Time Series (9)
![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)

- **NeurIPS 2025** - FlowRefiner: A Robust Traffic Classification Framework against Label Noise [[Paper]](https://nips.cc/virtual/2025/poster/118975)
- **ICLR 2025** - Learning under Temporal Label Noise [[Paper]](https://openreview.net/forum?id=5o0phqAhsP)
- **Neurips 2024** - Information-theoretic Limits of Online Classification with Noisy Labels [[Paper]](https://nips.cc/virtual/2024/poster/95650)
- **ICCV 2023** - Learning from Noisy Pseudo Labels for Semi-Supervised Temporal Action Localization [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Learning_from_Noisy_Pseudo_Labels_for_Semi-Supervised_Temporal_Action_Localization_ICCV_2023_paper.pdf)
- **NeurIPS 2023** - Scale-teaching: Robust Multi-scale Training for Time Series Classification with Noisy Labels [[Paper]](https://openreview.net/forum?id=9D0fELXbrg)

### Retrieval (6)
![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)

- **AAAI 2026** - Neighbor-aware Instance Refining with Noisy Labels for Cross-Modal Retrieval [[Paper]](https://researchportal.northumbria.ac.uk/en/publications/neighbor-aware-instance-refining-with-noisy-labels-for-cross-moda/)
- **CVPR 2023** - RONO: Robust Discriminative Learning with Noisy Labels for 2D-3D Cross-Modal Retrieval [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Feng_RONO_Robust_Discriminative_Learning_With_Noisy_Labels_for_2D-3D_Cross-Modal_CVPR_2023_paper.pdf)
- **CVPR 2022** - Large-Scale Pre-training for Person Re-identification with Noisy Labels [[Paper]](http://arxiv.org/pdf/2203.16533)
- **ACM MM 2022** - Early-Learning Regularized Contrastive Learning for Cross-Modal Retrieval with Noisy Labels [[Paper]](https://doi.org/10.1145/3503161.3547809)
- **ArXiv 2022** - Learning with Label Noise for Image Retrieval by Selecting Interactions [[Paper]](https://arxiv.org/abs/2112.10453)

### Generative Models (8)
![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)

- **ICLR 2026** - Learning from Noisy Preferences: A Semi-Supervised Learning Approach to Direct Preference Optimization [[Paper]](https://openreview.net/forum?id=rRc04jyoAk)
- **ICCV 2025** - Guiding Noisy Label Conditional Diffusion Models with Score-based Discriminator Correction [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Cong_Guiding_Noisy_Label_Conditional_Diffusion_Models_with_Score-based_Discriminator_Correction_ICCV_2025_paper.html)
- **Neurips 2024** - Immiscible Diffusion: Accelerating Diffusion Training with Noise Assignment [[Paper]](https://nips.cc/virtual/2024/poster/93906)
- **ICML 2024** - Consistent Diffusion Meets Tweedie: Training Exact Ambient Diffusion Models with Noisy Data [[Paper]](https://proceedings.mlr.press/v235/daras24a.html)
- **ICLR 2024** - Label-Noise Robust Diffusion Models [[Paper]](https://openreview.net/forum?id=HXWTXXtHNl)

### Audio/Video (5)
![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)

- **ICLR 2025** - Learning to Generate Diverse Pedestrian Movements from Web Videos with Noisy Labels [[Paper]](https://openreview.net/forum?id=DydCqKa6AH)
- **CVPR 2023** - Collaborative Noisy Label Cleaner: Learning Scene-aware Trailers for Multi-modal Highlight Detection in Movies [[Paper]](https://arxiv.org/abs/2303.14768)
- **ECCV 2022** - Joint-Modal Label Denoising for Weakly-Supervised Audio-Visual Video Parsing [[Paper]](https://arxiv.org/abs/2204.11573)
- **NIPS 2020** - Modeling Noisy Annotations for Crowd Counting [[Paper]](https://papers.nips.cc/paper/2020/hash/22bb543b251c39ccdad8063d486987bb-Abstract.html)
- **NIPS 2020** - Labelling unlabelled videos from scratch with multi-modal self-supervision [[Paper]](https://papers.nips.cc/paper/2020/hash/31fefc0e570cb3860f2a6d4b38c6490d-Abstract.html)

### 3D/Point Cloud (2)
![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)

- **NeurIPS 2023** - ARTIC3D: Learning Robust Articulated 3D Shapes from Noisy Web Image Collections [[Paper]](https://openreview.net/forum?id=rJc5Lsn5QU)
- **CVPR 2023** - Semi-Supervised 2D Human Pose Estimation Driven by Position Inconsistency Pseudo Label Correction Module [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Semi-Supervised_2D_Human_Pose_Estimation_Driven_by_Position_Inconsistency_Pseudo_CVPR_2023_paper.pdf)

### Anomaly/OOD (15)
![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)

- **ICLR 2026** - Noise-Aware Generalization: Robustness to In-Domain Noise and Out-of-Domain Generalization [[Paper]](https://openreview.net/forum?id=wb83wO41QT)
- **Other Conferences 2025** - (KDD 2025) Noise-Resilient Point-wise Anomaly Detection in Time Series Using Weak Segment Labels [[Paper]](https://doi.org/10.1145/3690624.3709257)
- **Top Journals 2025** - Learning from Open-set Noisy Labels Based on Multi-prototype Modeling. (Published on Pattern Recognition) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320324006538)
- **CVPR 2024** - A Noisy Elephant in the Room: Is Your Out-of-Distribution Detector Robust to Label Noise? [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Lee_A_Noisy_Elephant_in_the_Room_Is_Your_Out-of-Distribution_Detector_Robust_CVPR_2024_paper.html)
- **AAAI 2024** - Unlocking the Power of Open Set: A New Perspective for Open-Set Noisy Label Learning [[Paper]](https://doi.org/10.1609/aaai.v38i14.29377)

### Crowdsourcing (13)
![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)

- **WACV 2026** - Reciprocal Teaching: Dynamic Multi-Model Teacher-Student Learning for Multiple Noisy Annotations [[Paper]](https://openaccess.thecvf.com/content/WACV2026/html/Ai_Reciprocal_Teaching_Dynamic_Multi-Model_Teacher-Student_Learning_for_Multiple_Noisy_Annotations_WACV_2026_paper.html)
- **KDD 2023** - To Aggregate or Not? Learning with Separate Noisy Labels [[Paper]](https://arxiv.org/abs/2206.07181)
- **ICML 2023** - Deep Clustering with Incomplete Noisy Pairwise Annotations: A Geometric Regularization Approach [[Paper]](https://proceedings.mlr.press/v202/nguyen23d)
- **CVPR 2023** - HandsOff: Labeled Dataset Generation with No Additional Human Annotations [[Paper]](https://arxiv.org/pdf/2212.12645.pdf)
- **CVPR 2023** - Leveraging Inter-Rater Agreement for Classification in the Presence of Noisy Labels [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Bucarelli_Leveraging_Inter-Rater_Agreement_for_Classification_in_the_Presence_of_Noisy_CVPR_2023_paper.pdf)

### Weak Supervision (29)
![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)

- **ICLR 2025** - Learning from Weak Labelers as Constraints [[Paper]](https://openreview.net/forum?id=2BtFKEeMGo)
- **ICCV 2023** - LNPL-MIL: Learning from Noisy Pseudo Labels for Promoting Multiple Instance Learning in Whole Slide Image [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Shao_LNPL-MIL_Learning_from_Noisy_Pseudo_Labels_for_Promoting_Multiple_Instance_ICCV_2023_paper.pdf)
- **KDD 2023** - Robust Positive-Unlabeled Learning via Noise Negative Sample Self-correction [[Paper]](https://dl.acm.org/doi/10.1145/3580305.3599491)
- **KDD 2023** - Neural-Hidden-CRF: A Robust Weakly-Supervised Sequence Labeler [[Paper]](https://browse.arxiv.org/pdf/2309.05086.pdf)
- **KDD 2023** - Complementary Classifier Induced Partial Label Learning [[Paper]](https://arxiv.org/abs/2305.09897)

<!-- TASK_TYPE_INDEX_END -->

## 🧰 Public Software

**Docta-AI:**
An advanced data-centric AI platform that detects and rectifies issues in any data format (i.e., label error detection). [[Website]](https://github.com/Docta-ai/docta)

## 🎓 Tutorial

**1st Learning and Mining with Noisy Labels Challenge** (IJCAI 2023)[[Website]](https://sites.google.com/ucsc.edu/tutorial-noisylabels/home)[[GitHub]](https://github.com/Docta-ai/IJCAI-tutorial)

## 📦 Content

- [Task Type Quick Index](#task-type-quick-index)
- [Benchmarks](#benchmarks)
- [Papers & Code in 2026](#papers--code-in-2026)
  - [ICLR 2026](#ICLR-2026)
  - [AAAI 2026](#AAAI-2026)
  - [WACV 2026](#WACV-2026)
  - [Top Journals 2026](#Top-Journals-2026)
- [Papers & Code in 2025](#papers--code-in-2025)
  - [NeurIPS 2025](#NeurIPS-2025)
  - [ICCV 2025](#ICCV-2025)
  - [ICML 2025](#ICML-2025)
  - [CVPR 2025](#CVPR-2025)
  - [ICLR 2025](#ICLR-2025)
  - [AAAI 2025](#AAAI-2025)
  - [Other Conferences 2025](#Other-Conferences-2025)
  - [Top Journals 2025](#Top-Journals-2025)
- [Papers & Code in 2024](#papers--code-in-2024)
  - [NeurIPS 2024](#NeurIPS-2024)
  - [ICML 2024](#ICML-2024)
  - [CVPR 2024](#CVPR-2024)
  - [ICLR 2024](#ICLR-2024)
  - [KDD 2024](#KDD-2024)
  - [ACM MM 2024](#ACM-MM-2024)
  - [AAAI 2024](#AAAI-2024)
  - [Top Journals 2024](#Top-Journals-2024)
- [Papers & Code in 2023](#papers--code-in-2023)
  - [ICCV 2023](#ICCV-2023)
  - [KDD 2023](#KDD-2023)
  - [NeurIPS 2023](#NeurIPS-2023)
  - [ICML 2023](#ICML-2023)
  - [CVPR 2023](#CVPR-2023)
  - [ICLR 2023](#ICLR-2023)
  - [AAAI 2023](#AAAI-2023)
  - [ACM MM 2023](#ACM-MM-2023)
  - [Top Journals 2023](#Top-Journals-2023)
- [Papers & Code in 2022](#papers--code-in-2022)
  - [NeurIPS 2022](#NeurIPS-2022)
  - [ECCV 2022](#ECCV-2022)
  - [ICML 2022](#ICML-2022)
  - [CVPR 2022](#CVPR-2022)
  - [ICLR 2022](#ICLR-2022)
  - [AAAI 2022](#AAAI-2022)
  - [KDD 2022](#KDD-2022)
  - [ACM MM 2022](#ACM-MM-2022)
  - [Top Journals 2022](#Top-Journals-2022)
  - [AISTATS 2022](#AISTATS-2022)
  - [Other Conferences 2022](#Other-Conferences-2022)
  - [ArXiv 2022](#ArXiv-2022)
- [Papers & Code in 2021](#papers--code-in-2021)
  - [NeurIPS 2021](#NeurIPS-2021)
  - [KDD 2021](#KDD-2021)
  - [ACM MM 2021](#ACM-MM-2021)
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
  - [KDD 2020](#KDD-2020)
  - [AAAI 2020](#AAAI-2020)
  - [CVPR 2020](#CVPR-2020)
  - [ECCV 2020](#ECCV-2020)
  - [ArXiv 2020](#ArXiv-2020)

---

## 📊 Benchmarks

Real-world noisy-label bechmarks:

| Dataset           | Noise Rate                        | Website                                                                         | Paper                                                                                                         |
| ----------------- | --------------------------------- | ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| CIFAR-10N         | ~8%/~20%/~40% (human label noise) | [[Website]](http://noisylabels.com/)                                               | [[Paper]](https://arxiv.org/abs/2110.12088)                                                                      |
| CIFAR-100N        | ~40% (human label noise)          | [[Website]](http://noisylabels.com/)                                               | [[Paper]](https://arxiv.org/abs/2110.12088)                                                                      |
| Red Stanford Cars | ~40% (synthetic noise)            | [[Website]](https://ai.googleblog.com/2020/08/understanding-deep-learning-on.html) | [[Paper]](http://proceedings.mlr.press/v119/jiang20c/jiang20c.pdf)                                               |
| Red Mini-ImageNet | ~40% (synthetic noise)            | [[Website]](https://ai.googleblog.com/2020/08/understanding-deep-learning-on.html) | [[Paper]](http://proceedings.mlr.press/v119/jiang20c/jiang20c.pdf)                                               |
| Animal-10N        | ~8% (real-world noise)            | [[Website]](https://dm.kaist.ac.kr/datasets/animal-10n/)                           | [[Paper]](http://proceedings.mlr.press/v97/song19b.html)                                                         |
| Food-101N         | ~20% (human label noise)          | [[Website]](https://github.com/kuanghuei/clean-net)                                | [[Paper]](https://arxiv.org/pdf/1711.07131.pdf)                                                                  |
| Clothing1M        | ~38% (real-world noise)           | [[Website]](https://github.com/Cysu/noisy_label)                                   | [[Paper]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Xiao_Learning_From_Massive_2015_CVPR_paper.pdf) |

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

## Papers & Code in 2026

---

### ICLR 2026

* Enhancing Learning with Noisy Labels via Rockafellian Relaxation.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=g4EpGiN5X3)
* TrainRef: Curating Data with Label Distribution and Minimal Reference for Accurate Prediction and Reliable Confidence.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=jSs8CDsF0A)
* Resurfacing the Instance-only Dependent Label Noise Model through Loss Correction.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=tuvkrivvbG)
* LANE: Label-Aware Noise Elimination for Fine-Grained Text Classification.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=PuayLKdrFz)
* Noise-Aware Generalization: Robustness to In-Domain Noise and Out-of-Domain Generalization.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=wb83wO41QT)
* Learning from Noisy Preferences: A Semi-Supervised Learning Approach to Direct Preference Optimization.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rRc04jyoAk)
* RE-PO: Robust Enhanced Policy Optimization as a General Framework for LLM Alignment.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=jDKpOvTCM8)

---

### AAAI 2026

* Jump-teaching: Combating Sample Selection Bias via Temporal Disagreement.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v40i26.39375)
* On the Learning Dynamics of Two-layer Linear Networks with Label Noise SGD.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v40i33.40069)
* Mitigating Endogenous Confirmation Bias in Noisy Label Learning for Vision-Language Models.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v40i29.39641)
* Neighbor-aware Instance Refining with Noisy Labels for Cross-Modal Retrieval.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://researchportal.northumbria.ac.uk/en/publications/neighbor-aware-instance-refining-with-noisy-labels-for-cross-moda/)

### WACV 2026

* FedEFC: Federated Learning Using Enhanced Forward Correction Against Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/WACV2026/html/Yu_FedEFC_Federated_Learning_Using_Enhanced_Forward_Correction_Against_Noisy_Labels_WACV_2026_paper.html)
* Reciprocal Teaching: Dynamic Multi-Model Teacher-Student Learning for Multiple Noisy Annotations.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/WACV2026/html/Ai_Reciprocal_Teaching_Dynamic_Multi-Model_Teacher-Student_Learning_for_Multiple_Noisy_Annotations_WACV_2026_paper.html)

---

### Top Journals 2026

* [[**Sxu**]](https://github.com/SenyuHou) Class-Aware Multi-Granularity Co-Diffusion Models for Learning With Noisy Labels on Imbalanced Datasets. (Published on TKDE)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TKDE.2026.3650911)[[Code]](https://github.com/SenyuHou/CaMCoD)
* Continuous Review and Timely Correction: Enhancing the Resistance to Noisy Labels via Self-Not-True and Class-Wise Distillation. (Published on TPAMI)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2025.3649111)
* Affinity-aware Uncertainty Quantification for Learning with Noisy Labels. (Published on Pattern Recognition)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320325011586)
* Federated Learning with Noisy Labels: A Comprehensive and Concise Review of Current Methodologies and Future Directions. (Published on Neural Networks)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0893608026003503)

## Papers & Code in 2025

---

### NeurIPS 2025

* [[**Sxu**]](https://github.com/SenyuHou) Noisy Multi-Label Learning through Co-Occurrence-Aware Diffusion.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/115033)
* Learning to Clean: Reinforcement Learning for Noisy Label Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2025/poster/115438)
* Enhancing Sample Selection Against Label Noise by Cutting Mislabeled Easy Examples.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/118281)
* Handling Label Noise via Instance-Level Difficulty Modeling and Dynamic Optimization.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2025/poster/116524)[[Code]](https://github.com/iTheresaApocalypse/IDO)
* Self-Boost via Optimal Retraining: An Analysis via Approximate Message Passing.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/116800)

* GD$^2$: Robust Graph Learning under Label Noise via Dual-View Prediction Discrepancy.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/115580)
* ELDET: Early-Learning Distillation with Noisy Labels for Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/118794)
* FlowRefiner: A Robust Traffic Classification Framework against Label Noise.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2025/poster/118975)

### ICCV 2025

* CA2C: A Prior-Knowledge-Free Approach for Robust Label Noise Learning via Asymmetric Co-learning and Co-training.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Sheng_CA2C_A_Prior-Knowledge-Free_Approach_for_Robust_Label_Noise_Learning_via_ICCV_2025_paper.html)
* Meta-Learning Dynamic Center Distance: Hard Sample Mining for Learning with Noisy Labels.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Mu_Meta-Learning_Dynamic_Center_Distance_Hard_Sample_Mining_for_Learning_with_ICCV_2025_paper.html)
* Joint Asymmetric Loss for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_Joint_Asymmetric_Loss_for_Learning_with_Noisy_Labels_ICCV_2025_paper.html)[[Code]](https://github.com/cswjl/joint-asymmetric-loss)
* Boosting Class Representation via Semantically Related Instances for Robust Long-Tailed Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Li_Boosting_Class_Representation_via_Semantically_Related_Instances_for_Robust_Long-Tailed_ICCV_2025_paper.html)[[Code]](https://github.com/yhli-ml/IBC)
* Guiding Noisy Label Conditional Diffusion Models with Score-based Discriminator Correction.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Cong_Guiding_Noisy_Label_Conditional_Diffusion_Models_with_Score-based_Discriminator_Correction_ICCV_2025_paper.html)
* Images as Noisy Labels: Unleashing the Potential of the Diffusion Model for Open-Vocabulary Semantic Segmentation.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Li_Images_as_Noisy_Labels_Unleashing_the_Potential_of_the_Diffusion_ICCV_2025_paper.html)

---

### ICML 2025

* On the Role of Label Noise in the Feature Learning Process.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/han25c.html)
* Retraining with Predicted Hard Labels Provably Increases Model Accuracy.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/das25b.html)
* FedClean: A General Robust Label Noise Correction for Federated Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/jiang25m.html)
* A Unified Theoretical Analysis of Private and Robust Offline Alignment: from RLHF to DPO.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/zhou25ac.html)

---

### CVPR 2025

* [[**Sxu**]](https://github.com/SenyuHou) Directional Label Diffusion Model for Learning from Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Hou_Directional_Label_Diffusion_Model_for_Learning_from_Noisy_Labels_CVPR_2025_paper.html)[[Code]](https://github.com/SenyuHou/DLD)
* NLPrompt: Noise-Label Prompt Learning for Vision-Language Models.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Pan_NLPrompt_Noise-Label_Prompt_Learning_for_Vision-Language_Models_CVPR_2025_paper.html)
* DiN: Diffusion Model for Robust Medical VQA with Semantic Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Guo_DiN_Diffusion_Model_for_Robust_Medical_VQA_with_Semantic_Noisy_CVPR_2025_paper.html)
* Theory-Inspired Deep Multi-View Multi-Label Learning with Incomplete Views and Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Li_Theory-Inspired_Deep_Multi-View_Multi-Label_Learning_with_Incomplete_Views_and_Noisy_CVPR_2025_paper.html)
* Minding Fuzzy Regions: A Data-driven Alternating Learning Paradigm for Stable Lesion Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Fang_Minding_Fuzzy_Regions_A_Data-driven_Alternating_Learning_Paradigm_for_Stable_CVPR_2025_paper.html)

---

### ICLR 2025

* Regretful Decisions under Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=7B9FCDoUzB)
* Learning under Temporal Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=5o0phqAhsP)
* Learning from Weak Labelers as Constraints.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=2BtFKEeMGo)
* Learning to Generate Diverse Pedestrian Movements from Web Videos with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=DydCqKa6AH)[[Code]](https://genforce.github.io/PedGen/)

---

### AAAI 2025

* Learning Causal Transition Matrix for Instance-dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v39i17.34014)
* Learning from Noisy Labels via Self-Taught On-the-Fly Meta Loss Rescaling.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v39i22.34580)
* Noisy Label Calibration for Multi-View Classification.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v39i20.35485)
* Enhanced Sample Selection with Confidence Tracking: Identifying Correctly Labeled Yet Hard-to-Learn Samples in Noisy Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v39i19.34180)
* Optimized Gradient Clipping for Noisy Label Learning.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v39i9.33025)

* Robust Logit Adjustment for Learning with Long-Tailed Noisy Data.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v39i15.33738)

### Other Conferences 2025

* (KDD 2025) Noise-Resilient Point-wise Anomaly Detection in Time Series Using Weak Segment Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3690624.3709257)
* (IJCAI 2025) Leveraging Peer-Informed Label Consistency for Robust Graph Neural Networks with Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2025/623)
* (AISTATS 2025) AlleNoise - Large-scale Text Classification Benchmark Dataset with Real-world Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v258/raczkowska25a.html)[[Code]](https://github.com/allegro/AlleNoise)

---

### Top Journals 2025

* SplitNet: Learnable Clean-Noisy Label Splitting for Learning with Noisy Labels. (Published on IJCV)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://link.springer.com/article/10.1007/s11263-024-02187-4)
* Improving the Instance-Dependent Transition Matrix Estimation by Exploiting Self-Supervised Learning. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2025.3595613)
* FedELR: When Federated Learning Meets Learning with Noisy Labels. (Published on Neural Networks)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0893608025001546)
* Learning from Open-set Noisy Labels Based on Multi-prototype Modeling. (Published on Pattern Recognition)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320324006538)
* A Survey on Learning with Noisy Labels in Natural Language Processing: How to Train Models with Label Noise. (Published on Engineering Applications of Artificial Intelligence)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0952197625001575)

## Papers & Code in 2024

---

### Neurips 2024

* Learning the Latent Causal Structure for Modeling Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93700)
* Learning from Noisy Labels via Conditional Distributionally Robust Optimization.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/96820)
* Sample Selection via Contrastive Fragmentation for Noisy Label Regression.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95898)
* Label Noise: Ignorance Is Bliss.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/94205)
* Robust Contrastive Multi-view Clustering against Dual Noisy Correspondence.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/96528)
* Noisy Label Learning with Instance-Dependent Outliers: Identifiability via Crowd Wisdom.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95831)
* Entity Alignment with Noisy Annotations from Large Language Models.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93478)
* Vision-Language Models are Strong Noisy Label Detectors.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/94056)
* Benchmarking the Reasoning Robustness against Noisy Rationales in Chain-of-thought Prompting.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95956)
* CoSW: Conditional Sample Weighting for Smoke Segmentation with Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95170)
* Immiscible Diffusion: Accelerating Diffusion Training with Noise Assignment.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93906)
* Curriculum Fine-tuning of Vision Foundation Model for Medical Image Classification Under Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93198)[[Code]](https://github.com/gist-ailab/CUFIT)
* NoisyGL: A Comprehensive Benchmark for Graph Neural Networks under Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/97611)
* Noisy Ostracods: A Fine-Grained, Imbalanced Real-World Dataset for Benchmarking Robust Machine Learning and Label Correction Methods.
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/97733)
* Perplexity-aware Correction for Robust Alignment with Noisy Preferences.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95367)
* Information-theoretic Limits of Online Classification with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95650)

---

### ICML 2024

* Pi-DUAL: Using privileged information to distinguish clean from noisy labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/wang24bb.html)
* Self-cognitive Denoising in the Presence of Multiple Noisy Label Sources.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/sun24o.html)
* Mitigating Label Noise on Graphs via Topological Sample Selection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/wu24ae.html)
* Provably Robust DPO: Aligning Language Models with Noisy Feedback.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/ray-chowdhury24a.html)
* Consistent Diffusion Meets Tweedie: Training Exact Ambient Diffusion Models with Noisy Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/daras24a.html)
* RIME: Robust Preference-based Reinforcement Learning with Noisy Preferences.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/cheng24k.html)
* FAFE: Immune Complex Modeling with Geodesic Distance Loss on Noisy Group Frames.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/wu24g.html)

---

### CVPR 2024

* Estimating Noisy Class Posterior with Part-level Labels for Noisy Label Learning.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Chen_Estimating_Noisy_Class_Posterior_with_Part-level_Labels_for_Noisy_Label_Learning_CVPR_2024_paper.html)
* Learning with Structural Labels for Learning with Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_Learning_with_Structural_Labels_for_Learning_with_Noisy_Labels_CVPR_2024_paper.html)
* Learning Discriminative Dynamics with Label Corruption for Noisy Label Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_Learning_Discriminative_Dynamics_with_Label_Corruption_for_Noisy_Label_Detection_CVPR_2024_paper.html)
* A Noisy Elephant in the Room: Is Your Out-of-Distribution Detector Robust to Label Noise?
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Lee_A_Noisy_Elephant_in_the_Room_Is_Your_Out-of-Distribution_Detector_Robust_CVPR_2024_paper.html)

---

### ICLR 2024

* Understanding and Mitigating the Label Noise in Pre-training on Downstream Tasks.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=TjhUtloBZU)
* Early Stopping Against Label Noise Without Validation Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=CMzF2aOfqp)
* Why is SAM Robust to Label Noise?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=3aZCPl3ZvR)
* Dirichlet-based Per-Sample Weighting by Transition Matrix for Noisy Label Learning.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=A4mJuFRMN8)
* Robust Classification via Regression for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=wfgZc3IMqo)
* Label-Noise Robust Diffusion Models.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=HXWTXXtHNl)
* Local Graph Clustering with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=89A5c6enfc)
* MOFI: Learning Image Representations from Noisy Entity Annotated Images.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=QQYpgReSRk)
* TextField3D: Towards Enhancing Open-Vocabulary 3D Generation with Noisy Text Fields.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=WOiOzHG2zD)

---

### KDD 2024

* Divide and Denoise: Learning from Noisy Labels in Fine-Grained Entity Typing with Cluster-Wise Loss Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3637528.3671834)

---

### ACM MM 2024

* Enhancing Robustness in Learning with Noisy Labels: An Asymmetric Co-Training Approach.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3664647.3680924)
* Mitigate Catastrophic Remembering via Continual Knowledge Purification for Noisy Label Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3664647.3680975)

* CLIPCleaner: Cleaning Noisy Labels with CLIP.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3664647.3681521)

### AAAI 2024

* [[**Sxu**]](https://github.com/SenyuHou) Which Is More Effective in Label Noise Cleaning, Correction or Filtering?
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v38i11.29183)

* Learning with Noisy Labels via Hashing Mutual Information Waiting.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v38i16.29578)
* FedDiv: Collaborative Noise Filtering for Federated Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v38i4.28153)
* Unlocking the Power of Open Set: A New Perspective for Open-Set Noisy Label Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v38i14.29377)

### Top Journals 2024

* Tackling Noisy Labels with Network Parameter Additive Decomposition. (Published on TPAMI)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2024.3367129)
* A Time-Consistency Curriculum for Learning from Instance-Dependent Noisy Labels. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2024.3433918)
* BadLabel: A Robust Perspective on Evaluating and Enhancing Label-noise Learning. (Published on TPAMI)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2024.3439233)

## Papers & Code in 2023

---

### ICCV 2023

* PADDLES: Phase-Amplitude Spectrum Disentangled Early Stopping for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Huang_PADDLES_Phase-Amplitude_Spectrum_Disentangled_Early_Stopping_for_Learning_with_Noisy_ICCV_2023_paper.pdf)[[Code]](https://github.com/CoderHHX/PADDLES)
* Sample-wise Label Confidence Incorporation for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ahn_Sample-wise_Label_Confidence_Incorporation_for_Learning_with_Noisy_Labels_ICCV_2023_paper.pdf)
* LA-Net: Landmark-Aware Learning for Reliable Facial Expression Recognition under Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_LA-Net_Landmark-Aware_Learning_for_Reliable_Facial_Expression_Recognition_under_Label_ICCV_2023_paper.pdf)
* Combating Noisy Labels with Sample Selection by Mining High-Discrepancy Examples.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Combating_Noisy_Labels_with_Sample_Selection_by_Mining_High-Discrepancy_Examples_ICCV_2023_paper.pdf)[[Code]](https://github.com/xiaoboxia/CoDis)
* RankMatch: Fostering Confidence and Consistency in Learning with Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_RankMatch_Fostering_Confidence_and_Consistency_in_Learning_with_Noisy_Labels_ICCV_2023_paper.pdf)
* SILT: Shadow-Aware Iterative Label Tuning for Learning to Detect Shadows from Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_SILT_Shadow-Aware_Iterative_Label_Tuning_for_Learning_to_Detect_Shadows_ICCV_2023_paper.pdf)[[Code]](https://github.com/hanyangclarence/SILT)
* Graph Matching with Bi-level Noisy Correspondence.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Lin_Graph_Matching_with_Bi-level_Noisy_Correspondence_ICCV_2023_paper.pdf)[[Code]](https://github.com/XLearning-SCU/2023-ICCV-COMMON)
* Learning from Noisy Pseudo Labels for Semi-Supervised Temporal Action Localization.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Learning_from_Noisy_Pseudo_Labels_for_Semi-Supervised_Temporal_Action_Localization_ICCV_2023_paper.pdf)[[Code]](https://github.com/kunnxia/NPL)
* Label-Noise Learning with Intrinsically Long-Tailed Data.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Lu_Label-Noise_Learning_with_Intrinsically_Long-Tailed_Data_ICCV_2023_paper.pdf)
* Semi-Supervised Semantic Segmentation under Label Noise via Diverse Learning Groups.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Semi-Supervised_Semantic_Segmentation_under_Label_Noise_via_Diverse_Learning_Groups_ICCV_2023_paper.pdf)
* Holistic Label Correction for Noisy Multi-Label Classification.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Holistic_Label_Correction_for_Noisy_Multi-Label_Classification_ICCV_2023_paper.pdf)[[Code]](https://github.com/xiaoboxia/HLC)
* When Noisy Labels Meet Long Tail Dilemmas: A Representation Calibration Method.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_When_Noisy_Labels_Meet_Long_Tail_Dilemmas_A_Representation_Calibration_ICCV_2023_paper.pdf)
* Why Is Prompt Tuning for Vision-Language Models Robust to Noisy Labels?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_Why_Is_Prompt_Tuning_for_Vision-Language_Models_Robust_to_Noisy_ICCV_2023_paper.pdf)[[Code]](https://github.com/CEWu/PTNL)
* Learning from Noisy Data for Semi-Supervised 3D Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_Learning_from_Noisy_Data_for_Semi-Supervised_3D_Object_Detection_ICCV_2023_paper.pdf)[[Code]](https://github.com/zehuichen123/NoiseDet)
* LNPL-MIL: Learning from Noisy Pseudo Labels for Promoting Multiple Instance Learning in Whole Slide Image.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Shao_LNPL-MIL_Learning_from_Noisy_Pseudo_Labels_for_Promoting_Multiple_Instance_ICCV_2023_paper.pdf)[[Code]](https://github.com/szc19990412/LNPL-MIL)
* BoMD: Bag of Multi-label Descriptors for Noisy Chest X-ray Classification.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_BoMD_Bag_of_Multi-label_Descriptors_for_Noisy_Chest_X-ray_Classification_ICCV_2023_paper.pdf)[[Code]](https://github.com/cyh-0/BoMD)

---

### KDD 2023

* To Aggregate or Not? Learning with Separate Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2206.07181)
* DyGen: Learning from Noisy Labels via Dynamics-Enhanced Generative Modeling.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://dl.acm.org/doi/10.1145/3580305.3599318)[[Code]](https://github.com/night-chen/DyGen)
* Robust Positive-Unlabeled Learning via Noise Negative Sample Self-correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://dl.acm.org/doi/10.1145/3580305.3599491)
* Neural-Hidden-CRF: A Robust Weakly-Supervised Sequence Labeler.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://browse.arxiv.org/pdf/2309.05086.pdf)[[Code]](https://github.com/junchenzhi/Neural-Hidden-CRF)
* Complementary Classifier Induced Partial Label Learning.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2305.09897)[[Code]](https://github.com/Chongjie-Si/PL-CL)
* Partial-label Learning with Mixed Closed-Set and Open-Set Out-of-Candidate Examples.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2307.00553)
* Weakly Supervised Multi-Label Classification of Full-Text Scientific Papers.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2306.14003)[[Code]](https://github.com/yuzhimanhua/FUTEX)

---

### NeurIPS 2023

* AQuA: A Benchmarking Tool for Label Quality Assessment.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=dhJ8VbcEtX)
* Efficient Testable Learning of Halfspaces with Adversarial Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=mIm0hsUUt1)
* Robust Data Pruning under Label Noise via Maximizing Re-labeling Accuracy.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=xWCp0uLcpG)
* Subclass-Dominant Label Noise: A Counterexample for the Success of Early Stopping.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=kR21XsZeAr)[[Code]](https://github.com/tmllab/2023_NeurIPS_SDN)
* Label Correction of Crowdsourced Noisy Annotations with an Instance-Dependent Noise Transition Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=nFEQNYsjQO)
* Active Negative Loss Functions for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2023/poster/71501)[[Code]](https://github.com/Virusdoll/Active-Negative-Loss)
* Label-Retrieval-Augmented Diffusion Models for Learning from Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2305.19518)[[Code]](https://github.com/puar-playground/LRA-diffusion)
* Training shallow ReLU networks on noisy data using hinge loss: when do we overfit and is it benign?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2306.09955)
* CSOT: Curriculum and Structure-Aware Optimal Transport for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=y50AnAbKp1)[[Code]](https://github.com/changwxx/CSOT-for-LNL)
* Label Poisoning is All You Need.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2310.18933)[[Code]](https://github.com/SewoongLab/FLIP)
* IPMix: Label-Preserving Data Augmentation Method for Training Robust Classifiers.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=No52399wXA)
* Neural Relation Graph: A Unified Framework for Identifying Label Noise and Outlier Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2301.12321)[[Code]](https://github.com/snu-mllab/Neural-Relation-Graph)
* Scale-teaching: Robust Multi-scale Training for Time Series Classification with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=9D0fELXbrg)[[Code]](https://github.com/qianlima-lab/Scale-teaching)
* SoTTA: Robust Test-Time Adaptation on Noisy Data Streams.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2310.10074)[[Code]](https://github.com/taeckyung/SoTTA)
* Deep Insights into Noisy Pseudo Labeling on Graph Data.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=XhNlBvb4XV)
* ARTIC3D: Learning Robust Articulated 3D Shapes from Noisy Web Image Collections.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rJc5Lsn5QU)[[Code]](https://chhankyao.github.io/artic3d/)
* ALIM: Adjusting Label Importance Mechanism for Noisy Partial Label Learning.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=PYSfn5xXEe)[[Code]](https://github.com/zeroQiaoba/ALIM)
* Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2305.11003)[[Code]](https://github.com/ChunmingHe/WS-SAM)
* SLaM: Student-Label Mixing for Distillation with Unlabeled Examples.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=N7tw0QXx3z)
* HQA-Attack: Toward High Quality Black-Box Hard-Label Adversarial Attack on Text.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=IOuuLBrGJR)[[Code]](https://github.com/HQA-Attack/HQAAttack-demo)

---

### ICML 2023

* Identifiability of Label Noise Transition Matrix.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/liu23g)
* Which is Better for Learning with Noisy Labels: The Semi-supervised Method or Modeling Label Noise?
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/yao23a)
* Mitigating Memorization of Noisy Labels by Clipping the Model Prediction.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2212.04055)[[Code]](https://github.com/hongxin001/LogitClip)
* CrossSplit: Mitigating Label Noise Memorization through Data Splitting.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v202/kim23a/kim23a.pdf)[[Code]](https://github.com/SAITPublic/CrossSplit)
* Understanding Self-Distillation in the Presence of Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v202/das23d/das23d.pdf)
* Delving into Noisy Label Detection with Clean Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/yu23b.html)
* When does Privileged information Explain Away Label Noise?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/ortiz-jimenez23a)
* Deep Clustering with Incomplete Noisy Pairwise Annotations: A Geometric Regularization Approach.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/nguyen23d)
* Accelerating Exploration with Unlabeled Prior Data.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Itorzn4Kwf)

---

### CVPR 2023

* Twin Contrastive Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2303.06930)[[Code]](https://github.com/Hzzone/TCL)
* Learning from Noisy Labels with Decoupled Meta Label Purifier.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2302.06810)[[Code]](https://github.com/yuanpengtu/DMLP)
* DISC: Learning from Noisy Labels via Dynamic Instance-Specific Selection and Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_DISC_Learning_From_Noisy_Labels_via_Dynamic_Instance-Specific_Selection_and_CVPR_2023_paper.pdf)[[Code]](https://github.com/jackyfl/disc)
* Fine-Grained Classification with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wei_Fine-Grained_Classification_With_Noisy_Labels_CVPR_2023_paper.pdf)
* OT-Filter: An Optimal Transport Filter for Learning With Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Feng_OT-Filter_An_Optimal_Transport_Filter_for_Learning_With_Noisy_Labels_CVPR_2023_paper.pdf)
* Exploring High-Quality Pseudo Masks for Weakly Supervised Instance Segmentation.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2210.05174)[[Code]](https://github.com/hustvl/BoxTeacher)
* HandsOff: Labeled Dataset Generation with No Additional Human Annotations.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2212.12645.pdf)[[Code]](https://github.com/austinxu87/handsoff/)
* Leveraging Inter-Rater Agreement for Classification in the Presence of Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Bucarelli_Leveraging_Inter-Rater_Agreement_for_Classification_in_the_Presence_of_Noisy_CVPR_2023_paper.pdf)
* Collaborative Noisy Label Cleaner: Learning Scene-aware Trailers for Multi-modal Highlight Detection in Movies.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2303.14768)[[Code]](https://github.com/TencentYoutuResearch/HighlightDetection-CLC)
* MixTeacher: Mining Promising Labels with Mixed Scale Teacher for Semi-supervised Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2303.09061)[[Code]](https://github.com/lliuz/MixTeacher)
* Exploiting Completeness and Uncertainty of Pseudo Labels for Weakly Supervised Video Anomaly Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Exploiting_Completeness_and_Uncertainty_of_Pseudo_Labels_for_Weakly_Supervised_CVPR_2023_paper.pdf)[[Code]](https://github.com/ArielZc/CU-Net)
* Semi-Supervised 2D Human Pose Estimation Driven by Position Inconsistency Pseudo Label Correction Module.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Semi-Supervised_2D_Human_Pose_Estimation_Driven_by_Position_Inconsistency_Pseudo_CVPR_2023_paper.pdf)[[Code]](https://github.com/hlz0606/SSPCM)
* Learning with Noisy labels via Self-supervised Adversarial Noisy Masking.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Tu_Learning_With_Noisy_Labels_via_Self-Supervised_Adversarial_Noisy_Masking_CVPR_2023_paper.pdf)[[Code]](https://github.com/yuanpengtu/SANM)
* RONO: Robust Discriminative Learning with Noisy Labels for 2D-3D Cross-Modal Retrieval.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Feng_RONO_Robust_Discriminative_Learning_With_Noisy_Labels_for_2D-3D_Cross-Modal_CVPR_2023_paper.pdf)[[Code]](https://github.com/penghu-cs/RONO)

---

### ICLR 2023

* Distributionally Robust Post-hoc Classifiers under Prior Shifts.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=3KUfbI9_DQE)[[Code]](https://github.com/weijiaheng/Drops)
* Mitigating Memorization of Noisy Labels via Regularization between Representations.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=6qcYDVlVLnK)
* On the Edge of Benign Overfitting: Label Noise and Overparameterization Level.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=UrEwJebCxk)
* Memorization-Dilation: Modeling Neural Collapse Under Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=cJWxqmmDL2b)
* Quantifying and Mitigating the Impact of Label Errors on Model Disparity Metrics.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=RUzSobdYy0V)
* When Source-Free Domain Adaptation Meets Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=u2Pd6x794I)
* A law of adversarial risk, interpolation, and label noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=0_TxFpAsEI)
* SoftMatch: Addressing the Quantity-Quality Tradeoff in Semi-supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=ymt1zQXBDiF)
* Mitigating Dataset Bias by Using Per-Sample Gradient.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=7mgUec-7GMv)
* MCAL: Minimum Cost Human-Machine Active Labeling.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=1FxRPKrH8bw)
* Deep Learning From Crowdsourced Labels: Coupled Cross-Entropy Minimization, Identifiability, and Regularization.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=_qVhsWyWB9)
* CLIPSep: Learning Text-queried Sound Separation with Noisy Unlabeled Videos.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=H-T3F0dMbyj)
* Learning to Segment from Noisy Annotations: A Spatial Correction Approach.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=Qc_OopMEBnC)
* Mutual Partial Label Learning with Competitive Label Noise.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=EUrxG8IBCrC)
* Leveraging Unlabeled Data to Track Memorization .
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=ORp91sAbzI)
* CLIPSep: Learning Text-queried Sound Separation with Noisy Unlabeled Videos.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=H-T3F0dMbyj)
* Does Decentralized Learning with Non-IID Unlabeled Data Benefit from Self Supervision?.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=2L9gzS80tA4)
* Label Propagation with Weak Supervision .
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=aCuFa-RRqtI)
* Pushing the Accuracy-Group Robustness Frontier with Introspective Self-play.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=MofT9KEF0kw)
* Towards Lightweight, Model-Agnostic and Diversity-Aware Active Anomaly Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=-vKlt84fHs)
* Weakly Supervised Explainable Phrasal Reasoning with Neural Fuzzy Logic.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=Hu4r-dedqR0)
* Towards Addressing Label Skews in One-Shot Federated Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=rzrqh85f4Sc)
* Instance-wise Batch Label Restoration via Gradients in Federated Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=FIrQfNSOoTr)
* That Label's got Style: Handling Label Style Bias for Uncertain Image Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=wZ2SVhOTzBX)
* Learning Hyper Label Model for Programmatic Weak Supervision.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=aCQt_BrkSjC)
* Rhino: Deep Causal Temporal Relationship Learning with History-dependent Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=i_1rbq8yFWC)

---

### AAAI 2023

* Class-Independent Regularization for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v37i6.25890)

---

### ACM MM 2023

* PNT-Edge: Towards Robust Edge Detection with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3581783.3612412)
* Adaptive Contrastive Learning on Multimodal Transformer for Review Helpfulness Predictions with Multimodal Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multimodal](https://img.shields.io/badge/task-Multimodal-0F766E?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3581783.3612405)
* ALEX: Towards Effective Graph Transfer Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3581783.3611891)

---

### Top Journals 2023

* A Parametrical Model for Instance-Dependent Label Noise. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3301876)
* Noisy Label Learning With Provable Consistency for a Wider Family of Losses. (Published on TPAMI)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3296156)
* Regularly Truncated M-Estimators for Learning With Noisy Labels. (Published on TPAMI)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3347850)
* Learning to Learn From Noisy Labeled Data. (Published on TKDE)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TKDE.2023.3271677)
* Robust Point Cloud Segmentation With Noisy Annotations. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3233772)

## Papers & Code in 2022

---

### NeurIPS 2022

* Learning from Label Proportions by Learning with Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=cqyBfRwOTm1)
* Class-Dependent Label-Noise Learning with Cycle-Consistency Regularization.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=IvnoGKQuXi)
* Robustness to Label Noise Depends on the Shape of the Noise Distribution.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=AlpR6dzKjfy)
* Label Noise in Adversarial Training: A Novel Perspective to Study Robust Overfitting.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=9_O9mTLYJQp)
* Estimating Noise Transition Matrix with Label Correlations for Noisy Multi-Label Learning .
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=GwXrGy_vc8m)[[Code]](https://github.com/ShikunLi/Estimating_T_For_Noisy_Mutli-Labels)
* On Image Segmentation With Noisy Labels: Characterization and Volume Properties of the Optimal Solutions to Accuracy and Dice.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=WDS1M0gsfXk)
* SoftPatch: Unsupervised Anomaly Detection with Noisy Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=pIYYJflkhZ)

---

### ECCV 2022

* Neighborhood Collective Estimation for Noisy Label Identification and Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2208.03207)[[Code]](https://github.com/lijichang/LNL-NCE)
* Teaching with Soft Label Smoothing for Mitigating Noisy Labels in Facial Expressions.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720639.pdf)[[Code]](https://github.com/toharl/soft)
* Learn From All: Erasing Attention Consistency for Noisy Label Facial Expression Recognition.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.10299)[[Code]](https://github.com/zyh-uaiaaaa/Erasing-Attention-Consistency)
* Centrality and Consistency: Two-Stage Clean Samples Identification for Learning with Instance-Dependent Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.14476)[[Code]](https://github.com/uitrbn/TSCSI_IDN)
* Learning with Noisy Labels by Efficient Transition Matrix Estimation to Combat Label Miscorrection.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.14932)[[Code]](https://github.com/hyperconnect/FasTEN)
* Self-Filtering: A Noise-Aware Sample Selection for Label Noise with Confidence Penalization.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2208.11351)
* BoundaryFace: A mining framework with noise label self-correction for Face Recognition.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730092.pdf)[[Code]](https://gitee.com/swjtugx/classmate/tree/master/OurGroup/BoundaryFace)
* Active label correction using robust parameter update and entropy propagation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136810001.pdf)
* A data-centric approach for improving ambiguous labels with combined semi-supervised classification and clustering.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.16209)[[Code]](https://github.com/Emprime/dc3)

---

* Learning from Multiple Annotator Noisy Labels via Sample-wise Label Fusion.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136840402.pdf)[[Code]](https://github.com/zhengqigao/Learning-from-Multiple-Annotator-Noisy-Labels)
* Identifying Hard Noise in Long-Tailed Sample Distribution.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.13378)[[Code]](https://github.com/yxymessi/H2E-Framework)
* Embedding contrastive unsupervised features to cluster in- and out-of-distribution noise in corrupted image datasets.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.01573)[[Code]](https://github.com/PaulAlbert31/SNCF)
* WeLSA: Learning To Predict 6D Pose From Weakly Labeled Data Using Shape Alignment.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680633.pdf)
* Joint-Modal Label Denoising for Weakly-Supervised Audio-Visual Video Parsing.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2204.11573)[[Code]](https://github.com/MCG-NJU/JoMoLD)
* PseCo: Pseudo Labeling and Consistency Training for Semi-Supervised Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.16317)[[Code]](https://github.com/ligang-cs/PseCo)

### ICML 2022

* To Smooth or Not? When Label Smoothing Meets Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.04149)[[Code]](https://github.com/UCSC-REAL/negative-label-smoothing)
* Detecting Corrupted Labels Without Training a Model to Predict.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.06283)[[Code]](https://github.com/UCSC-REAL/SimiFeat)
* Beyond Images: Label Noise Transition Matrix Estimation for Tasks with Lower-Quality Features.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.01273)
* From Noisy Prediction to True Label: Noisy Prediction Calibration via Generative Model
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2205.00690)[[Code]](https://github.com/BaeHeeSun/NPC)
* Robust Training under Label Noise by Over-parameterization.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.14026)[[Code]](https://github.com/shengliu66/SOP)
* Estimating Instance-dependent Label-noise Transition Matrix using DNNs.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.13001)
* Transfer and Marginalize: Explaining Away Label Noise with Privileged Information.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.09244)
* Guaranteed Robust Deep Learning against Extreme Label Noise using Self-supervised Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
* Robust Meta-learning with Sampling Noise and Label Noise via Eigen-Reptile.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2206.01944v1.pdf)[[Code]](https://github.com/anfeather/eigen-reptile)
* Learning General Halfspaces with Adversarial Label Noise via Online Gradient Descent.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v162/diakonikolas22b.html)
* Guaranteed Robust Deep Learning against Extreme Label Noise using Self-supervised Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)

---

### CVPR 2022

* Selective-Supervised Contrastive Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.04181)[[Code]](https://github.com/ShikunLi/Sel-CL)
* Scalable Penalized Regression for Noise Detection in Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.07788)[[Code]](https://github.com/Yikai-Wang/SPR-LNL)
* Large-Scale Pre-training for Person Re-identification with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](http://arxiv.org/pdf/2203.16533)[[Code]](https://github.com/dengpanfu/luperson-nl)
* Adaptive Early-Learning Correction for Segmentation from Noisy Annotations.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.03740)[[Code]](https://github.com/Kangningthu/ADELE)

---

### ICLR 2022

* Learning with Noisy Labels Revisited: A Study Using Real-World Human Annotations.
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=TBWA6PLJZQm&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICLR.cc%2F2022%2FConference%2FAuthors%23your-submissions))[[Code]](https://github.com/zwzhu-d/cifar-10-100n)
* Resolving Training Biases via Influence-based Data Relabeling.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=EskfH0bwNVn)
* Sample Selection with Uncertainty of Losses for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=xENf4QUL4LW)
* An Information Fusion Approach to Learning with Instance-Dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=ecH2FKaARUp)
* Meta Discovery: Learning to Discover Novel Classes given Very Limited Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=MEpKGLsY8f)

---

* Contrastive Label Disambiguation for Partial Label Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=EhYjZy6e1gJ)

### AAAI 2022

* Noise-Robust Learning from Multiple Unsupervised Sources of Inferred Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20367)
* Deep Neural Networks Learn Meta-Structures from Noisy Labels in Semantic Segmentation.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20194)

---

### KDD 2022

* Communication-Efficient Robust Federated Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3534678.3539252)
* Adaptive Learning for Weakly Labeled Streams.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3534678.3539334)

---

### ACM MM 2022

* Early-Learning Regularized Contrastive Learning for Cross-Modal Retrieval with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3503161.3547809)

---

### Top Journals 2022

* Wasserstein Adversarial Regularization for Learning with Label Noise. (Published on TPAMI)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2022.3156685)
* Extended T: Learning With Mixed Closed-Set and Open-Set Noisy Labels. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2022.3180545)

---

### ArXiv 2022

* Identifiability of Label Noise Transition Matrix.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.02016)
* Constrained Instance and Class Reweighting for Robust Learning under Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.05428)
* AUGLOSS: A Learning Methodology for Real-World Dataset Corruption.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2206.02286.pdf)
* Do We Need to Penalize Variance of Losses for Learning with Label Noise?.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.12739)
* Robust Training under Label Noise by Over-parameterization.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.14026)[[Code]](https://github.com/shengliu66/SOP)
* On Learning Contrastive Representations for Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.01785)
* Learning from Label Proportions by Learning with Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.02496)
* Benign Overfitting without Linearity: Neural Network Classifiers Trained by Gradient Descent for Noisy Linear Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.05928#:~:text=11%20Feb%202022%5D-,Benign%20Overfitting%20without%20Linearity%3A%20Neural%20Network%20Classifiers%20Trained%20by,Descent%20for%20Noisy%20Linear%20Data&text=Abstract%3A%20Benign%20overfitting%2C%20the%20phenomenon,models%20trained%20with%20gradient%20descent.)
* Synergistic Network Learning and Label Correction for Noise-robust Image Classification.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.13472)
* Transfer and Marginalize: Explaining Away Label Noise with Privileged Information.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.09244)
* Convolutional Network Fabric Pruning With Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.07268)
* Learning to Bootstrap for Combating Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.04291)
* Learning with Neighbor Consistency for Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.02200)
* Investigating Why Contrastive Learning Benefits Robustness Against Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.12498)
* PARS: Pseudo-Label Aware Robust Sample Selection for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.10836)
* GMM Discriminant Analysis with Noisy Label for Each Class.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.10242)
* Two Wrongs Don't Make a Right: Combating Confirmation Bias in Learning with Label Noise.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2112.02960)

---

* To Aggregate or Not? Learning with Separate Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2206.07181)
* Learning with Label Noise for Image Retrieval by Selecting Interactions.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2112.10453)

## Papers & Code in 2021

### NeurIPS 2021

* Can Less be More? When Increasing-to-Balancing Label Noise Rates Considered Beneficial.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2107.05913#:~:text=We%20are%20primarily%20inspired%20by,fairness%20guarantees%20against%20label%20bias.)[[Code]](https://github.com/UCSC-REAL/CanLessBeMore)
* Generalized Jensen-Shannon Divergence Loss for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.04522)[[Code]](https://github.com/ErikEnglesson/GJS)
* Understanding and Improving Early Stopping for Learning with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.15853)[[Code]](https://github.com/tmllab/PES)
* How does a Neural Network's Architecture Impact its Robustness to Noisy Labels?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Ir-WwGboFN-)[[Code]](https://github.com/jinglingli/alignment_noisy_label)
* FINE Samples for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.11628v3.pdf)[[Code]](https://github.com/Kthyeon/FINE_official)
* Label Noise SGD Provably Prefers Flat Global Minimizers.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.06530)[[Code]](https://github.com/adamian98/LabelNoiseFlatMinimizers)
* Improved Regularization and Robustness for Fine-tuning in Neural Networks.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=QX32YlxrQJc)[[Code]](https://github.com/NEU-StatsML-Research/Regularized-Self-Labeling)
* Instance-dependent Label-noise Learning under a Structural Causal Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2109.02986)
* Combating Noise: Semi-supervised Learning by Region Uncertainty Quantification.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.00928)
* DP-SSL: Towards Robust Semi-supervised Learning with A Few Labeled Samples.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.13740)
* Corruption Robust Active Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Ruw3MHL9jAO)

---

* Open-set Label Noise Can Improve Robustness Against Inherent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.10891)[[Code]](https://github.com/hongxin001/ODNL)

### KDD 2021

* Robust Learning by Self-Transition for Handling Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3447548.3467222)

---

* NRGNN: Learning a Label Noise Resistant Graph Neural Network on Sparsely and Noisily Labeled Graphs.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3447548.3467364)

### ACM MM 2021

* Co-learning: Learning from Noisy Labels with Self-supervision.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3474085.3475622)

---

### IJCAI 2021

* Towards Understanding Deep Learning from Noisy Labels with Small-Loss Criterion.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2021/0340.pdf)
* Modeling Noisy Hierarchical Types in Fine-Grained Entity Typing: A Content-Based Weighting Approach.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2019/0731.pdf)
* Multi-level Generative Models for Partial Label Learning with Non-random Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2021/0449.pdf)

---

### ICML 2021

* The importance of understanding instance-level noisy labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.05336.pdf)
* Clusterability as an Alternative to Anchor Points When Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.05291.pdf)[[Code]](https://github.com/zwzhu-d/HOC)
* Learning Noise Transition Matrix from Only Noisy Labels via Total Variation Regularization.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.02414v2.pdf)[[Code]](https://github.com/YivanZhang/lio)
* Class2Simi: A Noise Reduction Perspective on Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2006.07831)
* Provably End-to-end Label-noise Learning without Anchor Points.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.02400.pdf)
* Asymmetric Loss Functions for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2106.03110v1.pdf)[[Code]](https://github.com/hitcszx/ALFs)
* Confidence Scores Make Instance-dependent Label-noise Learning Possible.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2001.03772)
* Provable Generalization of SGD-trained Neural Networks of Any Width in the Presence of Adversarial Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2101.01152)
* Wasserstein Distributional Normalization For Robust Distributional Certification of Noisy Labeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v139/park21a/park21a.pdf)
* Learning from Noisy Labels with No Change to the Training Process.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v139/zhang21k/zhang21k.pdf)

---

* Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.05918v2.pdf)[[Code]](https://github.com/MicPie/clasp)

### ICLR 2021

* When Optimizing f-Divergence is Robust with Label Noise.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=WesiCoRVQ15)[[Code]](https://github.com/weijiaheng/Robust-f-divergence-measures)
* Learning with Instance-Dependent Label Noise: A Sample Sieve Approach.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=2VXyy9mIyU3)[[Code]](https://github.com/haochenglouis/cores)
* Noise against noise: stochastic label noise helps combat inherent label noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=80FMcTSZ6J0)[[Code]](https://github.com/chenpf1025/SLN)
* Learning with Feature-Dependent Label Noise: A Progressive Approach.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=ZPa2SyGcbwh)[[Code]](https://github.com/pxiangwu/PLC)
* Robust early-learning: Hindering the memorization of noisy labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=Eql5b1_hTE4)[[Code]](https://github.com/xiaoboxia/CDR)
* Robust Curriculum Learning: from clean label detection to noisy label self-correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=lmTWnm3coJJ)
* How Does Mixup Help With Robustness and Generalization?
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=8yKEo06dKNo)
* MoPro: Webly Supervised Learning with Momentum Prototypes.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=0-EYBhgw80y) [[Code]](https://github.com/salesforce/MoPro)
* Theoretical Analysis of Self-Training with Deep Networks on Unlabeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=rC8sJ4i6kaH)

---

### CVPR 2021

* A Second-Order Approach to Learning with Instance-Dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.11854)[[Code]](https://github.com/UCSC-REAL/CAL)
* Improving Unsupervised Image Clustering With Robust Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.11150)
* Multi-Objective Interpolation Training for Robustness to Label Noise.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.04462)[[Code]](https://git.io/JI40X)
* Noise-resistant Deep Metric Learning with Ranking-based Instance Selection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.16047)[[Code]](https://github.com/alibaba-edu/Ranking-based-Instance-Selection)
* Augmentation Strategies for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.02130)[[Code]](https://github.com/KentoNishi/Augmentation-for-LNL)
* Jo-SRC: A Contrastive Approach for Combating Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.13029.pdf)[[Code]](https://github.com/NUST-Machine-Intelligence-Laboratory/Jo-SRC)
* Multi-Objective Interpolation Training for Robustness to Label Noise.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.04462)[[Code]](https://github.com/DiegoOrtego/LabelNoiseMOIT)
* Partially View-aligned Representation Learning with Noise-robust Contrastive Loss.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Partially_View-Aligned_Representation_Learning_With_Noise-Robust_Contrastive_Loss_CVPR_2021_paper.pdf)[[Code]](https://github.com/XLearning-SCU/2021-CVPR-MvCLN)
* Correlated Input-Dependent Label Noise in Large-Scale Image Classification.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.10305)
* DAT: Training Deep Networks Robust To Label-Noise by Matching the Feature Distributions.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Qu_DAT_Training_Deep_Networks_Robust_To_Label-Noise_by_Matching_the_CVPR_2021_paper.pdf)
* Faster Meta Update Strategy for Noise-Robust Deep Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://github.com/youjiangxu/FaMUS/tree/main/paper)[[Code]](https://github.com/youjiangxu/FaMUS)
* Joint Negative and Positive Learning for Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.06574)
* Faster Meta Update Strategy for Noise-Robust Deep Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.15092)
* AutoDO: Robust AutoAugment for Biased Data with Label Noise via Scalable Probabilistic Implicit Differentiation.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.05863)[[Code]](https://github.com/gudovskiy/autodo)
* All Labels Are Not Created Equal: Enhancing Semi-supervision via Label Grouping and Co-training.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.05248)[[Code]](https://github.com/islam-nassar/semco)
* DualGraph: A graph-based method for reasoning about label noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_DualGraph_A_Graph-Based_Method_for_Reasoning_About_Label_Noise_CVPR_2021_paper.pdf)
* Background-Aware Pooling and Noise-Aware Loss for Weakly-Supervised Semantic Segmentation.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.00905)
* Meta Pseudo Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2003.10580.pdf)[[Code]](https://github.com/google-research/google-research/tree/master/meta_pseudo_labels)
* SimPLE: Similar Pseudo Label Exploitation for Semi-Supervised Classification.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.16725)[[Code]](https://github.com/zijian-hu/SimPLE)

---

### AAAI 2021

* Beyond Class-Conditional Assumption: A Primary Attempt to Combat Instance-Dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.05458)[[Code]](https://github.com/chenpf1025/IDN)
* Learning to Purify Noisy Labels via Meta Soft Label Corrector.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2008.00627)[[Code]](https://github.com/WuYichen-97/Learning-to-Purify-Noisy-Labels-via-Meta-Soft-Label-Corrector)
* Robustness of Accuracy Metric and its Inspirations in Learning with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.04193)[[Code]](https://github.com/chenpf1025/RobustnessAccuracy)
* Learning from Noisy Labels with Complementary Loss Functions.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://palm.seu.edu.cn/zhangml/files/AAAI'21a.pdf)[[Code]](https://github.com/dengbaowang/CompLossForNoisyLabels)
* Analysing the Noise Model Error for Realistic Noisy Label Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2101.09763)[[Code]](https://github.com/uds-lsv/noise-estimation)
* Tackling Instance-Dependent Label Noise via a Universal Probabilistic Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://niug1984.github.io/paper/wang_aaai21.pdf)
* Learning with Group Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://gcatnjust.github.io/ChenGong/paper/wang_aaai21_2.pdf)
* Meta Label Correction for Noisy Label Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.microsoft.com/en-us/research/publication/meta-label-correction-for-noisy-label-learning/)

---

### Other Conferences 2021

* (ICCV 2021) Learning with Noisy Labels via Sparse Regularization.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2108.00192)
* (WACV 2022) Towards a Robust Differentiable Architecture Search under Label Noise.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.12197)
* (BMVC 2021) PropMix: Hard Sample Filtering and Proportional MixUp for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.11809)[[Code]](https://github.com/filipe-research/PropMix.)
* (IJCAI2021 Workshop) An Ensemble Noise-Robust K-fold Cross-Validation Selection Method for Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2107.02347)

---

* (ICCV 2021) Learning with Noisy Labels for Robust Point Cloud Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://shuquanye.com/PNAL_website/)[[Code]](https://github.com/pleaseconnectwifi/PNAL)
* (WACV 2022) Addressing out-of-distribution label noise in webly-labelled data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.13699)[[Code]](https://github.com/PaulAlbert31/DSOS)

### ArXiv 2021

* Understanding Generalized Label Smoothing when Learning with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.04149)
* A Good Representation Detects Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.06283.pdf)
* Demystifying How Self-Supervised Features Improve Training from Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.09022.pdf)[[code]](https://github.com/UCSC-REAL/SelfSup_NoisyLabel)
* Pervasive Label Errors in Test Sets Destabilize Machine Learning Benchmarks.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.14749)[[Code]](https://github.com/cgnorthcutt/label-errors)
* Double Descent in Adversarial Training: An Implicit Label Noise Perspective.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.03135.pdf)
* Estimating Instance-dependent Label-noise Transition Matrix using DNNs.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.13001)
* A Theoretical Analysis of Learning with Noisily Labeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.04114)
* Sample Selection with Uncertainty of Losses for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.00445)
* Analysis of classifiers robust to noisy labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.00274)
* NoiLIn: Do Noisy Labels Always Hurt Adversarial Training?
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.14676)
* Alleviating Noisy-label Effects in Image Classification via Probability Transition Matrix.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.08866)
* Learning with Noisy Labels by Targeted Relabeling.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.08355)
* Simple Attention Module based Speaker Verification with Iterative noisy label detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.06534)
* Adaptive Hierarchical Similarity Metric Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.00006)
* A Survey of Label-noise Representation Learning: Past, Present and Future.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2011.04406.pdf)
* Noisy-Labeled NER with Confidence Estimation.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.04318.pdf)[[Code]](https://github.com/liukun95/Noisy-NER-Confidence-Estimation)
* Contrast to Divide: Self-Supervised Pre-Training for Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.13646.pdf)[[Code]](https://github.com/ContrastToDivide/C2D)
* Exponentiated Gradient Reweighting for Robust Training Under Label Noise and Beyond.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.01493.pdf)
* Understanding the Interaction of Adversarial Training with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.03482.pdf)
* Learning from Noisy Labels via Dynamic Loss Thresholding.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.02570.pdf)
* Self-Supervised Noisy Label Learning for Source-Free Unsupervised Domain Adaptation.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.11614.pdf)
* Transform consistency for learning with noisy labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.13872.pdf)
* Learning to Combat Noisy Labels via Classification Margins.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.00751.pdf)
* Joint Negative and Positive Learning for Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.06574.pdf)
* DST: Data Selection and joint Training for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.00813.pdf)
* LongReMix: Robust Learning with High Confidence Samples in a Noisy Label Environment.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.04173.pdf)
* Ensemble Learning with Manifold-Based Data Splitting for Noisy Label Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.07641.pdf)
* MetaLabelNet: Learning to Generate Soft-Labels from Noisy-Labels.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.10869.pdf)
* On the Robustness of Monte Carlo Dropout Trained with Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.12002.pdf)
* Co-matching: Combating Noisy Labels by Augmentation Anchoring.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.12814.pdf)
* Approximating Instance-Dependent Noise via Instance-Confidence Embedding.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.13569)
* Rethinking Noisy Label Models: Labeler-Dependent Noise with Adversarial Awareness.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.14083)
* ScanMix: Learning from Severe Label Noise viaSemantic Clustering and Semi-Supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.11395)
* Friends and Foes in Learning from Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.15055.pdf)
* A Fremework Using Contrastive Learning for Classification with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.09563.pdf)
* Contrastive Learning Improves Model Robustness Under Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.08984.pdf)[[Code]](https://github.com/arghosh/noisy_label_pretrain)
* Noise-Resistant Deep Metric Learning with Probabilistic Instance Filtering.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.01431.pdf)
* Compensation Learning.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.11921.pdf)
* kNet: A Deep kNN Network To Handle Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.09735.pdf)
* Memorization in Deep Neural Networks: Does the Loss Function matter?.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.09957.pdf)
* Mitigating Memorization in Sample Selection for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.07041.pdf)
* P-DIFF: Learning Classifier with Noisy Labels based on Probability Difference Distributions.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2009.06382)[[Code]](https://github.com/fistyee/P-DIFF)
* Decoupling Representation and Classifier for Noisy Label Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2011.08145.pdf)
* Contrastive Representations for Label Noise Require Fine-Tuning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.09154.pdf)
* NGC: A Unified Framework for Learning with Open-World Noisy Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.11035.pdf)
* Instance-dependent Label-noise Learning under a Structural Causal Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2109.02986.pdf)
* Assessing the Quality of the Datasets by Identifying Mislabeled Samples.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2109.05000.pdf)
* Learning to Aggregate and Refine Noisy Labels for Visual Sentiment Analysis.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2109.07509)
* Robustness and reliability when training with noisy labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.03321.pdf)
* Consistency Regularization Can Improve Robustness to Label Noise.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.01242.pdf)

---

* Learning from Multiple Annotators by Incorporating Instance Features.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.15146)
* Learning from Multiple Noisy Partial Labelers.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.04530)
* Instance Correction for Learning with Open-set Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.00455)
* Adaptive Early-Learning Correction for Segmentation from Noisy Annotations.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.03740)
* Robust Deep Learning from Crowds with Belief Propagation.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.00734)
* Prototypical Classifier for Robust Class-Imbalanced Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.11553)
* Study Group Learning: Improving Retinal Vessel Segmentation Trained with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.03451.pdf)[[Code]](https://github.com/SHI-Labs/SGL-Retinal-Vessel-Segmentation)
* Evaluating Multi-label Classifiers with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.08427.pdf)
* Robust Classification from Noisy Labels: Integrating Additional Knowledge for Chest Radiography Abnormality Assessment.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.05261.pdf)
* A Novel Perspective for Positive-Unlabeled Learning via Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.04685.pdf)
* Pathological Image Segmentation with Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.02602.pdf)
* CrowdTeacher: Robust Co-teaching with Noisy Answers & Sample-specific Perturbations for Tabular Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.17144.pdf)
* Learning from Noisy Labels for Entity-Centric Information Extraction.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.08656.pdf)
* Temporal-aware Language Representation Learning From Crowdsourced Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.07958.pdf)
* Learning From Long-Tailed Data With Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.11096.pdf)
* Robust Long-Tailed Learning Under Label Noise.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.11569.pdf)
* Robust Temporal Ensembling for Learning with Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2109.14563.pdf)
* Knowledge Distillation with Noisy Labels for Natural Language Understanding.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2109.10147.pdf)
* Noisy Annotations Robust Consensual Collaborative Affect Expression Recognition.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021W/ABAW/papers/Gera_Noisy_Annotations_Robust_Consensual_Collaborative_Affect_Expression_Recognition_ICCVW_2021_paper.pdf)

## Papers & Code in 2020

---

### ICML 2020

* Peer Loss Functions: Learning from Noisy Labels without Knowing Noise Rates.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/liu20e)[[Code 1]](https://github.com/weijiaheng/Multi-class-Peer-Loss-functions) [[Code 2]](https://github.com/gohsyi/PeerLoss)
* Normalized Loss Functions for Deep Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2006.13554)[[Code]](https://github.com/HanxunH/Active-Passive-Losses)
* SIGUA: Forgetting May Make Learning with Noisy Labels More Robust.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/han20c.html)[[Code]](https://github.com/bhanML/SIGUA)
* Error-Bounded Correction of Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/zheng20c.html)[[Code]](https://github.com/pingqingsheng/LRT)
* Training Binary Neural Networks through Learning with Noisy Supervision.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/han20d.html)[[Code]](https://github.com/zhaohui-yang/Binary-Neural-Networks)
* Improving generalization by controlling label-noise information in neural network weights.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/harutyunyan20a.html)[[Code]](https://github.com/hrayrhar/limit-label-memorization)
* Searching to Exploit Memorization Effect in Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/yao20b.html)[[Code]](https://github.com/jerermyyoung/rtlearning)
* Learning with Bounded Instance and Label-dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/cheng20c.html)
* Label-Noise Robust Domain Adaptation.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/yu20c.html)
* Beyond Synthetic Noise: Deep Learning on Controlled Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/jiang20c)
* Does label smoothing mitigate label noise?.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/lukasik20a.html)
* Deep k-NN for Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/bahri20a.html)
* Self-PU: Self Boosted and Calibrated Positive-Unlabeled Training.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2006.11280)[[Code]](https://github.com/VITA-Group/Self-PU)
* Learning with Multiple Complementary Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/feng20a.html)
* Extreme Multi-label Classification from Aggregated Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/shen20f.html)

---

### ICLR 2020

* DivideMix: Learning with Noisy Labels as Semi-supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=HJgExaVtwr)[[Code]](https://github.com/LiJunnan1992/DivideMix)
* Learning from Rules Generalizing Labeled Exemplars.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=SkeuexBtDr) [[Code]](https://github.com/awasthiabhijeet/Learning-From-Rules)
* Robust training with ensemble consensus.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=ryxOUTVYDH)[[Code]](https://github.com/jisoolee0123/Robust-training-with-ensemble-consensus)
* Self-labelling via simultaneous clustering and representation learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Hyx-jyBFPr)[[Code]](https://github.com/yukimasano/self-label)
* Can gradient clipping mitigate label noise?
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rklB76EKPr)[[Code]](https://github.com/dmizr/phuber)
* Curriculum Loss: Robust Learning and Generalization against Label Corruption.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rkgt0REKwS)
* Simple and Effective Regularization Methods for Training on Noisily Labeled Data with Generalization Guarantee.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Hke3gyHYwH)
* SELF: Learning to Filter Noisy Labels with Self-Ensembling.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=HkgsPhNYPS)

---

* Mutual Mean-Teaching: Pseudo Label Refinery for Unsupervised Domain Adaptation on Person Re-identification.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rJlnOhVYPS)[[Code]](https://github.com/yxgeee/MMT)

### NIPS 2020

* Part-dependent Label Noise: Towards Instance-dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/5607fe8879e4fd269e88387e8cb30b7e-Abstract.html)[[Code]](https://github.com/xiaoboxia/Part-dependent-label-noise)
* Identifying Mislabeled Data using the Area Under the Margin Ranking.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/c6102b3727b2a7d8b1bb6981147081ef-Abstract.html)[[Code]](https://github.com/asappresearch/aum)
* Dual T: Reducing Estimation Error for Transition Matrix in Label-noise Learning.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/512c5cad6c37edb98ae91c8a76c3a291-Abstract.html)
* Early-Learning Regularization Prevents Memorization of Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/ea89621bee7c88b2c5be6681c8ef4906-Abstract.html)[[Code]](https://github.com/shengliu66/ELR)
* Coresets for Robust Training of Deep Neural Networks against Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/8493eeaccb772c0878f99d60a0bd2bb3-Abstract.html)[[Code]](https://github.com/snap-stanford/crust)
* Robust Optimization for Fairness with Noisy Protected Groups.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/37d097caf1299d9aa79c2c2b843d2d78-Abstract.html)[[Code]](https://github.com/wenshuoguo/robust-fairness-code)
* Stochastic Optimization with Heavy-Tailed Noise via Accelerated Gradient Clipping.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/abd1c782880cc59759f4112fda0b8f98-Abstract.html)[[Code]](https://github.com/eduardgorbunov/accelerated_clipping)
* A Topological Filter for Learning with Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/f4e3ce3e7b581ff32e40968298ba013d-Abstract.html)[[Code]](https://github.com/pxiangwu/TopoFilter)
* Self-Adaptive Training: beyond Empirical Risk Minimization.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc//paper/2020/hash/e0ab531ec312161511493b002f9be2ee-Abstract.html)[[Code]](https://github.com/LayneH/self-adaptive-training)
* Non-Convex SGD Learns Halfspaces with Adversarial Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/d785bf9067f8af9e078b93cf26de2b54-Abstract.html)
* Efficient active learning of sparse halfspaces with arbitrary bounded noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/5034a5d62f91942d2a7aeaf527dfe111-Abstract.html)
* MetaPoison: Practical General-purpose Clean-label Data Poisoning.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/8ce6fc704072e351679ac97d4a985574-Abstract.html)[[Code 1]](https://github.com/wronnyhuang/metapoison)[[Code]](https://github.com/JonasGeiping/poisoning-gradient-matching)
* Provably Consistent Partial-Label Learning.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/7bd28f15a49d5e5848d6ec70e584e625-Abstract.html)
* Modeling Noisy Annotations for Crowd Counting.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/22bb543b251c39ccdad8063d486987bb-Abstract.html)[[Code]](https://github.com/jia-wan/NoisyCC-pytorch)
* Disentangling Human Error from the Ground Truth in Segmentation of Medical Images.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc//paper/2020/file/b5d17ed2b502da15aa727af0d51508d6-Paper.pdf)[[Code]](https://github.com/moucheng2017/Learn_Noisy_Labels_Medical_Images)
* Semi-Supervised Partial Label Learning via Confidence-Rated Margin Maximization.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/4dea382d82666332fb564f2e711cbc71-Abstract.html)
* Labelling unlabelled videos from scratch with multi-modal self-supervision.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/31fefc0e570cb3860f2a6d4b38c6490d-Abstract.html)[[Code]](https://github.com/facebookresearch/selavi)
* Distribution Aligning Refinery of Pseudo-label for Imbalanced Semi-supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/a7968b4339a1b85b7dbdb362dc44f9c4-Abstract.html)[[Code]](https://github.com/bbuing9/DARP)
* A Variational Approach for Learning from Positive and Unlabeled Data.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/aa0d2a804a3510442f2fd40f2100b054-Abstract.html)[[Code]](https://github.com/HC-Feynman/vpu)

---

### KDD 2020

* Semi-Supervised Multi-Label Learning from Crowds via Deep Sequential Generative Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3394486.3403167)

---

### AAAI 2020

* Reinforcement Learning with Perturbed Rewards.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/1810.01032) [[Code]](https://github.com/wangjksjtu/rl-perturbed-reward)
* Less Is Better: Unweighted Data Subsampling via Influence Function.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/1912.01321) [[Code]](https://github.com/RyanWangZf/Influence_Subsampling)
* Self-Paced Robust Learning for Leveraging Clean Labels in Noisy Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://xuczhang.github.io/papers/aaai20_sprl.pdf)
* Label Error Correction and Generation Through Label Relationships.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5778)

---

* Weakly Supervised Sequence Tagging from Noisy Rules.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/6009)[[Code]](https://github.com/BatsResearch/wiser)
* Coupled-View Deep Classifier Learning from Multiple Noisy Annotators.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5898)
* Partial multi-label learning with noisy label identification.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](http://www.xiemk.pro/publication/aaai20-pml-ni.pdf)

### CVPR 2020

* Combating noisy labels by agreement: A joint training method with co-regularization.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Wei_Combating_Noisy_Labels_by_Agreement_A_Joint_Training_Method_with_CVPR_2020_paper.html)[[Code]](https://github.com/hongxin001/JoCoR)
* Distilling Effective Supervision From Severe Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Distilling_Effective_Supervision_From_Severe_Label_Noise_CVPR_2020_paper.html)[[Code]](https://github.com/google-research/google-research/tree/master/ieg)
* Self-Training With Noisy Student Improves ImageNet Classification.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Xie_Self-Training_With_Noisy_Student_Improves_ImageNet_Classification_CVPR_2020_paper.html)[[Code]](https://github.com/google-research/noisystudent)
* Global-Local GCN: Large-Scale Label Noise Cleansing for Face Recognition.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Global-Local_GCN_Large-Scale_Label_Noise_Cleansing_for_Face_Recognition_CVPR_2020_paper.html)
* Spherical Space Domain Adaptation With Robust Pseudo-Label Loss.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.html)[[Code]](https://github.com/XJTU-XGU/RSDA)
* Training Noise-Robust Deep Neural Networks via Meta-Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Meta-learning](https://img.shields.io/badge/Meta--learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Training_Noise-Robust_Deep_Neural_Networks_via_Meta-Learning_CVPR_2020_paper.html)[[Code]](https://github.com/ZhenWang-PhD/Training-Noise-Robust-Deep-Neural-Networks-via-Meta-Learning)
* Generating Accurate Pseudo-Labels in Semi-Supervised Learning and Avoiding Overconfident Predictions via Hermite Polynomial Activations.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lokhande_Generating_Accurate_Pseudo-Labels_in_Semi-Supervised_Learning_and_Avoiding_Overconfident_Predictions_CVPR_2020_paper.html)[[Code]](https://github.com/lokhande-vishnu/DeepHermites)
* Revisiting Knowledge Distillation via Label Smoothing Regularization.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Yuan_Revisiting_Knowledge_Distillation_via_Label_Smoothing_Regularization_CVPR_2020_paper.html)[[Code]](https://github.com/yuanli2333/Teacher-free-Knowledge-Distillation)

---

* Noise Robust Generative Adversarial Networks.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Kaneko_Noise_Robust_Generative_Adversarial_Networks_CVPR_2020_paper.html)[[Code]](https://github.com/takuhirok/NR-GAN/)
* DLWL: Improving Detection for Lowshot Classes With Weakly Labelled Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Ramanathan_DLWL_Improving_Detection_for_Lowshot_Classes_With_Weakly_Labelled_Data_CVPR_2020_paper.html)
* Shoestring: Graph-Based Semi-Supervised Classification With Severely Limited Labeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lin_Shoestring_Graph-Based_Semi-Supervised_Classification_With_Severely_Limited_Labeled_Data_CVPR_2020_paper.html)[[Code]](https://github.com/iQua/CVPR2020-Shoestring)
* Noise-Aware Fully Webly Supervised Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Shen_Noise-Aware_Fully_Webly_Supervised_Object_Detection_CVPR_2020_paper.html)[[Code]](https://github.com/shenyunhang/NA-fWebSOD)
* Learning From Noisy Anchors for One-Stage Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_Learning_From_Noisy_Anchors_for_One-Stage_Object_Detection_CVPR_2020_paper.html)[[Code]](https://github.com/henrylee2570/NoisyAnchor)

### ECCV 2020

* 2020-ECCV - Suppressing Mislabeled Data via Grouping and Self-Attention.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2633_ECCV_2020_paper.php)[[Code]](https://github.com/kaiwang960112/AFM)
* 2020-ECCV - NoiseRank: Unsupervised Label Noise Reduction with Dependence Models.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/5921_ECCV_2020_paper.php)
* 2020-ECCV - Learning with Noisy Class Labels for Instance Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2062_ECCV_2020_paper.php)[[Code]](https://github.com/longrongyang/LNCIS)
* 2020-ECCV - Weakly Supervised Learning with Side Information for Noisy Labeled Images.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/7467_ECCV_2020_paper.php)
* 2020-ECCV - Learning Noise-Aware Encoder-Decoder from Noisy Labels by Alternating Back-Propagation for Saliency Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2760_ECCV_2020_paper.php)
* 2020-ECCV - Graph convolutional networks for learning with few clean and many noisy labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1060_ECCV_2020_paper.php)

---

### ArXiv 2020

* No Regret Sample Selection with Noisy Labels. (Published on Machine Learning)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2003.03179.pdf)[[Code]](https://github.com/songheony/TAkS)
* Meta Soft Label Generation for Noisy Labels. (Published on ICPR 2020)
  ![Meta-learning](https://img.shields.io/badge/Meta--learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2007.05836.pdf)[[Code]](https://github.com/gorkemalgan/MSLG_noisy_label)
* Learning from Noisy Labels with Deep Neural Networks: A Survey.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2007.08199.pdf)
* RAR-U-Net: a Residual Encoder to Attention Decoder by Residual Connections Framework for Spine Segmentation under Noisy Labels. (Published on ICIP 2021)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2009.12873.pdf)
* Learning from Small Amount of Medical Data with Noisy Labels: A Meta-Learning Approach. (Published on ICRPOA 2021)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Meta-learning](https://img.shields.io/badge/Meta--learning-A855F7)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2010.06939.pdf)

---

## Acknowledgements

This repository is partially based on and inspired by the following project:

- https://github.com/weijiaheng/Advances-in-Label-Noise-Learning
