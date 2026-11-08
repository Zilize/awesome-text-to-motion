# awesome-text-to-motion

<a href='https://zilize.github.io/awesome-text-to-motion/'>
  <img src='https://img.shields.io/badge/Project-Page-%23df5b46?style=flat&logo=Google%20chrome&logoColor=%23df5b46'  alt="project_page"/></a> 
<a href='https://zilize.github.io/awesome-text-to-motion/'>
  <img src='https://img.shields.io/badge/Interactive-Charts-%2346a5df?style=flat&logo=plotly&logoColor=white' alt="interactive_charts"/></a>
<a href='https://github.com/Zilize/awesome-text-to-motion/actions/workflows/static.yml'>
  <img src='https://img.shields.io/github/actions/workflow/status/zilize/awesome-text-to-motion/static.yml'  alt="workflow"/></a> 
<a href="https://zhuanlan.zhihu.com/p/1940481020941043393">
  <img src="https://img.shields.io/badge/知乎-文章-%23f5f5f5?style=flat&logo=Zhihu&logoColor=%23188de0" alt="知乎文章"/>
</a>

Text-driven human motion generation surveys, datasets and models, focusing on single-person scenarios without human-object/scene interaction.
Please refer to the [project page](https://zilize.github.io/awesome-text-to-motion/) for a better browsing experience with interactive visualizations and statistical charts.

<details>
<summary><b>Contribution Guide</b> (Click to expand)</summary>

---

We welcome contributions to make this repository more comprehensive and up-to-date! 

### How to Contribute

1. **Fork this repository** to your GitHub account
2. **Create a new branch** for your contribution
3. **Add your papers** following the guidelines below
4. **Submit a Pull Request** with a clear description of your changes

### Adding Papers

#### For Papers with arXiv IDs:
- **File**: `data/arxiv.csv`
- **Format**: Add a new row with the following columns:
  - `arxiv_id`: The arXiv ID (e.g., "2507.05419")
  - `survey`: "1" if it's a survey paper, "0" otherwise
  - `survey_abbr`: Abbreviation for survey papers (e.g., "Survey2507")
  - `model`: "1" if it's a model paper, "0" otherwise
  - `model_abbr`: Abbreviation for model papers (e.g., "MotionGen")
  - `dataset`: "1" if it's a dataset paper, "0" otherwise
  - `dataset_abbr`: Abbreviation for dataset papers (e.g., "MotionX")
  - `submission`: Conference/journal name (e.g., "CVPR")
  - `submission_year`: Year of submission (e.g., "2025")
  - `page`: Project page URL (if available)
  - `repo`: GitHub repository URL (if available)
  - `backbone_tags`: Comma-separated backbone tags (e.g., "Transformer, Diffusion")
  - `approach_tags`: Comma-separated approach tags (e.g., "Physical, Editing")

#### For Papers without arXiv IDs:
- **File**: `data/without-arxiv.json`
- **Format**: Add a new JSON object with the following structure:
```json
{
    "arxiv_id": "random-key-for-your-interest",
    "title": "Paper Title",
    "abstract": "Paper abstract...",
    "authors": ["Author 1", "Author 2"],
    "year": 2025,
    "month": 7,
    "url": "https://paper-url.com",
    "survey": false,
    "survey_abbr": "",
    "model": true,
    "model_abbr": "ModelName",
    "dataset": false,
    "dataset_abbr": "",
    "submission": "Conference",
    "submission_year": "2025",
    "page": "https://project-page.com",
    "repo": "https://github.com/user_name/repo",
    "backbone_tags": "Transformer, Diffusion",
    "approach_tags": "Physical, Editing"
}
```

Thank you for contributing to the awesome-text-to-motion collection! 🚀

---

</details>

## Contents

- [Surveys](#surveys)
- [Datasets](#datasets)
- [Models](#models)

## Surveys

- "Motion Generation: A Survey of Generative Approaches and Benchmarks". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2507.05419)

- "Multimodal Generative AI with Autoregressive LLMs for Human Motion Understanding and Generation: A Way Forward". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.03191)

- "Text-driven Motion Generation: Overview, Challenges and Directions". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2505.09379)

- "Human Motion Generation: A Survey". `TPAMI(2023)` [[URL]](https://arxiv.org/abs/2307.10894)



## Datasets

- **UniMo4D**: "X-MoGen: Unified Motion Generation across Humans and Animals". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2508.05162)

- **FineMotion**: "FineMotion: A Dataset and Benchmark with both Spatial and Temporal Annotation for Fine-grained Motion Generation and Editing". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2507.19850) [[Code]](https://github.com/BizhuWu/FineMotion)

- **SnapMoGen**: "SnapMoGen: Human Motion Generation from Expressive Texts". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2507.09122) [[Project Page]](https://snap-research.github.io/SnapMoGen/) [[Code]](https://github.com/snap-research/SnapMoGen)

- **MotionMillion**: "Go to Zero: Towards Zero-shot Motion Generation with Million-scale Data". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2507.07095) [[Project Page]](https://vankouf.github.io/MotionMillion/) [[Code]](https://github.com/VankouF/MotionMillion-Codes)

- **HumanAttr**: "Generating Attribute-Aware Human Motions from Textual Prompt". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.21912)

- **GBC-100K**: "From Motion to Behavior: Hierarchical Modeling of Humanoid Generative Behavior Control". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.00043)

- **STANCE**: "Dynamic Motion Blending for Versatile Motion Editing". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.20724) [[Project Page]](https://awfuact.github.io/motionrefit/) [[Code]](https://github.com/emptybulebox1/motionRefit/)

- **PerMo**: "PersonaBooth: Personalized Text-to-Motion Generation". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.07390) [[Project Page]](https://boeun-kim.github.io/page-PersonaBooth/) [[Code]](https://github.com/Boeun-Kim/PersonaBooth)

- **TMD**: "Motion Anything: Any to Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.06955) [[Project Page]](https://steve-zeyu-zhang.github.io/MotionAnything/)

- **Motion-X++**: "Motion-X++: A Large-Scale Multimodal 3D Whole-body Human Motion Dataset". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2501.05098)

- **MotionFix**: "MotionFix: Text-Driven 3D Human Motion Editing". `SIGGRAPH Asia(2024)` [[URL]](https://arxiv.org/abs/2408.00712) [[Project Page]](https://motionfix.is.tue.mpg.de/) [[Code]](https://github.com/atnikos/motionfix)

- **HumanML3D-Extend**: "Infinite Motion: Extended Motion Generation via Long Text Instructions". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2407.08443) [[Project Page]](https://shuochengzhai.github.io/Infinite-motion.github.io/)

- **MotionPercept**: "Aligning Human Motion Generation with Human Perceptions". `ICLR(2025)` [[URL]](https://arxiv.org/abs/2407.02272) [[Project Page]](https://motioncritic.github.io/) [[Code]](https://github.com/ou524u/MotionCritic)

- **PaM**: "MoDiPO: text-to-motion alignment via AI-feedback-driven Direct Preference Optimization". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2405.03803)

- **HumanML3D++**: "You Think, You ACT: The New Task of Arbitrary Text to Motion Generation". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2404.14745)

