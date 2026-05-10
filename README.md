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
![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)

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
![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)

## Statistical Overview

<table>
  <tr>
    <td width="50%" align="center">
      <img src="outputs/figures/yearly_lnl_trend.png" alt="Publication trends in Learning with Noisy Labels" width="100%">
      <br>
      <sub>Publication trends by year and task domain.</sub>
    </td>
    <td width="50%" align="center">
      <img src="outputs/figures/technical_keyword_ranking.png" alt="Top technical keywords in Learning with Noisy Labels" width="100%">
      <br>
      <sub>Top technical keywords in Classification LNL.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="outputs/figures/task_type_distribution.png" alt="Task type distribution in Learning with Noisy Labels" width="100%">
      <br>
      <sub>Task expansion beyond standard classification.</sub>
    </td>
    <td width="50%" align="center">
      <img src="outputs/figures/LNL_wordcloud_2020_to_2026.png" alt="Technical keyword word cloud from 2020 to 2026" width="100%">
      <br>
      <sub>Technical keyword word cloud for 2020-2026.</sub>
    </td>
  </tr>
</table>

<!-- TASK_TYPE_INDEX_START -->
## Task Type Quick Index

> Paper numbers are clickable and jump to the corresponding entries below. Classification LNL is omitted here because it contains many entries.

### Long-tailed Learning (18)
![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)

