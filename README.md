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
![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
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

<!-- TASK_TYPE_INDEX_START -->
## Task Type Quick Index

> Paper numbers are clickable and jump to the corresponding entries below. Classification LNL is omitted here because it contains many entries.

### Long-tailed Learning (12)
![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)

[P014](#paper-014), [P029](#paper-029), [P050](#paper-050), [P072](#paper-072), [P114](#paper-114), [P117](#paper-117), [P189](#paper-189), [P223](#paper-223), [P389](#paper-389), [P398](#paper-398), [P399](#paper-399), [P444](#paper-444)

### Multi-Label (10)
![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)

[P018](#paper-018), [P039](#paper-039), [P116](#paper-116), [P121](#paper-121), [P128](#paper-128), [P210](#paper-210), [P391](#paper-391), [P417](#paper-417), [P446](#paper-446), [P453](#paper-453)

### Graph Data (12)
![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)

[P023](#paper-023), [P052](#paper-052), [P071](#paper-071), [P077](#paper-077), [P092](#paper-092), [P112](#paper-112), [P143](#paper-143), [P200](#paper-200), [P282](#paper-282), [P321](#paper-321), [P464](#paper-464), [P472](#paper-472)

### Object Detection (6)
![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)

[P024](#paper-024), [P119](#paper-119), [P167](#paper-167), [P227](#paper-227), [P465](#paper-465), [P466](#paper-466)

### Segmentation (22)
![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)

[P031](#paper-031), [P040](#paper-040), [P068](#paper-068), [P111](#paper-111), [P115](#paper-115), [P146](#paper-146), [P163](#paper-163), [P183](#paper-183), [P194](#paper-194), [P198](#paper-198), [P205](#paper-205), [P211](#paper-211), [P241](#paper-241), [P249](#paper-249), [P322](#paper-322), [P337](#paper-337), [P390](#paper-390), [P394](#paper-394), [P441](#paper-441), [P469](#paper-469), [P471](#paper-471), [P476](#paper-476)

### NLP/Text (9)
![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)

[P004](#paper-004), [P053](#paper-053), [P058](#paper-058), [P093](#paper-093), [P095](#paper-095), [P148](#paper-148), [P285](#paper-285), [P396](#paper-396), [P401](#paper-401)

### Vision-Language (10)
![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)

[P010](#paper-010), [P037](#paper-037), [P038](#paper-038), [P066](#paper-066), [P094](#paper-094), [P098](#paper-098), [P118](#paper-118), [P182](#paper-182), [P186](#paper-186), [P297](#paper-297)

### Multimodal (1)
![Multimodal](https://img.shields.io/badge/task-Multimodal-0F766E?style=flat-square)

[P199](#paper-199)

### LLM Alignment (8)
![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)

[P007](#paper-007), [P035](#paper-035), [P065](#paper-065), [P067](#paper-067), [P073](#paper-073), [P078](#paper-078), [P080](#paper-080), [P225](#paper-225)

### Medical Imaging (5)
![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)

[P041](#paper-041), [P070](#paper-070), [P081](#paper-081), [P392](#paper-392), [P477](#paper-477)

### Federated Learning (8)
![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)

[P012](#paper-012), [P017](#paper-017), [P034](#paper-034), [P056](#paper-056), [P101](#paper-101), [P192](#paper-192), [P193](#paper-193), [P250](#paper-250)

### Time Series (9)
![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)

[P025](#paper-025), [P042](#paper-042), [P074](#paper-074), [P113](#paper-113), [P141](#paper-141), [P142](#paper-142), [P196](#paper-196), [P397](#paper-397), [P400](#paper-400)

### Retrieval (6)
![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)

[P011](#paper-011), [P171](#paper-171), [P240](#paper-240), [P252](#paper-252), [P268](#paper-268), [P426](#paper-426)

### Generative Models (8)
![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)

[P006](#paper-006), [P030](#paper-030), [P069](#paper-069), [P079](#paper-079), [P091](#paper-091), [P123](#paper-123), [P286](#paper-286), [P462](#paper-462)

### Audio/Video (5)
![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)

[P044](#paper-044), [P166](#paper-166), [P226](#paper-226), [P440](#paper-440), [P443](#paper-443)

### 3D/Point Cloud (2)
![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)

[P144](#paper-144), [P169](#paper-169)

### Anomaly/OOD (15)
![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)

[P005](#paper-005), [P051](#paper-051), [P057](#paper-057), [P085](#paper-085), [P102](#paper-102), [P127](#paper-127), [P140](#paper-140), [P168](#paper-168), [P190](#paper-190), [P212](#paper-212), [P224](#paper-224), [P254](#paper-254), [P280](#paper-280), [P338](#paper-338), [P387](#paper-387)

### Crowdsourcing (12)
![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)

[P013](#paper-013), [P122](#paper-122), [P156](#paper-156), [P164](#paper-164), [P165](#paper-165), [P181](#paper-181), [P222](#paper-222), [P385](#paper-385), [P388](#paper-388), [P395](#paper-395), [P402](#paper-402), [P452](#paper-452)

### Weak Supervision (29)
![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)

[P043](#paper-043), [P120](#paper-120), [P124](#paper-124), [P125](#paper-125), [P126](#paper-126), [P145](#paper-145), [P147](#paper-147), [P157](#paper-157), [P184](#paper-184), [P185](#paper-185), [P187](#paper-187), [P188](#paper-188), [P191](#paper-191), [P195](#paper-195), [P247](#paper-247), [P251](#paper-251), [P305](#paper-305), [P306](#paper-306), [P323](#paper-323), [P324](#paper-324), [P386](#paper-386), [P393](#paper-393), [P415](#paper-415), [P416](#paper-416), [P442](#paper-442), [P445](#paper-445), [P451](#paper-451), [P463](#paper-463), [P470](#paper-470)

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

* <a id="paper-001"></a> **[P001]** Enhancing Learning with Noisy Labels via Rockafellian Relaxation.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=g4EpGiN5X3)
* <a id="paper-002"></a> **[P002]** TrainRef: Curating Data with Label Distribution and Minimal Reference for Accurate Prediction and Reliable Confidence.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=jSs8CDsF0A)
* <a id="paper-003"></a> **[P003]** Resurfacing the Instance-only Dependent Label Noise Model through Loss Correction.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=tuvkrivvbG)
* <a id="paper-004"></a> **[P004]** LANE: Label-Aware Noise Elimination for Fine-Grained Text Classification.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=PuayLKdrFz)
* <a id="paper-005"></a> **[P005]** Noise-Aware Generalization: Robustness to In-Domain Noise and Out-of-Domain Generalization.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=wb83wO41QT)
* <a id="paper-006"></a> **[P006]** Learning from Noisy Preferences: A Semi-Supervised Learning Approach to Direct Preference Optimization.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rRc04jyoAk)
* <a id="paper-007"></a> **[P007]** RE-PO: Robust Enhanced Policy Optimization as a General Framework for LLM Alignment.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=jDKpOvTCM8)

---

### AAAI 2026

* <a id="paper-008"></a> **[P008]** Jump-teaching: Combating Sample Selection Bias via Temporal Disagreement.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2405.17137)
* <a id="paper-009"></a> **[P009]** On the Learning Dynamics of Two-layer Linear Networks with Label Noise SGD.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2603.10397)
* <a id="paper-010"></a> **[P010]** Mitigating Endogenous Confirmation Bias in Noisy Label Learning for Vision-Language Models.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/39641/43602)
* <a id="paper-011"></a> **[P011]** Neighbor-aware Instance Refining with Noisy Labels for Cross-Modal Retrieval.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2512.24064)

### WACV 2026

* <a id="paper-012"></a> **[P012]** FedEFC: Federated Learning Using Enhanced Forward Correction Against Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/WACV2026/html/Yu_FedEFC_Federated_Learning_Using_Enhanced_Forward_Correction_Against_Noisy_Labels_WACV_2026_paper.html)
* <a id="paper-013"></a> **[P013]** Reciprocal Teaching: Dynamic Multi-Model Teacher-Student Learning for Multiple Noisy Annotations.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/WACV2026/html/Ai_Reciprocal_Teaching_Dynamic_Multi-Model_Teacher-Student_Learning_for_Multiple_Noisy_Annotations_WACV_2026_paper.html)

---

### Top Journals 2026

* <a id="paper-014"></a> **[P014]** [[**Sxu**]](https://github.com/SenyuHou) Class-Aware Multi-Granularity Co-Diffusion Models for Learning With Noisy Labels on Imbalanced Datasets. (Published on TKDE)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TKDE.2026.3650911)[[Code]](https://github.com/SenyuHou/CaMCoD)
* <a id="paper-015"></a> **[P015]** Continuous Review and Timely Correction: Enhancing the Resistance to Noisy Labels via Self-Not-True and Class-Wise Distillation. (Published on TPAMI)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2025.3649111)
* <a id="paper-016"></a> **[P016]** Affinity-aware Uncertainty Quantification for Learning with Noisy Labels. (Published on Pattern Recognition)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320325011586)
* <a id="paper-017"></a> **[P017]** Federated Learning with Noisy Labels: A Comprehensive and Concise Review of Current Methodologies and Future Directions. (Published on Neural Networks)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0893608026003503)

## Papers & Code in 2025

---

### NeurIPS 2025

* <a id="paper-018"></a> **[P018]** [[**Sxu**]](https://github.com/SenyuHou) Noisy Multi-Label Learning through Co-Occurrence-Aware Diffusion.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/115033)
* <a id="paper-019"></a> **[P019]** Learning to Clean: Reinforcement Learning for Noisy Label Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2025/poster/115438)
* <a id="paper-020"></a> **[P020]** Enhancing Sample Selection Against Label Noise by Cutting Mislabeled Easy Examples.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/118281)
* <a id="paper-021"></a> **[P021]** Handling Label Noise via Instance-Level Difficulty Modeling and Dynamic Optimization.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2025/poster/116524)[[Code]](https://github.com/iTheresaApocalypse/IDO)
* <a id="paper-022"></a> **[P022]** Self-Boost via Optimal Retraining: An Analysis via Approximate Message Passing.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/116800)

* <a id="paper-023"></a> **[P023]** GD$^2$: Robust Graph Learning under Label Noise via Dual-View Prediction Discrepancy.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/115580)
* <a id="paper-024"></a> **[P024]** ELDET: Early-Learning Distillation with Noisy Labels for Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/118794)
* <a id="paper-025"></a> **[P025]** FlowRefiner: A Robust Traffic Classification Framework against Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2025/poster/118975)

### ICCV 2025

* <a id="paper-026"></a> **[P026]** CA2C: A Prior-Knowledge-Free Approach for Robust Label Noise Learning via Asymmetric Co-learning and Co-training.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Sheng_CA2C_A_Prior-Knowledge-Free_Approach_for_Robust_Label_Noise_Learning_via_ICCV_2025_paper.html)
* <a id="paper-027"></a> **[P027]** Meta-Learning Dynamic Center Distance: Hard Sample Mining for Learning with Noisy Labels.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Mu_Meta-Learning_Dynamic_Center_Distance_Hard_Sample_Mining_for_Learning_with_ICCV_2025_paper.html)
* <a id="paper-028"></a> **[P028]** Joint Asymmetric Loss for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_Joint_Asymmetric_Loss_for_Learning_with_Noisy_Labels_ICCV_2025_paper.html)[[Code]](https://github.com/cswjl/joint-asymmetric-loss)
* <a id="paper-029"></a> **[P029]** Boosting Class Representation via Semantically Related Instances for Robust Long-Tailed Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Li_Boosting_Class_Representation_via_Semantically_Related_Instances_for_Robust_Long-Tailed_ICCV_2025_paper.html)[[Code]](https://github.com/yhli-ml/IBC)
* <a id="paper-030"></a> **[P030]** Guiding Noisy Label Conditional Diffusion Models with Score-based Discriminator Correction.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Cong_Guiding_Noisy_Label_Conditional_Diffusion_Models_with_Score-based_Discriminator_Correction_ICCV_2025_paper.html)
* <a id="paper-031"></a> **[P031]** Images as Noisy Labels: Unleashing the Potential of the Diffusion Model for Open-Vocabulary Semantic Segmentation.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Li_Images_as_Noisy_Labels_Unleashing_the_Potential_of_the_Diffusion_ICCV_2025_paper.html)

