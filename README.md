# 📽️ Awesome Video Anomaly Detection
![GitHub License](https://img.shields.io/github/license/Junxi-Chen/Awesome-Video-Anomaly-Detection)
![Awesome](https://awesome.re/badge.svg)

Video anomaly detection (VAD) aims to identify, understand and describe anomalous events in videos. This repository collects the latest research papers, code, datasets, seminars, utilities and related resources for VAD, ***updated every Friday***. Like this repo😄? ⭐ it and feel free to open an [issue](https://github.com/Junxi-Chen/Awesome-Video-Anomaly-Detection/issues) for feedback.

 > [!note] 
 > Welcome to nominate VAD papers or related resources via [pull request](https://github.com/Junxi-Chen/Awesome-Video-Anomaly-Detection/pulls)! Please refer to [CONTRIBUTING.md](./CONTRIBUTING.md) for detailed guidelines.

## 📌 Contents
- [📌 Contents](#-contents)
- [🔥 Recent Updates](#-recent-updates)
- [🧪 New Setting Papers](#-new-setting-papers)
- [📃 Weakly-supervised VAD Papers](#-weakly-supervised-vad-papers)
  - [Prompt Involved Papers](#prompt-involved-papers)
- [📃 Semi-supervised VAD Papers](#-semi-supervised-vad-papers)
- [📃 Skeleton-based Papers](#-skeleton-based-papers)
- [📃 Fully-supervised VAD Papers](#-fully-supervised-vad-papers)
- [📑 Surveys](#-surveys)
- [🏗️ Benchmarks](#️-benchmarks)
- [💽 Datasets](#-datasets)
  - [Links](#links)
  - [Statistics](#statistics)
- [🧑🏻‍🏫 Seminars](#-seminars)
- [👷🏻‍♂️ Evaluation Metrics](#️-evaluation-metrics)
- [🛠️ Utilities](#️-utilities)
- [🔗 Related Repositories](#-related-repositories)
- [🙌🏻 Acknowledgements](#-acknowledgements)
- [🔖 Citation](#-citation)


## 🔥 Recent Updates
<!---
 &nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA) 
-->
Last Update: June, 2025

- ICCV '25
- CVPR '25
- ICML '25
- ICLR '25

Related Repositories: \
<a href='#uws4vad'>uws4vad-wiki</a> 🔥🔥🔥 \
<a href='#VAD-table'>Video-Anomaly-Detection</a>

Papers: \
<a href='#ADSM'>ADSM</a> \
<a href='#SeeKer'>SeeKer</a> \
<a href='#ADRM'>ADRM</a> \
<a href='#MA-PDM'>MA-PDM</a> \
<a href='#TAO'>TAO</a> \
<a href='#LEC-VAD'>LEC-VAD</a> \
<a href='#pi-VAD'>&pi;-VAD</a> \
<a href='#SFN-VAD'>SFN-VAD</a> \
<a href='#SVTA'>SVTA</a> \
<a href='#VAU-R1'>VAU-R1</a> \
<a href='#VERA'>VERA</a> \

## 🧪 New Setting Papers
<!--
1. [] **Aligning Effective Tokens with Video Anomaly in Large Language Models** <a id=''></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA) \
ICCV '25 [[paper]()]
-->

1. [TAO] **Track Any Anomalous Object: A Granular Video Anomaly Detection Pipeline** <a id='TAO'></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA) \
CVPR '25 [[paper](https://arxiv.org/pdf/2506.05175)][[project](https://tao-25.github.io/)][[code](https://github.com/yu2hi13/TAO)]

1. [SVTA] **Towards Scalable Video Anomaly Retrieval: A Synthetic Video-Text Benchmark** <a id='SVTA'></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA)\
![LLM](https://img.shields.io/badge/LLM-FFA500) ![benchmark](https://img.shields.io/badge/benchmark-548389) \
arXiv '25 [[paper](https://arxiv.org/pdf/2506.01466)][[project](https://svta-mm.github.io/SVTA.github.io/)]

1. [VAU-R1] **Advancing Video Anomaly Understanding
    via Reinforcement Fine-Tuning** <a id='VAU-R1'></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA)\
![LLM](https://img.shields.io/badge/LLM-FFA500) ![benchmark](https://img.shields.io/badge/benchmark-548389) \
arXiv '25 [[paper](https://arxiv.org/pdf/2505.23504)][[code](https://github.com/GVCLab/VAU-R1)]

1. [VANE-Bench] **VANE-Bench: Video Anomaly Evaluation Benchmark for Conversational LMMs** <a id='VANE-Bench'></a> \
![LLM](https://img.shields.io/badge/LLM-FFA500) ![benchmark](https://img.shields.io/badge/benchmark-548389) \
NAACL '25 [[paper](https://arxiv.org/pdf/2406.10326)][[code](https://github.com/rohit901/VANE-Bench)][[dataset](https://huggingface.co/datasets/rohit901/VANE-Bench)][[project](https://hananshafi.github.io/vane-benchmark/)]

1. [Sherlock] **Sherlock: Towards Multi-scene Video Abnormal Event Extraction and Localization via a Global-local Spatial-sensitive LLM** <a id='Sherlock'></a> \
    ![LLM](https://img.shields.io/badge/LLM-FFA500) ![benchmark](https://img.shields.io/badge/benchmark-548389) \
    WWW '25 [[paper](https://arxiv.org/pdf/2502.18863)][[OpenReview](https://openreview.net/forum?id=YHW5w2hZcZ#discussion)]

2. [SurveillanceVQA-589K] **SurveillanceVQA-589K: A Benchmark for Comprehensive Surveillance Video-Language Understanding with Large Models** <a id='SurveillanceVQA-589K'></a>\
![LLM](https://img.shields.io/badge/LLM-FFA500) ![benchmark](https://img.shields.io/badge/benchmark-548389) \
arXiv '25 [[paper](https://arxiv.org/pdf/2505.12589)][[annotation](https://huggingface.co/datasets/fei213/SurveillanceVQA-589K)]

1. [VERA] **VERA: Explainable Video Anomaly Detection via Verbalized Learning of Vision-Language Models**  <a id='VERA'></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA) \
![LLM](https://img.shields.io/badge/LLM-FFA500) \
CVPR '25 [[paper](https://arxiv.org/pdf/2412.01095)][[code](https://github.com/vera-framework/VERA)][[project](https://vera-framework.github.io)]

1. [Holmes-VAU] **Holmes-VAU: Towards Long-term Video Anomaly Understanding at Any Granularity** <a id='Holmes-VAU'></a> \
![LLM](https://img.shields.io/badge/LLM-FFA500) ![benchmark](https://img.shields.io/badge/benchmark-548389) \
CVPR '25 [[paper](https://arxiv.org/pdf/2412.06171)][[code & annotation](https://github.com/pipixin321/HolmesVAU)]

1. [HAWK] **HAWK: Learning to Understand Open-World Video Anomalies** <a id='HAWK'></a> \
![LLM](https://img.shields.io/badge/LLM-FFA500) ![benchmark](https://img.shields.io/badge/benchmark-548389) \
NeurIPS '24 [[paper](https://github.com/jqtangust/hawk)][[code](https://github.com/jqtangust/hawk)][[annotation](https://drive.google.com/file/d/1WCnizldWZvtS4Yg5SX7ay5C3kUQfz-Eg/view)]

1. [VAR] **Toward Video Anomaly Retrieval From Video Anomaly Detection: New Benchmarks and Model**\
![I3D](https://img.shields.io/badge/I3D-35BF5C)
![with-Audio](https://img.shields.io/badge/with--Audio-00B2FF) ![benchmark](https://img.shields.io/badge/benchmark-548389)\
       TIP '24 [[paper](https://ieeexplore.ieee.org/document/10471334/)][[dataset](https://github.com/Roc-Ng/VAR)]

1. [AnomalyRuler] **Follow the Rules: Reasoning for Video Anomaly Detection with Large Language Models** \
![LLM](https://img.shields.io/badge/LLM-FFA500)\
ECCV '24 [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10568.pdf)][[code](https://github.com/Yuchen413/AnomalyRuler)]

1. [UCA] **Towards Surveillance Video-and-Language Understanding: New Dataset, Baselines, and Challenges** <a id='UCA'></a> \
![benchmark](https://img.shields.io/badge/benchmark-548389) \
CVPR '24 [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Yuan_Towards_Surveillance_Video-and-Language_Understanding_New_Dataset_Baselines_and_Challenges_CVPR_2024_paper.pdf)][[code & annotation](https://github.com/Xuange923/Surveillance-Video-Understanding)][[project](https://xuange923.github.io/Surveillance-Video-Understanding)]

1. [GlanceVAD] **GlanceVAD: Exploring Glance Supervision for Label-efficient Video Anomaly Detection** <a id='GlanceVAD'></a> \
![I3D](https://img.shields.io/badge/I3D-35BF5C) ![benchmark](https://img.shields.io/badge/benchmark-548389) \
ICME '25 [[paper](https://arxiv.org/pdf/2403.06154)][[code & annotation](https://github.com/pipixin321/GlanceVAD)]

1. [OVVAD] **Open-Vocabulary Video Anomaly Detection** \
![CLIP-V](https://img.shields.io/badge/CLIP--V-6d4aff)
![CLIP-T](https://img.shields.io/badge/CLIP--T-C3B9FA)
![LLM](https://img.shields.io/badge/LLM-FFA500)\
CVPR '24 [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Wu_Open-Vocabulary_Video_Anomaly_Detection_CVPR_2024_paper.pdf)][[supp](https://openaccess.thecvf.com/content/CVPR2024/supplemental/Wu_Open-Vocabulary_Video_Anomaly_CVPR_2024_supplemental.pdf)]

1. [LAVAD] **Harnessing Large Language Models for Training-free Video Anomaly Detection** \
![LLM](https://img.shields.io/badge/LLM-FFA500)\
CVPR '24 [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Zanella_Harnessing_Large_Language_Models_for_Training-free_Video_Anomaly_Detection_CVPR_2024_paper.pdf)][[code](https://github.com/lucazanella/lavad)][[supp](https://openaccess.thecvf.com/content/CVPR2024/supplemental/Zanella_Harnessing_Large_Language_CVPR_2024_supplemental.pdf)]

1. [CUVA] **Uncovering What, Why and How:  A Comprehensive Benchmark for Causation Understanding of Video Anomaly** \
![LLM](https://img.shields.io/badge/LLM-FFA500) ![benchmark](https://img.shields.io/badge/benchmark-548389) \
CVPR '24 [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Du_Uncovering_What_Why_and_How_A_Comprehensive_Benchmark_for_Causation_CVPR_2024_paper.pdf)][[code & dataset](https://github.com/fesvhtr/CUVA)][[supp](https://openaccess.thecvf.com/content/CVPR2024/html/Du_Uncovering_What_Why_and_How_A_Comprehensive_Benchmark_for_Causation_CVPR_2024_paper.html)]

1.  [UCF-Crime-DVS] **UCF-Crime-DVS: A Novel Event-Based Dataset for Video Anomaly Detection with Spiking Neural** <a id='UCF-Crime-DVS'></a> \
![benchmark](https://img.shields.io/badge/benchmark-548389) \
[[paper](https://arxiv.org/pdf/2503.12905v1)][[code & dataset](https://github.com/YBQian-Roy/UCF-Crime-DVS)]

1.  [TDSD] **TDSD: Text-Driven Scene-Decoupled Weakly Supervised Video Anomaly Detection** <a id='TDSD'></a> \
![I3D](https://img.shields.io/badge/I3D-35BF5C)
![CLIP-V](https://img.shields.io/badge/CLIP--V-6d4aff)
![CLIP-T](https://img.shields.io/badge/CLIP--T-C3B9FA) ![benchmark](https://img.shields.io/badge/benchmark-548389)\
ACM MM '24 [[paper](https://openreview.net/pdf?id=TAVtkpjS9P)][[code](https://github.com/shengyangsun/TDSD)][[OpenReview](https://openreview.net/forum?id=TAVtkpjS9P&noteId=TAVtkpjS9P)]

## 📃 Weakly-supervised VAD Papers
<!--
1. [] **Mixture of Experts Guided by Gaussian Splatters Matters: A new Approach to Weakly-Supervised Video Anomaly Detection** <a id='ADRM'></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA)\
ICCV '25 [[paper]()]
-->

1. [ADRM] **Dual‑Detector Reoptimization for Federated Weakly Supervised Video Anomaly Detection via Adaptive Dynamic Recursive Mapping** <a id='ADRM'></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA)\
   ![Fed‑VAD](https://img.shields.io/badge/Fed--VAD-E64B35)
   ![MAEv2](https://img.shields.io/badge/MAEv2-4DBBD5)
   ![Edge‑Jetson](https://img.shields.io/badge/Edge--Jetson-76B900?logo=nvidia&logoColor=white)\
   TII '25  [[paper](https://ieeexplore.ieee.org/document/11036561)] [[code](https://github.com/rekkles2/Fed_WSVAD)] [[supp](https://github.com/rekkles2/Fed_WSVAD/blob/main/Figure/Appendix.pdf)]

1. [CDL] **Cross-Domain Learning for Video Anomaly Detection with Limited Supervision** \
![I3D](https://img.shields.io/badge/I3D-35BF5C)
![CLIP-V](https://img.shields.io/badge/CLIP--V-6d4aff)\
ECCV '24 [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04459.pdf)]

1. [HLGAtt] **Cross-Modal Fusion and Attention Mechanism for Weakly Supervised Video Anomaly Detection** <a id='HLGAtt'></a> \
![I3D](https://img.shields.io/badge/I3D-35BF5C)
![with-Audio](https://img.shields.io/badge/with--Audio-00B2FF)\
    CVPR '24 Workshop [[paper](https://openaccess.thecvf.com/content/CVPR2024W/MULA/papers/Ghadiya_Cross-Modal_Fusion_and_Attention_Mechanism_for_Weakly_Supervised_Video_Anomaly_CVPRW_2024_paper.pdf)] 

1. [ECU] **Exploiting Completeness and Uncertainty of Pseudo Labels for Weakly Supervised Video Anomaly Detection** <a id='ECU'></a>\
![I3D](https://img.shields.io/badge/I3D-35BF5C)\
CVPR '23 [[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Exploiting_Completeness_and_Uncertainty_of_Pseudo_Labels_for_Weakly_Supervised_CVPR_2023_paper.pdf)][[code](https://github.com/ArielZc/CU-Net)][[supp](https://openaccess.thecvf.com/content/CVPR2023/supplemental/Zhang_Exploiting_Completeness_and_CVPR_2023_supplemental.pdf)]

1. [CoMo] **Look Around for Anomalies: Weakly-supervised Anomaly Detection via Context-Motion Relational Learning** <a id='CoMo'></a> \
![I3D](https://img.shields.io/badge/I3D-35BF5C)\
CVPR '23 [[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Cho_Look_Around_for_Anomalies_Weakly-Supervised_Anomaly_Detection_via_Context-Motion_Relational_CVPR_2023_paper.pdf)][[supp](https://openaccess.thecvf.com/content/CVPR2023/supplemental/Cho_Look_Around_for_CVPR_2023_supplemental.pdf)]

1. [ADGCN] **Graph Convolutional Label Noise Cleaner: Train a Plug-and-play Action Classifier for Anomaly Detection** <a id='Plug-and-play'></a>\
CVPR 19' [[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhong_Graph_Convolutional_Label_Noise_Cleaner_Train_a_Plug-And-Play_Action_Classifier_CVPR_2019_paper.pdf)][[code](https://github.com/jx-zhong-for-academic-purpose/GCN-Anomaly-Detection)]

### Prompt Involved Papers
1. [&pi;-VAD] **Just Dance with $\pi$! A Poly-modal Inductor for Weakly-supervised Video Anomaly Detection** <a id='pi-VAD'></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA)\
![I3D](https://img.shields.io/badge/I3D-35BF5C) ![CLIP-T](https://img.shields.io/badge/CLIP--T-C3B9FA) \
CVPR '25 [[paper](https://arxiv.org/pdf/2505.13123)]

1. [LEC-VAD] **Learning Event Completeness for Weakly Supervised Video Anomaly Detection** <a id='LEC-VAD'></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA)\
![I3D](https://img.shields.io/badge/I3D-35BF5C) ![CLIP-V](https://img.shields.io/badge/CLIP--V-6d4aff) ![CLIP-T](https://img.shields.io/badge/CLIP--T-C3B9FA)\
ICML '25 [[paper](https://arxiv.org/pdf/2506.13095)]
  
1. [Fed-WSVAD] **Federated Weakly Supervised video Anomaly Detection with Multimodal Prompt** <a id='Fed-WSVAD'></a>\
![Fed‑VAD](https://img.shields.io/badge/Fed--VAD-E64B35)
![CLIP-V](https://img.shields.io/badge/CLIP--V-6d4aff)
![CLIP-T](https://img.shields.io/badge/CLIP--T-C3B9FA)\
AAAI '25 [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/35398/37553)][[code](https://github.com/wbfwonderful/Fed-WSVAD)]

1. [STPrompt] **Weakly Supervised Video Anomaly Detection and Localization with Spatio-Temporal Prompts** <a id='STPrompt'></a> \
![CLIP-V](https://img.shields.io/badge/CLIP--V-6d4aff)
![CLIP-T](https://img.shields.io/badge/CLIP--T-C3B9FA)\
ACM MM '24 [[paper](https://arxiv.org/pdf/2408.05905)][[OpenReview](https://openreview.net/forum?id=2es1ojI14x&referrer=%5Bthe%20profile%20of%20Peng%20Wu%5D(%2Fprofile%3Fid%3D~Peng_Wu2))]

1. [Vadclip] **Vadclip: Adapting vision-language models for weakly supervised video anomaly detection** <a id='Vadclip'></a> \
![CLIP-V](https://img.shields.io/badge/CLIP--V-6d4aff)
![CLIP-T](https://img.shields.io/badge/CLIP--T-C3B9FA)\
AAAI '24 [[paper](https://ojs.aaai.org/index.php/AAAI/article/download/28423/28826)][[code](https://github.com/nwpu-zxr/VadCLIP)] 

1. [PE-MIL] **Prompt-Enhanced Multiple Instance Learning for Weakly Supervised Video Anomaly Detection** <a id='PE-MIL'></a> \
![I3D](https://img.shields.io/badge/I3D-35BF5C)
![CLIP-T](https://img.shields.io/badge/CLIP--T-C3B9FA)
![with-Audio](https://img.shields.io/badge/with--Audio-00B2FF)\
CVPR '24 [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_Prompt-Enhanced_Multiple_Instance_Learning_for_Weakly_Supervised_Video_Anomaly_Detection_CVPR_2024_paper.pdf)][[code](https://github.com/Junxi-Chen/PE-MIL)][[supp](https://openaccess.thecvf.com/content/CVPR2024/supplemental/Chen_Prompt-Enhanced_Multiple_Instance_CVPR_2024_supplemental.pdf)]

1. [TPWNG] **Text Prompt with Normality Guidance for Weakly Supervised Video Anomaly Detection** \
![CLIP-V](https://img.shields.io/badge/CLIP--V-6d4aff)
![CLIP-T](https://img.shields.io/badge/CLIP--T-C3B9FA)\
CVPR '24 [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_Text_Prompt_with_Normality_Guidance_for_Weakly_Supervised_Video_Anomaly_CVPR_2024_paper.pdf)][[supp](https://openaccess.thecvf.com/content/CVPR2024/supplemental/Yang_Text_Prompt_with_CVPR_2024_supplemental.pdf)]

1. [PEL4VAD] **Learning Prompt-Enhanced Context features for Weakly-Supervised Video Anomaly Detection** \
![I3D](https://img.shields.io/badge/I3D-35BF5C)
![CLIP-T](https://img.shields.io/badge/CLIP--T-C3B9FA) \
TIP '24 [[paper](https://ieeexplore.ieee.org/document/10667004/)][[code](https://github.com/yujiangpu20/PEL4VAD)]

## 📃 Semi-supervised VAD Papers
1. [ADSM] **Autoregressive Denoising Score Matching is a Good Video Anomaly Detector** <a id='ADSM'></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA) \
ICCV '25 [[paper](https://arxiv.org/pdf/2506.23282)][[code](https://github.com/Bbeholder/ADSM)]
   

2. [MA-PDM] **Video Anomaly Detection with Motion and Appearance Guided Patch Diffusion Model** <a id='MA-PDM'></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA)\
AAAI '25 [[paper](https://arxiv.org/pdf/2412.09026)][[code](https://github.com/henrryzh1/MA-PDM/)]

1. [SFN-VAD] **MemoryOut: Learning Principal Features via Multimodal Sparse Filtering Network for Semi-supervised Video Anomaly Detection** <a id='SFN-VAD'></a>&nbsp;&nbsp;&nbsp;![New](https://img.shields.io/badge/New⭐-417FFA)\
arXiv '25 [[paper](https://arxiv.org/pdf/2506.02535)][[project](https://qzfm.github.io/sfn_vad_project_page/)]

1. [LPGB] **Local Patterns Generalize Better for Novel Anomalies** \
ICLR '25 [[paper](https://openreview.net/pdf?id=4ua4wyAQLm)][[code](https://github.com/AllenYLJiang/Local-Patterns-Generalize-Better/)][[OpenReview](https://openreview.net/forum?id=4ua4wyAQLm)]

1. [LANP] **Learning Anomalies with Normality Prior for Unsupervised Video Anomaly Detection** <a id="LANP"></a> \
![ResNext](https://img.shields.io/badge/ResNext-05CC47)\
ECCV '24 [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/00941.pdf)] 

1. [Joint-VAD] **Interleaving One-Class and Weakly-Supervised Models with Adaptive Thresholding for Unsupervised Video Anomaly Detection** \
![I3D](https://img.shields.io/badge/I3D-35BF5C)\
ECCV '24 [[paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04450.pdf)][[code](https://github.com/benedictstar/Joint-VAD)]

1. [SSAE] **Scene-Dependent Prediction in Latent Space for Video Anomaly Detection and Anticipation** <a id="SSAE"></a> \
T-PAMI '24[[paper](https://ieeexplore.ieee.org/abstract/document/10681297/)][[project](https://campusvaa.github.io)][[code](https://github.com/zugexiaodui/campus_vad_code)][[dataset](https://drive.google.com/drive/folders/1_EztmkNpTPyVb4lM0m4rLTXgXo_LzgF1?usp=share_link)]

1. [DoTA] **DoTA: Unsupervised Detection of Traffic Anomaly in Driving Videos** \
T-PAMI '23 [[paper](https://ieeexplore.ieee.org/document/9712446/)][[code](https://github.com/MoonBlvd/Detection-of-Traffic-Anomaly)][[dataset](https://drive.google.com/drive/folders/1_WzhwZC2NIpzZIpX7YCvapq66rtBc67n)]

1. [AED-MAE] **Self-Distilled Masked Auto-Encoders are Efficient Video Anomaly Detectors** <a id="AED-MAE"></a> \
CVPR '24 [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Ristea_Self-Distilled_Masked_Auto-Encoders_are_Efficient_Video_Anomaly_Detectors_CVPR_2024_paper.pdf)][[code](https://github.com/ristea/aed-mae/tree/main)][[supp](https://openaccess.thecvf.com/content/CVPR2024/supplemental/Ristea_Self-Distilled_Masked_Auto-Encoders_CVPR_2024_supplemental.pdf)]

1. [MSTL] **Multi-Scale Video Anomaly Detection by Multi-Grained Spatio-Temporal  Representation Learning** <a id="Zhang-CVPR24"></a> \
![I3D](https://img.shields.io/badge/I3D-35BF5C) \
CVPR '24 [[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Multi-Scale_Video_Anomaly_Detection_by_Multi-Grained_Spatio-Temporal_Representation_Learning_CVPR_2024_paper.pdf)][[supp](https://openaccess.thecvf.com/content/CVPR2024/supplemental/Zhang_Multi-Scale_Video_Anomaly_CVPR_2024_supplemental.pdf)]

1. [MULDE] **MULDE: Multiscale Log-Density Estimation via Denoising Score Matchi