[P031](#paper-031), [P044](#paper-044), [P067](#paper-067), [P080](#paper-080), [P110](#paper-110), [P160](#paper-160), [P188](#paper-188), [P249](#paper-249), [P285](#paper-285), [P288](#paper-288), [P303](#paper-303), [P305](#paper-305), [P376](#paper-376), [P383](#paper-383), [P548](#paper-548), [P557](#paper-557), [P558](#paper-558), [P585](#paper-585)

### Multi-Label (21)
![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)

[P035](#paper-035), [P060](#paper-060), [P132](#paper-132), [P174](#paper-174), [P182](#paper-182), [P190](#paper-190), [P287](#paper-287), [P293](#paper-293), [P308](#paper-308), [P310](#paper-310), [P317](#paper-317), [P332](#paper-332), [P441](#paper-441), [P444](#paper-444), [P475](#paper-475), [P550](#paper-550), [P602](#paper-602), [P642](#paper-642),
[P650](#paper-650), [P651](#paper-651), [P652](#paper-652)

### Graph Data (29)
![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)

[P010](#paper-010), [P025](#paper-025), [P040](#paper-040), [P090](#paper-090), [P109](#paper-109), [P117](#paper-117), [P125](#paper-125), [P127](#paper-127), [P140](#paper-140), [P159](#paper-159), [P172](#paper-172), [P173](#paper-173), [P183](#paper-183), [P185](#paper-185), [P189](#paper-189), [P210](#paper-210), [P213](#paper-213), [P229](#paper-229),
[P283](#paper-283), [P310](#paper-310), [P320](#paper-320), [P365](#paper-365), [P387](#paper-387), [P471](#paper-471), [P496](#paper-496), [P551](#paper-551), [P617](#paper-617), [P623](#paper-623), [P631](#paper-631)

### Object Detection (31)
![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)

[P041](#paper-041), [P089](#paper-089), [P104](#paper-104), [P151](#paper-151), [P152](#paper-152), [P162](#paper-162), [P163](#paper-163), [P185](#paper-185), [P189](#paper-189), [P227](#paper-227), [P250](#paper-250), [P266](#paper-266), [P267](#paper-267), [P268](#paper-268), [P272](#paper-272), [P290](#paper-290), [P300](#paper-300), [P308](#paper-308),
[P318](#paper-318), [P334](#paper-334), [P358](#paper-358), [P361](#paper-361), [P380](#paper-380), [P381](#paper-381), [P391](#paper-391), [P452](#paper-452), [P531](#paper-531), [P622](#paper-622), [P624](#paper-624), [P625](#paper-625), [P630](#paper-630)

### Segmentation (36)
![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)

[P056](#paper-056), [P061](#paper-061), [P063](#paper-063), [P069](#paper-069), [P081](#paper-081), [P106](#paper-106), [P147](#paper-147), [P153](#paper-153), [P155](#paper-155), [P162](#paper-162), [P216](#paper-216), [P243](#paper-243), [P254](#paper-254), [P263](#paper-263), [P270](#paper-270), [P272](#paper-272), [P282](#paper-282), [P286](#paper-286),
[P318](#paper-318), [P325](#paper-325), [P333](#paper-333), [P360](#paper-360), [P361](#paper-361), [P384](#paper-384), [P385](#paper-385), [P392](#paper-392), [P472](#paper-472), [P483](#paper-483), [P549](#paper-549), [P553](#paper-553), [P566](#paper-566), [P582](#paper-582), [P628](#paper-628), [P630](#paper-630), [P646](#paper-646), [P656](#paper-656)

### NLP/Text (69)
![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)

[P004](#paper-004), [P005](#paper-005), [P007](#paper-007), [P009](#paper-009), [P011](#paper-011), [P018](#paper-018), [P042](#paper-042), [P045](#paper-045), [P048](#paper-048), [P053](#paper-053), [P082](#paper-082), [P091](#paper-091), [P096](#paper-096), [P124](#paper-124), [P130](#paper-130), [P141](#paper-141), [P142](#paper-142), [P143](#paper-143),
[P144](#paper-144), [P146](#paper-146), [P147](#paper-147), [P191](#paper-191), [P192](#paper-192), [P195](#paper-195), [P218](#paper-218), [P229](#paper-229), [P242](#paper-242), [P246](#paper-246), [P264](#paper-264), [P266](#paper-266), [P272](#paper-272), [P306](#paper-306), [P308](#paper-308), [P312](#paper-312), [P317](#paper-317), [P345](#paper-345),
[P346](#paper-346), [P365](#paper-365), [P390](#paper-390), [P407](#paper-407), [P421](#paper-421), [P425](#paper-425), [P435](#paper-435), [P440](#paper-440), [P446](#paper-446), [P453](#paper-453), [P483](#paper-483), [P488](#paper-488), [P493](#paper-493), [P494](#paper-494), [P502](#paper-502), [P526](#paper-526), [P534](#paper-534), [P537](#paper-537),
[P555](#paper-555), [P560](#paper-560), [P580](#paper-580), [P585](#paper-585), [P597](#paper-597), [P606](#paper-606), [P609](#paper-609), [P610](#paper-610), [P611](#paper-611), [P619](#paper-619), [P621](#paper-621), [P639](#paper-639), [P649](#paper-649), [P652](#paper-652), [P654](#paper-654)

### Vision-Language (22)
![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)

[P018](#paper-018), [P023](#paper-023), [P024](#paper-024), [P058](#paper-058), [P059](#paper-059), [P079](#paper-079), [P104](#paper-104), [P129](#paper-129), [P142](#paper-142), [P145](#paper-145), [P154](#paper-154), [P195](#paper-195), [P226](#paper-226), [P242](#paper-242), [P246](#paper-246), [P289](#paper-289), [P365](#paper-365), [P425](#paper-425),
[P426](#paper-426), [P446](#paper-446), [P577](#paper-577), [P608](#paper-608)

### Multimodal (4)
![Multimodal](https://img.shields.io/badge/task-Multimodal-0F766E?style=flat-square)

[P062](#paper-062), [P128](#paper-128), [P186](#paper-186), [P319](#paper-319)

### LLM Alignment (14)
![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)

[P006](#paper-006), [P007](#paper-007), [P009](#paper-009), [P012](#paper-012), [P013](#paper-013), [P016](#paper-016), [P026](#paper-026), [P049](#paper-049), [P085](#paper-085), [P103](#paper-103), [P111](#paper-111), [P118](#paper-118), [P120](#paper-120), [P378](#paper-378)

### Medical Imaging (14)
![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)

[P050](#paper-050), [P059](#paper-059), [P061](#paper-061), [P081](#paper-081), [P108](#paper-108), [P121](#paper-121), [P291](#paper-291), [P293](#paper-293), [P307](#paper-307), [P551](#paper-551), [P582](#paper-582), [P646](#paper-646), [P656](#paper-656), [P657](#paper-657)

### Federated Learning (14)
![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)

[P026](#paper-026), [P029](#paper-029), [P034](#paper-034), [P048](#paper-048), [P094](#paper-094), [P161](#paper-161), [P178](#paper-178), [P179](#paper-179), [P180](#paper-180), [P187](#paper-187), [P252](#paper-252), [P253](#paper-253), [P305](#paper-305), [P395](#paper-395)

### Time Series (17)
![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)

[P022](#paper-022), [P026](#paper-026), [P042](#paper-042), [P051](#paper-051), [P082](#paper-082), [P087](#paper-087), [P089](#paper-089), [P112](#paper-112), [P211](#paper-211), [P212](#paper-212), [P256](#paper-256), [P284](#paper-284), [P304](#paper-304), [P396](#paper-396), [P481](#paper-481), [P556](#paper-556), [P559](#paper-559)

### Retrieval (29)
![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)

[P011](#paper-011), [P027](#paper-027), [P028](#paper-028), [P043](#paper-043), [P084](#paper-084), [P085](#paper-085), [P088](#paper-088), [P131](#paper-131), [P209](#paper-209), [P271](#paper-271), [P274](#paper-274), [P283](#paper-283), [P292](#paper-292), [P359](#paper-359), [P362](#paper-362), [P364](#paper-364), [P388](#paper-388), [P397](#paper-397),
[P409](#paper-409), [P426](#paper-426), [P442](#paper-442), [P469](#paper-469), [P470](#paper-470), [P476](#paper-476), [P532](#paper-532), [P538](#paper-538), [P541](#paper-541), [P611](#paper-611), [P635](#paper-635)

### Generative Models (27)
![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)

[P006](#paper-006), [P031](#paper-031), [P053](#paper-053), [P056](#paper-056), [P057](#paper-057), [P059](#paper-059), [P068](#paper-068), [P069](#paper-069), [P107](#paper-107), [P119](#paper-119), [P123](#paper-123), [P124](#paper-124), [P139](#paper-139), [P142](#paper-142), [P209](#paper-209), [P264](#paper-264), [P312](#paper-312), [P345](#paper-345),
[P365](#paper-365), [P425](#paper-425), [P494](#paper-494), [P537](#paper-537), [P620](#paper-620), [P621](#paper-621), [P639](#paper-639), [P652](#paper-652), [P654](#paper-654)

### Audio/Video (11)
![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)

[P053](#paper-053), [P082](#paper-082), [P087](#paper-087), [P242](#paper-242), [P246](#paper-246), [P266](#paper-266), [P268](#paper-268), [P284](#paper-284), [P379](#paper-379), [P581](#paper-581), [P584](#paper-584)

### 3D/Point Cloud (9)
![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)

[P142](#paper-142), [P214](#paper-214), [P269](#paper-269), [P271](#paper-271), [P290](#paper-290), [P325](#paper-325), [P378](#paper-378), [P566](#paper-566), [P580](#paper-580)

### Anomaly/OOD (28)
![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)

[P005](#paper-005), [P023](#paper-023), [P082](#paper-082), [P083](#paper-083), [P089](#paper-089), [P095](#paper-095), [P102](#paper-102), [P143](#paper-143), [P152](#paper-152), [P161](#paper-161), [P176](#paper-176), [P177](#paper-177), [P185](#paper-185), [P189](#paper-189), [P210](#paper-210), [P250](#paper-250), [P268](#paper-268), [P300](#paper-300),
[P316](#paper-316), [P334](#paper-334), [P372](#paper-372), [P377](#paper-377), [P411](#paper-411), [P423](#paper-423), [P527](#paper-527), [P542](#paper-542), [P546](#paper-546), [P567](#paper-567)

### Crowdsourcing (33)
![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)

[P017](#paper-017), [P030](#paper-030), [P052](#paper-052), [P102](#paper-102), [P103](#paper-103), [P122](#paper-122), [P133](#paper-133), [P208](#paper-208), [P230](#paper-230), [P241](#paper-241), [P243](#paper-243), [P264](#paper-264), [P265](#paper-265), [P311](#paper-311), [P314](#paper-314), [P325](#paper-325), [P335](#paper-335), [P351](#paper-351),
[P360](#paper-360), [P375](#paper-375), [P424](#paper-424), [P442](#paper-442), [P539](#paper-539), [P544](#paper-544), [P545](#paper-545), [P547](#paper-547), [P554](#paper-554), [P556](#paper-556), [P561](#paper-561), [P581](#paper-581), [P641](#paper-641), [P648](#paper-648), [P652](#paper-652)

### Semi-Supervised Learning (46)
![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)

[P010](#paper-010), [P012](#paper-012), [P052](#paper-052), [P062](#paper-062), [P081](#paper-081), [P087](#paper-087), [P153](#paper-153), [P162](#paper-162), [P164](#paper-164), [P171](#paper-171), [P191](#paper-191), [P213](#paper-213), [P216](#paper-216), [P237](#paper-237), [P248](#paper-248), [P251](#paper-251), [P255](#paper-255), [P263](#paper-263),
[P268](#paper-268), [P269](#paper-269), [P284](#paper-284), [P291](#paper-291), [P313](#paper-313), [P317](#paper-317), [P380](#paper-380), [P381](#paper-381), [P386](#paper-386), [P408](#paper-408), [P419](#paper-419), [P442](#paper-442), [P445](#paper-445), [P454](#paper-454), [P455](#paper-455), [P473](#paper-473), [P474](#paper-474), [P483](#paper-483),
[P552](#paper-552), [P585](#paper-585), [P600](#paper-600), [P611](#paper-611), [P618](#paper-618), [P619](#paper-619), [P624](#paper-624), [P629](#paper-629), [P634](#paper-634), [P640](#paper-640)

### Partial Label Learning (22)
![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)

[P054](#paper-054), [P055](#paper-055), [P126](#paper-126), [P132](#paper-132), [P174](#paper-174), [P215](#paper-215), [P244](#paper-244), [P309](#paper-309), [P310](#paper-310), [P315](#paper-315), [P330](#paper-330), [P352](#paper-352), [P393](#paper-393), [P394](#paper-394), [P441](#paper-441), [P443](#paper-443), [P444](#paper-444), [P494](#paper-494),
[P545](#paper-545), [P576](#paper-576), [P583](#paper-583), [P651](#paper-651)

### Weak Supervision (24)
![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)

[P084](#paper-084), [P181](#paper-181), [P182](#paper-182), [P217](#paper-217), [P231](#paper-231), [P245](#paper-245), [P247](#paper-247), [P272](#paper-272), [P308](#paper-308), [P314](#paper-314), [P363](#paper-363), [P378](#paper-378), [P379](#paper-379), [P385](#paper-385), [P388](#paper-388), [P396](#paper-396), [P425](#paper-425), [P466](#paper-466),
[P472](#paper-472), [P567](#paper-567), [P586](#paper-586), [P601](#paper-601), [P620](#paper-620), [P622](#paper-622)

### Other Tasks (47)
![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)

[P008](#paper-008), [P039](#paper-039), [P047](#paper-047), [P086](#paper-086), [P100](#paper-100), [P101](#paper-101), [P138](#paper-138), [P175](#paper-175), [P206](#paper-206), [P207](#paper-207), [P228](#paper-228), [P239](#paper-239), [P240](#paper-240), [P273](#paper-273), [P324](#paper-324), [P331](#paper-331), [P350](#paper-350), [P373](#paper-373),
[P374](#paper-374), [P406](#paper-406), [P422](#paper-422), [P436](#paper-436), [P437](#paper-437), [P438](#paper-438), [P439](#paper-439), [P468](#paper-468), [P482](#paper-482), [P528](#paper-528), [P529](#paper-529), [P530](#paper-530), [P533](#paper-533), [P535](#paper-535), [P536](#paper-536), [P540](#paper-540), [P543](#paper-543), [P573](#paper-573),
[P578](#paper-578), [P579](#paper-579), [P598](#paper-598), [P599](#paper-599), [P607](#paper-607), [P632](#paper-632), [P633](#paper-633), [P636](#paper-636), [P637](#paper-637), [P647](#paper-647), [P655](#paper-655)

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
  - [ICLR 2026](#iclr-2026)
  - [CVPR 2026](#cvpr-2026)
  - [AAAI 2026](#aaai-2026)
  - [WACV 2026](#wacv-2026)
  - [Top Journals 2026](#top-journals-2026)
- [Papers & Code in 2025](#papers--code-in-2025)
  - [NeurIPS 2025](#neurips-2025)
  - [ICML 2025](#icml-2025)
  - [ICLR 2025](#iclr-2025)
  - [CVPR 2025](#cvpr-2025)
  - [ICCV 2025](#iccv-2025)
  - [AAAI 2025](#aaai-2025)
  - [Other Conferences 2025](#other-conferences-2025)
  - [Top Journals 2025](#top-journals-2025)
- [Papers & Code in 2024](#papers--code-in-2024)
  - [Neurips 2024](#neurips-2024)
  - [ICML 2024](#icml-2024)
  - [ICLR 2024](#iclr-2024)
  - [CVPR 2024](#cvpr-2024)
  - [ECCV 2024](#eccv-2024)
  - [AAAI 2024](#aaai-2024)
  - [IJCAI 2024](#ijcai-2024)
  - [KDD 2024](#kdd-2024)
  - [ACM MM 2024](#acm-mm-2024)
  - [Top Journals 2024](#top-journals-2024)
- [Papers & Code in 2023](#papers--code-in-2023)
  - [NeurIPS 2023](#neurips-2023)
  - [ICML 2023](#icml-2023)
  - [ICLR 2023](#iclr-2023)
  - [CVPR 2023](#cvpr-2023)
  - [ICCV 2023](#iccv-2023)
  - [AAAI 2023](#aaai-2023)
  - [IJCAI 2023](#ijcai-2023)
  - [KDD 2023](#kdd-2023)
  - [ACM MM 2023](#acm-mm-2023)
  - [Top Journals 2023](#top-journals-2023)
- [Papers & Code in 2022](#papers--code-in-2022)
  - [NeurIPS 2022](#neurips-2022)
  - [ICML 2022](#icml-2022)
  - [ICLR 2022](#iclr-2022)
  - [CVPR 2022](#cvpr-2022)
  - [ECCV 2022](#eccv-2022)
  - [AAAI 2022](#aaai-2022)
  - [IJCAI 2022](#ijcai-2022)
  - [KDD 2022](#kdd-2022)
  - [ACM MM 2022](#acm-mm-2022)
  - [ArXiv 2022](#arxiv-2022)
  - [Top Journals 2022](#top-journals-2022)
- [Papers & Code in 2021](#papers--code-in-2021)
  - [NeurIPS 2021](#neurips-2021)
  - [ICML 2021](#icml-2021)
  - [ICLR 2021](#iclr-2021)
  - [CVPR 2021](#cvpr-2021)
  - [ICCV 2021](#iccv-2021)
  - [AAAI 2021](#aaai-2021)
  - [IJCAI 2021](#ijcai-2021)
  - [KDD 2021](#kdd-2021)
  - [ACM MM 2021](#acm-mm-2021)
  - [ArXiv 2021](#arxiv-2021)
  - [Other Conferences 2021](#other-conferences-2021)
- [Papers & Code in 2020](#papers--code-in-2020)
  - [NIPS 2020](#nips-2020)
  - [ICML 2020](#icml-2020)
  - [ICLR 2020](#iclr-2020)
  - [CVPR 2020](#cvpr-2020)
  - [ECCV 2020](#eccv-2020)
  - [AAAI 2020](#aaai-2020)
  - [IJCAI 2020](#ijcai-2020)
  - [KDD 2020](#kdd-2020)
  - [ArXiv 2020](#arxiv-2020)
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
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
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
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=tuvkrivvbG)
* <a id="paper-004"></a> **[P004]** LANE: Label-Aware Noise Elimination for Fine-Grained Text Classification.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=PuayLKdrFz)
* <a id="paper-005"></a> **[P005]** Noise-Aware Generalization: Robustness to In-Domain Noise and Out-of-Domain Generalization.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=wb83wO41QT)
* <a id="paper-006"></a> **[P006]** Learning from Noisy Preferences: A Semi-Supervised Learning Approach to Direct Preference Optimization.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rRc04jyoAk)
* <a id="paper-007"></a> **[P007]** RE-PO: Robust Enhanced Policy Optimization as a General Framework for LLM Alignment.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=jDKpOvTCM8)
* <a id="paper-008"></a> **[P008]** Conformal Prediction with Corrupted Labels: Uncertain Imputation and Robust Re-weighting.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://iclr.cc/virtual/2026/poster/10006410)
* <a id="paper-009"></a> **[P009]** Aligner, Diagnose Thyself: A Meta-Learning Paradigm for Fusing Intrinsic Feedback in Preference Alignment.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://iclr.cc/virtual/2026/poster/10007430)
* <a id="paper-010"></a> **[P010]** GNN-as-Judge: Unleashing the Power of LLMs for Graph Few-shot Semi-supervised Learning with GNN Feedback.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://iclr.cc/virtual/2026/poster/10007476)
* <a id="paper-011"></a> **[P011]** Task-Aware Data Selection via Proxy-Label Enhanced Distribution Matching for LLM Finetuning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://iclr.cc/virtual/2026/poster/10009535)
* <a id="paper-012"></a> **[P012]** Noisy-Pair Robust Representation Alignment for Positive-Unlabeled Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://iclr.cc/virtual/2026/poster/10006926)
* <a id="paper-013"></a> **[P013]** Align-SAM: Seeking Flatter Minima for Better Cross-Subset Alignment.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://iclr.cc/virtual/2026/poster/10009992)

---

---

### CVPR 2026

* <a id="paper-014"></a> **[P014]** Deconstructing the Failure of Ideal Noise Correction: A Three-Pillar Diagnosis.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2603.12997)
* <a id="paper-015"></a> **[P015]** Debiased Sample Selection for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.eric-weiwei.com/)
* <a id="paper-016"></a> **[P016]** Beyond Loss Values: Robust Dynamic Pruning via Loss Trajectory Alignment.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2604.07306)
* <a id="paper-017"></a> **[P017]** KαLOS finds Consensus: A Meta-Algorithm for Evaluating Inter-Annotator Agreement in Complex Vision Tasks.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://www.uni-weimar.de/en/media/chairs/computer-science-department/computer-vision/publications/)
* <a id="paper-018"></a> **[P018]** Text-Anchored Guided Optimization for Robust Fine-tuning Vision-Language Models under Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.eric-weiwei.com/)

---

---

### AAAI 2026

* <a id="paper-019"></a> **[P019]** Leveraging Dissimilarity Invariance as a Robust Anchor for Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/37381)
* <a id="paper-020"></a> **[P020]** On the Learning Dynamics of Two-layer Linear Networks with Label Noise SGD.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2603.10397)
* <a id="paper-021"></a> **[P021]** Is the Information Bottleneck Robust Enough? Towards Label-Noise Resistant Information Bottleneck Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2512.10573)
* <a id="paper-022"></a> **[P022]** Jump-teaching: Combating Sample Selection Bias via Temporal Disagreement.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2405.17137)
* <a id="paper-023"></a> **[P023]** Content Diversity-guided Ambiguity Mitigation for Open-Set Noisy Label Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/38398)
* <a id="paper-024"></a> **[P024]** Mitigating Endogenous Confirmation Bias in Noisy Label Learning for Vision-Language Models.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/39641/43602)
* <a id="paper-025"></a> **[P025]** Prototype-Guided Supervision for Graph Learning with Noisy and Sparse Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/39477)
* <a id="paper-026"></a> **[P026]** FedRNC: Addressing Spatio-Temporal Label Misalignment in Federated Noisy Class-Incremental Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/39359)
* <a id="paper-027"></a> **[P027]** Neighbor-aware Instance Refining with Noisy Labels for Cross-Modal Retrieval.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2512.24064)
* <a id="paper-028"></a> **[P028]** Meta-Guided Sample Reweighting for Robust Cross-Modal Hashing Retrieval with Noisy Labels.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/37894)

---

### WACV 2026

* <a id="paper-029"></a> **[P029]** FedEFC: Federated Learning Using Enhanced Forward Correction Against Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/WACV2026/html/Yu_FedEFC_Federated_Learning_Using_Enhanced_Forward_Correction_Against_Noisy_Labels_WACV_2026_paper.html)
* <a id="paper-030"></a> **[P030]** Reciprocal Teaching: Dynamic Multi-Model Teacher-Student Learning for Multiple Noisy Annotations.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/WACV2026/html/Ai_Reciprocal_Teaching_Dynamic_Multi-Model_Teacher-Student_Learning_for_Multiple_Noisy_Annotations_WACV_2026_paper.html)

---

---

### Top Journals 2026

* <a id="paper-031"></a> **[P031]** [[**Sxu**]](https://github.com/SenyuHou) Class-Aware Multi-Granularity Co-Diffusion Models for Learning With Noisy Labels on Imbalanced Datasets. (Published on TKDE)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TKDE.2026.3650911)[[Code]](https://github.com/SenyuHou/CaMCoD)
* <a id="paper-032"></a> **[P032]** Continuous Review and Timely Correction: Enhancing the Resistance to Noisy Labels via Self-Not-True and Class-Wise Distillation. (Published on TPAMI)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2025.3649111)
* <a id="paper-033"></a> **[P033]** Affinity-aware Uncertainty Quantification for Learning with Noisy Labels. (Published on Pattern Recognition)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320325011586)
* <a id="paper-034"></a> **[P034]** Federated Learning with Noisy Labels: A Comprehensive and Concise Review of Current Methodologies and Future Directions. (Published on Neural Networks)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0893608026003503)


## Papers & Code in 2025

---

### NeurIPS 2025

* <a id="paper-035"></a> **[P035]** [[**Sxu**]](https://github.com/SenyuHou) Noisy Multi-Label Learning through Co-Occurrence-Aware Diffusion.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/115033)
* <a id="paper-036"></a> **[P036]** Learning to Clean: Reinforcement Learning for Noisy Label Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2025/poster/115438)
* <a id="paper-037"></a> **[P037]** Enhancing Sample Selection Against Label Noise by Cutting Mislabeled Easy Examples.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/118281)
* <a id="paper-038"></a> **[P038]** Handling Label Noise via Instance-Level Difficulty Modeling and Dynamic Optimization.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2025/poster/116524)[[Code]](https://github.com/iTheresaApocalypse/IDO)
* <a id="paper-039"></a> **[P039]** Self-Boost via Optimal Retraining: An Analysis via Approximate Message Passing.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/116800)
* <a id="paper-040"></a> **[P040]** GD$^2$: Robust Graph Learning under Label Noise via Dual-View Prediction Discrepancy.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/115580)
* <a id="paper-041"></a> **[P041]** ELDET: Early-Learning Distillation with Noisy Labels for Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2025/poster/118794)
* <a id="paper-042"></a> **[P042]** FlowRefiner: A Robust Traffic Classification Framework against Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2025/poster/118975)
* <a id="paper-043"></a> **[P043]** SEGA: Shaping Semantic Geometry for Robust Hashing under Noisy Supervision.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2025/hash/0663a39baab211328fc865f91abc75ab-Abstract-Conference.html)
* <a id="paper-044"></a> **[P044]** Unlocker: Disentangle the Deadlock of Learning between Label-noisy and Long-tailed Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2025/hash/bcfcf7232cb74e1ef82d751880ff835b-Abstract-Conference.html)
* <a id="paper-045"></a> **[P045]** How Does Label Noise Gradient Descent Improve Generalization in the Low SNR Regime?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2025/hash/ffab50f3cad7cb5733ca324e5be20976-Abstract-Conference.html)

---

### ICML 2025

* <a id="paper-046"></a> **[P046]** On the Role of Label Noise in the Feature Learning Process.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/han25c.html)
* <a id="paper-047"></a> **[P047]** Retraining with Predicted Hard Labels Provably Increases Model Accuracy.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/das25b.html)
* <a id="paper-048"></a> **[P048]** FedClean: A General Robust Label Noise Correction for Federated Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/jiang25m.html)
* <a id="paper-049"></a> **[P049]** A Unified Theoretical Analysis of Private and Robust Offline Alignment: from RLHF to DPO.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v267/zhou25ac.html)

---

---

### ICLR 2025

* <a id="paper-050"></a> **[P050]** Regretful Decisions under Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=7B9FCDoUzB)
* <a id="paper-051"></a> **[P051]** Learning under Temporal Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=5o0phqAhsP)
* <a id="paper-052"></a> **[P052]** Learning from Weak Labelers as Constraints.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=2BtFKEeMGo)
* <a id="paper-053"></a> **[P053]** Learning to Generate Diverse Pedestrian Movements from Web Videos with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=DydCqKa6AH)[[Code]](https://genforce.github.io/PedGen/)
* <a id="paper-054"></a> **[P054]** Noise Separation guided Candidate Label Reconstruction for Noisy Partial Label Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2025/hash/a8b879590adff2b1874f97db59b65518-Abstract-Conference.html)
* <a id="paper-055"></a> **[P055]** Rethinking Self-Distillation: Label Averaging and Enhanced Soft Label Refinement with Partial Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2025/hash/9d4824d834b5fe8e6b53dcfe42cab8d2-Abstract-Conference.html)
* <a id="paper-056"></a> **[P056]** Multi-Task Dense Predictions via Unleashing the Power of Diffusion.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2025/hash/2f2b1d6bbd50865eca40e2774a057eef-Abstract-Conference.html)

---

---

### CVPR 2025

* <a id="paper-057"></a> **[P057]** [[**Sxu**]](https://github.com/SenyuHou) Directional Label Diffusion Model for Learning from Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Hou_Directional_Label_Diffusion_Model_for_Learning_from_Noisy_Labels_CVPR_2025_paper.html)[[Code]](https://github.com/SenyuHou/DLD)
* <a id="paper-058"></a> **[P058]** NLPrompt: Noise-Label Prompt Learning for Vision-Language Models.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Pan_NLPrompt_Noise-Label_Prompt_Learning_for_Vision-Language_Models_CVPR_2025_paper.html)
* <a id="paper-059"></a> **[P059]** DiN: Diffusion Model for Robust Medical VQA with Semantic Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Guo_DiN_Diffusion_Model_for_Robust_Medical_VQA_with_Semantic_Noisy_CVPR_2025_paper.html)
* <a id="paper-060"></a> **[P060]** Theory-Inspired Deep Multi-View Multi-Label Learning with Incomplete Views and Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Li_Theory-Inspired_Deep_Multi-View_Multi-Label_Learning_with_Incomplete_Views_and_Noisy_CVPR_2025_paper.html)
* <a id="paper-061"></a> **[P061]** Minding Fuzzy Regions: A Data-driven Alternating Learning Paradigm for Stable Lesion Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Fang_Minding_Fuzzy_Regions_A_Data-driven_Alternating_Learning_Paradigm_for_Stable_CVPR_2025_paper.html)
* <a id="paper-062"></a> **[P062]** ROLL: Robust Noisy Pseudo-label Learning for Multi-View Clustering with Noisy Correspondence.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Multimodal](https://img.shields.io/badge/task-Multimodal-0F766E?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Sun_ROLL_Robust_Noisy_Pseudo-label_Learning_for_Multi-View_Clustering_with_Noisy_CVPR_2025_paper.html)
* <a id="paper-063"></a> **[P063]** The Impact Label Noise and Choice of Threshold has on Cross-Entropy and Soft-Dice in Image Segmentation.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2025/html/Nordstrom_The_Impact_Label_Noise_and_Choice_of_Threshold_has_on_CVPR_2025_paper.html)

---

---

### ICCV 2025

* <a id="paper-064"></a> **[P064]** CA2C: A Prior-Knowledge-Free Approach for Robust Label Noise Learning via Asymmetric Co-learning and Co-training.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Sheng_CA2C_A_Prior-Knowledge-Free_Approach_for_Robust_Label_Noise_Learning_via_ICCV_2025_paper.html)
* <a id="paper-065"></a> **[P065]** Meta-Learning Dynamic Center Distance: Hard Sample Mining for Learning with Noisy Labels.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Mu_Meta-Learning_Dynamic_Center_Distance_Hard_Sample_Mining_for_Learning_with_ICCV_2025_paper.html)
* <a id="paper-066"></a> **[P066]** Joint Asymmetric Loss for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_Joint_Asymmetric_Loss_for_Learning_with_Noisy_Labels_ICCV_2025_paper.html)[[Code]](https://github.com/cswjl/joint-asymmetric-loss)
* <a id="paper-067"></a> **[P067]** Boosting Class Representation via Semantically Related Instances for Robust Long-Tailed Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Li_Boosting_Class_Representation_via_Semantically_Related_Instances_for_Robust_Long-Tailed_ICCV_2025_paper.html)[[Code]](https://github.com/yhli-ml/IBC)
* <a id="paper-068"></a> **[P068]** Guiding Noisy Label Conditional Diffusion Models with Score-based Discriminator Correction.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Cong_Guiding_Noisy_Label_Conditional_Diffusion_Models_with_Score-based_Discriminator_Correction_ICCV_2025_paper.html)
* <a id="paper-069"></a> **[P069]** Images as Noisy Labels: Unleashing the Potential of the Diffusion Model for Open-Vocabulary Semantic Segmentation.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Li_Images_as_Noisy_Labels_Unleashing_the_Potential_of_the_Diffusion_ICCV_2025_paper.html)

---

---

### AAAI 2025

* <a id="paper-070"></a> **[P070]** Combating Semantic Contamination in Learning with Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/32293)
* <a id="paper-071"></a> **[P071]** Enhancing Noise-Robust Losses for Large-Scale Noisy Data Learning.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/32752)
* <a id="paper-072"></a> **[P072]** SAP: Corrective Machine Unlearning with Scaled Activation Projection for Label Noise Robustness.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/33972)
* <a id="paper-073"></a> **[P073]** Learning Causal Transition Matrix for Instance-dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2412.13516)
* <a id="paper-074"></a> **[P074]** Label Noise Correction via Fuzzy Learning Machine.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/34055)
* <a id="paper-075"></a> **[P075]** Enhanced Sample Selection with Confidence Tracking: Identifying Correctly Labeled Yet Hard-to-Learn Samples in Noisy Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2504.17474)
* <a id="paper-076"></a> **[P076]** Noisy Label Calibration for Multi-View Classification.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/35485/37640)
* <a id="paper-077"></a> **[P077]** Revisiting Interpolation for Noisy Label Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/35489)
* <a id="paper-078"></a> **[P078]** Learning from Noisy Labels via Self-Taught On-the-Fly Meta Loss Rescaling.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2412.12955)
* <a id="paper-079"></a> **[P079]** Optimized Gradient Clipping for Noisy Label Learning.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2412.08941)
* <a id="paper-080"></a> **[P080]** Robust Logit Adjustment for Learning with Long-Tailed Noisy Data.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=PQ43wVvbvz)
* <a id="paper-081"></a> **[P081]** Weakly Supervised Gland Segmentation with Class Semantic Consistency and Purified Labels Filtration.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/32306)
* <a id="paper-082"></a> **[P082]** Energy vs. Noise: Towards Robust Temporal Action Localization in Open-World.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/32659)
* <a id="paper-083"></a> **[P083]** Learning with Open-world Noisy Data via Class-independent Margin in Dual Representation Space.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/32673)
* <a id="paper-084"></a> **[P084]** Relieving Universal Label Noise for Unsupervised Visible-Infrared Person Re-Identification by Inferring from Neighbors.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/32791)
* <a id="paper-085"></a> **[P085]** RoDA: Robust Domain Alignment for Cross-Domain Retrieval Against Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/33033)
* <a id="paper-086"></a> **[P086]** RepFace: Refining Closed-Set Noise with Progressive Label Correction for Face Recognition.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/33077)
* <a id="paper-087"></a> **[P087]** Rethinking Pseudo-Label Guided Learning for Weakly Supervised Temporal Action Localization from the Perspective of Noise Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/33094)
* <a id="paper-088"></a> **[P088]** Robust Self-Paced Hashing for Cross-Modal Retrieval with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/34199)

---

### Other Conferences 2025

* <a id="paper-089"></a> **[P089]** (KDD 2025) Noise-Resilient Point-wise Anomaly Detection in Time Series Using Weak Segment Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3690624.3709257)
* <a id="paper-090"></a> **[P090]** (IJCAI 2025) Leveraging Peer-Informed Label Consistency for Robust Graph Neural Networks with Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2025/623)
* <a id="paper-091"></a> **[P091]** (AISTATS 2025) AlleNoise - Large-scale Text Classification Benchmark Dataset with Real-world Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v258/raczkowska25a.html)[[Code]](https://github.com/allegro/AlleNoise)

---

---

### Top Journals 2025

* <a id="paper-092"></a> **[P092]** SplitNet: Learnable Clean-Noisy Label Splitting for Learning with Noisy Labels. (Published on IJCV)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://link.springer.com/article/10.1007/s11263-024-02187-4)
* <a id="paper-093"></a> **[P093]** Improving the Instance-Dependent Transition Matrix Estimation by Exploiting Self-Supervised Learning. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2025.3595613)
* <a id="paper-094"></a> **[P094]** FedELR: When Federated Learning Meets Learning with Noisy Labels. (Published on Neural Networks)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0893608025001546)
* <a id="paper-095"></a> **[P095]** Learning from Open-set Noisy Labels Based on Multi-prototype Modeling. (Published on Pattern Recognition)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320324006538)
* <a id="paper-096"></a> **[P096]** A Survey on Learning with Noisy Labels in Natural Language Processing: How to Train Models with Label Noise. (Published on Engineering Applications of Artificial Intelligence)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0952197625001575)


## Papers & Code in 2024

---

### Neurips 2024

* <a id="paper-097"></a> **[P097]** Learning the Latent Causal Structure for Modeling Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93700)
* <a id="paper-098"></a> **[P098]** Learning from Noisy Labels via Conditional Distributionally Robust Optimization.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/96820)
* <a id="paper-099"></a> **[P099]** Label Noise: Ignorance Is Bliss.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/94205)
* <a id="paper-100"></a> **[P100]** Sample Selection via Contrastive Fragmentation for Noisy Label Regression.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95898)
* <a id="paper-101"></a> **[P101]** Robust Contrastive Multi-view Clustering against Dual Noisy Correspondence.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/96528)
* <a id="paper-102"></a> **[P102]** Noisy Label Learning with Instance-Dependent Outliers: Identifiability via Crowd Wisdom.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95831)
* <a id="paper-103"></a> **[P103]** Entity Alignment with Noisy Annotations from Large Language Models.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93478)
* <a id="paper-104"></a> **[P104]** Vision-Language Models are Strong Noisy Label Detectors.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/94056)
* <a id="paper-105"></a> **[P105]** Benchmarking the Reasoning Robustness against Noisy Rationales in Chain-of-thought Prompting.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  [[Paper]](https://nips.cc/virtual/2024/poster/95956)
* <a id="paper-106"></a> **[P106]** CoSW: Conditional Sample Weighting for Smoke Segmentation with Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95170)
* <a id="paper-107"></a> **[P107]** Immiscible Diffusion: Accelerating Diffusion Training with Noise Assignment.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93906)
* <a id="paper-108"></a> **[P108]** Curriculum Fine-tuning of Vision Foundation Model for Medical Image Classification Under Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/93198)[[Code]](https://github.com/gist-ailab/CUFIT)
* <a id="paper-109"></a> **[P109]** NoisyGL: A Comprehensive Benchmark for Graph Neural Networks under Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/97611)
* <a id="paper-110"></a> **[P110]** Noisy Ostracods: A Fine-Grained, Imbalanced Real-World Dataset for Benchmarking Robust Machine Learning and Label Correction Methods.
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/97733)
* <a id="paper-111"></a> **[P111]** Perplexity-aware Correction for Robust Alignment with Noisy Preferences.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95367)
* <a id="paper-112"></a> **[P112]** Information-theoretic Limits of Online Classification with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://nips.cc/virtual/2024/poster/95650)

---

---

### ICML 2024

* <a id="paper-113"></a> **[P113]** Pi-DUAL: Using privileged information to distinguish clean from noisy labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/wang24bb.html)
* <a id="paper-114"></a> **[P114]** Self-cognitive Denoising in the Presence of Multiple Noisy Label Sources.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/sun24o.html)
* <a id="paper-115"></a> **[P115]** (KDD 2025) CLID-MU: Cross-Layer Information Divergence Based Meta Update Strategy for Learning with Noisy Labels.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3711896.3736880)
* <a id="paper-116"></a> **[P116]** (IJCAI 2025) COLUR: Confidence-Oriented Learning, Unlearning and Relearning with Noisy-Label Data for Model Restoration and Refinement.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2025/1038)
* <a id="paper-117"></a> **[P117]** Mitigating Label Noise on Graphs via Topological Sample Selection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/wu24ae.html)
* <a id="paper-118"></a> **[P118]** Provably Robust DPO: Aligning Language Models with Noisy Feedback.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/ray-chowdhury24a.html)
* <a id="paper-119"></a> **[P119]** Consistent Diffusion Meets Tweedie: Training Exact Ambient Diffusion Models with Noisy Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/daras24a.html)
* <a id="paper-120"></a> **[P120]** RIME: Robust Preference-based Reinforcement Learning with Noisy Preferences.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/cheng24k.html)
* <a id="paper-121"></a> **[P121]** FAFE: Immune Complex Modeling with Geodesic Distance Loss on Noisy Group Frames.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/wu24g.html)
* <a id="paper-122"></a> **[P122]** Don't Label Twice: Quantity Beats Quality when Comparing Binary Classifiers on a Budget.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/dorner24a.html)
* <a id="paper-123"></a> **[P123]** Stochastic Conditional Diffusion Models for Robust Semantic Image Synthesis.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v235/ko24e.html)
* <a id="paper-124"></a> **[P124]** (KDD 2025) Calibrating Pre-trained Language Classifiers on LLM-generated Noisy Labels via Iterative Refinement.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3711896.3736871)
* <a id="paper-125"></a> **[P125]** (KDD 2025) LLMs Are Noisy Oracles! LLM-based Noise-aware Graph Active Learning for Node Classification.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3711896.3737030)
* <a id="paper-126"></a> **[P126]** (KDD 2025) Mixed Blessing: Class-Wise Embedding guided Instance-Dependent Partial Label Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3690624.3709276)
* <a id="paper-127"></a> **[P127]** (KDD 2025) Delving into Instance-Dependent Label Noise in Graph Data: A Comprehensive Study and Benchmark.
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3711896.3737376)
* <a id="paper-128"></a> **[P128]** (IJCAI 2025) Dynamic Multiple High-order Correlations Fusion with Noise Filtering for Incomplete Multi-view Noisy-label Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multimodal](https://img.shields.io/badge/task-Multimodal-0F766E?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2025/703)
* <a id="paper-129"></a> **[P129]** (IJCAI 2025) Screening, Rectifying, and Re-Screening: A Unified Framework for Tuning Vision-Language Models with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2025/568)
* <a id="paper-130"></a> **[P130]** (IJCAI 2025) Meta Label Correction with Generalization Regularizer.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2025/698)
* <a id="paper-131"></a> **[P131]** (IJCAI 2025) Seeking Proxy Point via Stable Feature Space for Noisy Correspondence Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2025/231)
* <a id="paper-132"></a> **[P132]** (IJCAI 2025) Noise-Resistant Label Reconstruction Feature Selection for Partial Multi-Label Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2025/576)
* <a id="paper-133"></a> **[P133]** (IJCAI 2025) Adaptive Deep Learning from Crowds.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2025/475)
---

---

### ICLR 2024

* <a id="paper-134"></a> **[P134]** Understanding and Mitigating the Label Noise in Pre-training on Downstream Tasks.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=TjhUtloBZU)
* <a id="paper-135"></a> **[P135]** Early Stopping Against Label Noise Without Validation Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=CMzF2aOfqp)
* <a id="paper-136"></a> **[P136]** Why is SAM Robust to Label Noise?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=3aZCPl3ZvR)
* <a id="paper-137"></a> **[P137]** Dirichlet-based Per-Sample Weighting by Transition Matrix for Noisy Label Learning.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=A4mJuFRMN8)
* <a id="paper-138"></a> **[P138]** Robust Classification via Regression for Learning with Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=wfgZc3IMqo)
* <a id="paper-139"></a> **[P139]** Label-Noise Robust Diffusion Models.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=HXWTXXtHNl)
* <a id="paper-140"></a> **[P140]** Local Graph Clustering with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=89A5c6enfc)
* <a id="paper-141"></a> **[P141]** MOFI: Learning Image Representations from Noisy Entity Annotated Images.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=QQYpgReSRk)
* <a id="paper-142"></a> **[P142]** TextField3D: Towards Enhancing Open-Vocabulary 3D Generation with Noisy Text Fields.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=WOiOzHG2zD)
* <a id="paper-143"></a> **[P143]** Understanding Domain Generalization: A Noise Robustness Perspective.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2024/hash/5b289299aeb8e1023cd6ca4ae0178cbb-Abstract-Conference.html)
* <a id="paper-144"></a> **[P144]** An Efficient Tester-Learner for Halfspaces.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2024/hash/a759e253661be0fa3ffe3e37959ecc5e-Abstract-Conference.html)
* <a id="paper-145"></a> **[P145]** VDC: Versatile Data Cleanser based on Visual-Linguistic Inconsistency by Multimodal Large Language Models.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2024/hash/518046d86bbc41a0707727c38301ad8e-Abstract-Conference.html)
* <a id="paper-146"></a> **[P146]** To Grok or not to Grok: Disentangling Generalization and Memorization on Corrupted Algorithmic Datasets.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2024/hash/105fdc31cc9eb927cc5a0110f4031287-Abstract-Conference.html)
* <a id="paper-147"></a> **[P147]** Unmasking and Improving Data Credibility: A Study with Datasets for Training Harmless Language Models.
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://proceedings.iclr.cc/paper_files/paper/2024/hash/c3837ae3d17a91b08bf5cc19280e7fd2-Abstract-Conference.html)