---

### ICML 2025

* <a id="paper-032"></a> **[P032]** On the Role of Label Noise in the Feature Learning Process.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/han25c.html)
* <a id="paper-033"></a> **[P033]** Retraining with Predicted Hard Labels Provably Increases Model Accuracy.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/das25b.html)
* <a id="paper-034"></a> **[P034]** FedClean: A General Robust Label Noise Correction for Federated Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/jiang25m.html)
* <a id="paper-035"></a> **[P035]** A Unified Theoretical Analysis of Private and Robust Offline Alignment: from RLHF to DPO.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/zhou25ac.html)

---

### CVPR 2025

* <a id="paper-036"></a> **[P036]** [[**Sxu**]](https://github.com/SenyuHou) Directional Label Diffusion Model for Learning from Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Hou_Directional_Label_Diffusion_Model_for_Learning_from_Noisy_Labels_CVPR_2025_paper.html)[[Code]](https://github.com/SenyuHou/DLD)
* <a id="paper-037"></a> **[P037]** NLPrompt: Noise-Label Prompt Learning for Vision-Language Models.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Pan_NLPrompt_Noise-Label_Prompt_Learning_for_Vision-Language_Models_CVPR_2025_paper.html)
* <a id="paper-038"></a> **[P038]** DiN: Diffusion Model for Robust Medical VQA with Semantic Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Guo_DiN_Diffusion_Model_for_Robust_Medical_VQA_with_Semantic_Noisy_CVPR_2025_paper.html)
* <a id="paper-039"></a> **[P039]** Theory-Inspired Deep Multi-View Multi-Label Learning with Incomplete Views and Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Li_Theory-Inspired_Deep_Multi-View_Multi-Label_Learning_with_Incomplete_Views_and_Noisy_CVPR_2025_paper.html)
* <a id="paper-040"></a> **[P040]** Minding Fuzzy Regions: A Data-driven Alternating Learning Paradigm for Stable Lesion Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Fang_Minding_Fuzzy_Regions_A_Data-driven_Alternating_Learning_Paradigm_for_Stable_CVPR_2025_paper.html)

---

### ICLR 2025

* <a id="paper-041"></a> **[P041]** Regretful Decisions under Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=7B9FCDoUzB)
* <a id="paper-042"></a> **[P042]** Learning under Temporal Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=5o0phqAhsP)
* <a id="paper-043"></a> **[P043]** Learning from Weak Labelers as Constraints.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=2BtFKEeMGo)
* <a id="paper-044"></a> **[P044]** Learning to Generate Diverse Pedestrian Movements from Web Videos with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=DydCqKa6AH)[[Code]](https://genforce.github.io/PedGen/)

---

### AAAI 2025

* <a id="paper-045"></a> **[P045]** Learning Causal Transition Matrix for Instance-dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2412.13516)
* <a id="paper-046"></a> **[P046]** Learning from Noisy Labels via Self-Taught On-the-Fly Meta Loss Rescaling.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2412.12955)
* <a id="paper-047"></a> **[P047]** Noisy Label Calibration for Multi-View Classification.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/35485/37640)
* <a id="paper-048"></a> **[P048]** Enhanced Sample Selection with Confidence Tracking: Identifying Correctly Labeled Yet Hard-to-Learn Samples in Noisy Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2504.17474)
* <a id="paper-049"></a> **[P049]** Optimized Gradient Clipping for Noisy Label Learning.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2412.08941)

* <a id="paper-050"></a> **[P050]** Robust Logit Adjustment for Learning with Long-Tailed Noisy Data.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=PQ43wVvbvz)

### Other Conferences 2025

* <a id="paper-051"></a> **[P051]** (KDD 2025) Noise-Resilient Point-wise Anomaly Detection in Time Series Using Weak Segment Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3690624.3709257)
* <a id="paper-052"></a> **[P052]** (IJCAI 2025) Leveraging Peer-Informed Label Consistency for Robust Graph Neural Networks with Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2025/623)
* <a id="paper-053"></a> **[P053]** (AISTATS 2025) AlleNoise - Large-scale Text Classification Benchmark Dataset with Real-world Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v258/raczkowska25a.html)[[Code]](https://github.com/allegro/AlleNoise)

---

### Top Journals 2025

* <a id="paper-054"></a> **[P054]** SplitNet: Learnable Clean-Noisy Label Splitting for Learning with Noisy Labels. (Published on IJCV)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://link.springer.com/article/10.1007/s11263-024-02187-4)
* <a id="paper-055"></a> **[P055]** Improving the Instance-Dependent Transition Matrix Estimation by Exploiting Self-Supervised Learning. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2025.3595613)
* <a id="paper-056"></a> **[P056]** FedELR: When Federated Learning Meets Learning with Noisy Labels. (Published on Neural Networks)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0893608025001546)
* <a id="paper-057"></a> **[P057]** Learning from Open-set Noisy Labels Based on Multi-prototype Modeling. (Published on Pattern Recognition)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320324006538)
* <a id="paper-058"></a> **[P058]** A Survey on Learning with Noisy Labels in Natural Language Processing: How to Train Models with Label Noise. (Published on Engineering Applications of Artificial Intelligence)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0952197625001575)

## Papers & Code in 2024

---

### Neurips 2024

* <a id="paper-059"></a> **[P059]** Learning the Latent Causal Structure for Modeling Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93700)
* <a id="paper-060"></a> **[P060]** Learning from Noisy Labels via Conditional Distributionally Robust Optimization.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/96820)
* <a id="paper-061"></a> **[P061]** Sample Selection via Contrastive Fragmentation for Noisy Label Regression.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95898)
* <a id="paper-062"></a> **[P062]** Label Noise: Ignorance Is Bliss.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/94205)
* <a id="paper-063"></a> **[P063]** Robust Contrastive Multi-view Clustering against Dual Noisy Correspondence.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/96528)
* <a id="paper-064"></a> **[P064]** Noisy Label Learning with Instance-Dependent Outliers: Identifiability via Crowd Wisdom.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95831)
* <a id="paper-065"></a> **[P065]** Entity Alignment with Noisy Annotations from Large Language Models.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93478)
* <a id="paper-066"></a> **[P066]** Vision-Language Models are Strong Noisy Label Detectors.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/94056)
* <a id="paper-067"></a> **[P067]** Benchmarking the Reasoning Robustness against Noisy Rationales in Chain-of-thought Prompting.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95956)
* <a id="paper-068"></a> **[P068]** CoSW: Conditional Sample Weighting for Smoke Segmentation with Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95170)
* <a id="paper-069"></a> **[P069]** Immiscible Diffusion: Accelerating Diffusion Training with Noise Assignment.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93906)
* <a id="paper-070"></a> **[P070]** Curriculum Fine-tuning of Vision Foundation Model for Medical Image Classification Under Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93198)[[Code]](https://github.com/gist-ailab/CUFIT)
* <a id="paper-071"></a> **[P071]** NoisyGL: A Comprehensive Benchmark for Graph Neural Networks under Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/97611)
* <a id="paper-072"></a> **[P072]** Noisy Ostracods: A Fine-Grained, Imbalanced Real-World Dataset for Benchmarking Robust Machine Learning and Label Correction Methods.
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/97733)
* <a id="paper-073"></a> **[P073]** Perplexity-aware Correction for Robust Alignment with Noisy Preferences.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95367)
* <a id="paper-074"></a> **[P074]** Information-theoretic Limits of Online Classification with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95650)

---

### ICML 2024

* <a id="paper-075"></a> **[P075]** Pi-DUAL: Using privileged information to distinguish clean from noisy labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/wang24bb.html)
* <a id="paper-076"></a> **[P076]** Self-cognitive Denoising in the Presence of Multiple Noisy Label Sources.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/sun24o.html)
* <a id="paper-077"></a> **[P077]** Mitigating Label Noise on Graphs via Topological Sample Selection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/wu24ae.html)
* <a id="paper-078"></a> **[P078]** Provably Robust DPO: Aligning Language Models with Noisy Feedback.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/ray-chowdhury24a.html)
* <a id="paper-079"></a> **[P079]** Consistent Diffusion Meets Tweedie: Training Exact Ambient Diffusion Models with Noisy Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/daras24a.html)
* <a id="paper-080"></a> **[P080]** RIME: Robust Preference-based Reinforcement Learning with Noisy Preferences.
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/cheng24k.html)
* <a id="paper-081"></a> **[P081]** FAFE: Immune Complex Modeling with Geodesic Distance Loss on Noisy Group Frames.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/wu24g.html)

---

### CVPR 2024

* <a id="paper-082"></a> **[P082]** Estimating Noisy Class Posterior with Part-level Labels for Noisy Label Learning.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Chen_Estimating_Noisy_Class_Posterior_with_Part-level_Labels_for_Noisy_Label_Learning_CVPR_2024_paper.html)
* <a id="paper-083"></a> **[P083]** Learning with Structural Labels for Learning with Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_Learning_with_Structural_Labels_for_Learning_with_Noisy_Labels_CVPR_2024_paper.html)
* <a id="paper-084"></a> **[P084]** Learning Discriminative Dynamics with Label Corruption for Noisy Label Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_Learning_Discriminative_Dynamics_with_Label_Corruption_for_Noisy_Label_Detection_CVPR_2024_paper.html)
* <a id="paper-085"></a> **[P085]** A Noisy Elephant in the Room: Is Your Out-of-Distribution Detector Robust to Label Noise?
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Lee_A_Noisy_Elephant_in_the_Room_Is_Your_Out-of-Distribution_Detector_Robust_CVPR_2024_paper.html)

---

### ICLR 2024

* <a id="paper-086"></a> **[P086]** Understanding and Mitigating the Label Noise in Pre-training on Downstream Tasks.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=TjhUtloBZU)
* <a id="paper-087"></a> **[P087]** Early Stopping Against Label Noise Without Validation Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=CMzF2aOfqp)
* <a id="paper-088"></a> **[P088]** Why is SAM Robust to Label Noise?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=3aZCPl3ZvR)
* <a id="paper-089"></a> **[P089]** Dirichlet-based Per-Sample Weighting by Transition Matrix for Noisy Label Learning.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=A4mJuFRMN8)
* <a id="paper-090"></a> **[P090]** Robust Classification via Regression for Learning with Noisy Labels.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=wfgZc3IMqo)
* <a id="paper-091"></a> **[P091]** Label-Noise Robust Diffusion Models.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=HXWTXXtHNl)
* <a id="paper-092"></a> **[P092]** Local Graph Clustering with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=89A5c6enfc)
* <a id="paper-093"></a> **[P093]** MOFI: Learning Image Representations from Noisy Entity Annotated Images.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=QQYpgReSRk)
* <a id="paper-094"></a> **[P094]** TextField3D: Towards Enhancing Open-Vocabulary 3D Generation with Noisy Text Fields.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=WOiOzHG2zD)

---

### KDD 2024

* <a id="paper-095"></a> **[P095]** Divide and Denoise: Learning from Noisy Labels in Fine-Grained Entity Typing with Cluster-Wise Loss Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3637528.3671834)

---

### ACM MM 2024

* <a id="paper-096"></a> **[P096]** Enhancing Robustness in Learning with Noisy Labels: An Asymmetric Co-Training Approach.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3664647.3680924)
* <a id="paper-097"></a> **[P097]** Mitigate Catastrophic Remembering via Continual Knowledge Purification for Noisy Label Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3664647.3680975)

* <a id="paper-098"></a> **[P098]** CLIPCleaner: Cleaning Noisy Labels with CLIP.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3664647.3681521)

### AAAI 2024