- **MotionVerse**: "Large Motion Model for Unified Multi-Modal Motion Generation". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2404.01284) [[Project Page]](https://mingyuan-zhang.github.io/projects/LMM.html) [[Code]](https://github.com/mingyuan-zhang/LMM)

- **RICH-CAT**: "Contact-aware Human Motion Generation from Textual Descriptions". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2403.15709) [[Project Page]](https://xymsh.github.io/RICH-CAT/)

- **FineHumanML3D**: "Motion Generation from Fine-grained Textual Descriptions". `LREC-COLING(2024)` [[URL]](https://arxiv.org/abs/2403.13518) [[Code]](https://github.com/KunhangL/finemotiondiffuse)

- **BlindWays**: "Text to Blind Motion". `NeurIPS(2024)` [[URL]](https://arxiv.org/abs/2412.05277) [[Project Page]](https://blindways.github.io/)

- **LaViMo**: "Text Motion Translator: A Bi-Directional Model for Enhanced 3D Human Motion Generation from Open-Vocabulary Descriptions". `ECCV(2024)` [[URL]](https://eccv.ecva.net/virtual/2024/poster/266)

- **Inter-MT2**: "A Unified Framework for Motion Reasoning and Generation in Human Interaction". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2410.05628) [[Project Page]](https://vim-motion-language.github.io/)

- **MotionLib**: "Scaling Large Motion Models with Million-Level Human Motions". `ICML(2025)` [[URL]](https://arxiv.org/abs/2410.03311) [[Project Page]](https://beingbeyond.github.io/Being-M0/) [[Code]](https://github.com/BeingBeyond/Being-M0)

- **HumanML3D-synthesis**: "CLaM: An Open-Source Library for Performance Evaluation of Text-driven Human Motion Generation". `MM(24)` [[URL]](https://dl.acm.org/doi/10.1145/3664647.3685523) [[Code]](https://github.com/SheldongChen/CLaM/)

- **Limb-ET2M**: "Towards Emotion-enriched Text-to-Motion Generation via LLM-guided Limb-level Emotion Manipulating
". `MM(2024)` [[URL]](https://dl.acm.org/doi/10.1145/3664647.3681487) [[Code]](https://github.com/aekx/L3EM)

- **Motion-X**: "Motion-X: A Large-scale 3D Expressive Whole-body Human Motion Dataset". `NeurIPS(2023)` [[URL]](https://arxiv.org/abs/2307.00818) [[Project Page]](https://motion-x-dataset.github.io/) [[Code]](https://github.com/IDEA-Research/Motion-X)

- **HumanLong3D**: "AMD: Autoregressive Motion Diffusion". `AAAI(2024)` [[URL]](https://arxiv.org/abs/2305.09381) [[Code]](https://github.com/fluide1022/AMD)

- **HuMMan-MoGen**: "FineMoGen: Fine-Grained Spatio-Temporal Motion Generation and Editing". `NeurIPS(2023)` [[URL]](https://arxiv.org/abs/2312.15004) [[Project Page]](https://mingyuan-zhang.github.io/projects/FineMoGen.html) [[Code]](https://github.com/mingyuan-zhang/FineMoGen)

- **HumanML3D**: "Generating Diverse and Natural 3D Human Motions from Text". `CVPR(2022)` [[URL]](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_Generating_Diverse_and_Natural_3D_Human_Motions_From_Text_CVPR_2022_paper.pdf) [[Project Page]](https://ericguo5513.github.io/text-to-motion/) [[Code]](https://github.com/EricGuo5513/text-to-motion)

- **KIT**: "The KIT Motion-Language Dataset". `Big Data(2016)` [[URL]](https://arxiv.org/abs/1607.03827) [[Project Page]](https://motion-annotation.humanoids.kit.edu/dataset/)



## Models
- **TIMotion**: "Temporal and Interactive Framework for Efficient Human-Human Motion Generation". `CVPR(2025)` [[URL]](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_TIMotion_Temporal_and_Interactive_Framework_for_Efficient_Human-Human_Motion_Generation_CVPR_2025_paper.pdf) [[Project Page]](https://aigc-explorer.github.io/TIMotion-page/)

- **X-MoGen**: "X-MoGen: Unified Motion Generation across Humans and Animals". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2508.05162)

- **ReMoMask**: "ReMoMask: Retrieval-Augmented Masked Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2508.02605) [[Project Page]](https://aigeeksgroup.github.io/ReMoMask/) [[Code]](https://github.com/AIGeeksGroup/ReMoMask)

- **SASI**: "Semantically Consistent Text-to-Motion with Unsupervised Styles". `SIGGRAPH(2025)` [[URL]](https://dl.acm.org/doi/10.1145/3721238.3730641) [[Project Page]](https://fivezerojun.github.io/stylization.github.io/)

- **MoMask++**: "SnapMoGen: Human Motion Generation from Expressive Texts". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2507.09122) [[Project Page]](https://snap-research.github.io/SnapMoGen/) [[Code]](https://github.com/snap-research/SnapMoGen)

- **GotoZero**: "Go to Zero: Towards Zero-shot Motion Generation with Million-scale Data". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2507.07095) [[Project Page]](https://vankouf.github.io/MotionMillion/) [[Code]](https://github.com/VankouF/MotionMillion-Codes)

- **MOST**: "MOST: Motion Diffusion Model for Rare Text via Temporal Clip Banzhaf Interaction". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2507.06590)

- **MotionGPT3**: "MotionGPT3: Human Motion as a Second Modality". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.24086) [[Project Page]](https://motiongpt3.github.io/) [[Code]](https://github.com/OpenMotionLab/MotionGPT3)

- **AttrMoGen**: "Generating Attribute-Aware Human Motions from Textual Prompt". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.21912)

- **Motion-R1**: "Motion-R1: Chain-of-Thought Reasoning and Reinforcement Learning for Human Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.10353) [[Project Page]](https://motion-r1.github.io/) [[Code]](https://github.com/GigaAI-Research/Motion-R1)

- **MOGO**: "MOGO: Residual Quantized Hierarchical Causal Transformer for High-Quality and Real-Time 3D Human Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.05952)

- **ANT**: "ANT: Adaptive Neural Temporal-Aware Text-to-Motion Model". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.02452) [[Code]](https://github.com/CCSCovenant/ANT)

- **PHYLOMAN**: "From Motion to Behavior: Hierarchical Modeling of Humanoid Generative Behavior Control". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2506.00043)

- **ACMDM**: "Absolute Coordinates Make Motion Generation Easy". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2505.19377) [[Project Page]](https://neu-vi.github.io/ACMDM/) [[Code]](https://github.com/neu-vi/ACMDM)

- **MoMADiff**: "Towards Robust and Controllable Text-to-Motion via Masked Autoregressive Diffusion". `MM(2025)` [[URL]](https://arxiv.org/abs/2505.11013) [[Code]](https://github.com/zzysteve/MoMADiff)

- **ReAlign**: "ReAlign: Bilingual Text-to-Motion Generation via Step-Aware Reward-Guided Alignment". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2505.04974) [[Project Page]](https://wengwanjiang.github.io/ReAlign-page/)

- **GENMO**: "GENMO: A GENeralist Model for Human MOtion". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2505.01425) [[Project Page]](https://research.nvidia.com/labs/dair/genmo/)

- **DSDFM**: "Deterministic-to-Stochastic Diverse Latent Feature Mapping for Human Motion Synthesis". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2505.00998)

- **UniPhys**: "UniPhys: Unified Planner and Controller with Diffusion for Flexible Physics-Based Character Control". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2504.12540) [[Project Page]](https://wuyan01.github.io/uniphys-project/)

- **Shape-Move**: "Shape My Moves: Text-Driven Shape-Aware Synthesis of Human Motions". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2504.03639) [[Project Page]](https://shape-move.github.io/) [[Code]](https://github.com/shape-move/shape-move-public)

- **MG-MotionLLM**: "MG-MotionLLM: A Unified Framework for Motion Comprehension and Generation across Multiple Granularities". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2504.02478) [[Code]](https://github.com/CVI-SZU/MG-MotionLLM)

- **FlowMotion**: "FlowMotion: Target-Predictive Conditional Flow Matching for Jitter-Reduced Text-Driven Human Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2504.01338)

- **MixerMDM**: "MixerMDM: Learnable Composition of Human Motion Diffusion Models". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2504.01019) [[Project Page]](https://pabloruizponce.com/papers/MixerMDM) [[Code]](https://github.com/pabloruizponce/MixerMDM)

- **ReMoGPT**: "ReMoGPT: Part-Level Retrieval-Augmented Motion-Language Models". `AAAI(2025)` [[URL]](https://ojs.aaai.org/index.php/AAAI/article/view/33044)

- **UniTMGE**: "UniTMGE: Uniform Text-Motion Generation and Editing Model via Diffusion". `WACV(2025)` [[URL]](https://ieeexplore.ieee.org/document/10943808)

- **MotionReFit**: "Dynamic Motion Blending for Versatile Motion Editing". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.20724) [[Project Page]](https://awfuact.github.io/motionrefit/) [[Code]](https://github.com/emptybulebox1/motionRefit/)

- **LoRA-MDM**: "Dance Like a Chicken: Low-Rank Stylization for Human Motion Diffusion". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.19557) [[Project Page]](https://haimsaw.github.io/LoRA-MDM/) [[Code]](https://github.com/haimsaw/LoRA-MDM)

- **HMU**: "Human Motion Unlearning". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.18674) [[Project Page]](https://www.pinlab.org/hmu) [[Code]](https://github.com/edodema/human-motion-unlearning)

- **SimMotionEdit**: "SimMotionEdit: Text-Based Human Motion Editing with Motion Similarity Prediction". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.18211) [[Project Page]](https://ideas.cs.purdue.edu/research/projects/sim-motion-edit/) [[Code]](https://github.com/lzhyu/SimMotionEdit)

- **MotionStreamer**: "MotionStreamer: Streaming Motion Generation via Diffusion-based Autoregressive Model in Causal Latent Space". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2503.15451) [[Project Page]](https://zju3dv.github.io/MotionStreamer/) [[Code]](https://github.com/zju3dv/MotionStreamer/)

- **GenM3**: "GenM$^3$: Generative Pretrained Multi-path Motion Model for Text Conditional Human Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.14919)

- **Kinesis**: "Reinforcement learning-based motion imitation for physiologically plausible musculoskeletal motor control". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.14637) [[Code]](https://github.com/amathislab/Kinesis)

- **sMDM**: "Less is More: Improving Motion Diffusion Models with Sparse Keyframes". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.13859)

- **SALAD**: "SALAD: Skeleton-aware Latent Diffusion for Text-driven Motion Generation and Editing". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.13836) [[Project Page]](https://seokhyeonhong.github.io/projects/salad/) [[Code]](https://github.com/seokhyeonhong/salad)

- **PMG**: "Progressive Human Motion Generation Based on Text and Few Motion Frames". `TCSVT(2025)` [[URL]](https://arxiv.org/abs/2503.13300) [[Code]](https://github.com/qinghuannn/PMG)

- **PersonaBooth**: "PersonaBooth: Personalized Text-to-Motion Generation". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2503.07390) [[Project Page]](https://boeun-kim.github.io/page-PersonaBooth/) [[Code]](https://github.com/Boeun-Kim/PersonaBooth)

- **MotionAnything**: "Motion Anything: Any to Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.06955) [[Project Page]](https://steve-zeyu-zhang.github.io/MotionAnything/)

- **BioVAE**: "Biomechanics-Guided Residual Approach to Generalizable Human Motion Generation and Estimation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.06151)

- **MoMug**: "Unlocking Pretrained LLMs for Motion-Related Multimodal Generation: A Fine-Tuning Approach to Unify Diffusion and Next-Token Prediction". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2503.06119)

- **Fg-T2M++**: "Fg-T2M++: LLMs-Augmented Fine-Grained Text Driven Human Motion Generation". `IJCV(2025)` [[URL]](https://arxiv.org/abs/2502.05534)

- **MotionLab**: "MotionLab: Unified Human Motion Generation and Editing via the Motion-Condition-Motion Paradigm". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2502.02358) [[Project Page]](https://diouo.github.io/motionlab.github.io/) [[Code]](https://github.com/Diouo/MotionLab)

- **CASIM**: "CASIM: Composite Aware Semantic Injection for Text to Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2502.02063) [[Project Page]](https://cjerry1243.github.io/casim_t2m/) [[Code]](https://github.com/cjerry1243/casim_t2m)

- **SPORT**: "SPORT: From Zero-shot Prompts to Real-time Motion Generation". `TVCG(2025)` [[URL]](https://ieeexplore.ieee.org/document/10891181/)

- **MotionPCM**: "MotionPCM: Real-Time Motion Synthesis with Phased Consistency Model". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2501.19083)

- **Free-T2M**: "Free-T2M: Frequency Enhanced Text-to-Motion Diffusion Model With Consistency Loss". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2501.18232)

- **FlexMotion**: "FlexMotion: Lightweight, Physics-Aware, and Controllable Human Motion Generation". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2501.16778) [[Project Page]](https://openreview.net/forum?id=7652tHbbVE)

- **PackDiT**: "PackDiT: Joint Human Motion and Text Generation via Mutual Prompting". `arXiv(2025)` [[URL]](https://arxiv.org/abs/2501.16551)

- **MMDM**: "Text-driven Human Motion Generation with Motion Masked Diffusion Model". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2409.19686)

- **EgoLM**: "EgoLM: Multi-Modal Language Model of Egocentric Motions". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2409.18127) [[Project Page]](https://hongfz16.github.io/projects/EgoLM)

- **MoGenTS**: "MoGenTS: Motion Generation based on Spatial-Temporal Joint Modeling". `NeurIPS(2024)` [[URL]](https://arxiv.org/abs/2409.17686) [[Project Page]](https://aigc3d.github.io/mogents/) [[Code]](https://github.com/weihaosky/mogents)

- **UniMotion**: "Unimotion: Unifying 3D Human Motion Synthesis and Understanding". `3DV(2025)` [[URL]](https://arxiv.org/abs/2409.15904) [[Project Page]](https://coral79.github.io/uni-motion/) [[Code]](https://github.com/Coral79/Unimotion)

- **MaskedMimic**: "MaskedMimic: Unified Physics-Based Character Control Through Masked Motion Inpainting". `SIGGRAPH Asia(2024)` [[URL]](https://arxiv.org/abs/2409.14393) [[Project Page]](https://xbpeng.github.io/projects/MaskedMimic/index.html) [[Code]](https://github.com/NVlabs/ProtoMotions)

- **T2M-X**: "T2M-X: Learning Expressive Text-to-Motion Generation from Partially Annotated Data". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2409.13251)

- **MoRAG**: "MoRAG -- Multi-Fusion Retrieval Augmented Generation for Human Motion". `WACV(2025)` [[URL]](https://arxiv.org/abs/2409.12140) [[Project Page]](https://motion-rag.github.io/) [[Code]](https://github.com/Motion-RAG/MoRAG)

- **BAD**: "BAD: Bidirectional Auto-regressive Diffusion for Text-to-Motion Generation". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2409.10847) [[Project Page]](https://rohollahhs.github.io/BAD-page/) [[Code]](https://github.com/rohollahhs/bad/)

- **LaMoG**: "Lagrangian Motion Fields for Long-term Motion Generation". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2409.01522) [[Project Page]](https://plyfager.github.io/LaMoG/)

- **TextIM**: "TextIM: Part-aware Interactive Motion Synthesis from Text". `EUROGRAPHICS(2025)` [[URL]](https://arxiv.org/abs/2408.03302)

- **TMED**: "MotionFix: Text-Driven 3D Human Motion Editing". `SIGGRAPH Asia(2024)` [[URL]](https://arxiv.org/abs/2408.00712) [[Project Page]](https://motionfix.is.tue.mpg.de/) [[Code]](https://github.com/atnikos/motionfix)

- **ALERT-Motion**: "Autonomous LLM-Enhanced Adversarial Attack for Text-to-Motion". `AAAI(2025)` [[URL]](https://arxiv.org/abs/2408.00352)

- **MotionCraft**: "MotionCraft: Crafting Whole-Body Motion with Plug-and-Play Multimodal Controls". `AAAI(2025)` [[URL]](https://arxiv.org/abs/2407.21136) [[Project Page]](https://cure-lab.github.io/MotionCraft/) [[Code]](https://github.com/cure-lab/MotionCraft)

- **M2D2M**: "M2D2M: Multi-Motion Generation from Text with Discrete Diffusion Models". `ECCV(2024)` [[URL]](https://arxiv.org/abs/2407.14502)

- **SMooDi**: "SMooDi: Stylized Motion Diffusion Model". `ECCV(2024)` [[URL]](https://arxiv.org/abs/2407.12783) [[Project Page]](https://neu-vi.github.io/SMooDi/) [[Code]](https://github.com/neu-vi/SMooDi)

- **GuidedMotion**: "Local Action-Guided Motion Diffusion Model for Text-to-Motion Generation". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2407.10528) [[Project Page]](https://jpthu17.github.io/GuidedMotion-project/)

- **SuperPADL**: "SuperPADL: Scaling Language-Directed Physics-Based Control with Progressive Supervised Distillation". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2407.10481)

- **InfiniMotion**: "InfiniMotion: Mamba Boosts Memory in Transformer for Arbitrary Long Motion Generation". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2407.10061)

- **InfiniteMotion**: "Infinite Motion: Extended Motion Generation via Long Text Instructions". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2407.08443) [[Project Page]](https://shuochengzhai.github.io/Infinite-motion.github.io/)

- **MotionGPT**: "MotionGPT: Human Motion Synthesis with Improved Diversity and Realism via GPT-3 Prompting". `WACV(2024)` [[URL]](https://ieeexplore.ieee.org/document/10484383) [[Code]](https://github.com/humansensinglab/MotionGPT)

- **MoLA**: "MoLA: Motion Generation and Editing with Latent Diffusion Enhanced by Adversarial Training". `CVPR Workshop(2025)` [[URL]](https://arxiv.org/abs/2406.01867) [[Project Page]](https://kengouchida-sony.github.io/MoLA-demo/) [[Code]](https://github.com/sony/MoLA)

- **T2LM**: "T2LM: Long-Term 3D Human Motion Generation from Multiple Sentences". `CVPR Workshop(2024)` [[URL]](https://arxiv.org/abs/2406.00636)

- **ProgMoGen**: "Programmable Motion Generation for Open-Set Motion Control Tasks". `CVPR(2024)` [[URL]](https://arxiv.org/abs/2405.19283) [[Project Page]](https://hanchaoliu.github.io/Prog-MoGen/) [[Code]](https://github.com/HanchaoLiu/ProgMoGen)

- **Motion-Agent**: "Motion-Agent: A Conversational Framework for Human Motion Generation with LLMs". `ICLR(2025)` [[URL]](https://arxiv.org/abs/2405.17013) [[Project Page]](https://knoxzhao.github.io/Motion-Agent/) [[Code]](https://github.com/szqwu/Motion-Agent)

- **TMR++**: "A Cross-Dataset Study for Text-based 3D Human Motion Retrieval". `CVPR Workshop(2024)` [[URL]](https://arxiv.org/abs/2405.16909) [[Project Page]](https://imagine.enpc.fr/~leore.bensabath/TMR++/) [[Code]](https://github.com/leorebensabath/TMRPlusPlus)

- **M3GPT**: "M$^3$GPT: An Advanced Multimodal, Multitask Framework for Motion Comprehension and Generation". `NeurIPS(2024)` [[URL]](https://arxiv.org/abs/2405.16273) [[Project Page]](https://luomingshuang.github.io/M3GPT/) [[Code]](https://github.com/luomingshuang/M3GPT)

- **InstructMotion**: "Learning Generalizable Human Motion Generator with Reinforcement Learning". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2405.15541)

- **SMD**: "Shape Conditioned Human Motion Generation with Diffusion Model". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2405.06778)

- **StableMoFusion**: "StableMoFusion: Towards Robust and Efficient Diffusion-based Motion Generation Framework". `MM(2024)` [[URL]](https://arxiv.org/abs/2405.05691) [[Project Page]](https://h-y1heng.github.io/StableMoFusion-page/) [[Code]](https://github.com/Linketic/StableMoFusion)

- **MotionPatches**: "Exploring Vision Transformers for 3D Human Motion-Language Models with Motion Patches". `CVPR(2024)` [[URL]](https://arxiv.org/abs/2405.04771) [[Project Page]](https://yu1ut.com/MotionPatches-HP/) [[Code]](https://github.com/line/MotionPatches)

- **MoDiPO**: "MoDiPO: text-to-motion alignment via AI-feedback-driven Direct Preference Optimization". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2405.03803)

- **LGTM**: "LGTM: Local-to-Global Text-Driven Human Motion Diffusion Model". `SIGGRAPH(2024)` [[URL]](https://arxiv.org/abs/2405.03485) [[Code]](https://github.com/L-Sun/LGTM)

- **MLCT**: "Efficient Text-driven Motion Generation via Latent Consistency Training". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2405.02791)

- **SATO**: "SATO: Stable Text-to-Motion Framework". `MM(2024)` [[URL]](https://arxiv.org/abs/2405.01461) [[Project Page]](https://sato-team.github.io/Stable-Text-to-Motion-Framework/) [[Code]](https://github.com/sato-team/Stable-Text-to-Motion-Framework)

- **MotionLCM**: "MotionLCM: Real-time Controllable Motion Generation via Latent Consistency Model". `ECCV(2024)` [[URL]](https://arxiv.org/abs/2404.19759) [[Project Page]](https://dai-wenxun.github.io/MotionLCM-page/) [[Code]](https://github.com/Dai-Wenxun/MotionLCM)

- **TAAT**: "You Think, You ACT: The New Task of Arbitrary Text to Motion Generation". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2404.14745)

- **MCM**: "MCM: Multi-condition Motion Synthesis Framework". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2404.12886)

- **InstructMotion**: "Exploring Text-to-Motion Generation with Human Preference". `CVPR Workshop(2024)` [[URL]](https://arxiv.org/abs/2404.09445) [[Code]](https://github.com/THU-LYJ-Lab/InstructMotion)

- **MotionChain**: "MotionChain: Conversational Motion Controllers via Multimodal Prompts". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2404.01700)

- **LMM**: "Large Motion Model for Unified Multi-Modal Motion Generation". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2404.01284) [[Project Page]](https://mingyuan-zhang.github.io/projects/LMM.html) [[Code]](https://github.com/mingyuan-zhang/LMM)

- **BAMM**: "BAMM: Bidirectional Autoregressive Motion Model". `ECCV(2024)` [[URL]](https://arxiv.org/abs/2403.19435) [[Project Page]](https://www.ekkasit.com/BAMM-page/) [[Code]](https://github.com/exitudio/BAMM/)

- **ParCo**: "ParCo: Part-Coordinating Text-to-Motion Synthesis". `ECCV(2024)` [[URL]](https://arxiv.org/abs/2403.18512) [[Code]](https://github.com/qrzou/ParCo)

- **CATMO**: "Contact-aware Human Motion Generation from Textual Descriptions". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2403.15709) [[Project Page]](https://xymsh.github.io/RICH-CAT/)

- **CoMo**: "CoMo: Controllable Motion Generation through Language Guided Pose Code Editing". `ECCV(2024)` [[URL]](https://arxiv.org/abs/2403.13900) [[Project Page]](https://yh2371.github.io/como/) [[Code]](https://github.com/yh2371/CoMo)

- **AnySkill**: "AnySkill: Learning Open-Vocabulary Physical Skill for Interactive Agents". `CVPR(2024)` [[URL]](https://arxiv.org/abs/2403.12835) [[Project Page]](https://anyskill.github.io/) [[Code]](https://github.com/jiemingcui/anyskill)

- **MotionMamba**: "Motion Mamba: Efficient and Long Sequence Motion Generation". `ECCV(2024)` [[URL]](https://arxiv.org/abs/2403.07487) [[Project Page]](https://steve-zeyu-zhang.github.io/MotionMamba/)

- **MMoFusion**: "MMoFusion: Multi-modal Co-Speech Motion Generation with Diffusion Model". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2403.02905) [[Project Page]](https://mmofusion.github.io/) [[Code]](https://github.com/wangsen99/MMoFusion)

- **FlowMDM**: "Seamless Human Motion Composition with Blended Positional Encodings". `CVPR(2024)` [[URL]](https://arxiv.org/abs/2402.15509) [[Project Page]](https://barquerogerman.github.io/FlowMDM/) [[Code]](https://github.com/BarqueroGerman/FlowMDM)

- **LS-GAN**: "LS-GAN: Human Motion Synthesis with Latent-space GANs". `WACV(2025)` [[URL]](https://arxiv.org/abs/2501.01449) [[Code]](https://github.com/AmballaAvinash/motion-latent-diffusion)

- **EnergyMoGen**: "EnergyMoGen: Compositional Human Motion Generation with Energy-Based Diffusion Model in Latent Space". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2412.14706) [[Project Page]](https://jiro-zhang.github.io/EnergyMoGen/)

- **ScaMo**: "ScaMo: Exploring the Scaling Law in Autoregressive Motion Generation Model". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2412.14559) [[Project Page]](https://shunlinlu.github.io/ScaMo/) [[Code]](https://github.com/shunlinlu/ScaMo_code)

- **Light-T2M**: "Light-T2M: A Lightweight and Fast Model for Text-to-motion Generation". `AAAI(2025)` [[URL]](https://arxiv.org/abs/2412.11193) [[Code]](https://github.com/qinghuannn/light-t2m)

- **LoM**: "The Language of Motion: Unifying Verbal and Non-verbal Language of 3D Human Motion". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2412.10523) [[Project Page]](https://languageofmotion.github.io/) [[Code]](https://github.com/Juzezhang/language_of_motion)

- **CoMA**: "CoMA: Compositional Human Motion Generation with Multi-modal Agents". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2412.07320) [[Project Page]](https://gabrie-l.github.io/coma-page/) [[Code]](https://github.com/Siwensun/CoMA)

- **SoPo**: "SoPo: Text-to-Motion Generation Using Semi-Online Preference Optimization". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2412.05095) [[Project Page]](https://xiaofeng-tan.github.io/projects/SoPo/) [[Code]](https://github.com/Xiaofeng-Tan/SoPO)

- **RMD**: "RMD: A Simple Baseline for More General Human Motion Generation via Training-free Retrieval-Augmented Motion Diffuse". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2412.04343)

- **BiPO**: "BiPO: Bidirectional Partial Occlusion Network for Text-to-Motion Synthesis". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2412.00112)

- **MoTE**: "MoTe: Learning Motion-Text Diffusion Model for Multiple Generation Tasks". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2411.19786)

- **FTMoMamba**: "FTMoMamba: Motion Generation with Frequency and Text State Space Models". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2411.17532)

- **VersatileMotion**: "VersatileMotion: A Unified Framework for Motion Synthesis and Comprehension". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2411.17335)

- **MARDM**: "Rethinking Diffusion for Text-Driven Human Motion Generation: Redundant Representations, Evaluation, and Masked Autoregression". `CVPR(2025)` [[URL]](https://arxiv.org/abs/2411.16575) [[Project Page]](https://neu-vi.github.io/MARDM/) [[Code]](https://github.com/neu-vi/MARDM)

- **Morph**: "Morph: A Motion-free Physics Optimization Framework for Human Motion Generation". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2411.14951)

- **KMM**: "KMM: Key Frame Mask Mamba for Extended Motion Generation". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2411.06481) [[Project Page]](https://steve-zeyu-zhang.github.io/KMM/)

- **TMT**: "Text Motion Translator: A Bi-Directional Model for Enhanced 3D Human Motion Generation from Open-Vocabulary Descriptions". `ECCV(2024)` [[URL]](https://eccv.ecva.net/virtual/2024/poster/266)

- **M-Adaptor**: "M-Adaptor: Text-driven Whole-body Human Motion Generation". `CVPR Workshop(2025)` [[URL]](https://openaccess.thecvf.com/content/CVPR2025W/PVUW/html/Li_M-Adaptor_Text-driven_Whole-body_Human_Motion_Generation_CVPRW_2025_paper.html)

- **MotionGPT-2**: "MotionGPT-2: A General-Purpose Motion-Language Model for Motion Generation and Understanding". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2410.21747)

- **MotionCLR**: "Pay Attention and Move Better: Harnessing Attention for Interactive Motion Generation and Training-free Editing". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2410.18977) [[Project Page]](https://lhchen.top/MotionCLR/)

- **LEAD**: "LEAD: Latent Realignment for Human Motion Diffusion". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2410.14508)

- **MaskControl**: "MaskControl: Spatio-Temporal Control for Masked Motion Synthesis". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2410.10780) [[Project Page]](https://www.ekkasit.com/ControlMM-page/) [[Code]](https://github.com/exitudio/MaskControl/)

- **ReinDiffuse**: "ReinDiffuse: Crafting Physically Plausible Motions with Reinforced Diffusion Model". `WACV(2025)` [[URL]](https://arxiv.org/abs/2410.07296) [[Project Page]](https://reindiffuse.github.io/)

- **LaMP**: "LaMP: Language-Motion Pretraining for Motion Generation, Retrieval, and Captioning". `ICLR(2025)` [[URL]](https://arxiv.org/abs/2410.07093) [[Project Page]](https://aigc3d.github.io/LaMP/) [[Code]](https://github.com/gentlefress/LaMP)

- **MotionRL**: "MotionRL: Align Text-to-Motion Generation to Human Preferences with Multi-Reward Reinforcement Learning". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2410.06513)

- **VIM**: "A Unified Framework for Motion Reasoning and Generation in Human Interaction". `ICCV(2025)` [[URL]](https://arxiv.org/abs/2410.05628) [[Project Page]](https://vim-motion-language.github.io/)

- **DART**: "DartControl: A Diffusion-Based Autoregressive Motion Model for Real-Time Text-Driven Motion Control". `ICLR(2025)` [[URL]](https://arxiv.org/abs/2410.05260) [[Project Page]](https://zkf1997.github.io/DART/) [[Code]](https://github.com/zkf1997/DART)

- **UniMuMo**: "UniMuMo: Unified Text, Music and Motion Generation". `arXiv(2024)` [[URL]](https://arxiv.org/abs/2410.04534) [[Project Page]](https://hanyangclarence.github.io/unimumo_demo/) [[Code]](https://github.com/hanyangclarence/UniMuMo)

- **Being-M0**: "Scaling Large Motion Models with Million-Level Human Motions". `ICML(2025)` [[URL]](https://arxiv.org/abs/2410.03311) [[Project Page]](https://beingbeyond.github.io/Being-M0/) [[Code]](https://github.com/BeingBeyond/Being-M0)

- **CLaM**: "CLaM: An Open-Source Library for Performance Evaluation of Text-driven Human Motion Generation". `MM(24)` [[URL]](https://dl.acm.org/doi/10.1145/3664647.3685523) [[Code]](https://github.com/SheldongChen/CLaM/)

- **L3EM**: "Towards Emotion-enriched Text-to-Motion Generation via LLM-guided Limb-level Emotion Manipulating
". `MM(2024)` [[URL]](https://dl.acm.org/doi/10.1145/3664647.3681487) [[Code]](https://github.com/aekx/L3EM)

- **MotionMix**: "MotionMix: Weakly-Supervised Diffusion for Controllable Motion Generation". `AAAI(2024)` [[URL]](https://arxiv.org/abs/2401.11115) [[Project Page]](https://nhathoang2002.github.io/MotionMix-page/) [[Code]](https://github.com/NhatHoang2002/MotionMix)

- **STMC**: "Multi-Track Timeline Control for Text-Driven 3D Human Motion Generation". `CVPR Workshop(2024)` [[URL]](https://arxiv.org/abs/2401.08559) [[Project Page]](https://mathis.petrovich.fr/stmc/) [[Code]](https://github.com/nv-tlabs/stmc)

- **GUESS**: "GUESS:GradUally Enriching SyntheSis for Text-Driven Human Motion Generation". `TVCG(2024)` [[URL]](https://arxiv.org/abs/2401.02142) [[Code]](https://github.com/Xuehao-Gao/GUESS)

- **Fg-T2M**: "Fg-T2M: Fine-Grained Text-Driven Human Motion Generation via Diffusion Model". `ICCV(2023)` [[URL]](https://arxiv.org/abs/2309.06284)

- **AttT2M**: "AttT2M: Text-Driven Human Motion Generation with Multi-Perspective Attention Mechanism". `ICCV(2023)` [[URL]](https://arxiv.org/abs/2309.00796) [[Code]](https://github.com/ZcyMonkey/AttT2M)

- **M2DM**: "Priority-Centric Human Motion Generation in Discrete Latent Space". `ICCV(2023)` [[URL]](https://arxiv.org/abs/2308.14480)

- **ATOM**: "Language-guided Human Motion Synthesis with Atomic Actions". `MM(2023)` [[URL]](https://arxiv.org/abs/2308.09611) [[Code]](https://github.com/yhZhai/ATOM)

- **MotionGPT**: "MotionGPT: Human Motion as a Foreign Language". `NeurIPS(2023)` [[URL]](https://arxiv.org/abs/2306.14795) [[Project Page]](https://motion-gpt.github.io/) [[Code]](https://github.com/OpenMotionLab/MotionGPT)

- **MotionGPT**: "MotionGPT: Finetuned LLMs Are General-Purpose Motion Generators". `AAAI(2024)` [[URL]](https://arxiv.org/abs/2306.10900) [[Project Page]](https://qiqiapink.github.io/MotionGPT/) [[Code]](https://github.com/qiqiApink/MotionGPT)

- **DiffKFC**: "Enhanced Fine-grained Motion Diffusion for Text-driven Human Motion Synthesis". `AAAI(2024)` [[URL]](https://arxiv.org/abs/2305.13773)

- **GMD**: "Guided Motion Diffusion for Controllable Human Motion Synthesis". `ICCV(2023)` [[URL]](https://arxiv.org/abs/2305.12577) [[Project Page]](https://korrawe.github.io/gmd-project/) [[Code]](https://github.com/korrawe/guided-motion-diffusion)

- **MAA**: "Make-An-Animation: Large-Scale Text-conditional 3D Human Motion Generation". `ICCV(2023)` [[URL]](https://arxiv.org/abs/2305.09662) [[Project Page]](https://azadis.github.io/make-an-animation/)

- **AMD**: "AMD: Autoregressive Motion Diffusion". `AAAI(2024)` [[URL]](https://arxiv.org/abs/2305.09381) [[Code]](https://github.com/fluide1022/AMD)

- **TMR**: "TMR: Text-to-Motion Retrieval Using Contrastive 3D Human Motion Synthesis". `ICCV(2023)` [[URL]](https://arxiv.org/abs/2305.00976) [[Project Page]](https://mathis.petrovich.fr/tmr/) [[Code]](https://github.com/Mathux/TMR)

- **TM2D**: "TM2D: Bimodality Driven 3D Dance Generation via Music-Text Integration". `ICCV(2023)` [[URL]](https://arxiv.org/abs/2304.02419) [[Project Page]](https://garfield-kh.github.io/TM2D/) [[Code]](https://github.com/Garfield-kh/TM2D)

- **ReMoDiffuse**: "ReMoDiffuse: Retrieval-Augmented Motion Diffusion Model". `ICCV(2023)` [[URL]](https://arxiv.org/abs/2304.01116) [[Project Page]](https://mingyuan-zhang.github.io/projects/ReMoDiffuse.html) [[Code]](https://github.com/mingyuan-zhang/ReMoDiffuse)

- **priorMDM**: "Human Motion Diffusion as a Generative Prior". `ICLR(2024)` [[URL]](https://arxiv.org/abs/2303.01418) [[Project Page]](https://priormdm.github.io/priorMDM-page/) [[Code]](https://github.com/priorMDM/priorMDM)

- **InsActor**: "InsActor: Instruction-driven Physics-based Characters". `NeurIPS(2023)` [[URL]](https://arxiv.org/abs/2312.17135) [[Project Page]](https://jiawei-ren.github.io/projects/insactor/) [[Code]](https://github.com/jiawei-ren/insactor)

- **FineMoGen**: "FineMoGen: Fine-Grained Spatio-Temporal Motion Generation and Editing". `NeurIPS(2023)` [[URL]](https://arxiv.org/abs/2312.15004) [[Project Page]](https://mingyuan-zhang.github.io/projects/FineMoGen.html) [[Code]](https://github.com/mingyuan-zhang/FineMoGen)

- **PRO-Motion**: "Plan, Posture and Go: Towards Open-World Text-to-Motion Generation". `ECCV(2024)` [[URL]](https://arxiv.org/abs/2312.14828) [[Project Page]](https://moonsliu.github.io/Pro-Motion/)

- **IterativeEditing**: "Iterative Motion Editing with Natural Language". `SIGGRAPH(2024)` [[URL]](https://arxiv.org/abs/2312.11538) [[Project Page]](https://purvigoel.github.io/iterative-motion-editing/) [[Code]](https://github.com/purvigoel/iterative-editing-release)

- **CrossDiff**: "Realistic Human Motion Generation with Cross-Diffusion Models". `ECCV(2024)` [[URL]](https://arxiv.org/abs/2312.10993) [[Project Page]](https://wonderno.github.io/CrossDiff-webpage/) [[Code]](https://github.com/wonderNo/crossdiff)

- **B2A-HDM**: "Towards Detailed Text-to-Motion Synthesis via Basic-to-Advanced Hierarchical Diffusion Model". `AAAI(2024)` [[URL]](https://arxiv.org/abs/2312.10960)

- **OMG**: "OMG: Towards Open-vocabulary Motion Generation via Mixture of Controllers". `CVPR(2024)` [[URL]](https://arxiv.org/abs/2312.08985) [[Project Page]](https://tr3e.github.io/omg-page/)

- **MMM**: "MMM: Generative Masked Motion Model". `CVPR(2024)` [[URL]](https://arxiv.org/abs/2312.03596) [[Project Page]](https://www.ekkasit.com/MMM-page/) [[Code]](https://github.com/exitudio/MMM/)

- **EMDM**: "EMDM: Efficient Motion Diffusion Model for Fast and High-Quality Motion Generation". `ECCV(2024)` [[URL]](https://arxiv.org/abs/2312.02256) [[Project Page]](https://frank-zy-dou.github.io/projects/EMDM/index.html) [[Code]](https://github.com/Frank-ZY-Dou/EMDM)

- **MoMask**: "MoMask: Generative Masked Modeling of 3D Human Motions". `CVPR(2024)` [[URL]](https://arxiv.org/abs/2312.00063) [[Project Page]](https://ericguo5513.github.io/momask/) [[Code]](https://github.com/EricGuo5513/momask-codes)

- **TLControl**: "TLControl: Trajectory and Language Control for Human Motion Synthesis". `arXiv(2023)` [[URL]](https://arxiv.org/abs/2311.17135) [[Code]](https://github.com/HiWilliamWWL/TLControl)

- **UDE-2**: "A Unified Framework for Multimodal, Multi-Part Human Motion Synthesis". `arXiv(2023)` [[URL]](https://arxiv.org/abs/2311.16471) [[Project Page]](https://zixiangzhou916.github.io/UDE-2/) [[Code]](https://github.com/zixiangzhou916/UDE-2)

- **GraphMotion**: "Act As You Wish: Fine-Grained Control of Motion Diffusion Model with Hierarchical Semantic Graphs". `NeurIPS(2023)` [[URL]](https://arxiv.org/abs/2311.01015) [[Code]](https://github.com/jpthu17/GraphMotion)

- **HumanTOMATO**: "HumanTOMATO: Text-aligned Whole-body Motion Generation". `ICML(2024)` [[URL]](https://arxiv.org/abs/2310.12978) [[Project Page]](https://lhchen.top/HumanTOMATO/) [[Code]](https://github.com/IDEA-Research/HumanTOMATO)

- **MoConVQ**: "MoConVQ: Unified Physics-Based Motion Control via Scalable Discrete Representations". `SIGGRAPH(2024)` [[URL]](https://arxiv.org/abs/2310.10198) [[Project Page]](https://moconvq.github.io/) [[Code]](https://github.com/heyuanYao-pku/MoConVQ)

- **KP**: "Bridging the Gap between Human Motion and Action Semantics via Kinematic Phrases". `ECCV(2024)` [[URL]](https://arxiv.org/abs/2310.04189) [[Project Page]](https://foruck.github.io/KP/) [[Code]](https://github.com/Foruck/Kinematic-Phrases)

- **T2M-GPT**: "T2M-GPT: Generating Human Motion from Textual Descriptions with Discrete Representations". `CVPR(2023)` [[URL]](https://arxiv.org/abs/2301.06052) [[Project Page]](https://mael-zys.github.io/T2M-GPT/) [[Code]](https://github.com/Mael-zys/T2M-GPT)

- **Modiff**: "Modiff: Action-Conditioned 3D Motion Generation with Denoising Diffusion Probabilistic Models". `arXiv(2023)` [[URL]](https://arxiv.org/abs/2301.03949)

- **MDM**: "Human Motion Diffusion Model". `ICLR(2023)` [[URL]](https://arxiv.org/abs/2209.14916) [[Project Page]](https://guytevet.github.io/mdm-page/) [[Code]](https://github.com/GuyTevet/motion-diffusion-model)

- **TEACH**: "TEACH: Temporal Action Composition for 3D Humans". `3DV(2022)` [[URL]](https://arxiv.org/abs/2209.04066) [[Project Page]](https://teach.is.tue.mpg.de/) [[Code]](https://github.com/atnikos/teach)

- **FLAME**: "FLAME: Free-form Language-based Motion Synthesis & Editing". `AAAI(2023)` [[URL]](https://arxiv.org/abs/2209.00349) [[Project Page]](https://kakaobrain.github.io/flame/) [[Code]](https://github.com/kakaobrain/flame)

- **MotionDiffuse**: "MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model". `TPAMI(2024)` [[URL]](https://arxiv.org/abs/2208.15001) [[Project Page]](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html) [[Code]](https://github.com/mingyuan-zhang/MotionDiffuse)

- **TM2T**: "TM2T: Stochastic and Tokenized Modeling for the Reciprocal Generation of 3D Human Motions and Texts". `ECCV(2022)` [[URL]](https://arxiv.org/abs/2207.01696) [[Project Page]](https://ericguo5513.github.io/TM2T/) [[Code]](https://github.com/EricGuo5513/TM2T)

- **T2M**: "Generating Diverse and Natural 3D Human Motions from Text". `CVPR(2022)` [[URL]](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_Generating_Diverse_and_Natural_3D_Human_Motions_From_Text_CVPR_2022_paper.pdf) [[Project Page]](https://ericguo5513.github.io/text-to-motion/) [[Code]](https://github.com/EricGuo5513/text-to-motion)

- **AvatarCLIP**: "AvatarCLIP: Zero-Shot Text-Driven Generation and Animation of 3D Avatars". `SIGGRAPH(2022)` [[URL]](https://arxiv.org/abs/2205.08535) [[Project Page]](https://hongfz16.github.io/projects/AvatarCLIP.html) [[Code]](https://github.com/hongfz16/AvatarCLIP)

- **TEMOS**: "TEMOS: Generating diverse human motions from textual descriptions". `ECCV(2022)` [[URL]](https://arxiv.org/abs/2204.14109) [[Project Page]](https://mathis.petrovich.fr/temos/) [[Code]](https://github.com/Mathux/TEMOS)

- **ImplicitMotion**: "Implicit Neural Representations for Variable Length Human Motion Generation". `ECCV(2022)` [[URL]](https://arxiv.org/abs/2203.13694) [[Code]](https://github.com/PACerv/ImplicitMotion)

- **MotionCLIP**: "MotionCLIP: Exposing Human Motion Generation to CLIP Space". `ECCV(2022)` [[URL]](https://arxiv.org/abs/2203.08063) [[Project Page]](https://guytevet.github.io/motionclip-page/) [[Code]](https://github.com/GuyTevet/MotionCLIP)

- **MultiAct**: "MultiAct: Long-Term 3D Human Motion Generation from Multiple Action Labels". `AAAI(2023)` [[URL]](https://arxiv.org/abs/2212.05897) [[Code]](https://github.com/TaeryungLee/MultiAct_RELEASE)

- **MoFusion**: "MoFusion: A Framework for Denoising-Diffusion-based Motion Synthesis". `CVPR(2023)` [[URL]](https://arxiv.org/abs/2212.04495) [[Project Page]](https://vcai.mpi-inf.mpg.de/projects/MoFusion/)

- **MLD**: "Executing your Commands via Motion Diffusion in Latent Space". `CVPR(2023)` [[URL]](https://arxiv.org/abs/2212.04048) [[Project Page]](https://chenxin.tech/mld/) [[Code]](https://github.com/chenfengye/motion-latent-diffusion)

- **PhysDiff**: "PhysDiff: Physics-Guided Human Motion Diffusion Model". `ICCV(2023)` [[URL]](https://arxiv.org/abs/2212.02500) [[Project Page]](https://nvlabs.github.io/PhysDiff/)

- **UDE**: "UDE: A Unified Driving Engine for Human Motion Generation". `CVPR(2023)` [[URL]](https://arxiv.org/abs/2211.16016) [[Project Page]](https://zixiangzhou916.github.io/UDE/) [[Code]](https://github.com/zixiangzhou916/UDE/)

- **Action-GPT**: "Action-GPT: Leveraging Large-scale Language Models for Improved and Generalized Action Generation". `ICME(2023)` [[URL]](https://arxiv.org/abs/2211.15603) [[Project Page]](https://actiongpt.github.io/) [[Code]](https://github.com/actiongpt/actiongpt)

- **OOHMG**: "Being Comes from Not-being: Open-vocabulary Text-to-Motion Generation with Wordless Training". `arXiv(2022)` [[URL]](https://arxiv.org/abs/2210.15929) [[Code]](https://github.com/junfanlin/oohmg)

- **ACTOR**: "Action-Conditioned 3D Human Motion Synthesis with Transformer VAE". `ICCV(2021)` [[URL]](https://arxiv.org/abs/2104.05670) [[Project Page]](https://mathis.petrovich.fr/actor/) [[Code]](https://github.com/Mathux/ACTOR)

- **Action2Motion**: "Action2Motion: Conditioned Generation of 3D Human Motions". `MM(2020)` [[URL]](https://arxiv.org/abs/2007.15240) [[Project Page]](https://ericguo5513.github.io/action-to-motion/) [[Code]](https://github.com/EricGuo5513/action-to-motion)