---

---

### CVPR 2024

* <a id="paper-148"></a> **[P148]** Estimating Noisy Class Posterior with Part-level Labels for Noisy Label Learning.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Zhao_Estimating_Noisy_Class_Posterior_with_Part-level_Labels_for_Noisy_Label_CVPR_2024_paper.html)
* <a id="paper-149"></a> **[P149]** Learning with Structural Labels for Learning with Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Kim_Learning_with_Structural_Labels_for_Learning_with_Noisy_Labels_CVPR_2024_paper.html)
* <a id="paper-150"></a> **[P150]** L2B: Learning to Bootstrap Robust Models for Combating Label Noise.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Zhou_L2B_Learning_to_Bootstrap_Robust_Models_for_Combating_Label_Noise_CVPR_2024_paper.html)
* <a id="paper-151"></a> **[P151]** Learning Discriminative Dynamics with Label Corruption for Noisy Label Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Kim_Learning_Discriminative_Dynamics_with_Label_Corruption_for_Noisy_Label_Detection_CVPR_2024_paper.html)
* <a id="paper-152"></a> **[P152]** A Noisy Elephant in the Room: Is Your Out-of-Distribution Detector Robust to Label Noise?
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Humblot-Renaux_A_Noisy_Elephant_in_the_Room_Is_Your_Out-of-Distribution_Detector_CVPR_2024_paper.html)
* <a id="paper-153"></a> **[P153]** HPL-ESS: Hybrid Pseudo-Labeling for Unsupervised Event-based Semantic Segmentation.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Jing_HPL-ESS_Hybrid_Pseudo-Labeling_for_Unsupervised_Event-based_Semantic_Segmentation_CVPR_2024_paper.html)
* <a id="paper-154"></a> **[P154]** JoAPR: Cleaning the Lens of Prompt Learning for Vision-Language Models.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Guo_JoAPR_Cleaning_the_Lens_of_Prompt_Learning_for_Vision-Language_Models_CVPR_2024_paper.html)
* <a id="paper-155"></a> **[P155]** Stable Neighbor Denoising for Source-free Domain Adaptive Segmentation.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/html/Zhao_Stable_Neighbor_Denoising_for_Source-free_Domain_Adaptive_Segmentation_CVPR_2024_paper.html)

---

---

### ECCV 2024

* <a id="paper-156"></a> **[P156]** Foster Adaptivity and Balance in Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/3908_ECCV_2024_paper.php)
* <a id="paper-157"></a> **[P157]** LNL+K: Enhancing Learning with Noisy Labels Through Noise Source Knowledge Integration.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/7862_ECCV_2024_paper.php)
* <a id="paper-158"></a> **[P158]** MTaDCS: Moving Trace and Feature Density-based Confidence Sample Selection under Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/8968_ECCV_2024_paper.php)
* <a id="paper-159"></a> **[P159]** Instance-dependent Noisy-label Learning with Graphical Model Based Noise-rate Estimation.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/589_ECCV_2024_paper.php)
* <a id="paper-160"></a> **[P160]** Distribution-Aware Robust Learning from Long-Tailed Data with Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/2177_ECCV_2024_paper.php)
* <a id="paper-161"></a> **[P161]** Federated Learning with Local Openset Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/4952_ECCV_2024_paper.php)
* <a id="paper-162"></a> **[P162]** Learning Camouflaged Object Detection from Noisy Pseudo Label.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/51_ECCV_2024_paper.php)
* <a id="paper-163"></a> **[P163]** An accurate detection is not all you need to combat label noise in web-noisy datasets.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06511.pdf)
* <a id="paper-164"></a> **[P164]** De-Confusing Pseudo-Labels in Source-Free Domain Adaptation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10138.pdf)

---

---

### AAAI 2024

* <a id="paper-165"></a> **[P165]** [[**Sxu**]](https://github.com/SenyuHou) Which Is More Effective in Label Noise Cleaning, Correction or Filtering?
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29183/30238)
* <a id="paper-166"></a> **[P166]** Tackling Instance-Dependent Label Noise with Class Rebalance and Geometric Regularization.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3637528.3671707)
* <a id="paper-167"></a> **[P167]** Regroup Median Loss for Combating Label Noise.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29250)
* <a id="paper-168"></a> **[P168]** Mitigating Label Noise through Data Ambiguation.
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29286)
* <a id="paper-169"></a> **[P169]** Learning with Noisy Labels Using Hyperspherical Margin Weighting.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29626)
* <a id="paper-170"></a> **[P170]** Dirichlet-Based Prediction Calibration for Learning with Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29672)
* <a id="paper-171"></a> **[P171]** Contrastive Credibility Propagation for Reliable Semi-supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/30124)
* <a id="paper-172"></a> **[P172]** Divide and Denoise: Empowering Simple Models for Robust Semi-Supervised Node Classification against Label Noise.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3637528.3671798)
* <a id="paper-173"></a> **[P173]** Resurrecting Label Propagation for Graphs with Heterophily and Label Noise.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3637528.3671774)
* <a id="paper-174"></a> **[P174]** Noisy Label Removal for Partial Multi-Label Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3637528.3671677)
* <a id="paper-175"></a> **[P175]** Robust Loss Functions for Training Decision Trees with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29516)
* <a id="paper-176"></a> **[P176]** Hypothesis Testing for Class-Conditional Noise Using Local Maximum Likelihood.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/30174)
* <a id="paper-177"></a> **[P177]** Unlocking the Power of Open Set: A New Perspective for Open-Set Noisy Label Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2305.04203)
* <a id="paper-178"></a> **[P178]** FedDiv: Collaborative Noise Filtering for Federated Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2312.12263)
* <a id="paper-179"></a> **[P179]** FedFixer: Mitigating Heterogeneous Label Noise in Federated Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29179)
* <a id="paper-180"></a> **[P180]** Federated Label-Noise Learning with Local Diversity Product Regularization.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29659)
* <a id="paper-181"></a> **[P181]** Dual-Level Curriculum Meta-Learning for Noisy Few-Shot Learning Tasks.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29392)[[Code]](https://github.com/ritmininglab/DCML)
* <a id="paper-182"></a> **[P182]** Limited-Supervised Multi-Label Learning with Dependency Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29494)
* <a id="paper-183"></a> **[P183]** Robust Node Classification on Graph Data with Graph and Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29668)

---

### IJCAI 2024

* <a id="paper-184"></a> **[P184]** Fine-tuning Pre-trained Models for Robustness under Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2024/403)
* <a id="paper-185"></a> **[P185]** Robust Heterophilic Graph Learning against Label Noise for Anomaly Detection.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2024/271)
* <a id="paper-186"></a> **[P186]** Trusted Multi-view Learning with Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multimodal](https://img.shields.io/badge/task-Multimodal-0F766E?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2024/582)
* <a id="paper-187"></a> **[P187]** FedES: Federated Early-Stopping for Hindering Memorizing Heterogeneous Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2024/599)
* <a id="paper-188"></a> **[P188]** Learning from Long-Tailed Noisy Data with Sample Selection and Balanced Loss.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2024/605)
* <a id="paper-189"></a> **[P189]** CONC: Complex-noise-resistant Open-set Node Classification with Adaptive Noise Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2024/606)
* <a id="paper-190"></a> **[P190]** Towards Robust Multi-Label Learning against Dirty Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2024/617)
* <a id="paper-191"></a> **[P191]** Improving Pseudo Labels with Global-Local Denoising Framework for Cross-lingual Named Entity Recognition.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2024/691)

---

---

### KDD 2024

* <a id="paper-192"></a> **[P192]** Divide and Denoise: Learning from Noisy Labels in Fine-Grained Entity Typing with Cluster-Wise Loss Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3637528.3671834)

---

---

---

### ACM MM 2024

* <a id="paper-193"></a> **[P193]** Enhancing Robustness in Learning with Noisy Labels: An Asymmetric Co-Training Approach.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3664647.3680924)
* <a id="paper-194"></a> **[P194]** Mitigate Catastrophic Remembering via Continual Knowledge Purification for Noisy Label Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3664647.3680975)
* <a id="paper-195"></a> **[P195]** CLIPCleaner: Cleaning Noisy Labels with CLIP.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3664647.3681521)

---

### Top Journals 2024