* <a id="paper-099"></a> **[P099]** [[**Sxu**]](https://github.com/SenyuHou) Which Is More Effective in Label Noise Cleaning, Correction or Filtering?
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29183/30238)

* <a id="paper-100"></a> **[P100]** Learning with Noisy Labels via Hashing Mutual Information Waiting.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v38i16.29578)
* <a id="paper-101"></a> **[P101]** FedDiv: Collaborative Noise Filtering for Federated Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2312.12263)
* <a id="paper-102"></a> **[P102]** Unlocking the Power of Open Set: A New Perspective for Open-Set Noisy Label Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2305.04203)

### Top Journals 2024

* <a id="paper-103"></a> **[P103]** Tackling Noisy Labels with Network Parameter Additive Decomposition. (Published on TPAMI)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2024.3367129)
* <a id="paper-104"></a> **[P104]** A Time-Consistency Curriculum for Learning from Instance-Dependent Noisy Labels. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2024.3433918)
* <a id="paper-105"></a> **[P105]** BadLabel: A Robust Perspective on Evaluating and Enhancing Label-noise Learning. (Published on TPAMI)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2024.3439233)

## Papers & Code in 2023

---

### ICCV 2023

* <a id="paper-106"></a> **[P106]** PADDLES: Phase-Amplitude Spectrum Disentangled Early Stopping for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Huang_PADDLES_Phase-Amplitude_Spectrum_Disentangled_Early_Stopping_for_Learning_with_Noisy_ICCV_2023_paper.pdf)[[Code]](https://github.com/CoderHHX/PADDLES)
* <a id="paper-107"></a> **[P107]** Sample-wise Label Confidence Incorporation for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ahn_Sample-wise_Label_Confidence_Incorporation_for_Learning_with_Noisy_Labels_ICCV_2023_paper.pdf)
* <a id="paper-108"></a> **[P108]** LA-Net: Landmark-Aware Learning for Reliable Facial Expression Recognition under Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_LA-Net_Landmark-Aware_Learning_for_Reliable_Facial_Expression_Recognition_under_Label_ICCV_2023_paper.pdf)
* <a id="paper-109"></a> **[P109]** Combating Noisy Labels with Sample Selection by Mining High-Discrepancy Examples.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Combating_Noisy_Labels_with_Sample_Selection_by_Mining_High-Discrepancy_Examples_ICCV_2023_paper.pdf)[[Code]](https://github.com/xiaoboxia/CoDis)
* <a id="paper-110"></a> **[P110]** RankMatch: Fostering Confidence and Consistency in Learning with Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_RankMatch_Fostering_Confidence_and_Consistency_in_Learning_with_Noisy_Labels_ICCV_2023_paper.pdf)
* <a id="paper-111"></a> **[P111]** SILT: Shadow-Aware Iterative Label Tuning for Learning to Detect Shadows from Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_SILT_Shadow-Aware_Iterative_Label_Tuning_for_Learning_to_Detect_Shadows_ICCV_2023_paper.pdf)[[Code]](https://github.com/hanyangclarence/SILT)
* <a id="paper-112"></a> **[P112]** Graph Matching with Bi-level Noisy Correspondence.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Lin_Graph_Matching_with_Bi-level_Noisy_Correspondence_ICCV_2023_paper.pdf)[[Code]](https://github.com/XLearning-SCU/2023-ICCV-COMMON)
* <a id="paper-113"></a> **[P113]** Learning from Noisy Pseudo Labels for Semi-Supervised Temporal Action Localization.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Learning_from_Noisy_Pseudo_Labels_for_Semi-Supervised_Temporal_Action_Localization_ICCV_2023_paper.pdf)[[Code]](https://github.com/kunnxia/NPL)
* <a id="paper-114"></a> **[P114]** Label-Noise Learning with Intrinsically Long-Tailed Data.
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Lu_Label-Noise_Learning_with_Intrinsically_Long-Tailed_Data_ICCV_2023_paper.pdf)
* <a id="paper-115"></a> **[P115]** Semi-Supervised Semantic Segmentation under Label Noise via Diverse Learning Groups.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Semi-Supervised_Semantic_Segmentation_under_Label_Noise_via_Diverse_Learning_Groups_ICCV_2023_paper.pdf)
* <a id="paper-116"></a> **[P116]** Holistic Label Correction for Noisy Multi-Label Classification.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Holistic_Label_Correction_for_Noisy_Multi-Label_Classification_ICCV_2023_paper.pdf)[[Code]](https://github.com/xiaoboxia/HLC)
* <a id="paper-117"></a> **[P117]** When Noisy Labels Meet Long Tail Dilemmas: A Representation Calibration Method.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_When_Noisy_Labels_Meet_Long_Tail_Dilemmas_A_Representation_Calibration_ICCV_2023_paper.pdf)
* <a id="paper-118"></a> **[P118]** Why Is Prompt Tuning for Vision-Language Models Robust to Noisy Labels?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_Why_Is_Prompt_Tuning_for_Vision-Language_Models_Robust_to_Noisy_ICCV_2023_paper.pdf)[[Code]](https://github.com/CEWu/PTNL)
* <a id="paper-119"></a> **[P119]** Learning from Noisy Data for Semi-Supervised 3D Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_Learning_from_Noisy_Data_for_Semi-Supervised_3D_Object_Detection_ICCV_2023_paper.pdf)[[Code]](https://github.com/zehuichen123/NoiseDet)
* <a id="paper-120"></a> **[P120]** LNPL-MIL: Learning from Noisy Pseudo Labels for Promoting Multiple Instance Learning in Whole Slide Image.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Shao_LNPL-MIL_Learning_from_Noisy_Pseudo_Labels_for_Promoting_Multiple_Instance_ICCV_2023_paper.pdf)[[Code]](https://github.com/szc19990412/LNPL-MIL)
* <a id="paper-121"></a> **[P121]** BoMD: Bag of Multi-label Descriptors for Noisy Chest X-ray Classification.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_BoMD_Bag_of_Multi-label_Descriptors_for_Noisy_Chest_X-ray_Classification_ICCV_2023_paper.pdf)[[Code]](https://github.com/cyh-0/BoMD)

---

### KDD 2023

* <a id="paper-122"></a> **[P122]** To Aggregate or Not? Learning with Separate Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2206.07181)
* <a id="paper-123"></a> **[P123]** DyGen: Learning from Noisy Labels via Dynamics-Enhanced Generative Modeling.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://dl.acm.org/doi/10.1145/3580305.3599318)[[Code]](https://github.com/night-chen/DyGen)
* <a id="paper-124"></a> **[P124]** Robust Positive-Unlabeled Learning via Noise Negative Sample Self-correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://dl.acm.org/doi/10.1145/3580305.3599491)
* <a id="paper-125"></a> **[P125]** Neural-Hidden-CRF: A Robust Weakly-Supervised Sequence Labeler.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://browse.arxiv.org/pdf/2309.05086.pdf)[[Code]](https://github.com/junchenzhi/Neural-Hidden-CRF)
* <a id="paper-126"></a> **[P126]** Complementary Classifier Induced Partial Label Learning.
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2305.09897)[[Code]](https://github.com/Chongjie-Si/PL-CL)
* <a id="paper-127"></a> **[P127]** Partial-label Learning with Mixed Closed-Set and Open-Set Out-of-Candidate Examples.
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2307.00553)
* <a id="paper-128"></a> **[P128]** Weakly Supervised Multi-Label Classification of Full-Text Scientific Papers.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2306.14003)[[Code]](https://github.com/yuzhimanhua/FUTEX)

---

### NeurIPS 2023

* <a id="paper-129"></a> **[P129]** AQuA: A Benchmarking Tool for Label Quality Assessment.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=dhJ8VbcEtX)
* <a id="paper-130"></a> **[P130]** Efficient Testable Learning of Halfspaces with Adversarial Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=mIm0hsUUt1)
* <a id="paper-131"></a> **[P131]** Robust Data Pruning under Label Noise via Maximizing Re-labeling Accuracy.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=xWCp0uLcpG)
* <a id="paper-132"></a> **[P132]** Subclass-Dominant Label Noise: A Counterexample for the Success of Early Stopping.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=kR21XsZeAr)[[Code]](https://github.com/tmllab/2023_NeurIPS_SDN)
* <a id="paper-133"></a> **[P133]** Label Correction of Crowdsourced Noisy Annotations with an Instance-Dependent Noise Transition Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=nFEQNYsjQO)
* <a id="paper-134"></a> **[P134]** Active Negative Loss Functions for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2023/poster/71501)[[Code]](https://github.com/Virusdoll/Active-Negative-Loss)
* <a id="paper-135"></a> **[P135]** Label-Retrieval-Augmented Diffusion Models for Learning from Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2305.19518)[[Code]](https://github.com/puar-playground/LRA-diffusion)
* <a id="paper-136"></a> **[P136]** Training shallow ReLU networks on noisy data using hinge loss: when do we overfit and is it benign?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2306.09955)
* <a id="paper-137"></a> **[P137]** CSOT: Curriculum and Structure-Aware Optimal Transport for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=y50AnAbKp1)[[Code]](https://github.com/changwxx/CSOT-for-LNL)
* <a id="paper-138"></a> **[P138]** Label Poisoning is All You Need.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2310.18933)[[Code]](https://github.com/SewoongLab/FLIP)
* <a id="paper-139"></a> **[P139]** IPMix: Label-Preserving Data Augmentation Method for Training Robust Classifiers.
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=No52399wXA)
* <a id="paper-140"></a> **[P140]** Neural Relation Graph: A Unified Framework for Identifying Label Noise and Outlier Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2301.12321)[[Code]](https://github.com/snu-mllab/Neural-Relation-Graph)
* <a id="paper-141"></a> **[P141]** Scale-teaching: Robust Multi-scale Training for Time Series Classification with Noisy Labels.
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=9D0fELXbrg)[[Code]](https://github.com/qianlima-lab/Scale-teaching)
* <a id="paper-142"></a> **[P142]** SoTTA: Robust Test-Time Adaptation on Noisy Data Streams.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2310.10074)[[Code]](https://github.com/taeckyung/SoTTA)
* <a id="paper-143"></a> **[P143]** Deep Insights into Noisy Pseudo Labeling on Graph Data.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=XhNlBvb4XV)
* <a id="paper-144"></a> **[P144]** ARTIC3D: Learning Robust Articulated 3D Shapes from Noisy Web Image Collections.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rJc5Lsn5QU)[[Code]](https://chhankyao.github.io/artic3d/)
* <a id="paper-145"></a> **[P145]** ALIM: Adjusting Label Importance Mechanism for Noisy Partial Label Learning.
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=PYSfn5xXEe)[[Code]](https://github.com/zeroQiaoba/ALIM)
* <a id="paper-146"></a> **[P146]** Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2305.11003)[[Code]](https://github.com/ChunmingHe/WS-SAM)
* <a id="paper-147"></a> **[P147]** SLaM: Student-Label Mixing for Distillation with Unlabeled Examples.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=N7tw0QXx3z)
* <a id="paper-148"></a> **[P148]** HQA-Attack: Toward High Quality Black-Box Hard-Label Adversarial Attack on Text.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=IOuuLBrGJR)[[Code]](https://github.com/HQA-Attack/HQAAttack-demo)

---

### ICML 2023

* <a id="paper-149"></a> **[P149]** Identifiability of Label Noise Transition Matrix.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/liu23g)
* <a id="paper-150"></a> **[P150]** Which is Better for Learning with Noisy Labels: The Semi-supervised Method or Modeling Label Noise?
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/yao23a)
* <a id="paper-151"></a> **[P151]** Mitigating Memorization of Noisy Labels by Clipping the Model Prediction.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2212.04055)[[Code]](https://github.com/hongxin001/LogitClip)
* <a id="paper-152"></a> **[P152]** CrossSplit: Mitigating Label Noise Memorization through Data Splitting.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v202/kim23a/kim23a.pdf)[[Code]](https://github.com/SAITPublic/CrossSplit)
* <a id="paper-153"></a> **[P153]** Understanding Self-Distillation in the Presence of Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v202/das23d/das23d.pdf)
* <a id="paper-154"></a> **[P154]** Delving into Noisy Label Detection with Clean Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/yu23b.html)
* <a id="paper-155"></a> **[P155]** When does Privileged information Explain Away Label Noise?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/ortiz-jimenez23a)
* <a id="paper-156"></a> **[P156]** Deep Clustering with Incomplete Noisy Pairwise Annotations: A Geometric Regularization Approach.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/nguyen23d)
* <a id="paper-157"></a> **[P157]** Accelerating Exploration with Unlabeled Prior Data.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Itorzn4Kwf)