* <a id="paper-196"></a> **[P196]** Tackling Noisy Labels with Network Parameter Additive Decomposition. (Published on TPAMI)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2024.3367129)
* <a id="paper-197"></a> **[P197]** A Time-Consistency Curriculum for Learning from Instance-Dependent Noisy Labels. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2024.3433918)
* <a id="paper-198"></a> **[P198]** BadLabel: A Robust Perspective on Evaluating and Enhancing Label-noise Learning. (Published on TPAMI)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2024.3439233)


## Papers & Code in 2023

---

### NeurIPS 2023

* <a id="paper-199"></a> **[P199]** Robust Data Pruning under Label Noise via Maximizing Re-labeling Accuracy.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=xWCp0uLcpG)
* <a id="paper-200"></a> **[P200]** Subclass-Dominant Label Noise: A Counterexample for the Success of Early Stopping.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=kR21XsZeAr)[[Code]](https://github.com/tmllab/2023_NeurIPS_SDN)
* <a id="paper-201"></a> **[P201]** Active Negative Loss Functions for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://neurips.cc/virtual/2023/poster/71501)[[Code]](https://github.com/Virusdoll/Active-Negative-Loss)
* <a id="paper-202"></a> **[P202]** Training shallow ReLU networks on noisy data using hinge loss: when do we overfit and is it benign?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2306.09955)
* <a id="paper-203"></a> **[P203]** CSOT: Curriculum and Structure-Aware Optimal Transport for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=y50AnAbKp1)[[Code]](https://github.com/changwxx/CSOT-for-LNL)
* <a id="paper-204"></a> **[P204]** Label Poisoning is All You Need.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2310.18933)[[Code]](https://github.com/SewoongLab/FLIP)
* <a id="paper-205"></a> **[P205]** IPMix: Label-Preserving Data Augmentation Method for Training Robust Classifiers.
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=No52399wXA)
* <a id="paper-206"></a> **[P206]** AQuA: A Benchmarking Tool for Label Quality Assessment.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=dhJ8VbcEtX)
* <a id="paper-207"></a> **[P207]** Efficient Testable Learning of Halfspaces with Adversarial Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=mIm0hsUUt1)
* <a id="paper-208"></a> **[P208]** Label Correction of Crowdsourced Noisy Annotations with an Instance-Dependent Noise Transition Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=nFEQNYsjQO)
* <a id="paper-209"></a> **[P209]** Label-Retrieval-Augmented Diffusion Models for Learning from Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2305.19518)[[Code]](https://github.com/puar-playground/LRA-diffusion)
* <a id="paper-210"></a> **[P210]** Neural Relation Graph: A Unified Framework for Identifying Label Noise and Outlier Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2301.12321)[[Code]](https://github.com/snu-mllab/Neural-Relation-Graph)
* <a id="paper-211"></a> **[P211]** Scale-teaching: Robust Multi-scale Training for Time Series Classification with Noisy Labels.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=9D0fELXbrg)[[Code]](https://github.com/qianlima-lab/Scale-teaching)
* <a id="paper-212"></a> **[P212]** SoTTA: Robust Test-Time Adaptation on Noisy Data Streams.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2310.10074)[[Code]](https://github.com/taeckyung/SoTTA)
* <a id="paper-213"></a> **[P213]** Deep Insights into Noisy Pseudo Labeling on Graph Data.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=XhNlBvb4XV)
* <a id="paper-214"></a> **[P214]** ARTIC3D: Learning Robust Articulated 3D Shapes from Noisy Web Image Collections.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rJc5Lsn5QU)[[Code]](https://chhankyao.github.io/artic3d/)
* <a id="paper-215"></a> **[P215]** ALIM: Adjusting Label Importance Mechanism for Noisy Partial Label Learning.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=PYSfn5xXEe)[[Code]](https://github.com/zeroQiaoba/ALIM)
* <a id="paper-216"></a> **[P216]** Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2305.11003)[[Code]](https://github.com/ChunmingHe/WS-SAM)
* <a id="paper-217"></a> **[P217]** SLaM: Student-Label Mixing for Distillation with Unlabeled Examples.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=N7tw0QXx3z)
* <a id="paper-218"></a> **[P218]** HQA-Attack: Toward High Quality Black-Box Hard-Label Adversarial Attack on Text.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=IOuuLBrGJR)[[Code]](https://github.com/HQA-Attack/HQAAttack-demo)

---

---

### ICML 2023

* <a id="paper-219"></a> **[P219]** Identifiability of Label Noise Transition Matrix.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/liu23g)
* <a id="paper-220"></a> **[P220]** Which is Better for Learning with Noisy Labels: The Semi-supervised Method or Modeling Label Noise?
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/yao23a)
* <a id="paper-221"></a> **[P221]** CrossSplit: Mitigating Label Noise Memorization through Data Splitting.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v202/kim23a/kim23a.pdf)[[Code]](https://github.com/SAITPublic/CrossSplit)
* <a id="paper-222"></a> **[P222]** Understanding Self-Distillation in the Presence of Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v202/das23d/das23d.pdf)
* <a id="paper-223"></a> **[P223]** When does Privileged information Explain Away Label Noise?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/ortiz-jimenez23a)
* <a id="paper-224"></a> **[P224]** Random Classification Noise does not defeat All Convex Potential Boosters Irrespective of Model Choice.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/mansour23a.html)
* <a id="paper-225"></a> **[P225]** Label Distributionally Robust Losses for Multi-class Classification: Consistency, Robustness and Adaptivity.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/zhu23o.html)
* <a id="paper-226"></a> **[P226]** Mitigating Memorization of Noisy Labels by Clipping the Model Prediction.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2212.04055)[[Code]](https://github.com/hongxin001/LogitClip)
* <a id="paper-227"></a> **[P227]** Delving into Noisy Label Detection with Clean Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/yu23b.html)
* <a id="paper-228"></a> **[P228]** Robustly Learning a Single Neuron via Sharpness.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/wang23aq.html)
* <a id="paper-229"></a> **[P229]** GraphCleaner: Detecting Mislabelled Samples in Popular Graph Learning Benchmarks.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/li23ai.html)
* <a id="paper-230"></a> **[P230]** Deep Clustering with Incomplete Noisy Pairwise Annotations: A Geometric Regularization Approach.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v202/nguyen23d)
* <a id="paper-231"></a> **[P231]** Accelerating Exploration with Unlabeled Prior Data.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Itorzn4Kwf)

---

---

### ICLR 2023

* <a id="paper-232"></a> **[P232]** Mitigating Memorization of Noisy Labels via Regularization between Representations.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=6qcYDVlVLnK)
* <a id="paper-233"></a> **[P233]** On the Edge of Benign Overfitting: Label Noise and Overparameterization Level.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=UrEwJebCxk)
* <a id="paper-234"></a> **[P234]** Memorization-Dilation: Modeling Neural Collapse Under Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=cJWxqmmDL2b)

* <a id="paper-235"></a> **[P235]** Quantifying and Mitigating the Impact of Label Errors on Model Disparity Metrics.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=RUzSobdYy0V)
* <a id="paper-236"></a> **[P236]** A law of adversarial risk, interpolation, and label noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=0_TxFpAsEI)
* <a id="paper-237"></a> **[P237]** SoftMatch: Addressing the Quantity-Quality Tradeoff in Semi-supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=ymt1zQXBDiF)

* <a id="paper-238"></a> **[P238]** MCAL: Minimum Cost Human-Machine Active Labeling.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=1FxRPKrH8bw)
* <a id="paper-239"></a> **[P239]** When Source-Free Domain Adaptation Meets Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=u2Pd6x794I)
* <a id="paper-240"></a> **[P240]** Mitigating Dataset Bias by Using Per-Sample Gradient.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=7mgUec-7GMv)
* <a id="paper-241"></a> **[P241]** Deep Learning From Crowdsourced Labels: Coupled Cross-Entropy Minimization, Identifiability, and Regularization.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=_qVhsWyWB9)
* <a id="paper-242"></a> **[P242]** CLIPSep: Learning Text-queried Sound Separation with Noisy Unlabeled Videos.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=H-T3F0dMbyj)
* <a id="paper-243"></a> **[P243]** Learning to Segment from Noisy Annotations: A Spatial Correction Approach.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=Qc_OopMEBnC)
* <a id="paper-244"></a> **[P244]** Mutual Partial Label Learning with Competitive Label Noise.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=EUrxG8IBCrC)

* <a id="paper-245"></a> **[P245]** Leveraging Unlabeled Data to Track Memorization .
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=ORp91sAbzI)

* <a id="paper-246"></a> **[P246]** CLIPSep: Learning Text-queried Sound Separation with Noisy Unlabeled Videos.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=H-T3F0dMbyj)
* <a id="paper-247"></a> **[P247]** Does Decentralized Learning with Non-IID Unlabeled Data Benefit from Self Supervision?.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=2L9gzS80tA4)

* <a id="paper-248"></a> **[P248]** Label Propagation with Weak Supervision .
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=aCuFa-RRqtI)

* <a id="paper-249"></a> **[P249]** Pushing the Accuracy-Group Robustness Frontier with Introspective Self-play.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=MofT9KEF0kw)
* <a id="paper-250"></a> **[P250]** Towards Lightweight, Model-Agnostic and Diversity-Aware Active Anomaly Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=-vKlt84fHs)
* <a id="paper-251"></a> **[P251]** Weakly Supervised Explainable Phrasal Reasoning with Neural Fuzzy Logic.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=Hu4r-dedqR0)

* <a id="paper-252"></a> **[P252]** Towards Addressing Label Skews in One-Shot Federated Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=rzrqh85f4Sc)
* <a id="paper-253"></a> **[P253]** Instance-wise Batch Label Restoration via Gradients in Federated Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=FIrQfNSOoTr)
* <a id="paper-254"></a> **[P254]** That Label's got Style: Handling Label Style Bias for Uncertain Image Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=wZ2SVhOTzBX)
* <a id="paper-255"></a> **[P255]** Learning Hyper Label Model for Programmatic Weak Supervision.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=aCQt_BrkSjC)

* <a id="paper-256"></a> **[P256]** Rhino: Deep Causal Temporal Relationship Learning with History-dependent Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper \& Code]](https://openreview.net/forum?id=i_1rbq8yFWC)

---

---

### CVPR 2023

* <a id="paper-257"></a> **[P257]** Twin Contrastive Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2303.06930)[[Code]](https://github.com/Hzzone/TCL)
* <a id="paper-258"></a> **[P258]** Learning from Noisy Labels with Decoupled Meta Label Purifier.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2302.06810)[[Code]](https://github.com/yuanpengtu/DMLP)
* <a id="paper-259"></a> **[P259]** DISC: Learning from Noisy Labels via Dynamic Instance-Specific Selection and Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_DISC_Learning_From_Noisy_Labels_via_Dynamic_Instance-Specific_Selection_and_CVPR_2023_paper.pdf)[[Code]](https://github.com/jackyfl/disc)
* <a id="paper-260"></a> **[P260]** Fine-Grained Classification with Noisy Labels.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wei_Fine-Grained_Classification_With_Noisy_Labels_CVPR_2023_paper.pdf)
* <a id="paper-261"></a> **[P261]** OT-Filter: An Optimal Transport Filter for Learning With Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Feng_OT-Filter_An_Optimal_Transport_Filter_for_Learning_With_Noisy_Labels_CVPR_2023_paper.pdf)
* <a id="paper-262"></a> **[P262]** How To Prevent the Continuous Damage of Noises To Model Training?
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Yu_How_To_Prevent_the_Continuous_Damage_of_Noises_To_Model_CVPR_2023_paper.html)
* <a id="paper-263"></a> **[P263]** Exploring High-Quality Pseudo Masks for Weakly Supervised Instance Segmentation.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2210.05174)[[Code]](https://github.com/hustvl/BoxTeacher)
* <a id="paper-264"></a> **[P264]** HandsOff: Labeled Dataset Generation with No Additional Human Annotations.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2212.12645.pdf)[[Code]](https://github.com/austinxu87/handsoff/)
* <a id="paper-265"></a> **[P265]** Leveraging Inter-Rater Agreement for Classification in the Presence of Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Bucarelli_Leveraging_Inter-Rater_Agreement_for_Classification_in_the_Presence_of_Noisy_CVPR_2023_paper.pdf)
* <a id="paper-266"></a> **[P266]** Collaborative Noisy Label Cleaner: Learning Scene-aware Trailers for Multi-modal Highlight Detection in Movies.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2303.14768)[[Code]](https://github.com/TencentYoutuResearch/HighlightDetection-CLC)
* <a id="paper-267"></a> **[P267]** MixTeacher: Mining Promising Labels with Mixed Scale Teacher for Semi-supervised Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2303.09061)[[Code]](https://github.com/lliuz/MixTeacher)
* <a id="paper-268"></a> **[P268]** Exploiting Completeness and Uncertainty of Pseudo Labels for Weakly Supervised Video Anomaly Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Exploiting_Completeness_and_Uncertainty_of_Pseudo_Labels_for_Weakly_Supervised_CVPR_2023_paper.pdf)[[Code]](https://github.com/ArielZc/CU-Net)
* <a id="paper-269"></a> **[P269]** Semi-Supervised 2D Human Pose Estimation Driven by Position Inconsistency Pseudo Label Correction Module.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Semi-Supervised_2D_Human_Pose_Estimation_Driven_by_Position_Inconsistency_Pseudo_CVPR_2023_paper.pdf)[[Code]](https://github.com/hlz0606/SSPCM)
* <a id="paper-270"></a> **[P270]** Learning with Noisy labels via Self-supervised Adversarial Noisy Masking.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Tu_Learning_With_Noisy_Labels_via_Self-Supervised_Adversarial_Noisy_Masking_CVPR_2023_paper.pdf)[[Code]](https://github.com/yuanpengtu/SANM)
* <a id="paper-271"></a> **[P271]** RONO: Robust Discriminative Learning with Noisy Labels for 2D-3D Cross-Modal Retrieval.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Feng_RONO_Robust_Discriminative_Learning_With_Noisy_Labels_for_2D-3D_Cross-Modal_CVPR_2023_paper.pdf)[[Code]](https://github.com/penghu-cs/RONO)
* <a id="paper-272"></a> **[P272]** Texture-Guided Saliency Distilling for Unsupervised Salient Object Detection.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Zhou_Texture-Guided_Saliency_Distilling_for_Unsupervised_Salient_Object_Detection_CVPR_2023_paper.html)
* <a id="paper-273"></a> **[P273]** Semi-Supervised Domain Adaptation With Source Label Adaptation.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Yu_Semi-Supervised_Domain_Adaptation_With_Source_Label_Adaptation_CVPR_2023_paper.html)
* <a id="paper-274"></a> **[P274]** Data-Efficient Large Scale Place Recognition With Graded Similarity Supervision.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Leyva-Vallina_Data-Efficient_Large_Scale_Place_Recognition_With_Graded_Similarity_Supervision_CVPR_2023_paper.html)

---

---

### ICCV 2023

* <a id="paper-275"></a> **[P275]** PADDLES: Phase-Amplitude Spectrum Disentangled Early Stopping for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Huang_PADDLES_Phase-Amplitude_Spectrum_Disentangled_Early_Stopping_for_Learning_with_Noisy_ICCV_2023_paper.pdf)[[Code]](https://github.com/CoderHHX/PADDLES)
* <a id="paper-276"></a> **[P276]** Sample-wise Label Confidence Incorporation for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ahn_Sample-wise_Label_Confidence_Incorporation_for_Learning_with_Noisy_Labels_ICCV_2023_paper.pdf)
* <a id="paper-277"></a> **[P277]** LA-Net: Landmark-Aware Learning for Reliable Facial Expression Recognition under Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_LA-Net_Landmark-Aware_Learning_for_Reliable_Facial_Expression_Recognition_under_Label_ICCV_2023_paper.pdf)
* <a id="paper-278"></a> **[P278]** Combating Noisy Labels with Sample Selection by Mining High-Discrepancy Examples.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Combating_Noisy_Labels_with_Sample_Selection_by_Mining_High-Discrepancy_Examples_ICCV_2023_paper.pdf)[[Code]](https://github.com/xiaoboxia/CoDis)
* <a id="paper-279"></a> **[P279]** RankMatch: Fostering Confidence and Consistency in Learning with Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_RankMatch_Fostering_Confidence_and_Consistency_in_Learning_with_Noisy_Labels_ICCV_2023_paper.pdf)
* <a id="paper-280"></a> **[P280]** Late Stopping: Avoiding Confidently Learning from Mislabeled Examples.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Yuan_Late_Stopping_Avoiding_Confidently_Learning_from_Mislabeled_Examples_ICCV_2023_paper.html)
* <a id="paper-281"></a> **[P281]** Enhanced Meta Label Correction for Coping with Label Corruption.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Taraday_Enhanced_Meta_Label_Correction_for_Coping_with_Label_Corruption_ICCV_2023_paper.html)
* <a id="paper-282"></a> **[P282]** SILT: Shadow-Aware Iterative Label Tuning for Learning to Detect Shadows from Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_SILT_Shadow-Aware_Iterative_Label_Tuning_for_Learning_to_Detect_Shadows_ICCV_2023_paper.pdf)[[Code]](https://github.com/hanyangclarence/SILT)
* <a id="paper-283"></a> **[P283]** Graph Matching with Bi-level Noisy Correspondence.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Lin_Graph_Matching_with_Bi-level_Noisy_Correspondence_ICCV_2023_paper.pdf)[[Code]](https://github.com/XLearning-SCU/2023-ICCV-COMMON)
* <a id="paper-284"></a> **[P284]** Learning from Noisy Pseudo Labels for Semi-Supervised Temporal Action Localization.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Learning_from_Noisy_Pseudo_Labels_for_Semi-Supervised_Temporal_Action_Localization_ICCV_2023_paper.pdf)[[Code]](https://github.com/kunnxia/NPL)
* <a id="paper-285"></a> **[P285]** Label-Noise Learning with Intrinsically Long-Tailed Data.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Lu_Label-Noise_Learning_with_Intrinsically_Long-Tailed_Data_ICCV_2023_paper.pdf)
* <a id="paper-286"></a> **[P286]** Semi-Supervised Semantic Segmentation under Label Noise via Diverse Learning Groups.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Semi-Supervised_Semantic_Segmentation_under_Label_Noise_via_Diverse_Learning_Groups_ICCV_2023_paper.pdf)
* <a id="paper-287"></a> **[P287]** Holistic Label Correction for Noisy Multi-Label Classification.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xia_Holistic_Label_Correction_for_Noisy_Multi-Label_Classification_ICCV_2023_paper.pdf)[[Code]](https://github.com/xiaoboxia/HLC)
* <a id="paper-288"></a> **[P288]** When Noisy Labels Meet Long Tail Dilemmas: A Representation Calibration Method.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_When_Noisy_Labels_Meet_Long_Tail_Dilemmas_A_Representation_Calibration_ICCV_2023_paper.pdf)
* <a id="paper-289"></a> **[P289]** Why Is Prompt Tuning for Vision-Language Models Robust to Noisy Labels?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_Why_Is_Prompt_Tuning_for_Vision-Language_Models_Robust_to_Noisy_ICCV_2023_paper.pdf)[[Code]](https://github.com/CEWu/PTNL)
* <a id="paper-290"></a> **[P290]** Learning from Noisy Data for Semi-Supervised 3D Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_Learning_from_Noisy_Data_for_Semi-Supervised_3D_Object_Detection_ICCV_2023_paper.pdf)[[Code]](https://github.com/zehuichen123/NoiseDet)
* <a id="paper-291"></a> **[P291]** LNPL-MIL: Learning from Noisy Pseudo Labels for Promoting Multiple Instance Learning in Whole Slide Image.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Shao_LNPL-MIL_Learning_from_Noisy_Pseudo_Labels_for_Promoting_Multiple_Instance_ICCV_2023_paper.pdf)[[Code]](https://github.com/szc19990412/LNPL-MIL)
* <a id="paper-292"></a> **[P292]** Prototypical Mixing and Retrieval-Based Refinement for Label Noise-Resistant Image Retrieval.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Yang_Prototypical_Mixing_and_Retrieval-Based_Refinement_for_Label_Noise-Resistant_Image_Retrieval_ICCV_2023_paper.html)
* <a id="paper-293"></a> **[P293]** BoMD: Bag of Multi-label Descriptors for Noisy Chest X-ray Classification.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_BoMD_Bag_of_Multi-label_Descriptors_for_Noisy_Chest_X-ray_Classification_ICCV_2023_paper.pdf)[[Code]](https://github.com/cyh-0/BoMD)

---

---

### AAAI 2023

* <a id="paper-294"></a> **[P294]** Class-Independent Regularization for Learning with Noisy Labels.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25434)
* <a id="paper-295"></a> **[P295]** A Gift from Label Smoothing: Robust Training with Adaptive Label Smoothing via Auxiliary Classifier under Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26004)
* <a id="paper-296"></a> **[P296]** Learning from Training Dynamics: Identifying Mislabeled Data beyond Manually Designed Features.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25972)
* <a id="paper-297"></a> **[P297]** USDNL: Uncertainty-Based Single Dropout in Noisy Label Learning.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26264)
* <a id="paper-298"></a> **[P298]** Two Wrongs Don't Make a Right: Combating Confirmation Bias in Learning with Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26725)
* <a id="paper-299"></a> **[P299]** Rethinking Label Refurbishment: Model Robustness under Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26751)
* <a id="paper-300"></a> **[P300]** ADMoE: Anomaly Detection with Mixture-of-Experts from Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25620)

---

---

---

### IJCAI 2023

* <a id="paper-301"></a> **[P301]** MILD: Modeling the Instance Learning Dynamics for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2023/92)
* <a id="paper-302"></a> **[P302]** ProMix: Combating Label Noise via Maximizing Clean Sample Utility.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2023/494)
* <a id="paper-303"></a> **[P303]** Stochastic Feature Averaging for Learning with Long-Tailed Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2023/434)
* <a id="paper-304"></a> **[P304]** CTW: Confident Time-Warping for Time-Series Label-Noise Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2023/450)
* <a id="paper-305"></a> **[P305]** FedNoRo: Towards Noise-Robust Federated Learning by Addressing Class Imbalance and Label Noise Heterogeneity.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2023/492)
* <a id="paper-306"></a> **[P306]** Generalization Guarantees of Self-Training of Halfspaces under Label Noise Corruption.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2023/420)
* <a id="paper-307"></a> **[P307]** A Noisy-Label-Learning Formulation for Immune Repertoire Classification and Disease-Associated Immune Receptor Sequence Identification.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2023/527)
* <a id="paper-308"></a> **[P308]** Learning Few-shot Sample-set Operations for Noisy Multi-label Aspect Category Detection.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2023/589)
* <a id="paper-309"></a> **[P309]** Unreliable Partial Label Learning with Recursive Separation.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2023/468)
* <a id="paper-310"></a> **[P310]** Deep Partial Multi-Label Learning with Graph Disambiguation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2023/479)

---

---

### KDD 2023

* <a id="paper-311"></a> **[P311]** To Aggregate or Not? Learning with Separate Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2206.07181)
* <a id="paper-312"></a> **[P312]** DyGen: Learning from Noisy Labels via Dynamics-Enhanced Generative Modeling.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://dl.acm.org/doi/10.1145/3580305.3599318)[[Code]](https://github.com/night-chen/DyGen)
* <a id="paper-313"></a> **[P313]** Robust Positive-Unlabeled Learning via Noise Negative Sample Self-correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://dl.acm.org/doi/10.1145/3580305.3599491)
* <a id="paper-314"></a> **[P314]** Neural-Hidden-CRF: A Robust Weakly-Supervised Sequence Labeler.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://browse.arxiv.org/pdf/2309.05086.pdf)[[Code]](https://github.com/junchenzhi/Neural-Hidden-CRF)
* <a id="paper-315"></a> **[P315]** Complementary Classifier Induced Partial Label Learning.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2305.09897)[[Code]](https://github.com/Chongjie-Si/PL-CL)
* <a id="paper-316"></a> **[P316]** Partial-label Learning with Mixed Closed-Set and Open-Set Out-of-Candidate Examples.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2307.00553)
* <a id="paper-317"></a> **[P317]** Weakly Supervised Multi-Label Classification of Full-Text Scientific Papers.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2306.14003)[[Code]](https://github.com/yuzhimanhua/FUTEX)

---

---

### ACM MM 2023

* <a id="paper-318"></a> **[P318]** PNT-Edge: Towards Robust Edge Detection with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3581783.3612412)
* <a id="paper-319"></a> **[P319]** Adaptive Contrastive Learning on Multimodal Transformer for Review Helpfulness Predictions with Multimodal Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multimodal](https://img.shields.io/badge/task-Multimodal-0F766E?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3581783.3612405)
* <a id="paper-320"></a> **[P320]** ALEX: Towards Effective Graph Transfer Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3581783.3611891)

---

---

### Top Journals 2023

* <a id="paper-321"></a> **[P321]** A Parametrical Model for Instance-Dependent Label Noise. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3301876)
* <a id="paper-322"></a> **[P322]** Regularly Truncated M-Estimators for Learning With Noisy Labels. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3347850)
* <a id="paper-323"></a> **[P323]** Learning to Learn From Noisy Labeled Data. (Published on TKDE)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TKDE.2023.3271677)
* <a id="paper-324"></a> **[P324]** Noisy Label Learning With Provable Consistency for a Wider Family of Losses. (Published on TPAMI)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3296156)
* <a id="paper-325"></a> **[P325]** Robust Point Cloud Segmentation With Noisy Annotations. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2023.3233772)


## Papers & Code in 2022

---

### NeurIPS 2022

* <a id="paper-326"></a> **[P326]** Class-Dependent Label-Noise Learning with Cycle-Consistency Regularization.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=IvnoGKQuXi)
* <a id="paper-327"></a> **[P327]** Robustness to Label Noise Depends on the Shape of the Noise Distribution.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=AlpR6dzKjfy)
* <a id="paper-328"></a> **[P328]** Noise Attention Learning: Enhancing Noise Robustness by Gradient Scaling.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/92864e1191ed272deb0914b3bb50f97c-Abstract-Conference.html)
* <a id="paper-329"></a> **[P329]** Confidence-based Reliable Learning under Dual Noises.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/e444859b2a22df6b56af9381ad1e9480-Abstract-Conference.html)
* <a id="paper-330"></a> **[P330]** Learning from Label Proportions by Learning with Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=cqyBfRwOTm1)

* <a id="paper-331"></a> **[P331]** Label Noise in Adversarial Training: A Novel Perspective to Study Robust Overfitting.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=9_O9mTLYJQp)
* <a id="paper-332"></a> **[P332]** Estimating Noise Transition Matrix with Label Correlations for Noisy Multi-Label Learning .
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=GwXrGy_vc8m)[[Code]](https://github.com/ShikunLi/Estimating_T_For_Noisy_Mutli-Labels)
* <a id="paper-333"></a> **[P333]** On Image Segmentation With Noisy Labels: Characterization and Volume Properties of the Optimal Solutions to Accuracy and Dice.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=WDS1M0gsfXk)
* <a id="paper-334"></a> **[P334]** SoftPatch: Unsupervised Anomaly Detection with Noisy Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper & Code]](https://openreview.net/forum?id=pIYYJflkhZ)
* <a id="paper-335"></a> **[P335]** Is one annotation enough? - A data-centric image classification benchmark for noisy and ambiguous label estimation.
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/d6c03035b8bc551f474f040fe8607cab-Abstract-Datasets_and_Benchmarks.html)

---

---

### ICML 2022

* <a id="paper-336"></a> **[P336]** To Smooth or Not? When Label Smoothing Meets Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.04149)[[Code]](https://github.com/UCSC-REAL/negative-label-smoothing)
* <a id="paper-337"></a> **[P337]** Detecting Corrupted Labels Without Training a Model to Predict.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.06283)[[Code]](https://github.com/UCSC-REAL/SimiFeat)
* <a id="paper-338"></a> **[P338]** Beyond Images: Label Noise Transition Matrix Estimation for Tasks with Lower-Quality Features.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.01273)
* <a id="paper-339"></a> **[P339]** Robust Training under Label Noise by Over-parameterization.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.14026)[[Code]](https://github.com/shengliu66/SOP)
* <a id="paper-340"></a> **[P340]** Estimating Instance-dependent Bayes-label Transition Matrix using a Deep Neural Network.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v162/yang22p.html)
* <a id="paper-341"></a> **[P341]** Guaranteed Robust Deep Learning against Extreme Label Noise using Self-supervised Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
* <a id="paper-342"></a> **[P342]** Robust Meta-learning with Sampling Noise and Label Noise via Eigen-Reptile.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2206.01944v1.pdf)[[Code]](https://github.com/anfeather/eigen-reptile)
* <a id="paper-343"></a> **[P343]** Guaranteed Robust Deep Learning against Extreme Label Noise using Self-supervised Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
* <a id="paper-344"></a> **[P344]** Transfer and Marginalize: Explaining Away Label Noise with Privileged Information.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v162/collier22a.html)

---
* <a id="paper-345"></a> **[P345]** From Noisy Prediction to True Label: Noisy Prediction Calibration via Generative Model
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2205.00690)[[Code]](https://github.com/BaeHeeSun/NPC)
* <a id="paper-346"></a> **[P346]** Learning General Halfspaces with Adversarial Label Noise via Online Gradient Descent.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v162/diakonikolas22b.html)

---

### ICLR 2022

* <a id="paper-347"></a> **[P347]** Resolving Training Biases via Influence-based Data Relabeling.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=EskfH0bwNVn)
* <a id="paper-348"></a> **[P348]** Sample Selection with Uncertainty of Losses for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=xENf4QUL4LW)
* <a id="paper-349"></a> **[P349]** An Information Fusion Approach to Learning with Instance-Dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=ecH2FKaARUp)
* <a id="paper-350"></a> **[P350]** Meta Discovery: Learning to Discover Novel Classes given Very Limited Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=MEpKGLsY8f)

---

* <a id="paper-351"></a> **[P351]** Learning with Noisy Labels Revisited: A Study Using Real-World Human Annotations.
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=TBWA6PLJZQm&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICLR.cc%2F2022%2FConference%2FAuthors%23your-submissions))[[Code]](https://github.com/zwzhu-d/cifar-10-100n)
* <a id="paper-352"></a> **[P352]** Contrastive Label Disambiguation for Partial Label Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper and Code]](https://openreview.net/forum?id=EhYjZy6e1gJ)

---

### CVPR 2022


* <a id="paper-353"></a> **[P353]** Selective-Supervised Contrastive Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.04181)[[Code]](https://github.com/ShikunLi/Sel-CL)
* <a id="paper-354"></a> **[P354]** Noise Is Also Useful: Negative Correlation-Steered Latent Contrastive Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Yan_Noise_Is_Also_Useful_Negative_Correlation-Steered_Latent_Contrastive_Learning_CVPR_2022_paper.html)
* <a id="paper-355"></a> **[P355]** PNP: Robust Learning From Noisy Labels by Probabilistic Noise Prediction.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Sun_PNP_Robust_Learning_From_Noisy_Labels_by_Probabilistic_Noise_Prediction_CVPR_2022_paper.html)
* <a id="paper-356"></a> **[P356]** UniCon: Combating Label Noise Through Uniform Selection and Contrastive Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Karim_UniCon_Combating_Label_Noise_Through_Uniform_Selection_and_Contrastive_Learning_CVPR_2022_paper.html)
* <a id="paper-357"></a> **[P357]** Instance-Dependent Label-Noise Learning With Manifold-Regularized Transition Matrix Estimation.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Cheng_Instance-Dependent_Label-Noise_Learning_With_Manifold-Regularized_Transition_Matrix_Estimation_CVPR_2022_paper.html)
* <a id="paper-358"></a> **[P358]** Scalable Penalized Regression for Noise Detection in Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.07788)[[Code]](https://github.com/Yikai-Wang/SPR-LNL)
* <a id="paper-359"></a> **[P359]** Large-Scale Pre-training for Person Re-identification with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](http://arxiv.org/pdf/2203.16533)[[Code]](https://github.com/dengpanfu/luperson-nl)
* <a id="paper-360"></a> **[P360]** Adaptive Early-Learning Correction for Segmentation from Noisy Annotations.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.03740)[[Code]](https://github.com/Kangningthu/ADELE)
* <a id="paper-361"></a> **[P361]** Learning From Pixel-Level Noisy Label: A New Perspective for Light Field Saliency Detection.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Feng_Learning_From_Pixel-Level_Noisy_Label_A_New_Perspective_for_Light_CVPR_2022_paper.html)
* <a id="paper-362"></a> **[P362]** Mutual Quantization for Cross-Modal Search With Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Yang_Mutual_Quantization_for_Cross-Modal_Search_With_Noisy_Labels_CVPR_2022_paper.html)
* <a id="paper-363"></a> **[P363]** Few-Shot Learning With Noisy Labels.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Liang_Few-Shot_Learning_With_Noisy_Labels_CVPR_2022_paper.html)
* <a id="paper-364"></a> **[P364]** Learning With Twin Noisy Labels for Visible-Infrared Person Re-Identification.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Yang_Learning_With_Twin_Noisy_Labels_for_Visible-Infrared_Person_Re-Identification_CVPR_2022_paper.html)
* <a id="paper-365"></a> **[P365]** The Devil Is in the Labels: Noisy Label Correction for Robust Scene Graph Generation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Li_The_Devil_Is_in_the_Labels_Noisy_Label_Correction_for_CVPR_2022_paper.html)

---

---

### ECCV 2022

* <a id="paper-366"></a> **[P366]** Teaching with Soft Label Smoothing for Mitigating Noisy Labels in Facial Expressions.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720639.pdf)[[Code]](https://github.com/toharl/soft)
* <a id="paper-367"></a> **[P367]** Learn From All: Erasing Attention Consistency for Noisy Label Facial Expression Recognition.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.10299)[[Code]](https://github.com/zyh-uaiaaaa/Erasing-Attention-Consistency)
* <a id="paper-368"></a> **[P368]** Centrality and Consistency: Two-Stage Clean Samples Identification for Learning with Instance-Dependent Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.14476)[[Code]](https://github.com/uitrbn/TSCSI_IDN)
* <a id="paper-369"></a> **[P369]** Learning with Noisy Labels by Efficient Transition Matrix Estimation to Combat Label Miscorrection.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.14932)[[Code]](https://github.com/hyperconnect/FasTEN)
* <a id="paper-370"></a> **[P370]** Self-Filtering: A Noise-Aware Sample Selection for Label Noise with Confidence Penalization.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2208.11351)
* <a id="paper-371"></a> **[P371]** Active label correction using robust parameter update and entropy propagation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136810001.pdf)
* <a id="paper-372"></a> **[P372]** Neighborhood Collective Estimation for Noisy Label Identification and Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2208.03207)[[Code]](https://github.com/lijichang/LNL-NCE)
* <a id="paper-373"></a> **[P373]** BoundaryFace: A mining framework with noise label self-correction for Face Recognition.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730092.pdf)[[Code]](https://gitee.com/swjtugx/classmate/tree/master/OurGroup/BoundaryFace)
* <a id="paper-374"></a> **[P374]** A data-centric approach for improving ambiguous labels with combined semi-supervised classification and clustering.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.16209)[[Code]](https://github.com/Emprime/dc3)

---
* <a id="paper-375"></a> **[P375]** Learning from Multiple Annotator Noisy Labels via Sample-wise Label Fusion.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136840402.pdf)[[Code]](https://github.com/zhengqigao/Learning-from-Multiple-Annotator-Noisy-Labels)
* <a id="paper-376"></a> **[P376]** Identifying Hard Noise in Long-Tailed Sample Distribution.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.13378)[[Code]](https://github.com/yxymessi/H2E-Framework)
* <a id="paper-377"></a> **[P377]** Embedding contrastive unsupervised features to cluster in- and out-of-distribution noise in corrupted image datasets.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2207.01573)[[Code]](https://github.com/PaulAlbert31/SNCF)
* <a id="paper-378"></a> **[P378]** WeLSA: Learning To Predict 6D Pose From Weakly Labeled Data Using Shape Alignment.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![LLM Alignment](https://img.shields.io/badge/task-LLM%20Alignment-9333EA?style=flat-square)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680633.pdf)
* <a id="paper-379"></a> **[P379]** Joint-Modal Label Denoising for Weakly-Supervised Audio-Visual Video Parsing.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2204.11573)[[Code]](https://github.com/MCG-NJU/JoMoLD)
* <a id="paper-380"></a> **[P380]** PseCo: Pseudo Labeling and Consistency Training for Semi-Supervised Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.16317)[[Code]](https://github.com/ligang-cs/PseCo)
* <a id="paper-381"></a> **[P381]** W2N: Switching from Weak Supervision to Noisy Supervision for Object Detection.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/4020_ECCV_2022_paper.php)

---

---

### AAAI 2022

* <a id="paper-382"></a> **[P382]** Noise-Robust Learning from Multiple Unsupervised Sources of Inferred Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20806)
* <a id="paper-383"></a> **[P383]** Uncertainty-Aware Learning against Label Noise on Imbalanced Datasets.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20654)
* <a id="paper-384"></a> **[P384]** Deep Neural Networks Learn Meta-Structures from Noisy Labels in Semantic Segmentation.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20085)
* <a id="paper-385"></a> **[P385]** Uncertainty Estimation via Response Scaling for Pseudo-Mask Noise Mitigation in Weakly-Supervised Semantic Segmentation.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20034)
* <a id="paper-386"></a> **[P386]** GearNet: Stepwise Dual Learning for Weakly Supervised Domain Adaptation.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20851)
* <a id="paper-387"></a> **[P387]** Defending Graph Convolutional Networks against Dynamic Graph Perturbations via Bayesian Self-Supervision.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20362)
* <a id="paper-388"></a> **[P388]** Delving into Probabilistic Uncertainty for Unsupervised Domain Adaptive Person Re-identification.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/19960)