---

### CVPR 2023

* <a id="paper-158"></a> **[P158]** Twin Contrastive Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2303.06930)[[Code]](https://github.com/Hzzone/TCL)
* <a id="paper-159"></a> **[P159]** Learning from Noisy Labels with Decoupled Meta Label Purifier.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2302.06810)[[Code]](https://github.com/yuanpengtu/DMLP)
* <a id="paper-160"></a> **[P160]** DISC: Learning from Noisy Labels via Dynamic Instance-Specific Selection and Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_DISC_Learning_From_Noisy_Labels_via_Dynamic_Instance-Specific_Selection_and_CVPR_2023_paper.pdf)[[Code]](https://github.com/jackyfl/disc)
* <a id="paper-161"></a> **[P161]** Fine-Grained Classification with Noisy Labels.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wei_Fine-Grained_Classification_With_Noisy_Labels_CVPR_2023_paper.pdf)
* <a id="paper-162"></a> **[P162]** OT-Filter: An Optimal Transport Filter for Learning With Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Feng_OT-Filter_An_Optimal_Transport_Filter_for_Learning_With_Noisy_Labels_CVPR_2023_paper.pdf)
* <a id="paper-163"></a> **[P163]** Exploring High-Quality Pseudo Masks for Weakly Supervised Instance Segmentation.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2210.05174)[[Code]](https://github.com/hustvl/BoxTeacher)
* <a id="paper-164"></a> **[P164]** HandsOff: Labeled Dataset Generation with No Additional Human Annotations.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2212.12645.pdf)[[Code]](https://github.com/austinxu87/handsoff/)
* <a id="paper-165"></a> **[P165]** Leveraging Inter-Rater Agreement for Classification in the Presence of Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Bucarelli_Leveraging_Inter-Rater_Agreement_for_Classification_in_the_Presence_of_Noisy_CVPR_2023_paper.pdf)
* <a id="paper-166"></a> **[P166]** Collaborative Noisy Label Cleaner: Learning Scene-aware Trailers for Multi-modal Highlight Detection in Movies.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2303.14768)[[Code]](https://github.com/TencentYoutuResearch/HighlightDetection-CLC)
* <a id="paper-167"></a> **[P167]** MixTeacher: Mining Promising Labels with Mixed Scale Teacher for Semi-supervised Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2303.09061)[[Code]](https://github.com/lliuz/MixTeacher)
* <a id="paper-168"></a> **[P168]** Exploiting Completeness and Uncertainty of Pseudo Labels for Weakly Supervised Video Anomaly Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Exploiting_Completeness_and_Uncertainty_of_Pseudo_Labels_for_Weakly_Supervised_CVPR_2023_paper.pdf)[[Code]](https://github.com/ArielZc/CU-Net)
* <a id="paper-169"></a> **[P169]** Semi-Supervised 2D Human Pose Estimation Driven by Position Inconsistency Pseudo Label Correction Module.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Semi-Supervised_2D_Human_Pose_Estimation_Driven_by_Position_Inconsistency_Pseudo_CVPR_2023_paper.pdf)[[Code]](https://github.com/hlz0606/SSPCM)
* <a id="paper-170"></a> **[P170]** Learning with Noisy labels via Self-supervised Adversarial Noisy Masking.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Tu_Learning_With_Noisy_Labels_via_Self-Supervised_Adversarial_Noisy_Masking_CVPR_2023_paper.pdf)[[Code]](https://github.com/yuanpengtu/SANM)
* <a id="paper-171"></a> **[P171]** RONO: Robust Discriminative Learning with Noisy Labels for 2D-3D Cross-Modal Retrieval.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Feng_RONO_Robust_Discriminative_Learning_With_Noisy_Labels_for_2D-3D_Cross-Modal_CVPR_2023_paper.pdf)[[Code]](https://github.com/penghu-cs/RONO)

---

### ICLR 2023

* <a id="paper-172"></a> **[P172]** Mitigating Memorization of Noisy Labels via Regularization between Representations.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=6qcYDVlVLnK)
* <a id="paper-173"></a> **[P173]** On the Edge of Benign Overfitting: Label Noise and Overparameterization Level.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=UrEwJebCxk)
* <a id="paper-174"></a> **[P174]** Memorization-Dilation: Modeling Neural Collapse Under Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=cJWxqmmDL2b)
* <a id="paper-175"></a> **[P175]** Quantifying and Mitigating the Impact of Label Errors on Model Disparity Metrics.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=RUzSobdYy0V)
* <a id="paper-176"></a> **[P176]** When Source-Free Domain Adaptation Meets Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=u2Pd6x794I)
* <a id="paper-177"></a> **[P177]** A law of adversarial risk, interpolation, and label noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=0_TxFpAsEI)
* <a id="paper-178"></a> **[P178]** SoftMatch: Addressing the Quantity-Quality Tradeoff in Semi-supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=ymt1zQXBDiF)
* <a id="paper-179"></a> **[P179]** Mitigating Dataset Bias by Using Per-Sample Gradient.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=7mgUec-7GMv)
* <a id="paper-180"></a> **[P180]** MCAL: Minimum Cost Human-Machine Active Labeling.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=1FxRPKrH8bw)
* <a id="paper-181"></a> **[P181]** Deep Learning From Crowdsourced Labels: Coupled Cross-Entropy Minimization, Identifiability, and Regularization.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=_qVhsWyWB9)
* <a id="paper-182"></a> **[P182]** CLIPSep: Learning Text-queried Sound Separation with Noisy Unlabeled Videos.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=H-T3F0dMbyj)
* <a id="paper-183"></a> **[P183]** Learning to Segment from Noisy Annotations: A Spatial Correction Approach.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=Qc_OopMEBnC)
* <a id="paper-184"></a> **[P184]** Mutual Partial Label Learning with Competitive Label Noise.
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=EUrxG8IBCrC)
* <a id="paper-185"></a> **[P185]** Leveraging Unlabeled Data to Track Memorization .
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=ORp91sAbzI)
* <a id="paper-186"></a> **[P186]** CLIPSep: Learning Text-queried Sound Separation with Noisy Unlabeled Videos.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=H-T3F0dMbyj)
* <a id="paper-187"></a> **[P187]** Does Decentralized Learning with Non-IID Unlabeled Data Benefit from Self Supervision?.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=2L9gzS80tA4)
* <a id="paper-188"></a> **[P188]** Label Propagation with Weak Supervision .
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=aCuFa-RRqtI)
* <a id="paper-189"></a> **[P189]** Pushing the Accuracy-Group Robustness Frontier with Introspective Self-play.
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=MofT9KEF0kw)
* <a id="paper-190"></a> **[P190]** Towards Lightweight, Model-Agnostic and Diversity-Aware Active Anomaly Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=-vKlt84fHs)
* <a id="paper-191"></a> **[P191]** Weakly Supervised Explainable Phrasal Reasoning with Neural Fuzzy Logic.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=Hu4r-dedqR0)
* <a id="paper-192"></a> **[P192]** Towards Addressing Label Skews in One-Shot Federated Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=rzrqh85f4Sc)
* <a id="paper-193"></a> **[P193]** Instance-wise Batch Label Restoration via Gradients in Federated Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=FIrQfNSOoTr)
* <a id="paper-194"></a> **[P194]** That Label's got Style: Handling Label Style Bias for Uncertain Image Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=wZ2SVhOTzBX)
* <a id="paper-195"></a> **[P195]** Learning Hyper Label Model for Programmatic Weak Supervision.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=aCQt_BrkSjC)
* <a id="paper-196"></a> **[P196]** Rhino: Deep Causal Temporal Relationship Learning with History-dependent Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=i_1rbq8yFWC)

---

### AAAI 2023

* <a id="paper-197"></a> **[P197]** Class-Independent Regularization for Learning with Noisy Labels.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1609/aaai.v37i6.25890)

---

### ACM MM 2023

* <a id="paper-198"></a> **[P198]** PNT-Edge: Towards Robust Edge Detection with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3581783.3612412)
* <a id="paper-199"></a> **[P199]** Adaptive Contrastive Learning on Multimodal Transformer for Review Helpfulness Predictions with Multimodal Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multimodal](https://img.shields.io/badge/task-Multimodal-0F766E?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3581783.3612405)
* <a id="paper-200"></a> **[P200]** ALEX: Towards Effective Graph Transfer Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3581783.3611891)

---

### Top Journals 2023

* <a id="paper-201"></a> **[P201]** A Parametrical Model for Instance-Dependent Label Noise. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3301876)
* <a id="paper-202"></a> **[P202]** Noisy Label Learning With Provable Consistency for a Wider Family of Losses. (Published on TPAMI)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3296156)
* <a id="paper-203"></a> **[P203]** Regularly Truncated M-Estimators for Learning With Noisy Labels. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3347850)
* <a id="paper-204"></a> **[P204]** Learning to Learn From Noisy Labeled Data. (Published on TKDE)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TKDE.2023.3271677)
* <a id="paper-205"></a> **[P205]** Robust Point Cloud Segmentation With Noisy Annotations. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3233772)

## Papers & Code in 2022

---

### NeurIPS 2022

* <a id="paper-206"></a> **[P206]** Learning from Label Proportions by Learning with Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=cqyBfRwOTm1)
* <a id="paper-207"></a> **[P207]** Class-Dependent Label-Noise Learning with Cycle-Consistency Regularization.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=IvnoGKQuXi)
* <a id="paper-208"></a> **[P208]** Robustness to Label Noise Depends on the Shape of the Noise Distribution.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=AlpR6dzKjfy)
* <a id="paper-209"></a> **[P209]** Label Noise in Adversarial Training: A Novel Perspective to Study Robust Overfitting.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=9_O9mTLYJQp)
* <a id="paper-210"></a> **[P210]** Estimating Noise Transition Matrix with Label Correlations for Noisy Multi-Label Learning .
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=GwXrGy_vc8m)[[Code]](https://github.com/ShikunLi/Estimating_T_For_Noisy_Mutli-Labels)
* <a id="paper-211"></a> **[P211]** On Image Segmentation With Noisy Labels: Characterization and Volume Properties of the Optimal Solutions to Accuracy and Dice.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=WDS1M0gsfXk)
* <a id="paper-212"></a> **[P212]** SoftPatch: Unsupervised Anomaly Detection with Noisy Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=pIYYJflkhZ)

---

### ECCV 2022