---

---

### IJCAI 2022

* <a id="paper-389"></a> **[P389]** SELC: Self-Ensemble Label Correction Improves Learning with Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2022/455)
* <a id="paper-390"></a> **[P390]** Automatic Noisy Label Correction for Fine-Grained Entity Typing.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2022/599)
* <a id="paper-391"></a> **[P391]** SCMT: Self-Correction Mean Teacher for Semi-supervised Object Detection.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2022/207)
* <a id="paper-392"></a> **[P392]** CARD: Semi-supervised Semantic Segmentation via Class-agnostic Relation based Denoising.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2022/202)
* <a id="paper-393"></a> **[P393]** Webly-Supervised Fine-Grained Recognition with Partial Label Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2022/209)
* <a id="paper-394"></a> **[P394]** Ambiguity-Induced Contrastive Learning for Instance-Dependent Partial Label Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2022/502)

---

---

### KDD 2022

* <a id="paper-395"></a> **[P395]** Communication-Efficient Robust Federated Learning with Noisy Labels.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Federated Learning](https://img.shields.io/badge/task-Federated%20Learning-0284C7?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3534678.3539252)
* <a id="paper-396"></a> **[P396]** Adaptive Learning for Weakly Labeled Streams.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3534678.3539334)

---

---

### ACM MM 2022

* <a id="paper-397"></a> **[P397]** Early-Learning Regularized Contrastive Learning for Cross-Modal Retrieval with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3503161.3547809)

---

---

### ArXiv 2022

* <a id="paper-398"></a> **[P398]** Constrained Instance and Class Reweighting for Robust Learning under Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.05428)
* <a id="paper-399"></a> **[P399]** Do We Need to Penalize Variance of Losses for Learning with Label Noise?.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.12739)
* <a id="paper-400"></a> **[P400]** On Learning Contrastive Representations for Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2203.01785)
* <a id="paper-401"></a> **[P401]** Benign Overfitting without Linearity: Neural Network Classifiers Trained by Gradient Descent for Noisy Linear Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.05928#:~:text=11%20Feb%202022%5D-,Benign%20Overfitting%20without%20Linearity%3A%20Neural%20Network%20Classifiers%20Trained%20by,Descent%20for%20Noisy%20Linear%20Data&text=Abstract%3A%20Benign%20overfitting%2C%20the%20phenomenon,models%20trained%20with%20gradient%20descent.)
* <a id="paper-402"></a> **[P402]** Convolutional Network Fabric Pruning With Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.07268)
* <a id="paper-403"></a> **[P403]** Learning with Neighbor Consistency for Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.02200)
* <a id="paper-404"></a> **[P404]** Investigating Why Contrastive Learning Benefits Robustness Against Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.12498)
* <a id="paper-405"></a> **[P405]** GMM Discriminant Analysis with Noisy Label for Each Class.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.10242)

---
* <a id="paper-406"></a> **[P406]** AUGLOSS: A Learning Methodology for Real-World Dataset Corruption.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2206.02286.pdf)
* <a id="paper-407"></a> **[P407]** Synergistic Network Learning and Label Correction for Noise-robust Image Classification.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2202.13472)
* <a id="paper-408"></a> **[P408]** PARS: Pseudo-Label Aware Robust Sample Selection for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2201.10836)
* <a id="paper-409"></a> **[P409]** Learning with Label Noise for Image Retrieval by Selecting Interactions.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2112.10453)

---

### Top Journals 2022

* <a id="paper-410"></a> **[P410]** Wasserstein Adversarial Regularization for Learning with Label Noise. (Published on TPAMI)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2022.3156685)
* <a id="paper-411"></a> **[P411]** Extended T: Learning With Mixed Closed-Set and Open-Set Noisy Labels. (Published on TPAMI)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://doi.org/10.1109/TPAMI.2022.3180545)

---


## Papers & Code in 2021

---

### NeurIPS 2021

* <a id="paper-412"></a> **[P412]** Can Less be More? When Increasing-to-Balancing Label Noise Rates Considered Beneficial.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2107.05913#:~:text=We%20are%20primarily%20inspired%20by,fairness%20guarantees%20against%20label%20bias.)[[Code]](https://github.com/UCSC-REAL/CanLessBeMore)
* <a id="paper-413"></a> **[P413]** Understanding and Improving Early Stopping for Learning with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.15853)[[Code]](https://github.com/tmllab/PES)
* <a id="paper-414"></a> **[P414]** How does a Neural Network's Architecture Impact its Robustness to Noisy Labels?
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Ir-WwGboFN-)[[Code]](https://github.com/jinglingli/alignment_noisy_label)
* <a id="paper-415"></a> **[P415]** FINE Samples for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.11628v3.pdf)[[Code]](https://github.com/Kthyeon/FINE_official)
* <a id="paper-416"></a> **[P416]** Label Noise SGD Provably Prefers Flat Global Minimizers.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.06530)[[Code]](https://github.com/adamian98/LabelNoiseFlatMinimizers)
* <a id="paper-417"></a> **[P417]** Improved Regularization and Robustness for Fine-tuning in Neural Networks.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=QX32YlxrQJc)[[Code]](https://github.com/NEU-StatsML-Research/Regularized-Self-Labeling)
* <a id="paper-418"></a> **[P418]** Instance-dependent Label-noise Learning under a Structural Causal Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2109.02986)
* <a id="paper-419"></a> **[P419]** Combating Noise: Semi-supervised Learning by Region Uncertainty Quantification.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.00928)
* <a id="paper-420"></a> **[P420]** DP-SSL: Towards Robust Semi-supervised Learning with A Few Labeled Samples.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.13740)
* <a id="paper-421"></a> **[P421]** Generalized Jensen-Shannon Divergence Loss for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.04522)[[Code]](https://github.com/ErikEnglesson/GJS)
* <a id="paper-422"></a> **[P422]** Corruption Robust Active Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Ruw3MHL9jAO)

---
* <a id="paper-423"></a> **[P423]** Open-set Label Noise Can Improve Robustness Against Inherent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.10891)[[Code]](https://github.com/hongxin001/ODNL)
* <a id="paper-424"></a> **[P424]** Interactive Label Cleaning with Example-based Explanations.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc/paper/2021/hash/6c349155b122aa8ad5c877007e05f24f-Abstract.html)
* <a id="paper-425"></a> **[P425]** Learning to Generate Visual Questions with Noisy Supervision.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc/paper/2021/hash/60792d855cd8a912a97711f91a1f155c-Abstract.html)
* <a id="paper-426"></a> **[P426]** Learning with Noisy Correspondence for Cross-modal Matching.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc/paper/2021/hash/f5e62af885293cf4d511ceef31e61c80-Abstract.html)

---

### ICML 2021

* <a id="paper-427"></a> **[P427]** Understanding Instance-Level Label Noise: Disparate Impacts and Treatments.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v139/liu21a.html)
* <a id="paper-428"></a> **[P428]** Clusterability as an Alternative to Anchor Points When Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.05291.pdf)[[Code]](https://github.com/zwzhu-d/HOC)
* <a id="paper-429"></a> **[P429]** Learning Noise Transition Matrix from Only Noisy Labels via Total Variation Regularization.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.02414v2.pdf)[[Code]](https://github.com/YivanZhang/lio)
* <a id="paper-430"></a> **[P430]** Class2Simi: A Noise Reduction Perspective on Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2006.07831)
* <a id="paper-431"></a> **[P431]** Provably End-to-end Label-noise Learning without Anchor Points.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.02400.pdf)
* <a id="paper-432"></a> **[P432]** Asymmetric Loss Functions for Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2106.03110v1.pdf)[[Code]](https://github.com/hitcszx/ALFs)
* <a id="paper-433"></a> **[P433]** Confidence Scores Make Instance-dependent Label-noise Learning Possible.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2001.03772)
* <a id="paper-434"></a> **[P434]** Learning from Noisy Labels with No Change to the Training Process.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v139/zhang21k/zhang21k.pdf)
* <a id="paper-435"></a> **[P435]** Provable Generalization of SGD-trained Neural Networks of Any Width in the Presence of Adversarial Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2101.01152)
* <a id="paper-436"></a> **[P436]** Wasserstein Distributional Normalization For Robust Distributional Certification of Noisy Labeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v139/park21a/park21a.pdf)
* <a id="paper-437"></a> **[P437]** Provable Robustness of Adversarial Training for Learning Halfspaces with Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v139/zou21a.html)
* <a id="paper-438"></a> **[P438]** Agnostic Learning of Halfspaces with Gradient Descent via Soft Margins.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v139/frei21a.html)
* <a id="paper-439"></a> **[P439]** On the Power of Localized Perceptron for Label-Optimal Learning of Halfspaces with Adversarial Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v139/shen21a.html)
* <a id="paper-440"></a> **[P440]** Hierarchical Modeling of Label Dependency and Label Noise in Fine-grained Entity Typing.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2021/544)
* <a id="paper-441"></a> **[P441]** Partial Multi-Label Optimal Margin Distribution Machine.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2021/303)
* <a id="paper-442"></a> **[P442]** Bipartite Matching for Crowd Counting with Point Supervision.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2021/119)
* <a id="paper-443"></a> **[P443]** Two-stage Training for Learning from Label Proportions.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2021/377)
* <a id="paper-444"></a> **[P444]** Partial Multi-Label Learning with Meta Disambiguation.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3447548.3467259)
* <a id="paper-445"></a> **[P445]** Weakly Supervised Spatial Deep Learning based on Imperfect Vector Labels with Registration Errors.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3447548.3467386)
---
* <a id="paper-446"></a> **[P446]** Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.05918v2.pdf)[[Code]](https://github.com/MicPie/clasp)

---

### ICLR 2021

* <a id="paper-447"></a> **[P447]** When Optimizing f-Divergence is Robust with Label Noise.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=WesiCoRVQ15)[[Code]](https://github.com/weijiaheng/Robust-f-divergence-measures)
* <a id="paper-448"></a> **[P448]** Learning with Instance-Dependent Label Noise: A Sample Sieve Approach.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=2VXyy9mIyU3)[[Code]](https://github.com/haochenglouis/cores)
* <a id="paper-449"></a> **[P449]** Noise against noise: stochastic label noise helps combat inherent label noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=80FMcTSZ6J0)[[Code]](https://github.com/chenpf1025/SLN)
* <a id="paper-450"></a> **[P450]** Learning with Feature-Dependent Label Noise: A Progressive Approach.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=ZPa2SyGcbwh)[[Code]](https://github.com/pxiangwu/PLC)
* <a id="paper-451"></a> **[P451]** Robust early-learning: Hindering the memorization of noisy labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=Eql5b1_hTE4)[[Code]](https://github.com/xiaoboxia/CDR)
* <a id="paper-452"></a> **[P452]** Robust Curriculum Learning: from clean label detection to noisy label self-correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=lmTWnm3coJJ)
* <a id="paper-453"></a> **[P453]** How Does Mixup Help With Robustness and Generalization?
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=8yKEo06dKNo)
* <a id="paper-454"></a> **[P454]** MoPro: Webly Supervised Learning with Momentum Prototypes.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=0-EYBhgw80y) [[Code]](https://github.com/salesforce/MoPro)
* <a id="paper-455"></a> **[P455]** Theoretical Analysis of Self-Training with Deep Networks on Unlabeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=rC8sJ4i6kaH)

---

---

### CVPR 2021

* <a id="paper-456"></a> **[P456]** A Second-Order Approach to Learning with Instance-Dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.11854)[[Code]](https://github.com/UCSC-REAL/CAL)
* <a id="paper-457"></a> **[P457]** Multi-Objective Interpolation Training for Robustness to Label Noise.
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.04462)[[Code]](https://git.io/JI40X)
* <a id="paper-458"></a> **[P458]** Augmentation Strategies for Learning with Noisy Labels.
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.02130)[[Code]](https://github.com/KentoNishi/Augmentation-for-LNL)
* <a id="paper-459"></a> **[P459]** Jo-SRC: A Contrastive Approach for Combating Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.13029.pdf)[[Code]](https://github.com/NUST-Machine-Intelligence-Laboratory/Jo-SRC)
* <a id="paper-460"></a> **[P460]** Partially View-aligned Representation Learning with Noise-robust Contrastive Loss.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Partially_View-Aligned_Representation_Learning_With_Noise-Robust_Contrastive_Loss_CVPR_2021_paper.pdf)[[Code]](https://github.com/XLearning-SCU/2021-CVPR-MvCLN)
* <a id="paper-461"></a> **[P461]** Correlated Input-Dependent Label Noise in Large-Scale Image Classification.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.10305)
* <a id="paper-462"></a> **[P462]** Faster Meta Update Strategy for Noise-Robust Deep Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://github.com/youjiangxu/FaMUS/tree/main/paper)[[Code]](https://github.com/youjiangxu/FaMUS)
* <a id="paper-463"></a> **[P463]** Joint Negative and Positive Learning for Noisy Labels.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.06574)
* <a id="paper-464"></a> **[P464]** Faster Meta Update Strategy for Noise-Robust Deep Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.15092)
* <a id="paper-465"></a> **[P465]** AutoDO: Robust AutoAugment for Biased Data with Label Noise via Scalable Probabilistic Implicit Differentiation.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.05863)[[Code]](https://github.com/gudovskiy/autodo)
* <a id="paper-466"></a> **[P466]** All Labels Are Not Created Equal: Enhancing Semi-supervision via Label Grouping and Co-training.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.05248)[[Code]](https://github.com/islam-nassar/semco)
* <a id="paper-467"></a> **[P467]** ProSelfLC: Progressive Self Label Correction for Training Robust Deep Neural Networks.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Wang_ProSelfLC_Progressive_Self_Label_Correction_for_Training_Robust_Deep_Neural_CVPR_2021_paper.html)
* <a id="paper-468"></a> **[P468]** Improving Unsupervised Image Clustering With Robust Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.11150)
* <a id="paper-469"></a> **[P469]** Noise-resistant Deep Metric Learning with Ranking-based Instance Selection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.16047)[[Code]](https://github.com/alibaba-edu/Ranking-based-Instance-Selection)
* <a id="paper-470"></a> **[P470]** DAT: Training Deep Networks Robust To Label-Noise by Matching the Feature Distributions.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Qu_DAT_Training_Deep_Networks_Robust_To_Label-Noise_by_Matching_the_CVPR_2021_paper.pdf)
* <a id="paper-471"></a> **[P471]** DualGraph: A graph-based method for reasoning about label noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_DualGraph_A_Graph-Based_Method_for_Reasoning_About_Label_Noise_CVPR_2021_paper.pdf)
* <a id="paper-472"></a> **[P472]** Background-Aware Pooling and Noise-Aware Loss for Weakly-Supervised Semantic Segmentation.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.00905)
* <a id="paper-473"></a> **[P473]** Meta Pseudo Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2003.10580.pdf)[[Code]](https://github.com/google-research/google-research/tree/master/meta_pseudo_labels)
* <a id="paper-474"></a> **[P474]** SimPLE: Similar Pseudo Label Exploitation for Semi-Supervised Classification.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.16725)[[Code]](https://github.com/zijian-hu/SimPLE)
* <a id="paper-475"></a> **[P475]** Re-Labeling ImageNet: From Single to Multi-Labels, From Global to Localized Labels.
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Yun_Re-Labeling_ImageNet_From_Single_to_Multi-Labels_From_Global_to_Localized_CVPR_2021_paper.html)
* <a id="paper-476"></a> **[P476]** Learning Cross-Modal Retrieval With Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Hu_Learning_Cross-Modal_Retrieval_With_Noisy_Labels_CVPR_2021_paper.html)

---

---

### ICCV 2021

* <a id="paper-477"></a> **[P477]** Me-Momentum: Extracting Hard Confident Examples From Noisily Labeled Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Bai_Me-Momentum_Extracting_Hard_Confident_Examples_From_Noisily_Labeled_Data_ICCV_2021_paper.html)
* <a id="paper-478"></a> **[P478]** Searching for Robustness: Loss Learning for Noisy Classification Tasks.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Gao_Searching_for_Robustness_Loss_Learning_for_Noisy_Classification_Tasks_ICCV_2021_paper.html)
* <a id="paper-479"></a> **[P479]** Learning From Noisy Data With Robust Representation Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Li_Learning_From_Noisy_Data_With_Robust_Representation_Learning_ICCV_2021_paper.html)
* <a id="paper-480"></a> **[P480]** Switchable K-Class Hyperplanes for Noise-Robust Representation Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Liu_Switchable_K-Class_Hyperplanes_for_Noise-Robust_Representation_Learning_ICCV_2021_paper.html)
* <a id="paper-481"></a> **[P481]** Continual Learning on Noisy Data Streams via Self-Purified Replay.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Kim_Continual_Learning_on_Noisy_Data_Streams_via_Self-Purified_Replay_ICCV_2021_paper.html)
* <a id="paper-482"></a> **[P482]** Adaptive Label Noise Cleaning With Meta-Supervision for Deep Face Recognition.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Zhang_Adaptive_Label_Noise_Cleaning_With_Meta-Supervision_for_Deep_Face_Recognition_ICCV_2021_paper.html)
* <a id="paper-483"></a> **[P483]** Uncertainty-Aware Pseudo Label Refinery for Domain Adaptive Semantic Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Uncertainty-Aware_Pseudo_Label_Refinery_for_Domain_Adaptive_Semantic_Segmentation_ICCV_2021_paper.html)