* <a id="paper-213"></a> **[P213]** Neighborhood Collective Estimation for Noisy Label Identification and Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2208.03207)[[Code]](https://github.com/lijichang/LNL-NCE)
* <a id="paper-214"></a> **[P214]** Teaching with Soft Label Smoothing for Mitigating Noisy Labels in Facial Expressions.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720639.pdf)[[Code]](https://github.com/toharl/soft)
* <a id="paper-215"></a> **[P215]** Learn From All: Erasing Attention Consistency for Noisy Label Facial Expression Recognition.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.10299)[[Code]](https://github.com/zyh-uaiaaaa/Erasing-Attention-Consistency)
* <a id="paper-216"></a> **[P216]** Centrality and Consistency: Two-Stage Clean Samples Identification for Learning with Instance-Dependent Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.14476)[[Code]](https://github.com/uitrbn/TSCSI_IDN)
* <a id="paper-217"></a> **[P217]** Learning with Noisy Labels by Efficient Transition Matrix Estimation to Combat Label Miscorrection.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.14932)[[Code]](https://github.com/hyperconnect/FasTEN)
* <a id="paper-218"></a> **[P218]** Self-Filtering: A Noise-Aware Sample Selection for Label Noise with Confidence Penalization.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2208.11351)
* <a id="paper-219"></a> **[P219]** BoundaryFace: A mining framework with noise label self-correction for Face Recognition.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730092.pdf)[[Code]](https://gitee.com/swjtugx/classmate/tree/master/OurGroup/BoundaryFace)
* <a id="paper-220"></a> **[P220]** Active label correction using robust parameter update and entropy propagation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136810001.pdf)
* <a id="paper-221"></a> **[P221]** A data-centric approach for improving ambiguous labels with combined semi-supervised classification and clustering.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.16209)[[Code]](https://github.com/Emprime/dc3)

---

* <a id="paper-222"></a> **[P222]** Learning from Multiple Annotator Noisy Labels via Sample-wise Label Fusion.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136840402.pdf)[[Code]](https://github.com/zhengqigao/Learning-from-Multiple-Annotator-Noisy-Labels)
* <a id="paper-223"></a> **[P223]** Identifying Hard Noise in Long-Tailed Sample Distribution.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.13378)[[Code]](https://github.com/yxymessi/H2E-Framework)
* <a id="paper-224"></a> **[P224]** Embedding contrastive unsupervised features to cluster in- and out-of-distribution noise in corrupted image datasets.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.01573)[[Code]](https://github.com/PaulAlbert31/SNCF)
* <a id="paper-225"></a> **[P225]** WeLSA: Learning To Predict 6D Pose From Weakly Labeled Data Using Shape Alignment.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680633.pdf)
* <a id="paper-226"></a> **[P226]** Joint-Modal Label Denoising for Weakly-Supervised Audio-Visual Video Parsing.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2204.11573)[[Code]](https://github.com/MCG-NJU/JoMoLD)
* <a id="paper-227"></a> **[P227]** PseCo: Pseudo Labeling and Consistency Training for Semi-Supervised Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.16317)[[Code]](https://github.com/ligang-cs/PseCo)

### ICML 2022

* <a id="paper-228"></a> **[P228]** To Smooth or Not? When Label Smoothing Meets Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.04149)[[Code]](https://github.com/UCSC-REAL/negative-label-smoothing)
* <a id="paper-229"></a> **[P229]** Detecting Corrupted Labels Without Training a Model to Predict.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.06283)[[Code]](https://github.com/UCSC-REAL/SimiFeat)
* <a id="paper-230"></a> **[P230]** Beyond Images: Label Noise Transition Matrix Estimation for Tasks with Lower-Quality Features.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.01273)
* <a id="paper-231"></a> **[P231]** From Noisy Prediction to True Label: Noisy Prediction Calibration via Generative Model
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2205.00690)[[Code]](https://github.com/BaeHeeSun/NPC)
* <a id="paper-232"></a> **[P232]** Robust Training under Label Noise by Over-parameterization.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.14026)[[Code]](https://github.com/shengliu66/SOP)
* <a id="paper-233"></a> **[P233]** Estimating Instance-dependent Label-noise Transition Matrix using DNNs.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.13001)
* <a id="paper-234"></a> **[P234]** Guaranteed Robust Deep Learning against Extreme Label Noise using Self-supervised Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
* <a id="paper-235"></a> **[P235]** Robust Meta-learning with Sampling Noise and Label Noise via Eigen-Reptile.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2206.01944v1.pdf)[[Code]](https://github.com/anfeather/eigen-reptile)
* <a id="paper-236"></a> **[P236]** Learning General Halfspaces with Adversarial Label Noise via Online Gradient Descent.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v162/diakonikolas22b.html)
* <a id="paper-237"></a> **[P237]** Guaranteed Robust Deep Learning against Extreme Label Noise using Self-supervised Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)

---

### CVPR 2022

* <a id="paper-238"></a> **[P238]** Selective-Supervised Contrastive Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.04181)[[Code]](https://github.com/ShikunLi/Sel-CL)
* <a id="paper-239"></a> **[P239]** Scalable Penalized Regression for Noise Detection in Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.07788)[[Code]](https://github.com/Yikai-Wang/SPR-LNL)
* <a id="paper-240"></a> **[P240]** Large-Scale Pre-training for Person Re-identification with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](http://arxiv.org/pdf/2203.16533)[[Code]](https://github.com/dengpanfu/luperson-nl)
* <a id="paper-241"></a> **[P241]** Adaptive Early-Learning Correction for Segmentation from Noisy Annotations.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.03740)[[Code]](https://github.com/Kangningthu/ADELE)

---

### ICLR 2022

* <a id="paper-242"></a> **[P242]** Learning with Noisy Labels Revisited: A Study Using Real-World Human Annotations.
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=TBWA6PLJZQm&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICLR.cc%2F2022%2FConference%2FAuthors%23your-submissions))[[Code]](https://github.com/zwzhu-d/cifar-10-100n)
* <a id="paper-243"></a> **[P243]** Resolving Training Biases via Influence-based Data Relabeling.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=EskfH0bwNVn)
* <a id="paper-244"></a> **[P244]** Sample Selection with Uncertainty of Losses for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=xENf4QUL4LW)
* <a id="paper-245"></a> **[P245]** An Information Fusion Approach to Learning with Instance-Dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=ecH2FKaARUp)
* <a id="paper-246"></a> **[P246]** Meta Discovery: Learning to Discover Novel Classes given Very Limited Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=MEpKGLsY8f)

---

* <a id="paper-247"></a> **[P247]** Contrastive Label Disambiguation for Partial Label Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=EhYjZy6e1gJ)

### AAAI 2022

* <a id="paper-248"></a> **[P248]** Noise-Robust Learning from Multiple Unsupervised Sources of Inferred Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20367)
* <a id="paper-249"></a> **[P249]** Deep Neural Networks Learn Meta-Structures from Noisy Labels in Semantic Segmentation.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20194)

---

### KDD 2022

* <a id="paper-250"></a> **[P250]** Communication-Efficient Robust Federated Learning with Noisy Labels.
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3534678.3539252)
* <a id="paper-251"></a> **[P251]** Adaptive Learning for Weakly Labeled Streams.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3534678.3539334)

---

### ACM MM 2022

* <a id="paper-252"></a> **[P252]** Early-Learning Regularized Contrastive Learning for Cross-Modal Retrieval with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3503161.3547809)

---

### Top Journals 2022

* <a id="paper-253"></a> **[P253]** Wasserstein Adversarial Regularization for Learning with Label Noise. (Published on TPAMI)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2022.3156685)
* <a id="paper-254"></a> **[P254]** Extended T: Learning With Mixed Closed-Set and Open-Set Noisy Labels. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2022.3180545)

---

### ArXiv 2022

* <a id="paper-255"></a> **[P255]** Constrained Instance and Class Reweighting for Robust Learning under Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.05428)
* <a id="paper-256"></a> **[P256]** AUGLOSS: A Learning Methodology for Real-World Dataset Corruption.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2206.02286.pdf)
* <a id="paper-257"></a> **[P257]** Do We Need to Penalize Variance of Losses for Learning with Label Noise?.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.12739)
* <a id="paper-258"></a> **[P258]** On Learning Contrastive Representations for Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.01785)
* <a id="paper-259"></a> **[P259]** Benign Overfitting without Linearity: Neural Network Classifiers Trained by Gradient Descent for Noisy Linear Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.05928#:~:text=11%20Feb%202022%5D-,Benign%20Overfitting%20without%20Linearity%3A%20Neural%20Network%20Classifiers%20Trained%20by,Descent%20for%20Noisy%20Linear%20Data&text=Abstract%3A%20Benign%20overfitting%2C%20the%20phenomenon,models%20trained%20with%20gradient%20descent.)
* <a id="paper-260"></a> **[P260]** Synergistic Network Learning and Label Correction for Noise-robust Image Classification.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.13472)
* <a id="paper-261"></a> **[P261]** Convolutional Network Fabric Pruning With Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.07268)
* <a id="paper-262"></a> **[P262]** Learning to Bootstrap for Combating Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.04291)
* <a id="paper-263"></a> **[P263]** Learning with Neighbor Consistency for Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.02200)
* <a id="paper-264"></a> **[P264]** Investigating Why Contrastive Learning Benefits Robustness Against Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.12498)
* <a id="paper-265"></a> **[P265]** PARS: Pseudo-Label Aware Robust Sample Selection for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.10836)
* <a id="paper-266"></a> **[P266]** GMM Discriminant Analysis with Noisy Label for Each Class.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.10242)
* <a id="paper-267"></a> **[P267]** Two Wrongs Don't Make a Right: Combating Confirmation Bias in Learning with Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2112.02960)

---

* <a id="paper-268"></a> **[P268]** Learning with Label Noise for Image Retrieval by Selecting Interactions.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2112.10453)

## Papers & Code in 2021

### NeurIPS 2021

* <a id="paper-269"></a> **[P269]** Can Less be More? When Increasing-to-Balancing Label Noise Rates Considered Beneficial.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2107.05913#:~:text=We%20are%20primarily%20inspired%20by,fairness%20guarantees%20against%20label%20bias.)[[Code]](https://github.com/UCSC-REAL/CanLessBeMore)
* <a id="paper-270"></a> **[P270]** Generalized Jensen-Shannon Divergence Loss for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.04522)[[Code]](https://github.com/ErikEnglesson/GJS)
* <a id="paper-271"></a> **[P271]** Understanding and Improving Early Stopping for Learning with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.15853)[[Code]](https://github.com/tmllab/PES)
* <a id="paper-272"></a> **[P272]** How does a Neural Network's Architecture Impact its Robustness to Noisy Labels?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Ir-WwGboFN-)[[Code]](https://github.com/jinglingli/alignment_noisy_label)
* <a id="paper-273"></a> **[P273]** FINE Samples for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.11628v3.pdf)[[Code]](https://github.com/Kthyeon/FINE_official)
* <a id="paper-274"></a> **[P274]** Label Noise SGD Provably Prefers Flat Global Minimizers.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.06530)[[Code]](https://github.com/adamian98/LabelNoiseFlatMinimizers)
* <a id="paper-275"></a> **[P275]** Improved Regularization and Robustness for Fine-tuning in Neural Networks.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=QX32YlxrQJc)[[Code]](https://github.com/NEU-StatsML-Research/Regularized-Self-Labeling)
* <a id="paper-276"></a> **[P276]** Instance-dependent Label-noise Learning under a Structural Causal Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2109.02986)
* <a id="paper-277"></a> **[P277]** Combating Noise: Semi-supervised Learning by Region Uncertainty Quantification.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.00928)
* <a id="paper-278"></a> **[P278]** DP-SSL: Towards Robust Semi-supervised Learning with A Few Labeled Samples.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.13740)
* <a id="paper-279"></a> **[P279]** Corruption Robust Active Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Ruw3MHL9jAO)

---

* <a id="paper-280"></a> **[P280]** Open-set Label Noise Can Improve Robustness Against Inherent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.10891)[[Code]](https://github.com/hongxin001/ODNL)

### KDD 2021

* <a id="paper-281"></a> **[P281]** Robust Learning by Self-Transition for Handling Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3447548.3467222)

---

* <a id="paper-282"></a> **[P282]** NRGNN: Learning a Label Noise Resistant Graph Neural Network on Sparsely and Noisily Labeled Graphs.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3447548.3467364)

### ACM MM 2021

* <a id="paper-283"></a> **[P283]** Co-learning: Learning from Noisy Labels with Self-supervision.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3474085.3475622)

---

### IJCAI 2021