---

---

### AAAI 2021

* <a id="paper-484"></a> **[P484]** Beyond Class-Conditional Assumption: A Primary Attempt to Combat Instance-Dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.05458)[[Code]](https://github.com/chenpf1025/IDN)
* <a id="paper-485"></a> **[P485]** Learning to Purify Noisy Labels via Meta Soft Label Corrector.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2008.00627)[[Code]](https://github.com/WuYichen-97/Learning-to-Purify-Noisy-Labels-via-Meta-Soft-Label-Corrector)
* <a id="paper-486"></a> **[P486]** Robustness of Accuracy Metric and its Inspirations in Learning with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2012.04193)[[Code]](https://github.com/chenpf1025/RobustnessAccuracy)
* <a id="paper-487"></a> **[P487]** Learning from Noisy Labels with Complementary Loss Functions.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://palm.seu.edu.cn/zhangml/files/AAAI'21a.pdf)[[Code]](https://github.com/dengbaowang/CompLossForNoisyLabels)
* <a id="paper-488"></a> **[P488]** Analysing the Noise Model Error for Realistic Noisy Label Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2101.09763)[[Code]](https://github.com/uds-lsv/noise-estimation)
* <a id="paper-489"></a> **[P489]** Tackling Instance-Dependent Label Noise via a Universal Probabilistic Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://niug1984.github.io/paper/wang_aaai21.pdf)
* <a id="paper-490"></a> **[P490]** Learning with Group Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://gcatnjust.github.io/ChenGong/paper/wang_aaai21_2.pdf)
* <a id="paper-491"></a> **[P491]** Meta Label Correction for Noisy Label Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.microsoft.com/en-us/research/publication/meta-label-correction-for-noisy-label-learning/)

---

---

### IJCAI 2021

* <a id="paper-492"></a> **[P492]** Towards Understanding Deep Learning from Noisy Labels with Small-Loss Criterion.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2021/0340.pdf)
* <a id="paper-493"></a> **[P493]** Modeling Noisy Hierarchical Types in Fine-Grained Entity Typing: A Content-Based Weighting Approach.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2019/0731.pdf)
* <a id="paper-494"></a> **[P494]** Multi-level Generative Models for Partial Label Learning with Non-random Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2021/0449.pdf)

---

---

### KDD 2021

* <a id="paper-495"></a> **[P495]** Robust Learning by Self-Transition for Handling Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3447548.3467222)

---
* <a id="paper-496"></a> **[P496]** NRGNN: Learning a Label Noise Resistant Graph Neural Network on Sparsely and Noisily Labeled Graphs.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3447548.3467364)

---

### ACM MM 2021

* <a id="paper-497"></a> **[P497]** Co-learning: Learning from Noisy Labels with Self-supervision.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3474085.3475622)

---

---

### ArXiv 2021

* <a id="paper-498"></a> **[P498]** Demystifying How Self-Supervised Features Improve Training from Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.09022.pdf)[[code]](https://github.com/UCSC-REAL/SelfSup_NoisyLabel)
* <a id="paper-499"></a> **[P499]** A Theoretical Analysis of Learning with Noisily Labeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2104.04114)
* <a id="paper-500"></a> **[P500]** Analysis of classifiers robust to noisy labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.00274)
* <a id="paper-501"></a> **[P501]** Alleviating Noisy-label Effects in Image Classification via Probability Transition Matrix.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.08866)
* <a id="paper-502"></a> **[P502]** Learning with Noisy Labels by Targeted Relabeling.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.08355)
* <a id="paper-503"></a> **[P503]** Contrast to Divide: Self-Supervised Pre-Training for Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.13646.pdf)[[Code]](https://github.com/ContrastToDivide/C2D)
* <a id="paper-504"></a> **[P504]** Exponentiated Gradient Reweighting for Robust Training Under Label Noise and Beyond.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.01493.pdf)
* <a id="paper-505"></a> **[P505]** Learning from Noisy Labels via Dynamic Loss Thresholding.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.02570.pdf)
* <a id="paper-506"></a> **[P506]** Transform consistency for learning with noisy labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.13872.pdf)
* <a id="paper-507"></a> **[P507]** Learning to Combat Noisy Labels via Classification Margins.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.00751.pdf)
* <a id="paper-508"></a> **[P508]** DST: Data Selection and joint Training for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.00813.pdf)
* <a id="paper-509"></a> **[P509]** LongReMix: Robust Learning with High Confidence Samples in a Noisy Label Environment.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.04173.pdf)
* <a id="paper-510"></a> **[P510]** Ensemble Learning with Manifold-Based Data Splitting for Noisy Label Correction.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.07641.pdf)
* <a id="paper-511"></a> **[P511]** On the Robustness of Monte Carlo Dropout Trained with Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.12002.pdf)
* <a id="paper-512"></a> **[P512]** Approximating Instance-Dependent Noise via Instance-Confidence Embedding.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.13569)
* <a id="paper-513"></a> **[P513]** Friends and Foes in Learning from Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.15055.pdf)
* <a id="paper-514"></a> **[P514]** A Fremework Using Contrastive Learning for Classification with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.09563.pdf)
* <a id="paper-515"></a> **[P515]** Contrastive Learning Improves Model Robustness Under Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.08984.pdf)[[Code]](https://github.com/arghosh/noisy_label_pretrain)
* <a id="paper-516"></a> **[P516]** Compensation Learning.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.11921.pdf)
* <a id="paper-517"></a> **[P517]** kNet: A Deep kNN Network To Handle Label Noise.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.09735.pdf)
* <a id="paper-518"></a> **[P518]** Memorization in Deep Neural Networks: Does the Loss Function matter?.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.09957.pdf)
* <a id="paper-519"></a> **[P519]** Mitigating Memorization in Sample Selection for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.07041.pdf)
* <a id="paper-520"></a> **[P520]** P-DIFF: Learning Classifier with Noisy Labels based on Probability Difference Distributions.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2009.06382)[[Code]](https://github.com/fistyee/P-DIFF)
* <a id="paper-521"></a> **[P521]** Decoupling Representation and Classifier for Noisy Label Learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2011.08145.pdf)
* <a id="paper-522"></a> **[P522]** Contrastive Representations for Label Noise Require Fine-Tuning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.09154.pdf)
* <a id="paper-523"></a> **[P523]** Learning to Aggregate and Refine Noisy Labels for Visual Sentiment Analysis.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2109.07509)
* <a id="paper-524"></a> **[P524]** Robustness and reliability when training with noisy labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.03321.pdf)
* <a id="paper-525"></a> **[P525]** Consistency Regularization Can Improve Robustness to Label Noise.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.01242.pdf)

---
* <a id="paper-526"></a> **[P526]** Understanding Generalized Label Smoothing when Learning with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.04149)
* <a id="paper-527"></a> **[P527]** A Good Representation Detects Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.06283.pdf)
* <a id="paper-528"></a> **[P528]** Pervasive Label Errors in Test Sets Destabilize Machine Learning Benchmarks.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.14749)[[Code]](https://github.com/cgnorthcutt/label-errors)
* <a id="paper-529"></a> **[P529]** Double Descent in Adversarial Training: An Implicit Label Noise Perspective.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2110.03135.pdf)
* <a id="paper-530"></a> **[P530]** NoiLIn: Do Noisy Labels Always Hurt Adversarial Training?
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.14676)
* <a id="paper-531"></a> **[P531]** Simple Attention Module based Speaker Verification with Iterative noisy label detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.06534)
* <a id="paper-532"></a> **[P532]** Adaptive Hierarchical Similarity Metric Learning with Noisy Labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.00006)
* <a id="paper-533"></a> **[P533]** A Survey of Label-noise Representation Learning: Past, Present and Future.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2011.04406.pdf)
* <a id="paper-534"></a> **[P534]** Noisy-Labeled NER with Confidence Estimation.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.04318.pdf)[[Code]](https://github.com/liukun95/Noisy-NER-Confidence-Estimation)
* <a id="paper-535"></a> **[P535]** Understanding the Interaction of Adversarial Training with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.03482.pdf)
* <a id="paper-536"></a> **[P536]** Self-Supervised Noisy Label Learning for Source-Free Unsupervised Domain Adaptation.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.11614.pdf)
* <a id="paper-537"></a> **[P537]** MetaLabelNet: Learning to Generate Soft-Labels from Noisy-Labels.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.10869.pdf)
* <a id="paper-538"></a> **[P538]** Co-matching: Combating Noisy Labels by Augmentation Anchoring.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.12814.pdf)
* <a id="paper-539"></a> **[P539]** Rethinking Noisy Label Models: Labeler-Dependent Noise with Adversarial Awareness.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2105.14083)
* <a id="paper-540"></a> **[P540]** ScanMix: Learning from Severe Label Noise viaSemantic Clustering and Semi-Supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2103.11395)
* <a id="paper-541"></a> **[P541]** Noise-Resistant Deep Metric Learning with Probabilistic Instance Filtering.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.01431.pdf)
* <a id="paper-542"></a> **[P542]** NGC: A Unified Framework for Learning with Open-World Noisy Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.11035.pdf)
* <a id="paper-543"></a> **[P543]** Assessing the Quality of the Datasets by Identifying Mislabeled Samples.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2109.05000.pdf)
* <a id="paper-544"></a> **[P544]** Learning from Multiple Annotators by Incorporating Instance Features.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.15146)
* <a id="paper-545"></a> **[P545]** Learning from Multiple Noisy Partial Labelers.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.04530)
* <a id="paper-546"></a> **[P546]** Instance Correction for Learning with Open-set Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2106.00455)
* <a id="paper-547"></a> **[P547]** Robust Deep Learning from Crowds with Belief Propagation.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2111.00734)
* <a id="paper-548"></a> **[P548]** Prototypical Classifier for Robust Class-Imbalanced Learning.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.11553)
* <a id="paper-549"></a> **[P549]** Study Group Learning: Improving Retinal Vessel Segmentation Trained with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.03451.pdf)[[Code]](https://github.com/SHI-Labs/SGL-Retinal-Vessel-Segmentation)
* <a id="paper-550"></a> **[P550]** Evaluating Multi-label Classifiers with Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2102.08427.pdf)
* <a id="paper-551"></a> **[P551]** Robust Classification from Noisy Labels: Integrating Additional Knowledge for Chest Radiography Abnormality Assessment.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.05261.pdf)
* <a id="paper-552"></a> **[P552]** A Novel Perspective for Positive-Unlabeled Learning via Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.04685.pdf)
* <a id="paper-553"></a> **[P553]** Pathological Image Segmentation with Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.02602.pdf)
* <a id="paper-554"></a> **[P554]** CrowdTeacher: Robust Co-teaching with Noisy Answers & Sample-specific Perturbations for Tabular Data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2103.17144.pdf)
* <a id="paper-555"></a> **[P555]** Learning from Noisy Labels for Entity-Centric Information Extraction.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2104.08656.pdf)
* <a id="paper-556"></a> **[P556]** Temporal-aware Language Representation Learning From Crowdsourced Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2107.07958.pdf)
* <a id="paper-557"></a> **[P557]** Learning From Long-Tailed Data With Noisy Labels.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.11096.pdf)
* <a id="paper-558"></a> **[P558]** Robust Long-Tailed Learning Under Label Noise.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2108.11569.pdf)
* <a id="paper-559"></a> **[P559]** Robust Temporal Ensembling for Learning with Noisy Labels.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Time Series](https://img.shields.io/badge/task-Time%20Series-0891B2?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2109.14563.pdf)
* <a id="paper-560"></a> **[P560]** Knowledge Distillation with Noisy Labels for Natural Language Understanding.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2109.10147.pdf)
* <a id="paper-561"></a> **[P561]** Noisy Annotations Robust Consensual Collaborative Affect Expression Recognition.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021W/ABAW/papers/Gera_Noisy_Annotations_Robust_Consensual_Collaborative_Affect_Expression_Recognition_ICCVW_2021_paper.pdf)

---

### Other Conferences 2021

* <a id="paper-562"></a> **[P562]** (ICCV 2021) Learning with Noisy Labels via Sparse Regularization.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2108.00192)
* <a id="paper-563"></a> **[P563]** (WACV 2022) Towards a Robust Differentiable Architecture Search under Label Noise.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.12197)
* <a id="paper-564"></a> **[P564]** (BMVC 2021) PropMix: Hard Sample Filtering and Proportional MixUp for Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Data Augmentation](https://img.shields.io/badge/Data%20Augmentation-84CC16)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.11809)[[Code]](https://github.com/filipe-research/PropMix.)
* <a id="paper-565"></a> **[P565]** (IJCAI2021 Workshop) An Ensemble Noise-Robust K-fold Cross-Validation Selection Method for Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2107.02347)

---
* <a id="paper-566"></a> **[P566]** (ICCV 2021) Learning with Noisy Labels for Robust Point Cloud Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  [[Paper]](https://shuquanye.com/PNAL_website/)[[Code]](https://github.com/pleaseconnectwifi/PNAL)
* <a id="paper-567"></a> **[P567]** (WACV 2022) Addressing out-of-distribution label noise in webly-labelled data.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Anomaly/OOD](https://img.shields.io/badge/task-Anomaly%2FOOD-EF4444?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2110.13699)[[Code]](https://github.com/PaulAlbert31/DSOS)


## Papers & Code in 2020

---

### NIPS 2020

* <a id="paper-568"></a> **[P568]** Part-dependent Label Noise: Towards Instance-dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/5607fe8879e4fd269e88387e8cb30b7e-Abstract.html)[[Code]](https://github.com/xiaoboxia/Part-dependent-label-noise)
* <a id="paper-569"></a> **[P569]** Identifying Mislabeled Data using the Area Under the Margin Ranking.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/c6102b3727b2a7d8b1bb6981147081ef-Abstract.html)[[Code]](https://github.com/asappresearch/aum)
* <a id="paper-570"></a> **[P570]** Dual T: Reducing Estimation Error for Transition Matrix in Label-noise Learning.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/512c5cad6c37edb98ae91c8a76c3a291-Abstract.html)
* <a id="paper-571"></a> **[P571]** Early-Learning Regularization Prevents Memorization of Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/ea89621bee7c88b2c5be6681c8ef4906-Abstract.html)[[Code]](https://github.com/shengliu66/ELR)
* <a id="paper-572"></a> **[P572]** Coresets for Robust Training of Deep Neural Networks against Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/8493eeaccb772c0878f99d60a0bd2bb3-Abstract.html)[[Code]](https://github.com/snap-stanford/crust)
* <a id="paper-573"></a> **[P573]** Robust Optimization for Fairness with Noisy Protected Groups.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/37d097caf1299d9aa79c2c2b843d2d78-Abstract.html)[[Code]](https://github.com/wenshuoguo/robust-fairness-code)
* <a id="paper-574"></a> **[P574]** A Topological Filter for Learning with Label Noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/f4e3ce3e7b581ff32e40968298ba013d-Abstract.html)[[Code]](https://github.com/pxiangwu/TopoFilter)
* <a id="paper-575"></a> **[P575]** Self-Adaptive Training: beyond Empirical Risk Minimization.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc//paper/2020/hash/e0ab531ec312161511493b002f9be2ee-Abstract.html)[[Code]](https://github.com/LayneH/self-adaptive-training)
* <a id="paper-576"></a> **[P576]** Provably Consistent Partial-Label Learning.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/7bd28f15a49d5e5848d6ec70e584e625-Abstract.html)
* <a id="paper-577"></a> **[P577]** Stochastic Optimization with Heavy-Tailed Noise via Accelerated Gradient Clipping.
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/abd1c782880cc59759f4112fda0b8f98-Abstract.html)[[Code]](https://github.com/eduardgorbunov/accelerated_clipping)
* <a id="paper-578"></a> **[P578]** Non-Convex SGD Learns Halfspaces with Adversarial Label Noise.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/d785bf9067f8af9e078b93cf26de2b54-Abstract.html)
* <a id="paper-579"></a> **[P579]** Efficient active learning of sparse halfspaces with arbitrary bounded noise.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/5034a5d62f91942d2a7aeaf527dfe111-Abstract.html)
* <a id="paper-580"></a> **[P580]** MetaPoison: Practical General-purpose Clean-label Data Poisoning.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![3D/Point Cloud](https://img.shields.io/badge/task-3D%2FPoint%20Cloud-64748B?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/8ce6fc704072e351679ac97d4a985574-Abstract.html)[[Code 1]](https://github.com/wronnyhuang/metapoison)[[Code]](https://github.com/JonasGeiping/poisoning-gradient-matching)
* <a id="paper-581"></a> **[P581]** Modeling Noisy Annotations for Crowd Counting.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/22bb543b251c39ccdad8063d486987bb-Abstract.html)[[Code]](https://github.com/jia-wan/NoisyCC-pytorch)
* <a id="paper-582"></a> **[P582]** Disentangling Human Error from the Ground Truth in Segmentation of Medical Images.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://proceedings.neurips.cc//paper/2020/file/b5d17ed2b502da15aa727af0d51508d6-Paper.pdf)[[Code]](https://github.com/moucheng2017/Learn_Noisy_Labels_Medical_Images)
* <a id="paper-583"></a> **[P583]** Semi-Supervised Partial Label Learning via Confidence-Rated Margin Maximization.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/4dea382d82666332fb564f2e711cbc71-Abstract.html)
* <a id="paper-584"></a> **[P584]** Labelling unlabelled videos from scratch with multi-modal self-supervision.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Audio/Video](https://img.shields.io/badge/task-Audio%2FVideo-0EA5E9?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/31fefc0e570cb3860f2a6d4b38c6490d-Abstract.html)[[Code]](https://github.com/facebookresearch/selavi)
* <a id="paper-585"></a> **[P585]** Distribution Aligning Refinery of Pseudo-label for Imbalanced Semi-supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Long-tailed Learning](https://img.shields.io/badge/task-Long--tailed%20Learning-B45309?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/a7968b4339a1b85b7dbdb362dc44f9c4-Abstract.html)[[Code]](https://github.com/bbuing9/DARP)
* <a id="paper-586"></a> **[P586]** A Variational Approach for Learning from Positive and Unlabeled Data.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://papers.nips.cc/paper/2020/hash/aa0d2a804a3510442f2fd40f2100b054-Abstract.html)[[Code]](https://github.com/HC-Feynman/vpu)

---

---

### ICML 2020

* <a id="paper-587"></a> **[P587]** Peer Loss Functions: Learning from Noisy Labels without Knowing Noise Rates.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/liu20e)[[Code 1]](https://github.com/weijiaheng/Multi-class-Peer-Loss-functions) [[Code 2]](https://github.com/gohsyi/PeerLoss)
* <a id="paper-588"></a> **[P588]** Normalized Loss Functions for Deep Learning with Noisy Labels.
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2006.13554)[[Code]](https://github.com/HanxunH/Active-Passive-Losses)
* <a id="paper-589"></a> **[P589]** SIGUA: Forgetting May Make Learning with Noisy Labels More Robust.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/han20c.html)[[Code]](https://github.com/bhanML/SIGUA)
* <a id="paper-590"></a> **[P590]** Error-Bounded Correction of Noisy Labels.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/zheng20c.html)[[Code]](https://github.com/pingqingsheng/LRT)
* <a id="paper-591"></a> **[P591]** Training Binary Neural Networks through Learning with Noisy Supervision.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/han20d.html)[[Code]](https://github.com/zhaohui-yang/Binary-Neural-Networks)
* <a id="paper-592"></a> **[P592]** Searching to Exploit Memorization Effect in Learning with Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/yao20b.html)[[Code]](https://github.com/jerermyyoung/rtlearning)
* <a id="paper-593"></a> **[P593]** Learning with Bounded Instance and Label-dependent Label Noise.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/cheng20c.html)
* <a id="paper-594"></a> **[P594]** Beyond Synthetic Noise: Deep Learning on Controlled Noisy Labels.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/jiang20c)
* <a id="paper-595"></a> **[P595]** Does label smoothing mitigate label noise?.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/lukasik20a.html)
* <a id="paper-596"></a> **[P596]** Deep k-NN for Noisy Labels.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/bahri20a.html)
* <a id="paper-597"></a> **[P597]** Improving generalization by controlling label-noise information in neural network weights.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/harutyunyan20a.html)[[Code]](https://github.com/hrayrhar/limit-label-memorization)
* <a id="paper-598"></a> **[P598]** Label-Noise Robust Domain Adaptation.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/yu20c.html)
* <a id="paper-599"></a> **[P599]** Certified Robustness to Label-Flipping Attacks via Randomized Smoothing.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://proceedings.mlr.press/v119/rosenfeld20b.html)
* <a id="paper-600"></a> **[P600]** Self-PU: Self Boosted and Calibrated Positive-Unlabeled Training.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://arxiv.org/abs/2006.11280)[[Code]](https://github.com/VITA-Group/Self-PU)
* <a id="paper-601"></a> **[P601]** Learning with Multiple Complementary Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/feng20a.html)
* <a id="paper-602"></a> **[P602]** Extreme Multi-label Classification from Aggregated Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](http://proceedings.mlr.press/v119/shen20f.html)

---

---

### ICLR 2020

* <a id="paper-603"></a> **[P603]** DivideMix: Learning with Noisy Labels as Semi-supervised Learning.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=HJgExaVtwr)[[Code]](https://github.com/LiJunnan1992/DivideMix)
* <a id="paper-604"></a> **[P604]** Robust training with ensemble consensus.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=ryxOUTVYDH)[[Code]](https://github.com/jisoolee0123/Robust-training-with-ensemble-consensus)
* <a id="paper-605"></a> **[P605]** SELF: Learning to Filter Noisy Labels with Self-Ensembling.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=HkgsPhNYPS)