* <a id="paper-284"></a> **[P284]** Towards Understanding Deep Learning from Noisy Labels with Small-Loss Criterion.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2021/0340.pdf)
* <a id="paper-285"></a> **[P285]** Modeling Noisy Hierarchical Types in Fine-Grained Entity Typing: A Content-Based Weighting Approach.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2019/0731.pdf)
* <a id="paper-286"></a> **[P286]** Multi-level Generative Models for Partial Label Learning with Non-random Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2021/0449.pdf)

---

### ICML 2021

* <a id="paper-287"></a> **[P287]** The importance of understanding instance-level noisy labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.05336.pdf)
* <a id="paper-288"></a> **[P288]** Clusterability as an Alternative to Anchor Points When Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.05291.pdf)[[Code]](https://github.com/zwzhu-d/HOC)
* <a id="paper-289"></a> **[P289]** Learning Noise Transition Matrix from Only Noisy Labels via Total Variation Regularization.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.02414v2.pdf)[[Code]](https://github.com/YivanZhang/lio)
* <a id="paper-290"></a> **[P290]** Class2Simi: A Noise Reduction Perspective on Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2006.07831)
* <a id="paper-291"></a> **[P291]** Provably End-to-end Label-noise Learning without Anchor Points.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.02400.pdf)
* <a id="paper-292"></a> **[P292]** Asymmetric Loss Functions for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2106.03110v1.pdf)[[Code]](https://github.com/hitcszx/ALFs)
* <a id="paper-293"></a> **[P293]** Confidence Scores Make Instance-dependent Label-noise Learning Possible.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2001.03772)
* <a id="paper-294"></a> **[P294]** Provable Generalization of SGD-trained Neural Networks of Any Width in the Presence of Adversarial Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2101.01152)
* <a id="paper-295"></a> **[P295]** Wasserstein Distributional Normalization For Robust Distributional Certification of Noisy Labeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v139/park21a/park21a.pdf)
* <a id="paper-296"></a> **[P296]** Learning from Noisy Labels with No Change to the Training Process.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v139/zhang21k/zhang21k.pdf)

---

* <a id="paper-297"></a> **[P297]** Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.05918v2.pdf)[[Code]](https://github.com/MicPie/clasp)

### ICLR 2021

* <a id="paper-298"></a> **[P298]** When Optimizing f-Divergence is Robust with Label Noise.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=WesiCoRVQ15)[[Code]](https://github.com/weijiaheng/Robust-f-divergence-measures)
* <a id="paper-299"></a> **[P299]** Learning with Instance-Dependent Label Noise: A Sample Sieve Approach.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=2VXyy9mIyU3)[[Code]](https://github.com/haochenglouis/cores)
* <a id="paper-300"></a> **[P300]** Noise against noise: stochastic label noise helps combat inherent label noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=80FMcTSZ6J0)[[Code]](https://github.com/chenpf1025/SLN)
* <a id="paper-301"></a> **[P301]** Learning with Feature-Dependent Label Noise: A Progressive Approach.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=ZPa2SyGcbwh)[[Code]](https://github.com/pxiangwu/PLC)
* <a id="paper-302"></a> **[P302]** Robust early-learning: Hindering the memorization of noisy labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=Eql5b1_hTE4)[[Code]](https://github.com/xiaoboxia/CDR)
* <a id="paper-303"></a> **[P303]** Robust Curriculum Learning: from clean label detection to noisy label self-correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=lmTWnm3coJJ)
* <a id="paper-304"></a> **[P304]** How Does Mixup Help With Robustness and Generalization?
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=8yKEo06dKNo)
* <a id="paper-305"></a> **[P305]** MoPro: Webly Supervised Learning with Momentum Prototypes.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=0-EYBhgw80y) [[Code]](https://github.com/salesforce/MoPro)
* <a id="paper-306"></a> **[P306]** Theoretical Analysis of Self-Training with Deep Networks on Unlabeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=rC8sJ4i6kaH)

---

### CVPR 2021

* <a id="paper-307"></a> **[P307]** A Second-Order Approach to Learning with Instance-Dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.11854)[[Code]](https://github.com/UCSC-REAL/CAL)
* <a id="paper-308"></a> **[P308]** Improving Unsupervised Image Clustering With Robust Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.11150)
* <a id="paper-309"></a> **[P309]** Multi-Objective Interpolation Training for Robustness to Label Noise.
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.04462)[[Code]](https://git.io/JI40X)
* <a id="paper-310"></a> **[P310]** Noise-resistant Deep Metric Learning with Ranking-based Instance Selection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.16047)[[Code]](https://github.com/alibaba-edu/Ranking-based-Instance-Selection)
* <a id="paper-311"></a> **[P311]** Augmentation Strategies for Learning with Noisy Labels.
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.02130)[[Code]](https://github.com/KentoNishi/Augmentation-for-LNL)
* <a id="paper-312"></a> **[P312]** Jo-SRC: A Contrastive Approach for Combating Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.13029.pdf)[[Code]](https://github.com/NUST-Machine-Intelligence-Laboratory/Jo-SRC)
* <a id="paper-313"></a> **[P313]** Partially View-aligned Representation Learning with Noise-robust Contrastive Loss.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Partially_View-Aligned_Representation_Learning_With_Noise-Robust_Contrastive_Loss_CVPR_2021_paper.pdf)[[Code]](https://github.com/XLearning-SCU/2021-CVPR-MvCLN)
* <a id="paper-314"></a> **[P314]** Correlated Input-Dependent Label Noise in Large-Scale Image Classification.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.10305)
* <a id="paper-315"></a> **[P315]** DAT: Training Deep Networks Robust To Label-Noise by Matching the Feature Distributions.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Qu_DAT_Training_Deep_Networks_Robust_To_Label-Noise_by_Matching_the_CVPR_2021_paper.pdf)
* <a id="paper-316"></a> **[P316]** Faster Meta Update Strategy for Noise-Robust Deep Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://github.com/youjiangxu/FaMUS/tree/main/paper)[[Code]](https://github.com/youjiangxu/FaMUS)
* <a id="paper-317"></a> **[P317]** Joint Negative and Positive Learning for Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.06574)
* <a id="paper-318"></a> **[P318]** Faster Meta Update Strategy for Noise-Robust Deep Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.15092)
* <a id="paper-319"></a> **[P319]** AutoDO: Robust AutoAugment for Biased Data with Label Noise via Scalable Probabilistic Implicit Differentiation.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.05863)[[Code]](https://github.com/gudovskiy/autodo)
* <a id="paper-320"></a> **[P320]** All Labels Are Not Created Equal: Enhancing Semi-supervision via Label Grouping and Co-training.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.05248)[[Code]](https://github.com/islam-nassar/semco)
* <a id="paper-321"></a> **[P321]** DualGraph: A graph-based method for reasoning about label noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_DualGraph_A_Graph-Based_Method_for_Reasoning_About_Label_Noise_CVPR_2021_paper.pdf)
* <a id="paper-322"></a> **[P322]** Background-Aware Pooling and Noise-Aware Loss for Weakly-Supervised Semantic Segmentation.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.00905)
* <a id="paper-323"></a> **[P323]** Meta Pseudo Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2003.10580.pdf)[[Code]](https://github.com/google-research/google-research/tree/master/meta_pseudo_labels)
* <a id="paper-324"></a> **[P324]** SimPLE: Similar Pseudo Label Exploitation for Semi-Supervised Classification.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.16725)[[Code]](https://github.com/zijian-hu/SimPLE)

---

### AAAI 2021

* <a id="paper-325"></a> **[P325]** Beyond Class-Conditional Assumption: A Primary Attempt to Combat Instance-Dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.05458)[[Code]](https://github.com/chenpf1025/IDN)
* <a id="paper-326"></a> **[P326]** Learning to Purify Noisy Labels via Meta Soft Label Corrector.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2008.00627)[[Code]](https://github.com/WuYichen-97/Learning-to-Purify-Noisy-Labels-via-Meta-Soft-Label-Corrector)
* <a id="paper-327"></a> **[P327]** Robustness of Accuracy Metric and its Inspirations in Learning with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.04193)[[Code]](https://github.com/chenpf1025/RobustnessAccuracy)
* <a id="paper-328"></a> **[P328]** Learning from Noisy Labels with Complementary Loss Functions.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://palm.seu.edu.cn/zhangml/files/AAAI'21a.pdf)[[Code]](https://github.com/dengbaowang/CompLossForNoisyLabels)
* <a id="paper-329"></a> **[P329]** Analysing the Noise Model Error for Realistic Noisy Label Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2101.09763)[[Code]](https://github.com/uds-lsv/noise-estimation)
* <a id="paper-330"></a> **[P330]** Tackling Instance-Dependent Label Noise via a Universal Probabilistic Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://niug1984.github.io/paper/wang_aaai21.pdf)
* <a id="paper-331"></a> **[P331]** Learning with Group Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://gcatnjust.github.io/ChenGong/paper/wang_aaai21_2.pdf)
* <a id="paper-332"></a> **[P332]** Meta Label Correction for Noisy Label Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.microsoft.com/en-us/research/publication/meta-label-correction-for-noisy-label-learning/)

---

### Other Conferences 2021

* <a id="paper-333"></a> **[P333]** (ICCV 2021) Learning with Noisy Labels via Sparse Regularization.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2108.00192)
* <a id="paper-334"></a> **[P334]** (WACV 2022) Towards a Robust Differentiable Architecture Search under Label Noise.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.12197)
* <a id="paper-335"></a> **[P335]** (BMVC 2021) PropMix: Hard Sample Filtering and Proportional MixUp for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.11809)[[Code]](https://github.com/filipe-research/PropMix.)
* <a id="paper-336"></a> **[P336]** (IJCAI2021 Workshop) An Ensemble Noise-Robust K-fold Cross-Validation Selection Method for Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2107.02347)

---

* <a id="paper-337"></a> **[P337]** (ICCV 2021) Learning with Noisy Labels for Robust Point Cloud Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://shuquanye.com/PNAL_website/)[[Code]](https://github.com/pleaseconnectwifi/PNAL)
* <a id="paper-338"></a> **[P338]** (WACV 2022) Addressing out-of-distribution label noise in webly-labelled data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.13699)[[Code]](https://github.com/PaulAlbert31/DSOS)

### ArXiv 2021

* <a id="paper-339"></a> **[P339]** Understanding Generalized Label Smoothing when Learning with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.04149)
* <a id="paper-340"></a> **[P340]** A Good Representation Detects Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.06283.pdf)
* <a id="paper-341"></a> **[P341]** Demystifying How Self-Supervised Features Improve Training from Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.09022.pdf)[[code]](https://github.com/UCSC-REAL/SelfSup_NoisyLabel)
* <a id="paper-342"></a> **[P342]** Pervasive Label Errors in Test Sets Destabilize Machine Learning Benchmarks.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.14749)[[Code]](https://github.com/cgnorthcutt/label-errors)
* <a id="paper-343"></a> **[P343]** Double Descent in Adversarial Training: An Implicit Label Noise Perspective.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.03135.pdf)
* <a id="paper-344"></a> **[P344]** A Theoretical Analysis of Learning with Noisily Labeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.04114)
* <a id="paper-345"></a> **[P345]** Analysis of classifiers robust to noisy labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.00274)
* <a id="paper-346"></a> **[P346]** NoiLIn: Do Noisy Labels Always Hurt Adversarial Training?
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.14676)
* <a id="paper-347"></a> **[P347]** Alleviating Noisy-label Effects in Image Classification via Probability Transition Matrix.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.08866)
* <a id="paper-348"></a> **[P348]** Learning with Noisy Labels by Targeted Relabeling.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.08355)
* <a id="paper-349"></a> **[P349]** Simple Attention Module based Speaker Verification with Iterative noisy label detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.06534)
* <a id="paper-350"></a> **[P350]** Adaptive Hierarchical Similarity Metric Learning with Noisy Labels.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.00006)
* <a id="paper-351"></a> **[P351]** A Survey of Label-noise Representation Learning: Past, Present and Future.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2011.04406.pdf)
* <a id="paper-352"></a> **[P352]** Noisy-Labeled NER with Confidence Estimation.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.04318.pdf)[[Code]](https://github.com/liukun95/Noisy-NER-Confidence-Estimation)
* <a id="paper-353"></a> **[P353]** Contrast to Divide: Self-Supervised Pre-Training for Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.13646.pdf)[[Code]](https://github.com/ContrastToDivide/C2D)
* <a id="paper-354"></a> **[P354]** Exponentiated Gradient Reweighting for Robust Training Under Label Noise and Beyond.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.01493.pdf)
* <a id="paper-355"></a> **[P355]** Understanding the Interaction of Adversarial Training with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.03482.pdf)
* <a id="paper-356"></a> **[P356]** Learning from Noisy Labels via Dynamic Loss Thresholding.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.02570.pdf)
* <a id="paper-357"></a> **[P357]** Self-Supervised Noisy Label Learning for Source-Free Unsupervised Domain Adaptation.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.11614.pdf)
* <a id="paper-358"></a> **[P358]** Transform consistency for learning with noisy labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.13872.pdf)
* <a id="paper-359"></a> **[P359]** Learning to Combat Noisy Labels via Classification Margins.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.00751.pdf)
* <a id="paper-360"></a> **[P360]** DST: Data Selection and joint Training for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.00813.pdf)
* <a id="paper-361"></a> **[P361]** LongReMix: Robust Learning with High Confidence Samples in a Noisy Label Environment.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.04173.pdf)
* <a id="paper-362"></a> **[P362]** Ensemble Learning with Manifold-Based Data Splitting for Noisy Label Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.07641.pdf)
* <a id="paper-363"></a> **[P363]** MetaLabelNet: Learning to Generate Soft-Labels from Noisy-Labels.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.10869.pdf)
* <a id="paper-364"></a> **[P364]** On the Robustness of Monte Carlo Dropout Trained with Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.12002.pdf)
* <a id="paper-365"></a> **[P365]** Co-matching: Combating Noisy Labels by Augmentation Anchoring.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.12814.pdf)
* <a id="paper-366"></a> **[P366]** Approximating Instance-Dependent Noise via Instance-Confidence Embedding.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.13569)
* <a id="paper-367"></a> **[P367]** Rethinking Noisy Label Models: Labeler-Dependent Noise with Adversarial Awareness.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.14083)
* <a id="paper-368"></a> **[P368]** ScanMix: Learning from Severe Label Noise viaSemantic Clustering and Semi-Supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.11395)
* <a id="paper-369"></a> **[P369]** Friends and Foes in Learning from Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.15055.pdf)
* <a id="paper-370"></a> **[P370]** A Fremework Using Contrastive Learning for Classification with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.09563.pdf)
* <a id="paper-371"></a> **[P371]** Contrastive Learning Improves Model Robustness Under Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.08984.pdf)[[Code]](https://github.com/arghosh/noisy_label_pretrain)
* <a id="paper-372"></a> **[P372]** Noise-Resistant Deep Metric Learning with Probabilistic Instance Filtering.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.01431.pdf)
* <a id="paper-373"></a> **[P373]** Compensation Learning.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.11921.pdf)
* <a id="paper-374"></a> **[P374]** kNet: A Deep kNN Network To Handle Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.09735.pdf)
* <a id="paper-375"></a> **[P375]** Memorization in Deep Neural Networks: Does the Loss Function matter?.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.09957.pdf)
* <a id="paper-376"></a> **[P376]** Mitigating Memorization in Sample Selection for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.07041.pdf)
* <a id="paper-377"></a> **[P377]** P-DIFF: Learning Classifier with Noisy Labels based on Probability Difference Distributions.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2009.06382)[[Code]](https://github.com/fistyee/P-DIFF)
* <a id="paper-378"></a> **[P378]** Decoupling Representation and Classifier for Noisy Label Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2011.08145.pdf)
* <a id="paper-379"></a> **[P379]** Contrastive Representations for Label Noise Require Fine-Tuning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.09154.pdf)
* <a id="paper-380"></a> **[P380]** NGC: A Unified Framework for Learning with Open-World Noisy Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.11035.pdf)
* <a id="paper-381"></a> **[P381]** Assessing the Quality of the Datasets by Identifying Mislabeled Samples.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2109.05000.pdf)
* <a id="paper-382"></a> **[P382]** Learning to Aggregate and Refine Noisy Labels for Visual Sentiment Analysis.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2109.07509)
* <a id="paper-383"></a> **[P383]** Robustness and reliability when training with noisy labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.03321.pdf)
* <a id="paper-384"></a> **[P384]** Consistency Regularization Can Improve Robustness to Label Noise.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.01242.pdf)

---

* <a id="paper-385"></a> **[P385]** Learning from Multiple Annotators by Incorporating Instance Features.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.15146)
* <a id="paper-386"></a> **[P386]** Learning from Multiple Noisy Partial Labelers.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.04530)
* <a id="paper-387"></a> **[P387]** Instance Correction for Learning with Open-set Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.00455)
* <a id="paper-388"></a> **[P388]** Robust Deep Learning from Crowds with Belief Propagation.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.00734)
* <a id="paper-389"></a> **[P389]** Prototypical Classifier for Robust Class-Imbalanced Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.11553)
* <a id="paper-390"></a> **[P390]** Study Group Learning: Improving Retinal Vessel Segmentation Trained with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.03451.pdf)[[Code]](https://github.com/SHI-Labs/SGL-Retinal-Vessel-Segmentation)
* <a id="paper-391"></a> **[P391]** Evaluating Multi-label Classifiers with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.08427.pdf)
* <a id="paper-392"></a> **[P392]** Robust Classification from Noisy Labels: Integrating Additional Knowledge for Chest Radiography Abnormality Assessment.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.05261.pdf)
* <a id="paper-393"></a> **[P393]** A Novel Perspective for Positive-Unlabeled Learning via Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.04685.pdf)
* <a id="paper-394"></a> **[P394]** Pathological Image Segmentation with Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.02602.pdf)
* <a id="paper-395"></a> **[P395]** CrowdTeacher: Robust Co-teaching with Noisy Answers & Sample-specific Perturbations for Tabular Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.17144.pdf)
* <a id="paper-396"></a> **[P396]** Learning from Noisy Labels for Entity-Centric Information Extraction.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.08656.pdf)
* <a id="paper-397"></a> **[P397]** Temporal-aware Language Representation Learning From Crowdsourced Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.07958.pdf)
* <a id="paper-398"></a> **[P398]** Learning From Long-Tailed Data With Noisy Labels.
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.11096.pdf)
* <a id="paper-399"></a> **[P399]** Robust Long-Tailed Learning Under Label Noise.
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.11569.pdf)
* <a id="paper-400"></a> **[P400]** Robust Temporal Ensembling for Learning with Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2109.14563.pdf)
* <a id="paper-401"></a> **[P401]** Knowledge Distillation with Noisy Labels for Natural Language Understanding.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2109.10147.pdf)
* <a id="paper-402"></a> **[P402]** Noisy Annotations Robust Consensual Collaborative Affect Expression Recognition.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021W/ABAW/papers/Gera_Noisy_Annotations_Robust_Consensual_Collaborative_Affect_Expression_Recognition_ICCVW_2021_paper.pdf)

## Papers & Code in 2020

---

### ICML 2020

* <a id="paper-403"></a> **[P403]** Peer Loss Functions: Learning from Noisy Labels without Knowing Noise Rates.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/liu20e)[[Code 1]](https://github.com/weijiaheng/Multi-class-Peer-Loss-functions) [[Code 2]](https://github.com/gohsyi/PeerLoss)
* <a id="paper-404"></a> **[P404]** Normalized Loss Functions for Deep Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2006.13554)[[Code]](https://github.com/HanxunH/Active-Passive-Losses)
* <a id="paper-405"></a> **[P405]** SIGUA: Forgetting May Make Learning with Noisy Labels More Robust.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/han20c.html)[[Code]](https://github.com/bhanML/SIGUA)
* <a id="paper-406"></a> **[P406]** Error-Bounded Correction of Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/zheng20c.html)[[Code]](https://github.com/pingqingsheng/LRT)
* <a id="paper-407"></a> **[P407]** Training Binary Neural Networks through Learning with Noisy Supervision.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/han20d.html)[[Code]](https://github.com/zhaohui-yang/Binary-Neural-Networks)
* <a id="paper-408"></a> **[P408]** Improving generalization by controlling label-noise information in neural network weights.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/harutyunyan20a.html)[[Code]](https://github.com/hrayrhar/limit-label-memorization)
* <a id="paper-409"></a> **[P409]** Searching to Exploit Memorization Effect in Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/yao20b.html)[[Code]](https://github.com/jerermyyoung/rtlearning)
* <a id="paper-410"></a> **[P410]** Learning with Bounded Instance and Label-dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/cheng20c.html)
* <a id="paper-411"></a> **[P411]** Label-Noise Robust Domain Adaptation.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/yu20c.html)
* <a id="paper-412"></a> **[P412]** Beyond Synthetic Noise: Deep Learning on Controlled Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/jiang20c)
* <a id="paper-413"></a> **[P413]** Does label smoothing mitigate label noise?.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/lukasik20a.html)
* <a id="paper-414"></a> **[P414]** Deep k-NN for Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/bahri20a.html)
* <a id="paper-415"></a> **[P415]** Self-PU: Self Boosted and Calibrated Positive-Unlabeled Training.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2006.11280)[[Code]](https://github.com/VITA-Group/Self-PU)
* <a id="paper-416"></a> **[P416]** Learning with Multiple Complementary Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/feng20a.html)
* <a id="paper-417"></a> **[P417]** Extreme Multi-label Classification from Aggregated Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/shen20f.html)

---

### ICLR 2020

* <a id="paper-418"></a> **[P418]** DivideMix: Learning with Noisy Labels as Semi-supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=HJgExaVtwr)[[Code]](https://github.com/LiJunnan1992/DivideMix)
* <a id="paper-419"></a> **[P419]** Learning from Rules Generalizing Labeled Exemplars.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=SkeuexBtDr) [[Code]](https://github.com/awasthiabhijeet/Learning-From-Rules)
* <a id="paper-420"></a> **[P420]** Robust training with ensemble consensus.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=ryxOUTVYDH)[[Code]](https://github.com/jisoolee0123/Robust-training-with-ensemble-consensus)
* <a id="paper-421"></a> **[P421]** Self-labelling via simultaneous clustering and representation learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Hyx-jyBFPr)[[Code]](https://github.com/yukimasano/self-label)
* <a id="paper-422"></a> **[P422]** Can gradient clipping mitigate label noise?
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rklB76EKPr)[[Code]](https://github.com/dmizr/phuber)
* <a id="paper-423"></a> **[P423]** Curriculum Loss: Robust Learning and Generalization against Label Corruption.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rkgt0REKwS)
* <a id="paper-424"></a> **[P424]** Simple and Effective Regularization Methods for Training on Noisily Labeled Data with Generalization Guarantee.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Hke3gyHYwH)
* <a id="paper-425"></a> **[P425]** SELF: Learning to Filter Noisy Labels with Self-Ensembling.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=HkgsPhNYPS)

---