---
* <a id="paper-606"></a> **[P606]** Learning from Rules Generalizing Labeled Exemplars.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/pdf?id=SkeuexBtDr) [[Code]](https://github.com/awasthiabhijeet/Learning-From-Rules)
* <a id="paper-607"></a> **[P607]** Self-labelling via simultaneous clustering and representation learning.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Hyx-jyBFPr)[[Code]](https://github.com/yukimasano/self-label)
* <a id="paper-608"></a> **[P608]** Can gradient clipping mitigate label noise?
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Vision-Language](https://img.shields.io/badge/task-Vision--Language-0D9488?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rklB76EKPr)[[Code]](https://github.com/dmizr/phuber)
* <a id="paper-609"></a> **[P609]** Curriculum Loss: Robust Learning and Generalization against Label Corruption.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rkgt0REKwS)
* <a id="paper-610"></a> **[P610]** Simple and Effective Regularization Methods for Training on Noisily Labeled Data with Generalization Guarantee.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=Hke3gyHYwH)
* <a id="paper-611"></a> **[P611]** Mutual Mean-Teaching: Pseudo Label Refinery for Unsupervised Domain Adaptation on Person Re-identification.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openreview.net/forum?id=rJlnOhVYPS)[[Code]](https://github.com/yxgeee/MMT)

---

### CVPR 2020

* <a id="paper-612"></a> **[P612]** Combating noisy labels by agreement: A joint training method with co-regularization.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Wei_Combating_Noisy_Labels_by_Agreement_A_Joint_Training_Method_with_CVPR_2020_paper.html)[[Code]](https://github.com/hongxin001/JoCoR)
* <a id="paper-613"></a> **[P613]** Distilling Effective Supervision From Severe Label Noise.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Distilling_Effective_Supervision_From_Severe_Label_Noise_CVPR_2020_paper.html)[[Code]](https://github.com/google-research/google-research/tree/master/ieg)
* <a id="paper-614"></a> **[P614]** Self-Training With Noisy Student Improves ImageNet Classification.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Xie_Self-Training_With_Noisy_Student_Improves_ImageNet_Classification_CVPR_2020_paper.html)[[Code]](https://github.com/google-research/noisystudent)
* <a id="paper-615"></a> **[P615]** Training Noise-Robust Deep Neural Networks via Meta-Learning.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Training_Noise-Robust_Deep_Neural_Networks_via_Meta-Learning_CVPR_2020_paper.html)[[Code]](https://github.com/ZhenWang-PhD/Training-Noise-Robust-Deep-Neural-Networks-via-Meta-Learning)
* <a id="paper-616"></a> **[P616]** Task Agnostic Robust Learning on Corrupt Outputs by Correlation-Guided Mixture Density Networks.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Choi_Task_Agnostic_Robust_Learning_on_Corrupt_Outputs_by_Correlation-Guided_Mixture_CVPR_2020_paper.html)

---
* <a id="paper-617"></a> **[P617]** Global-Local GCN: Large-Scale Label Noise Cleansing for Face Recognition.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Global-Local_GCN_Large-Scale_Label_Noise_Cleansing_for_Face_Recognition_CVPR_2020_paper.html)
* <a id="paper-618"></a> **[P618]** Spherical Space Domain Adaptation With Robust Pseudo-Label Loss.
  ![Loss Correction](https://img.shields.io/badge/Loss%20Correction-F43F5E)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Gu_Spherical_Space_Domain_Adaptation_With_Robust_Pseudo-Label_Loss_CVPR_2020_paper.html)[[Code]](https://github.com/XJTU-XGU/RSDA)
* <a id="paper-619"></a> **[P619]** Generating Accurate Pseudo-Labels in Semi-Supervised Learning and Avoiding Overconfident Predictions via Hermite Polynomial Activations.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lokhande_Generating_Accurate_Pseudo-Labels_in_Semi-Supervised_Learning_and_Avoiding_Overconfident_Predictions_CVPR_2020_paper.html)[[Code]](https://github.com/lokhande-vishnu/DeepHermites)
* <a id="paper-620"></a> **[P620]** Learning From Web Data With Self-Organizing Memory Module.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Tu_Learning_From_Web_Data_With_Self-Organizing_Memory_Module_CVPR_2020_paper.html)
* <a id="paper-621"></a> **[P621]** Noise Robust Generative Adversarial Networks.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Kaneko_Noise_Robust_Generative_Adversarial_Networks_CVPR_2020_paper.html)[[Code]](https://github.com/takuhirok/NR-GAN/)
* <a id="paper-622"></a> **[P622]** DLWL: Improving Detection for Lowshot Classes With Weakly Labelled Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  ![Weak Supervision](https://img.shields.io/badge/task-Weak%20Supervision-4B5563?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Ramanathan_DLWL_Improving_Detection_for_Lowshot_Classes_With_Weakly_Labelled_Data_CVPR_2020_paper.html)
* <a id="paper-623"></a> **[P623]** Shoestring: Graph-Based Semi-Supervised Classification With Severely Limited Labeled Data.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lin_Shoestring_Graph-Based_Semi-Supervised_Classification_With_Severely_Limited_Labeled_Data_CVPR_2020_paper.html)[[Code]](https://github.com/iQua/CVPR2020-Shoestring)
* <a id="paper-624"></a> **[P624]** Noise-Aware Fully Webly Supervised Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Shen_Noise-Aware_Fully_Webly_Supervised_Object_Detection_CVPR_2020_paper.html)[[Code]](https://github.com/shenyunhang/NA-fWebSOD)
* <a id="paper-625"></a> **[P625]** Learning From Noisy Anchors for One-Stage Object Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_Learning_From_Noisy_Anchors_for_One-Stage_Object_Detection_CVPR_2020_paper.html)[[Code]](https://github.com/henrylee2570/NoisyAnchor)

---

### ECCV 2020

* <a id="paper-626"></a> **[P626]** Suppressing Mislabeled Data via Grouping and Self-Attention.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2633_ECCV_2020_paper.php)[[Code]](https://github.com/kaiwang960112/AFM)
* <a id="paper-627"></a> **[P627]** NoiseRank: Unsupervised Label Noise Reduction with Dependence Models.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/5921_ECCV_2020_paper.php)
* <a id="paper-628"></a> **[P628]** Learning with Noisy Class Labels for Instance Segmentation.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2062_ECCV_2020_paper.php)[[Code]](https://github.com/longrongyang/LNCIS)
* <a id="paper-629"></a> **[P629]** Weakly Supervised Learning with Side Information for Noisy Labeled Images.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/7467_ECCV_2020_paper.php)
* <a id="paper-630"></a> **[P630]** Learning Noise-Aware Encoder-Decoder from Noisy Labels by Alternating Back-Propagation for Saliency Detection.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Object Detection](https://img.shields.io/badge/task-Object%20Detection-EA580C?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2760_ECCV_2020_paper.php)
* <a id="paper-631"></a> **[P631]** Graph convolutional networks for learning with few clean and many noisy labels.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Graph Data](https://img.shields.io/badge/task-Graph%20Data-16A34A?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1060_ECCV_2020_paper.php)
* <a id="paper-632"></a> **[P632]** Robust and On-the-fly Dataset Denoising for Image Classification.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Datasets](https://img.shields.io/badge/Datasets-0F766E)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740545.pdf)
* <a id="paper-633"></a> **[P633]** Sub-center ArcFace: Boosting Face Recognition by Large-scale Noisy Web Faces.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1445_ECCV_2020_paper.php)
* <a id="paper-634"></a> **[P634]** Webly Supervised Image Classification with Self-Contained Confidence.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/701_ECCV_2020_paper.php)
* <a id="paper-635"></a> **[P635]** Unsupervised Domain Adaptation with Noise Resistible Mutual-Training for Person Re-identification.
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Retrieval](https://img.shields.io/badge/task-Retrieval-2563EB?style=flat-square)
  [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1391_ECCV_2020_paper.php)

---

---

---

### AAAI 2020

* <a id="paper-636"></a> **[P636]** Reinforcement Learning with Perturbed Rewards.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/abs/1810.01032) [[Code]](https://github.com/wangjksjtu/rl-perturbed-reward)
* <a id="paper-637"></a> **[P637]** Less Is Better: Unweighted Data Subsampling via Influence Function.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/abs/1912.01321) [[Code]](https://github.com/RyanWangZf/Influence_Subsampling)
* <a id="paper-638"></a> **[P638]** Self-Paced Robust Learning for Leveraging Clean Labels in Noisy Data.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://xuczhang.github.io/papers/aaai20_sprl.pdf)
* <a id="paper-639"></a> **[P639]** Label Error Correction and Generation Through Label Relationships.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5778)

---
* <a id="paper-640"></a> **[P640]** Weakly Supervised Sequence Tagging from Noisy Rules.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Semi-Supervised Learning](https://img.shields.io/badge/task-Semi--Supervised%20Learning-22C55E?style=flat-square)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/6009)[[Code]](https://github.com/BatsResearch/wiser)
* <a id="paper-641"></a> **[P641]** Coupled-View Deep Classifier Learning from Multiple Noisy Annotators.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5898)
* <a id="paper-642"></a> **[P642]** Partial multi-label learning with noisy label identification.
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](http://www.xiemk.pro/publication/aaai20-pml-ni.pdf)

---

### IJCAI 2020

* <a id="paper-643"></a> **[P643]** Can Cross Entropy Loss Be Robust to Label Noise?
  ![Robust Loss](https://img.shields.io/badge/Robust%20Loss-EF4444)
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2020/305)
* <a id="paper-644"></a> **[P644]** Label Distribution for Learning with Noisy Labels.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2020/356)
* <a id="paper-645"></a> **[P645]** A Bi-level Formulation for Label Noise Learning with Spectral Cluster Discovery.
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2020/361)
* <a id="paper-646"></a> **[P646]** Cross-denoising Network against Corrupted Labels in Medical Image Segmentation with Domain Shift.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2020/146)
* <a id="paper-647"></a> **[P647]** Towards Accurate and Robust Domain Adaptation under Noisy Environments.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2020/314)
* <a id="paper-648"></a> **[P648]** Aggregating Crowd Wisdom with Side Information via a Clustering-based Label-aware Autoencoder.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2020/214)
* <a id="paper-649"></a> **[P649]** Learning with Noise: Improving Distantly-Supervised Fine-grained Entity Typing via Automatic Relabeling.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2020/527)
* <a id="paper-650"></a> **[P650]** Recovering Accurate Labeling Information from Partially Valid Data for Effective Multi-Label Learning.
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2020/191)
* <a id="paper-651"></a> **[P651]** Partial Multi-Label Learning via Multi-Subspace Representation.
  ![Representation Learning](https://img.shields.io/badge/Representation%20Learning-14B8A6)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  ![Partial Label Learning](https://img.shields.io/badge/task-Partial%20Label%20Learning-A16207?style=flat-square)
  [[Paper]](https://www.ijcai.org/proceedings/2020/362)

---

---

### KDD 2020

* <a id="paper-652"></a> **[P652]** Semi-Supervised Multi-Label Learning from Crowds via Deep Sequential Generative Model.
  ![Noise Modeling](https://img.shields.io/badge/Noise%20Modeling-8B5CF6)
  ![Semi-Supervised](https://img.shields.io/badge/Semi--Supervised-22C55E)
  ![Multi-Label](https://img.shields.io/badge/task-Multi--Label-BE185D?style=flat-square)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  ![Crowdsourcing](https://img.shields.io/badge/task-Crowdsourcing-F59E0B?style=flat-square)
  [[Paper]](https://doi.org/10.1145/3394486.3403167)

---

---

### ArXiv 2020

* <a id="paper-653"></a> **[P653]** No Regret Sample Selection with Noisy Labels. (Published on Machine Learning)
  ![Sample Selection](https://img.shields.io/badge/Sample%20Selection-F59E0B)
  ![Classification LNL](https://img.shields.io/badge/task-Classification%20LNL-DC2626?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2003.03179.pdf)[[Code]](https://github.com/songheony/TAkS)
* <a id="paper-654"></a> **[P654]** Meta Soft Label Generation for Noisy Labels. (Published on ICPR 2020)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![NLP/Text](https://img.shields.io/badge/task-NLP%2FText-7C3AED?style=flat-square)
  ![Generative Models](https://img.shields.io/badge/task-Generative%20Models-8B5CF6?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2007.05836.pdf)[[Code]](https://github.com/gorkemalgan/MSLG_noisy_label)
* <a id="paper-655"></a> **[P655]** Learning from Noisy Labels with Deep Neural Networks: A Survey.
  ![Theory](https://img.shields.io/badge/Theory-6B7280)
  ![Other Robust Techniques](https://img.shields.io/badge/Other%20Robust%20Techniques-64748B)
  ![Other Tasks](https://img.shields.io/badge/task-Other%20Tasks-6B7280?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2007.08199.pdf)
* <a id="paper-656"></a> **[P656]** RAR-U-Net: a Residual Encoder to Attention Decoder by Residual Connections Framework for Spine Segmentation under Noisy Labels. (Published on ICIP 2021)
  ![Label Correction](https://img.shields.io/badge/Label%20Correction-3B82F6)
  ![Segmentation](https://img.shields.io/badge/task-Segmentation-F97316?style=flat-square)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2009.12873.pdf)
* <a id="paper-657"></a> **[P657]** Learning from Small Amount of Medical Data with Noisy Labels: A Meta-Learning Approach. (Published on ICRPOA 2021)
  ![Meta-Learning](https://img.shields.io/badge/Meta--Learning-A855F7)
  ![Medical Imaging](https://img.shields.io/badge/task-Medical%20Imaging-DB2777?style=flat-square)
  [[Paper]](https://arxiv.org/pdf/2010.06939.pdf)

---

## Acknowledgements

This repository is partially based on and inspired by the following project:

- https://github.com/weijiaheng/Advances-in-Label-Noise-Learning