* <a id="paper-426"></a> **[P426]** Mutual Mean-Teaching: Pseudo Label Refinery for Unsupervised Domain Adaptation on Person Re-identification.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rJlnOhVYPS)[[Code]](https://github.com/yxgeee/MMT)

### NIPS 2020

* <a id="paper-427"></a> **[P427]** Part-dependent Label Noise: Towards Instance-dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/5607fe8879e4fd269e88387e8cb30b7e-Abstract.html)[[Code]](https://github.com/xiaoboxia/Part-dependent-label-noise)
* <a id="paper-428"></a> **[P428]** Identifying Mislabeled Data using the Area Under the Margin Ranking.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/c6102b3727b2a7d8b1bb6981147081ef-Abstract.html)[[Code]](https://github.com/asappresearch/aum)
* <a id="paper-429"></a> **[P429]** Dual T: Reducing Estimation Error for Transition Matrix in Label-noise Learning.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/512c5cad6c37edb98ae91c8a76c3a291-Abstract.html)
* <a id="paper-430"></a> **[P430]** Early-Learning Regularization Prevents Memorization of Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/ea89621bee7c88b2c5be6681c8ef4906-Abstract.html)[[Code]](https://github.com/shengliu66/ELR)
* <a id="paper-431"></a> **[P431]** Coresets for Robust Training of Deep Neural Networks against Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/8493eeaccb772c0878f99d60a0bd2bb3-Abstract.html)[[Code]](https://github.com/snap-stanford/crust)
* <a id="paper-432"></a> **[P432]** Robust Optimization for Fairness with Noisy Protected Groups.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/37d097caf1299d9aa79c2c2b843d2d78-Abstract.html)[[Code]](https://github.com/wenshuoguo/robust-fairness-code)
* <a id="paper-433"></a> **[P433]** Stochastic Optimization with Heavy-Tailed Noise via Accelerated Gradient Clipping.
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/abd1c782880cc59759f4112fda0b8f98-Abstract.html)[[Code]](https://github.com/eduardgorbunov/accelerated_clipping)
* <a id="paper-434"></a> **[P434]** A Topological Filter for Learning with Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/f4e3ce3e7b581ff32e40968298ba013d-Abstract.html)[[Code]](https://github.com/pxiangwu/TopoFilter)
* <a id="paper-435"></a> **[P435]** Self-Adaptive Training: beyond Empirical Risk Minimization.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc//paper/2020/hash/e0ab531ec312161511493b002f9be2ee-Abstract.html)[[Code]](https://github.com/LayneH/self-adaptive-training)
* <a id="paper-436"></a> **[P436]** Non-Convex SGD Learns Halfspaces with Adversarial Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/d785bf9067f8af9e078b93cf26de2b54-Abstract.html)
* <a id="paper-437"></a> **[P437]** Efficient active learning of sparse halfspaces with arbitrary bounded noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/5034a5d62f91942d2a7aeaf527dfe111-Abstract.html)
* <a id="paper-438"></a> **[P438]** MetaPoison: Practical General-purpose Clean-label Data Poisoning.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/8ce6fc704072e351679ac97d4a985574-Abstract.html)[[Code 1]](https://github.com/wronnyhuang/metapoison)[[Code]](https://github.com/JonasGeiping/poisoning-gradient-matching)
* <a id="paper-439"></a> **[P439]** Provably Consistent Partial-Label Learning.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/7bd28f15a49d5e5848d6ec70e584e625-Abstract.html)
* <a id="paper-440"></a> **[P440]** Modeling Noisy Annotations for Crowd Counting.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/22bb543b251c39ccdad8063d486987bb-Abstract.html)[[Code]](https://github.com/jia-wan/NoisyCC-pytorch)
* <a id="paper-441"></a> **[P441]** Disentangling Human Error from the Ground Truth in Segmentation of Medical Images.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc//paper/2020/file/b5d17ed2b502da15aa727af0d51508d6-Paper.pdf)[[Code]](https://github.com/moucheng2017/Learn_Noisy_Labels_Medical_Images)
* <a id="paper-442"></a> **[P442]** Semi-Supervised Partial Label Learning via Confidence-Rated Margin Maximization.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/4dea382d82666332fb564f2e711cbc71-Abstract.html)
* <a id="paper-443"></a> **[P443]** Labelling unlabelled videos from scratch with multi-modal self-supervision.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/31fefc0e570cb3860f2a6d4b38c6490d-Abstract.html)[[Code]](https://github.com/facebookresearch/selavi)
* <a id="paper-444"></a> **[P444]** Distribution Aligning Refinery of Pseudo-label for Imbalanced Semi-supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/a7968b4339a1b85b7dbdb362dc44f9c4-Abstract.html)[[Code]](https://github.com/bbuing9/DARP)
* <a id="paper-445"></a> **[P445]** A Variational Approach for Learning from Positive and Unlabeled Data.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/aa0d2a804a3510442f2fd40f2100b054-Abstract.html)[[Code]](https://github.com/HC-Feynman/vpu)

---

### KDD 2020

* <a id="paper-446"></a> **[P446]** Semi-Supervised Multi-Label Learning from Crowds via Deep Sequential Generative Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3394486.3403167)

---

### AAAI 2020

* <a id="paper-447"></a> **[P447]** Reinforcement Learning with Perturbed Rewards.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/1810.01032) [[Code]](https://github.com/wangjksjtu/rl-perturbed-reward)
* <a id="paper-448"></a> **[P448]** Less Is Better: Unweighted Data Subsampling via Influence Function.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/1912.01321) [[Code]](https://github.com/RyanWangZf/Influence_Subsampling)
* <a id="paper-449"></a> **[P449]** Self-Paced Robust Learning for Leveraging Clean Labels in Noisy Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://xuczhang.github.io/papers/aaai20_sprl.pdf)
* <a id="paper-450"></a> **[P450]** Label Error Correction and Generation Through Label Relationships.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5778)

---

* <a id="paper-451"></a> **[P451]** Weakly Supervised Sequence Tagging from Noisy Rules.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/6009)[[Code]](https://github.com/BatsResearch/wiser)
* <a id="paper-452"></a> **[P452]** Coupled-View Deep Classifier Learning from Multiple Noisy Annotators.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5898)
* <a id="paper-453"></a> **[P453]** Partial multi-label learning with noisy label identification.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](http://www.xiemk.pro/publication/aaai20-pml-ni.pdf)

### CVPR 2020

* <a id="paper-454"></a> **[P454]** Combating noisy labels by agreement: A joint training method with co-regularization.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Wei_Combating_Noisy_Labels_by_Agreement_A_Joint_Training_Method_with_CVPR_2020_paper.html)[[Code]](https://github.com/hongxin001/JoCoR)
* <a id="paper-455"></a> **[P455]** Distilling Effective Supervision From Severe Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Distilling_Effective_Supervision_From_Severe_Label_Noise_CVPR_2020_paper.html)[[Code]](https://github.com/google-research/google-research/tree/master/ieg)
* <a id="paper-456"></a> **[P456]** Self-Training With Noisy Student Improves ImageNet Classification.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Xie_Self-Training_With_Noisy_Student_Improves_ImageNet_Classification_CVPR_2020_paper.html)[[Code]](https://github.com/google-research/noisystudent)
* <a id="paper-457"></a> **[P457]** Global-Local GCN: Large-Scale Label Noise Cleansing for Face Recognition.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Global-Local_GCN_Large-Scale_Label_Noise_Cleansing_for_Face_Recognition_CVPR_2020_paper.html)
* <a id="paper-458"></a> **[P458]** Spherical Space Domain Adaptation With Robust Pseudo-Label Loss.
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.html)[[Code]](https://github.com/XJTU-XGU/RSDA)
* <a id="paper-459"></a> **[P459]** Training Noise-Robust Deep Neural Networks via Meta-Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Meta-learning](https://img.shields.io/badge/Meta--learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Training_Noise-Robust_Deep_Neural_Networks_via_Meta-Learning_CVPR_2020_paper.html)[[Code]](https://github.com/ZhenWang-PhD/Training-Noise-Robust-Deep-Neural-Networks-via-Meta-Learning)
* <a id="paper-460"></a> **[P460]** Generating Accurate Pseudo-Labels in Semi-Supervised Learning and Avoiding Overconfident Predictions via Hermite Polynomial Activations.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lokhande_Generating_Accurate_Pseudo-Labels_in_Semi-Supervised_Learning_and_Avoiding_Overconfident_Predictions_CVPR_2020_paper.html)[[Code]](https://github.com/lokhande-vishnu/DeepHermites)
* <a id="paper-461"></a> **[P461]** Revisiting Knowledge Distillation via Label Smoothing Regularization.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Yuan_Revisiting_Knowledge_Distillation_via_Label_Smoothing_Regularization_CVPR_2020_paper.html)[[Code]](https://github.com/yuanli2333/Teacher-free-Knowledge-Distillation)

---

* <a id="paper-462"></a> **[P462]** Noise Robust Generative Adversarial Networks.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Kaneko_Noise_Robust_Generative_Adversarial_Networks_CVPR_2020_paper.html)[[Code]](https://github.com/takuhirok/NR-GAN/)
* <a id="paper-463"></a> **[P463]** DLWL: Improving Detection for Lowshot Classes With Weakly Labelled Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Ramanathan_DLWL_Improving_Detection_for_Lowshot_Classes_With_Weakly_Labelled_Data_CVPR_2020_paper.html)
* <a id="paper-464"></a> **[P464]** Shoestring: Graph-Based Semi-Supervised Classification With Severely Limited Labeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lin_Shoestring_Graph-Based_Semi-Supervised_Classification_With_Severely_Limited_Labeled_Data_CVPR_2020_paper.html)[[Code]](https://github.com/iQua/CVPR2020-Shoestring)
* <a id="paper-465"></a> **[P465]** Noise-Aware Fully Webly Supervised Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Shen_Noise-Aware_Fully_Webly_Supervised_Object_Detection_CVPR_2020_paper.html)[[Code]](https://github.com/shenyunhang/NA-fWebSOD)
* <a id="paper-466"></a> **[P466]** Learning From Noisy Anchors for One-Stage Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_Learning_From_Noisy_Anchors_for_One-Stage_Object_Detection_CVPR_2020_paper.html)[[Code]](https://github.com/henrylee2570/NoisyAnchor)

### ECCV 2020

* <a id="paper-467"></a> **[P467]** Suppressing Mislabeled Data via Grouping and Self-Attention.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2633_ECCV_2020_paper.php)[[Code]](https://github.com/kaiwang960112/AFM)
* <a id="paper-468"></a> **[P468]** NoiseRank: Unsupervised Label Noise Reduction with Dependence Models.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/5921_ECCV_2020_paper.php)
* <a id="paper-469"></a> **[P469]** Learning with Noisy Class Labels for Instance Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2062_ECCV_2020_paper.php)[[Code]](https://github.com/longrongyang/LNCIS)
* <a id="paper-470"></a> **[P470]** Weakly Supervised Learning with Side Information for Noisy Labeled Images.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/7467_ECCV_2020_paper.php)
* <a id="paper-471"></a> **[P471]** Learning Noise-Aware Encoder-Decoder from Noisy Labels by Alternating Back-Propagation for Saliency Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2760_ECCV_2020_paper.php)
* <a id="paper-472"></a> **[P472]** Graph convolutional networks for learning with few clean and many noisy labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-supervised](https://img.shields.io/badge/Semi--supervised-22C55E)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1060_ECCV_2020_paper.php)

---

### ArXiv 2020

* <a id="paper-473"></a> **[P473]** No Regret Sample Selection with Noisy Labels. (Published on Machine Learning)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2003.03179.pdf)[[Code]](https://github.com/songheony/TAkS)
* <a id="paper-474"></a> **[P474]** Meta Soft Label Generation for Noisy Labels. (Published on ICPR 2020)
  ![Meta-learning](https://img.shields.io/badge/Meta--learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2007.05836.pdf)[[Code]](https://github.com/gorkemalgan/MSLG_noisy_label)
* <a id="paper-475"></a> **[P475]** Learning from Noisy Labels with Deep Neural Networks: A Survey.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2007.08199.pdf)
* <a id="paper-476"></a> **[P476]** RAR-U-Net: a Residual Encoder to Attention Decoder by Residual Connections Framework for Spine Segmentation under Noisy Labels. (Published on ICIP 2021)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2009.12873.pdf)
* <a id="paper-477"></a> **[P477]** Learning from Small Amount of Medical Data with Noisy Labels: A Meta-Learning Approach. (Published on ICRPOA 2021)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Meta-learning](https://img.shields.io/badge/Meta--learning-A855F7)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2010.06939.pdf)

---

## Acknowledgements

This repository is partially based on and inspired by the following project:

- https://github.com/weijiaheng/Advances-in-Label-Noise-Learning
