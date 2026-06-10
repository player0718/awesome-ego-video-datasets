<div align="center">

# 🎥 Awesome Egocentric Video Datasets

**📜 A Curated List of Egocentric (First-Person) Video Datasets, Benchmarks, and Tools**

<p align="center">
  <img src="banner.png" alt="Awesome Egocentric Video Datasets" width="100%">
</p>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE)

</div>

## Overview

- 🎯 [Aim](#aim) | 📚 [Papers & Surveys](#papers--surveys)
- 🎬 [Video Generation & World-Model Pretraining](#-video-generation--world-model-pretraining)
- 🧠 [Memory, Summarization & Long-form Understanding](#-memory-summarization--long-form-understanding)
- 💬 [VLMs, Instructions & QA](#-vlms-instructions--qa)
- 🏃 [Action & Activity Recognition](#-action--activity-recognition)
- ✋ [Hand–Object Interaction, Dexterity & 3D](#-handobject-interaction-dexterity--3d)
- 📋 [Procedural Activities & Skill Learning](#-procedural-activities--skill-learning)
- 🗺️ [3D Scene Understanding & Localization](#-3d-scene-understanding--localization)
- 🛠️ [Tools & Libraries](#-tools--libraries) | 🔗 [Related Awesome Lists](#-related-awesome-lists) | 🤝 [Contributing](#-contributing) | 📄 [License](#license)

## Aim

This repository tracks egocentric video datasets through a task-first view: every dataset appears once as a primary entry under one of seven research themes, with cross-links where it also matters. The goal is fast navigation for researchers who need scale, task fit, benchmark context, and official resources without bouncing across multiple index files.

## Papers & Surveys

Sorted newest to oldest, with flagship surveys and corpus papers highlighted first.

- **Building Egocentric Procedural AI Assistant: Methods, Benchmarks, and Challenges** (2025) — Li et al., 2025 survey and benchmark paper of egocentric procedural activity understanding, focus on building egocentric procedural AI assistant.
  [![arXiv](https://img.shields.io/badge/arXiv-2511.13261-b31b1b.svg)](https://arxiv.org/abs/2511.13261)

- [⭐️] **Challenges and Trends in Egocentric Vision: A Survey** (2025) — Li et al., 2025 survey of datasets, tasks, benchmarks, and open challenges in egocentric vision.
  [![arXiv](https://img.shields.io/badge/arXiv-2503.15275-b31b1b.svg)](https://arxiv.org/abs/2503.15275)

- [⭐️] **Bridging Perspectives: A Survey on Cross-view Collaborative Intelligence with Egocentric-Exocentric Vision** (2025) — Cross-view survey covering ego-exo collaboration, paired capture, and collaborative perception.
  [![arXiv](https://img.shields.io/badge/arXiv-2506.06253-b31b1b.svg)](https://arxiv.org/abs/2506.06253)

- **HD-EPIC: A Highly-Detailed Egocentric Video Dataset** (2025) — Dataset paper introducing fine-grained kitchen understanding with dense multimodal annotations.
  [![arXiv](https://img.shields.io/badge/arXiv-2502.04144-b31b1b.svg)](https://arxiv.org/abs/2502.04144)

- **Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives** (2024) — Large-scale paired ego-exo dataset paper spanning skilled activity and multiview understanding.
  [![arXiv](https://img.shields.io/badge/arXiv-2311.18259-b31b1b.svg)](https://arxiv.org/abs/2311.18259)

- **EgoExoLearn: A Dataset for Bridging Asynchronous Ego- and Exo-centric View of Procedural Activities in Real World** (2024) — Procedural ego-exo paper focused on asynchronous activity alignment in real environments.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_EgoExoLearn_A_Dataset_for_Bridging_Asynchronous_Ego-_and_Exo-centric_View_CVPR_2024_paper.html)

- **EgoSchema: A Diagnostic Benchmark for Very Long-form Video Language Understanding** (2023) — Benchmark paper targeting long-form memory and reasoning over egocentric video.
  [![arXiv](https://img.shields.io/badge/arXiv-2308.09126-b31b1b.svg)](https://arxiv.org/abs/2308.09126)

- [⭐️] **Ego4D: Around the World in 3,000 Hours of Egocentric Video** (2022) — Flagship corpus paper introducing the large-scale Ego4D benchmark suite.
  [![arXiv](https://img.shields.io/badge/arXiv-2110.07058-b31b1b.svg)](https://arxiv.org/abs/2110.07058)

- [⭐️] **Rescaling Egocentric Vision: Collection, Pipeline and Challenges for EPIC-KITCHENS-100** (2021) — Canonical kitchen benchmark paper for action recognition, detection, and anticipation.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://link.springer.com/article/10.1007/s11263-021-01531-2)

- **Charades-Ego: A Large-Scale Dataset of Paired Third and First Person Videos** (2018) — Early paired ego-exo benchmark for activity transfer and alignment.
  [![arXiv](https://img.shields.io/badge/arXiv-1804.09626-b31b1b.svg)](https://arxiv.org/abs/1804.09626)

- **Position: Life-Logging Video Streams Make the Privacy-Utility Trade-off Inevitable** (2026) — Zou et al., 2026 position paper arguing the privacy-utility trade-off in always-on life-logging video streams (smart glasses, body cameras) is a foundational challenge for proactive wearable AI, calling for pipeline-aware privacy-preserving designs, leakage metrics, and standardized benchmarks.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.10404-b31b1b.svg)](https://arxiv.org/abs/2605.10404)

## 🎬 Video Generation & World-Model Pretraining

> Datasets here emphasize large-scale first-person pretraining corpora, video generation, editing, or world-model supervision from ego video.

### Datasets at a glance

| Name | Year | Scale | Key tasks | Paper | Link |
|------|------|-------|-----------|-------|------|
| ⭐ Ropedia Xperience-10M | 2026 | Large multi-stream experiences | Multimodal ego learning | N/A | [Hugging Face](https://huggingface.co/datasets/ropedia-ai/xperience-10m) |
| ⭐ EgoVid-5M | 2024 | 5M clips | Video generation, motion+text | [Paper](https://arxiv.org/abs/2411.08380) | [Site](https://egovid.github.io/) |
| DreamDojo-HV | 2026 | Very large FP video (see paper) | World models, pretraining | [Paper](https://arxiv.org/abs/2602.06949) | N/A |
| Ego-1K | 2026 | Multiview clips (~1K takes) | Neural 3D/4D synthesis | [Paper](https://arxiv.org/abs/2603.13741) | [Hugging Face](https://huggingface.co/datasets/facebook/ego-1k) |
| In-lab | 2026 | Lab tabletop trajectories | Skills, world models (w/ DreamDojo) | [Paper](https://arxiv.org/abs/2602.06949) | N/A |
| EgoEdit | 2025 | 100K editing pairs | Egocentric video editing | [Paper](https://arxiv.org/abs/2512.06065) | [Site](https://snap-research.github.io/EgoEdit) |
| HumanNet | 2026 | ~1M h human-centric video (ego + exo) | VLA / embodied pretraining | [Paper](https://arxiv.org/abs/2605.06747) | N/A |
| MobileEgo Anywhere | 2026 | 200 h smartphone-collected long-horizon ego | Long-horizon ego data infra, VLA | [Paper](https://arxiv.org/abs/2605.05945) | N/A |

### Entries

- [⭐️] **Ropedia Xperience-10M** (2026) — 10M multimodal experiences with 6 RGB streams, stereo depth, pose/SLAM, hand-body mocap, audio, and IMU for large-scale ego pretraining.
  [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://ropedia.com/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Ropedia/HOMIE-toolkit) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/ropedia-ai/xperience-10m)

- [⭐️] **EgoVid-5M** (2024) — 5M first-person clips curated for text-and-motion-conditioned video generation from wearable footage.
  [![arXiv](https://img.shields.io/badge/arXiv-2411.08380-b31b1b.svg)](https://arxiv.org/abs/2411.08380) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2411.08380) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/JeffWang987/EgoVid)

- **DreamDojo-HV** (2026) — Very large FP video (see paper); World models, pretraining.
  [![arXiv](https://img.shields.io/badge/arXiv-2602.06949-b31b1b.svg)](https://arxiv.org/abs/2602.06949) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2602.06949)

- **Ego-1K** (2026) — Multiview clips (~1K takes); Neural 3D/4D synthesis.
  [![arXiv](https://img.shields.io/badge/arXiv-2603.13741-b31b1b.svg)](https://arxiv.org/abs/2603.13741) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2603.13741) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/facebook/ego-1k)

- **In-lab** (2026) — Lab tabletop trajectories; Skills, world models (w/ DreamDojo).
  [![arXiv](https://img.shields.io/badge/arXiv-2602.06949-b31b1b.svg)](https://arxiv.org/abs/2602.06949) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2602.06949)

- **EgoEdit** (2025) — 100K editing pairs; Egocentric video editing.
  [![arXiv](https://img.shields.io/badge/arXiv-2512.06065-b31b1b.svg)](https://arxiv.org/abs/2512.06065) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2512.06065)

- **HumanNet** (2026) — ~1M h of human-centric video (mix of ego and exo) with interaction-centric annotations; the authors report 1k h of ego human video outperforms 100 h of real-robot data for VLA training.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.06747-b31b1b.svg)](https://arxiv.org/abs/2605.06747)

- **MobileEgo Anywhere** (2026) — 200 h of hour-plus egocentric trajectories collected on commodity smartphones, released with an open-source mobile capture app and a processing pipeline aimed at VLA pretraining.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.05945-b31b1b.svg)](https://arxiv.org/abs/2605.05945)

### Benchmarks built on these datasets

| Benchmark | Capability | Primary data | Official link | Notes |
|-----------|------------|--------------|---------------|-------|
| EgoEdit | Egocentric video editing | EgoEdit / EgoEditData | [Project](https://snap-research.github.io/EgoEdit) | Dataset+benchmark |

## 🧠 Memory, Summarization & Long-form Understanding

> This section collects long-horizon lifelog, summarization, and persistent-memory datasets where temporal continuity matters as much as recognition.

### Datasets at a glance

| Name | Year | Scale | Key tasks | Paper | Link |
|------|------|-------|-----------|-------|------|
| ⭐ EgoLife | 2025 | ~266–300 h daily life | Long-form assistants, memory | [Paper](https://arxiv.org/abs/2503.03803) | [Site](https://egolife-ai.github.io/) |
| ⭐ EgoSchema | 2023 | 250+ h / 5K QA | Long-form video QA | [Paper](https://arxiv.org/abs/2308.09126) | [Site](https://egoschema.github.io/) |
| SuperMemory-VQA | 2026 | 52.9 h / 4,853 QA | Long-horizon memory VQA | [Paper](https://arxiv.org/abs/2606.00825) | [HF](https://huggingface.co/datasets/OSU-AIoT-MLSys-Lab/SuperMemory-VQA) |
| EgoMemReason | 2026 | 500 MCQs over EgoLife | Week-long memory reasoning | [Paper](https://arxiv.org/abs/2605.09874) | [HF](https://huggingface.co/datasets/Ted412/EgoMemReason) |
| EgoExoMem | 2026 | 2.6K MCQs / 390 videos | Cross-view memory reasoning | [Paper](https://arxiv.org/abs/2605.18734) | [GitHub](https://github.com/RuipingL/EgoExoMem) |
| EgoIntrospect | 2026 | 180 h / 60 subjects | Internal-state reasoning, memory | [Paper](https://arxiv.org/abs/2605.17262) | [Site](https://ego-introspect.github.io/) |
| MA-EgoQA | 2026 | 1,741 QA / 6 agents / 7 days | Multi-agent egocentric QA | [Paper](https://arxiv.org/abs/2603.09827) | [Site](https://ma-egoqa.github.io/) |
| VidChapters-7M | 2023 | 817K videos / 7M chapters | Chaptering (not ego-only) | [Paper](https://arxiv.org/abs/2309.13952) | [Site](https://antoyang.github.io/vidchapters.html) |
| Multi-Ego | 2022 | ~12 h / 41 seq. | Multi-wearer, summarization | [Paper](https://openaccess.thecvf.com/content/WACV2022/html/Elfeki_Multi-Stream_Dynamic_Video_Summarization_WACV_2022_paper.html) | [GitHub](https://github.com/M-Elfeki/Multi-DPP) |
| DoMSEV | 2018 | 80 h, 48 seq. | Semantic fast-forward, first-person video | [Paper](https://openaccess.thecvf.com/content_cvpr_2018/html/Silva_A_Weighted_Sparse_CVPR_2018_paper.html) | [Site](https://www.verlab.dcc.ufmg.br/semantic-hyperlapse/cvpr2018-dataset/) |
| HUJI-EgoSeg | 2014 | 29 long egocentric videos (~1–5 h each), pixel-level temporal segmentation annotations | memory, summarization & long-form understanding | [Paper](https://openaccess.thecvf.com/content_cvpr_2014/html/Poleg_Temporal_Segmentation_of_2014_CVPR_paper.html) | [Site](http://www.cs.huji.ac.il/~yedMDpid/egoseg/) |
| UT Ego | 2012 | ~17 h, 4 long videos | Summarization, long-form ego | [Paper](https://doi.org/10.1109/CVPR.2012.6247820) | [Site](http://vision.cs.utexas.edu/projects/egocentric_data/UT_Egocentric_Dataset.html) |
| VINST / Visual Diaries | 2011 | 31 egocentric videos capturing daily commutes; used for temporal segmentation and video summarization | memory, summarization & long-form understanding | [Paper](https://doi.org/10.1109/CVPR.2011.5995731) | [Site](https://www.csc.kth.se/cvap/vinst/NovEgoMotion.html) |
| EgoStream | 2026 | 2,250 Q / 8,528 evals, streams up to 45.3 h | Streaming episodic memory | [Paper](https://arxiv.org/abs/2605.31557) | [Site](https://saroo25.github.io/Egostream/) |

### Entries

- **SuperMemory-VQA** (2026) — 52.9 h of everyday Meta Aria recordings with RGB, processed gaze, IMU, SLAM trajectories, point clouds, redacted transcripts, and 4,853 human-verified long-horizon memory QA pairs.
  [![arXiv](https://img.shields.io/badge/arXiv-2606.00825-b31b1b.svg)](https://arxiv.org/abs/2606.00825) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/OSU-AIoT-MLSys-Lab/SuperMemory-VQA)

- **EgoMemReason** (2026) — 500 multiple-choice questions over week-long EgoLife video for entity, event, and behavior memory reasoning, with public questions and leaderboard evaluation.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.09874-b31b1b.svg)](https://arxiv.org/abs/2605.09874) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://egomemreason.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Ziyang412/EgoMemReason) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/Ted412/EgoMemReason)

- **EgoExoMem** (2026) — 2.6K human-verified MCQs over 390 synchronized egocentric and exocentric videos from EgoExo4D and LEMMA for cross-view memory reasoning.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.18734-b31b1b.svg)](https://arxiv.org/abs/2605.18734) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/RuipingL/EgoExoMem)

- **EgoIntrospect** (2026) — 180 h of user-driven egocentric recordings from 60 subjects with synchronized video, audio, gaze, motion, and physiological signals for affective experience, request intent, and cognitive-memory reasoning; the paper states data will be made public.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.17262-b31b1b.svg)](https://arxiv.org/abs/2605.17262) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://ego-introspect.github.io/)

- **MA-EgoQA** (2026) — 1,741 QA pairs over six temporally aligned EgoLife egocentric streams spanning seven days, targeting multi-agent social interaction, task coordination, theory-of-mind, temporal reasoning, and environmental interaction.
  [![arXiv](https://img.shields.io/badge/arXiv-2603.09827-b31b1b.svg)](https://arxiv.org/abs/2603.09827) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://ma-egoqa.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/KangsanKim07/MA-EgoQA)

- [⭐️] **EgoLife** (2025) — ~266-300 h of daily-life capture in EgoHouse with Meta Aria, third-person cameras, and mmWave sensors for persistent assistant memory.
  [![arXiv](https://img.shields.io/badge/arXiv-2503.03803-b31b1b.svg)](https://arxiv.org/abs/2503.03803) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://egolife-ai.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/EvolvingLMMs-Lab/EgoLife) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/lmms-lab/EgoLife)

- [⭐️] **EgoSchema** (2023) — 250+ h of long-form Ego4D video with 5K QA pairs designed to probe memory and causal understanding over extended clips.
  [![arXiv](https://img.shields.io/badge/arXiv-2308.09126-b31b1b.svg)](https://arxiv.org/abs/2308.09126) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2308.09126) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/egoschema/EgoSchema)

- **VidChapters-7M** (2023) — 817K videos / 7M chapters; Chaptering (not ego-only).
  [![arXiv](https://img.shields.io/badge/arXiv-2309.13952-b31b1b.svg)](https://arxiv.org/abs/2309.13952) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://antoyang.github.io/vidchapters.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/antoyang/VidChapters)

- **Multi-Ego** (2022) — ~12 h / 41 seq; Multi-wearer, summarization.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/WACV2022/html/Elfeki_Multi-Stream_Dynamic_Video_Summarization_WACV_2022_paper.html) [![arXiv](https://img.shields.io/badge/arXiv-1812.00108-b31b1b.svg)](https://arxiv.org/abs/1812.00108) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/M-Elfeki/Multi-DPP)

- **DoMSEV** (2018) — 80 h, 48 seq; Semantic fast-forward, first-person video.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2018/html/Silva_A_Weighted_Sparse_CVPR_2018_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://www.verlab.dcc.ufmg.br/semantic-hyperlapse/cvpr2018-dataset/)

- **HUJI-EgoSeg** (2014) — 29 long egocentric videos (~1–5 h each), pixel-level temporal segmentation annotations; memory, summarization & long-form understanding.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2014/html/Poleg_Temporal_Segmentation_of_2014_CVPR_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](http://www.cs.huji.ac.il/~yedMDpid/egoseg/)

- **UT Ego** (2012) — ~17 h, 4 long videos; Summarization, long-form ego.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.1109/CVPR.2012.6247820) [![Project](https://img.shields.io/badge/Project-Link-blue.svg)](http://vision.cs.utexas.edu/projects/egocentric_data/UT_Egocentric_Dataset.html)

- **VINST / Visual Diaries** (2011) — 31 egocentric videos capturing daily commutes; used for temporal segmentation and video summarization; memory, summarization & long-form understanding.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.1109/CVPR.2011.5995731) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://www.csc.kth.se/cvap/vinst/NovEgoMotion.html)

- **EgoStream** (2026) — 2,250 curated questions expanded to 8,528 recall-conditioned evaluations via Answer Validity Windows over egocentric streams up to 45.3 h (curated from Ego4D, EgoLife, EgoTempo, Multi-Hop EgoQA, and HD-EPIC), spanning seven cognitive memory dimensions for diagnosing streaming episodic memory in video-language models.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.31557-b31b1b.svg)](https://arxiv.org/abs/2605.31557) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://saroo25.github.io/Egostream/)

### Benchmarks built on these datasets

| Benchmark | Capability | Primary data | Official link | Notes |
|-----------|------------|--------------|---------------|-------|
| SuperMemory-VQA | Long-horizon egocentric memory VQA with answerability checks | SuperMemory-VQA | [HF](https://huggingface.co/datasets/OSU-AIoT-MLSys-Lab/SuperMemory-VQA) | Dataset+benchmark |
| EgoMemReason | Week-long entity, event, and behavior memory reasoning | EgoLife | [HF](https://huggingface.co/datasets/Ted412/EgoMemReason) | Standalone |
| EgoExoMem | Cross-view memory reasoning over synchronized ego-exo videos | EgoExo4D / LEMMA | [GitHub](https://github.com/RuipingL/EgoExoMem) | Standalone |
| EgoIntrospect | User internal-state reasoning over multimodal egocentric streams | EgoIntrospect | [Site](https://ego-introspect.github.io/) | Dataset+benchmark |
| MA-EgoQA | Multi-agent egocentric video QA over week-long streams | EgoLife | [Site](https://ma-egoqa.github.io/) | Standalone |
| EgoSchema | Long-form video-language understanding | Ego4D | [Site](https://egoschema.github.io/) | Standalone |
| EgoStream | Streaming episodic memory diagnosis | Ego4D / EgoLife / EgoTempo / Multi-Hop EgoQA / HD-EPIC | [Site](https://saroo25.github.io/Egostream/) | Standalone |

## 💬 VLMs, Instructions & QA

> These datasets target egocentric video-language pretraining, instruction following, dialog, and question answering over first-person streams.

### Datasets at a glance

| Name | Year | Scale | Key tasks | Paper | Link |
|------|------|-------|-----------|-------|------|
| ⭐ HD-EPIC | 2025 | ~41 h / dense labels | Fine-grained kitchen, VQA | [Paper](https://arxiv.org/abs/2502.04144) | [Site](https://hd-epic.github.io/) |
| EgoTL | 2026 | 100+ daily household tasks | Long-horizon reasoning, spatial QA | [Paper](https://arxiv.org/abs/2604.09535) | [Site](https://ego-tl.github.io/) |
| MM-Conv | 2026 | 6.7 h / 4,211 expressions | Context-aware 3D dialogue grounding | [Paper](https://arxiv.org/abs/2605.21796) | N/A |
| Minerva-Ego | 2026 | 1,160 QA / 156 videos | Spatiotemporal reasoning traces | [Paper](https://arxiv.org/abs/2605.15342) | [GitHub](https://github.com/google-deepmind/neptune) |
| EgoEverything | 2026 | 100+ h / 5K+ MCQs | Long-context AR VideoQA | [Paper](https://arxiv.org/abs/2604.08342) | N/A |
| EgoEsportsQA | 2026 | 1,745 QA pairs | Esports VideoQA, reasoning | [Paper](https://arxiv.org/abs/2604.12320) | N/A |
| MyEgo | 2026 | 541 long videos / 5K QA | Personalized VideoQA, ego-grounding | [Paper](https://arxiv.org/abs/2604.01966) | [GitHub](https://github.com/Ryougetsu3606/MyEgo) |
| LifeDialBench / EgoMem | 2026 | EgoMem + LifeMem (coming soon) | Lifelog memory, online eval | [Paper](https://arxiv.org/abs/2604.11182) | [GitHub](https://github.com/qys77714/LifeDialBench) |
| Ego2Web | 2026 | 500 video-instruction pairs | Egocentric video-grounded web agents | [Paper](https://arxiv.org/abs/2603.22529) | [HF](https://huggingface.co/datasets/Shoubin/Ego2Web) |
| EgoEMS | 2025 | 20+ h emergency scenarios | EMS QA, multimodal | [Paper](https://arxiv.org/abs/2511.09894) | [GitHub](https://github.com/UVA-DSA/EgoEMS) |
| HowToDIV | 2025 | ~24 h instructional | Dialog, procedural QA | [Paper](https://arxiv.org/abs/2508.11192) | [GitHub](https://github.com/google/howtodiv) |
| InterVLA | 2025 | 11.4 h interactions | Instruction, ego–exo mocap | [Paper](https://arxiv.org/abs/2508.04681) | [Site](https://liangxuy.github.io/InterVLA/) |
| AssistQ | 2022 | 100 long videos / 529 QA | Instructional QA | [Paper](https://arxiv.org/abs/2203.04203) | [GitHub](https://github.com/showlab/AssistQ) |
| EgoClip | 2022 | 3.8M clip–text pairs | Video-language pretraining | [Paper](https://arxiv.org/abs/2206.01670) | [GitHub](https://github.com/showlab/EgoVLP) |
| EgoTaskQA | 2022 | ~2K videos / 40K QA | Causal & task QA | [Paper](https://arxiv.org/abs/2210.03929) | [Site](https://sites.google.com/view/egotaskqa) |
| EgoVQA | 2019 | 600+ QAs | Video QA | [Paper](https://openaccess.thecvf.com/content_ICCVW_2019/html/EPIC/Fan_EgoVQA_-_An_Egocentric_Video_Question_Answering_Benchmark_Dataset_ICCVW_2019_paper.html) | N/A |
| NoRA | 2026 | 1,420 clips / support graphs | Normative action reasoning | [Paper](https://arxiv.org/abs/2606.04806) | N/A |
| Causal-Plan-1M | 2026 | 1M QA / 22.2K clips / 770+ h | Physically grounded planning QA | [Paper](https://arxiv.org/abs/2606.01810) | [HF](https://huggingface.co/datasets/anonymous-causal-plan/Causal_Plan) |
| Pause-and-Think | 2026 | 10K QA clips + 300-sample benchmark | Assistive action suggestion | [Paper](https://arxiv.org/abs/2606.00616) | [GitHub](https://github.com/sssshivvvv/pause-and-think) |
| EgoCoT-Bench | 2026 | 351 videos / 3,172 QA | Grounded operation-centric CoT QA | [Paper](https://arxiv.org/abs/2605.19559) | [Site](https://dstardust.github.io/EgoCoT/) |

### Entries

- **EgoTL** (2026) — 100+ daily household tasks with think-aloud chains, navigation and manipulation annotations, and metric spatial labels for long-horizon egocentric reasoning and QA.
  [![arXiv](https://img.shields.io/badge/arXiv-2604.09535-b31b1b.svg)](https://arxiv.org/abs/2604.09535) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://ego-tl.github.io/)

- **MM-Conv** (2026) — 6.7 h of egocentric VR interaction with synchronized speech, motion, gaze, 3D scene geometry, and 4,211 verified referring expressions for context-aware conversational grounding; full public release is described as following camera-ready.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.21796-b31b1b.svg)](https://arxiv.org/abs/2605.21796)

- **Minerva-Ego** (2026) — 1,160 hand-crafted multiple-choice questions over 156 HD-EPIC egocentric videos, paired with dense spatiotemporal human reasoning traces and object masks for diagnosable video reasoning.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.15342-b31b1b.svg)](https://arxiv.org/abs/2605.15342) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/google-deepmind/neptune)

- **EgoEverything** (2026) — 100+ h of AR egocentric video with 5K+ multiple-choice questions for human-behavior-inspired long-context video understanding.
  [![arXiv](https://img.shields.io/badge/arXiv-2604.08342-b31b1b.svg)](https://arxiv.org/abs/2604.08342)

- **EgoEsportsQA** (2026) — 1,745 expert QA pairs from first-person shooter esports videos for testing fast virtual-scene perception and tactical reasoning.
  [![arXiv](https://img.shields.io/badge/arXiv-2604.12320-b31b1b.svg)](https://arxiv.org/abs/2604.12320)

- **MyEgo** (2026) — 541 long egocentric videos with 5K personalized questions about the camera wearer, their activities, and past context.
  [![arXiv](https://img.shields.io/badge/arXiv-2604.01966-b31b1b.svg)](https://arxiv.org/abs/2604.01966) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Ryougetsu3606/MyEgo)

- **LifeDialBench / EgoMem** (2026) — Lifelog memory benchmark with EgoMem built from real-world egocentric videos and an online evaluation protocol; the project page currently marks the dataset and scripts as coming soon.
  [![arXiv](https://img.shields.io/badge/arXiv-2604.11182-b31b1b.svg)](https://arxiv.org/abs/2604.11182) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/qys77714/LifeDialBench)

- **Ego2Web** (2026) — 500 egocentric video-instruction pairs for evaluating web agents that must ground real-world first-person visual context before executing online tasks.
  [![arXiv](https://img.shields.io/badge/arXiv-2603.22529-b31b1b.svg)](https://arxiv.org/abs/2603.22529) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://ego2web.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Yui010206/Ego2Web) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/Shoubin/Ego2Web)

- [⭐️] **HD-EPIC** (2025) — ~41 h of densely labeled cooking video with recipe steps, audio events, gaze, 3D grounding, and VQA supervision.
  [![arXiv](https://img.shields.io/badge/arXiv-2502.04144-b31b1b.svg)](https://arxiv.org/abs/2502.04144) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2502.04144) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/hd-epic/hd-epic-annotations)

- **EgoEMS** (2025) — 20+ h emergency scenarios; EMS QA, multimodal.
  [![arXiv](https://img.shields.io/badge/arXiv-2511.09894-b31b1b.svg)](https://arxiv.org/abs/2511.09894) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2511.09894) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/UVA-DSA/EgoEMS)

- **HowToDIV** (2025) — ~24 h instructional; Dialog, procedural QA.
  [![arXiv](https://img.shields.io/badge/arXiv-2508.11192-b31b1b.svg)](https://arxiv.org/abs/2508.11192) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2508.11192) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/google/howtodiv)

- **InterVLA** (2025) — 11.4 h interactions; Instruction, ego–exo mocap.
  [![arXiv](https://img.shields.io/badge/arXiv-2508.04681-b31b1b.svg)](https://arxiv.org/abs/2508.04681) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2508.04681)

- **AssistQ** (2022) — 100 long videos / 529 QA; Instructional QA.
  [![arXiv](https://img.shields.io/badge/arXiv-2203.04203-b31b1b.svg)](https://arxiv.org/abs/2203.04203) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/showlab/AssistQ)

- **EgoClip** (2022) — 3.8M clip–text pairs; Video-language pretraining.
  [![arXiv](https://img.shields.io/badge/arXiv-2206.01670-b31b1b.svg)](https://arxiv.org/abs/2206.01670) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/showlab/EgoVLP)

- **EgoTaskQA** (2022) — ~2K videos / 40K QA; Causal & task QA.
  [![arXiv](https://img.shields.io/badge/arXiv-2210.03929-b31b1b.svg)](https://arxiv.org/abs/2210.03929) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://sites.google.com/view/egotaskqa) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Buzz-Beater/EgoTaskQA)

- **EgoVQA** (2019) — 600+ QAs; Video QA.
  [![Paper](https://img.shields.io/badge/Paper-ICCVW19-b31b1b.svg)](https://openaccess.thecvf.com/content_ICCVW_2019/html/EPIC/Fan_EgoVQA_-_An_Egocentric_Video_Question_Answering_Benchmark_Dataset_ICCVW_2019_paper.html)

- **NoRA** (2026) — 1,420 Ego4D-derived clips (190 human-verified HumanGold + 1,230 LLM-validated LLMSilver) with fact–reason–action support-graph annotations for benchmarking grounded normative action reasoning in VLMs.
  [![arXiv](https://img.shields.io/badge/arXiv-2606.04806-b31b1b.svg)](https://arxiv.org/abs/2606.04806)

- **Causal-Plan-1M** (2026) — 1M QA pairs with four-stage causal reasoning-trace annotations over 22,201 egocentric clips (770+ h curated from Ego4D, EPIC-KITCHENS, HoloAssist, MECCANO, and others), plus the 1,200-instance Causal-Plan-Bench for physically grounded embodied planning.
  [![arXiv](https://img.shields.io/badge/arXiv-2606.01810-b31b1b.svg)](https://arxiv.org/abs/2606.01810) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/THUSI-Lab/Causal-Reasoner) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/anonymous-causal-plan/Causal_Plan)

- **Pause-and-Think** (2026) — 10,051 reasoning-annotated training QA clips and a 300-sample benchmark curated from EPIC-KITCHENS, Ego4D, and Assembly101 with structured thinking/answer supervision for video-grounded assistive action suggestion and goal planning.
  [![arXiv](https://img.shields.io/badge/arXiv-2606.00616-b31b1b.svg)](https://arxiv.org/abs/2606.00616) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/sssshivvvv/pause-and-think)

- **EgoCoT-Bench** (2026) — 3,172 verifiable QA pairs over 351 first-person videos (sourced from Ego4D, EPIC-KITCHENS, Charades-Ego, MECCANO, and HD-EPIC) with step-by-step rationale annotations for evaluating grounded operation-centric chain-of-thought reasoning in MLLMs.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.19559-b31b1b.svg)](https://arxiv.org/abs/2605.19559) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://dstardust.github.io/EgoCoT/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/DStardust/EgoCoT) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/DStardust/EgoCoT-Bench)

- *EgoSchema — see [Memory, Summarization & Long-form Understanding](#-memory-summarization--long-form-understanding)*

### Benchmarks built on these datasets

| Benchmark | Capability | Primary data | Official link | Notes |
|-----------|------------|--------------|---------------|-------|
| EgoTL-Bench | Long-horizon planning, action reasoning, perceptual-metric understanding | EgoTL | [Site](https://ego-tl.github.io/) | Dataset+benchmark |
| MM-Conv | Context-aware grounding in spontaneous 3D dialogue | MM-Conv | [Paper](https://arxiv.org/abs/2605.21796) | Dataset+benchmark |
| Minerva-Ego | Egocentric multi-step VideoQA with spatiotemporal reasoning traces | HD-EPIC | [GitHub](https://github.com/google-deepmind/neptune) | Standalone |
| EgoEverything | Long-context AR VideoQA | EgoEverything | [Paper](https://arxiv.org/abs/2604.08342) | Standalone |
| EgoEsportsQA | Esports VideoQA and tactical reasoning | EgoEsportsQA | [Paper](https://arxiv.org/abs/2604.12320) | Standalone |
| MyEgo | Personalized egocentric VideoQA | MyEgo | [GitHub](https://github.com/Ryougetsu3606/MyEgo) | Dataset+benchmark |
| LifeDialBench / EgoMem | Lifelog memory and online evaluation | EgoMem | [GitHub](https://github.com/qys77714/LifeDialBench) | Dataset+benchmark |
| Ego2Web | Egocentric video-grounded web-agent execution | Ego2Web | [Site](https://ego2web.github.io/) | Dataset+benchmark |
| EgoExoBench | Cross-perspective video understanding in MLLMs | Ego-Exo4D / LEMMA / EgoExoLearn / TF2023 / EgoMe / CVMHAT | [GitHub](https://github.com/ayiyayi/EgoExoBench) | Standalone |
| EgoBabyVLM / Machine-DevBench | Cross-modal learning from naturalistic egocentric video | Naturalistic infant/adult ego video corpora | [Paper](https://arxiv.org/abs/2605.19130) | Standalone |
| EgoEMS | EMS QA, multimodal assessment | EgoEMS | [GitHub](https://github.com/UVA-DSA/EgoEMS) | Dataset+benchmark |
| HD-EPIC | Fine-grained kitchen understanding, VQA | HD-EPIC | [Site](https://hd-epic.github.io/) | Dataset+benchmark |
| HowToDIV | Multi-turn instructional dialog & QA | HowToDIV | [GitHub](https://github.com/google/howtodiv) | Standalone |
| InterVLA | Instruction following, interaction understanding | InterVLA | [Site](https://liangxuy.github.io/InterVLA/) | Dataset+benchmark |
| AssistQ | Instructional affordance-centric QA | AssistQ | [GitHub](https://github.com/showlab/AssistQ) | Standalone |
| EgoTaskQA | Causal, predictive, explanatory, counterfactual QA | EgoTaskQA | [Site](https://sites.google.com/view/egotaskqa) | Standalone |
| EgoVQA | Egocentric video QA | EgoVQA | [Open Access (ICCVW 2019 / EPIC)](https://openaccess.thecvf.com/content_ICCVW_2019/html/EPIC/Fan_EgoVQA_-_An_Egocentric_Video_Question_Answering_Benchmark_Dataset_ICCVW_2019_paper.html) | Standalone |
| NoRA | Grounded normative action reasoning | Ego4D | [Paper](https://arxiv.org/abs/2606.04806) | Standalone |
| Causal-Plan-Bench | Physically grounded embodied planning QA | Causal-Plan-1M | [HF](https://huggingface.co/datasets/anonymous-causal-plan/Causal_Plan) | Dataset+benchmark |
| Pause-and-Think | Video-grounded assistive action suggestion | EPIC-KITCHENS / Ego4D / Assembly101 | [GitHub](https://github.com/sssshivvvv/pause-and-think) | Dataset+benchmark |
| EgoCoT-Bench | Grounded operation-centric chain-of-thought QA | Ego4D / EPIC-KITCHENS / Charades-Ego / MECCANO / HD-EPIC | [Site](https://dstardust.github.io/EgoCoT/) | Standalone |

## 🏃 Action & Activity Recognition

> Canonical action-recognition, activity-analysis, affect, and interaction datasets built around first-person human behavior live here.

### Datasets at a glance

| Name | Year | Scale | Key tasks | Paper | Link |
|------|------|-------|-----------|-------|------|
| ⭐ Ego4D | 2022 | ~3,670 h | AR, VQA, forecasting, many | [Paper](https://arxiv.org/abs/2110.07058) | [Site](https://ego4d-data.org/) |
| ⭐ EPIC-KITCHENS-100 | 2021 | 100 h / 90K segments | Action recognition, many | [Paper](https://link.springer.com/article/10.1007/s11263-021-01531-2) | [Site](https://epic-kitchens.github.io/) |
| ChildLens | 2026 | 108.58 h / 354 videos | Child activity analysis | [Paper](https://link.springer.com/article/10.3758/s13428-026-02982-6) | [Data](https://doi.org/10.17617/4.fe) |
| EgoScale | 2026 | 20k+ h labeled manipulation (paper) | Action, dexterous transfer | [Paper](https://arxiv.org/abs/2602.16710) | N/A |
| World In Your Hands | 2025 | 1000+ h labeled manipulation (paper) | Action, dexterous transfer, VLA training | [Paper](https://arxiv.org/abs/2512.24310) | [Github](https://github.com/tars-robotics/World-In-Your-Hands) |
| EgoCampus | 2025 | ~32 h / campus paths (paper) | Gaze, pedestrian ego | [Paper](https://arxiv.org/abs/2512.07668) | [GitHub](https://github.com/ComputerVisionRutgers/EgoCampus) |
| CogDrive (EyeCue) | 2026 | Multi-scenario driving clips | Driver cognitive-distraction detection, gaze + ego | [Paper](https://arxiv.org/abs/2605.07859) | N/A |
| AEA | 2024 | 143 seq. / ~7.3 h | Everyday activities, Aria | [Paper](https://arxiv.org/abs/2402.13349) | [Site](https://www.projectaria.com/datasets/aea/) |
| EgoSurgery (Phase / Tool / HTS) | 2024 | Open-surgery ego video | Phase, tools, segmentation | [Phase](https://arxiv.org/abs/2405.19644) / [Tool](https://arxiv.org/abs/2406.03095) / [HTS](https://arxiv.org/abs/2503.18755) | [GitHub](https://github.com/Fujiry0/EgoSurgery) |
| EgoExo-Fitness | 2024 | 32 h / 1,276 seq. | Full-body action, quality assessment | [Paper](https://arxiv.org/abs/2406.08877) | [GitHub](https://github.com/iSEE-Laboratory/EgoExo-Fitness) |
| E³ (Exploring Embodied Emotion) | 2024 | 50+ h | Emotion, multimodal ego | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/d611d5c0251d9680f869c5d2c46c6fcd-Abstract-Datasets_and_Benchmarks_Track.html) | [GitHub](https://github.com/Exploring-Embodied-Emotion-official/E3) |
| EGOFALLS | 2023 | Fall samples / AV | Fall detection | [Paper](https://arxiv.org/abs/2309.04579) | [Site](https://www.dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/HO5GE3) |
| Epic-Sounding-Object | 2023 | 3.2K short clips | Audio-visual localization | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Huang_Egocentric_Audio-Visual_Object_Localization_CVPR_2023_paper.html) | [GitHub](https://github.com/WikiChao/Ego-AV-Loc) |
| HoloAssist | 2023 | 169 h | Interactive assistants | [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_HoloAssist_an_Egocentric_Human_Interaction_Dataset_for_Interactive_AI_Assistants_ICCV_2023_paper.html) | [Site](https://holoassist.github.io/) |
| WEAR | 2023 | ~19 h outdoor sports | Activity + IMU | [Paper](https://arxiv.org/abs/2304.05088) | [Site](https://mariusbock.github.io/wear/) |
| N-EPIC-KITCHENS | 2022 | Event + RGB subset | Action, neuromorphic | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Plizzari_E2GOMOTION_Motion_Augmented_Event_Stream_for_Egocentric_Action_Recognition_CVPR_2022_paper.html) | [GitHub](https://github.com/EgocentricVision/N-EPIC-Kitchens) |
| Ego-Deliver | 2021 | 5,360 videos | Delivery ego analysis | N/A | [Site](https://egodeliver.github.io/EgoDeliver_Dataset/) |
| HOMAGE | 2021 | 30 h / compositional | Home activities | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Rai_Home_Action_Genome_Cooperative_Compositional_Action_Understanding_CVPR_2021_paper.html) | [Site](https://homeactiongenome.org/) |
| MECCANO | 2021 | ~55 h industrial | HOI, ego | [Paper](https://openaccess.thecvf.com/content/WACV2021/html/Ragusa_The_MECCANO_Dataset_Understanding_Human-Object_Interactions_From_Egocentric_Videos_in_WACV_2021_paper.html) | [Site](https://iplab.dmi.unict.it/MECCANO/) |
| EGO-CH | 2020 | 27+ h, cultural sites | Visitor behavior, POI tasks | [Paper](https://arxiv.org/abs/2002.00899) | N/A |
| EgoCom | 2020 | 38.5 h conversation | Multiperson ego dialog | [Paper](https://doi.org/10.1109/TPAMI.2020.3025105) | [GitHub](https://github.com/facebookresearch/EgoCom-Dataset) |
| LEMMA | 2020 | Multi-view activities | Multi-agent tasks | [Paper](https://arxiv.org/abs/2007.15781) | [Site](https://sites.google.com/view/lemma-activity) |
| Charades-Ego | 2018 | Paired ego / exo | Alignment, actions | [Paper](https://arxiv.org/abs/1804.09626) | [Site](https://prior.allenai.org/projects/charades-ego) |
| EGTEA Gaze+ | 2018 | 28 h cooking | Gaze + action recognition | [Paper](https://openaccess.thecvf.com/content_ECCV_2018/html/Yin_Li_In_the_Eye_ECCV_2018_paper.html) | [Site](https://cbs.ic.gatech.edu/fpv/) |
| EgoGesture | 2017 | 2K+ videos / 24K samples | Gesture recognition | [Paper](https://doi.org/10.1109/TMM.2018.2808769) | [Site](https://nlpr.ia.ac.cn/iva/yfzhang/datasets/egogesture.html) |
| Stanford ECM | 2017 | 31 hours, augmented with heart rate and accelerometer, 23–24 daily activity categories | action & activity recognition | [Paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Nakamura_Jointly_Learning_Energy_CVPR_2017_paper.html) | N/A |
| THU-READ | 2017 | 1,920 clips (8 subjects × 40 actions × 3 reps × 2 modalities), RGB-D from helmet-mounted sensor | action & activity recognition | [Paper](https://doi.org/10.1109/ICIP.2017.8296915) | [Site](https://ivg.au.tsinghua.edu.cn/dataset/THU_READ.php) |
| PEV (UTokyo Paired Ego-Video) | 2016 | 1,226 pairs of first-person clips, synchronous dyadic conversations, 8 interaction categories, 6 subjects | action & activity recognition | [Paper](https://openaccess.thecvf.com/content_cvpr_2016/html/Yonetani_Recognizing_Micro-Actions_and_CVPR_2016_paper.html) | N/A |
| FPPA | 2015 | 5 subjects, 5 daily actions, egocentric video with hand and gaze cues | action & activity recognition | [Paper](https://openaccess.thecvf.com/content_iccv_2015/html/Zhou_Temporal_Perception_and_ICCV_2015_paper.html) | N/A |
| JPL-Interaction | 2013 | 84 videos, 7 activity types (4 positive, 1 neutral, 2 negative interactions), 320×240@30 fps | action & activity recognition | [Paper](https://openaccess.thecvf.com/content_cvpr_2013/html/Ryoo_First-Person_Activity_Recognition_2013_CVPR_paper.html) | [Site](http://michaelryoo.com/jpl-interaction.html) |
| ADL | 2012 | ~10 h, 20 participants | ADL recognition, objects | [Paper](https://doi.org/10.1109/CVPR.2012.6248010) | [Site](https://www.csee.umbc.edu/~hpirsiav/papers/ADLdataset/) |
| Social Interactions | 2012 | 8 social events, ~60 hours, head-mounted cameras, multiple participants per event | action & activity recognition | [Paper](https://doi.org/10.1109/CVPR.2012.6247805) | [Site](https://cbs.ic.gatech.edu/fpv/) |
| EgoAction | 2011 | First-person sports videos (skateboarding, skiing, cycling, etc | action & activity recognition | [Paper](https://doi.org/10.1109/CVPR.2011.5995406) | N/A |
| Ego-METAS | 2026 | 100+ h / 5 modalities | Online action segmentation, sensor routing | [Paper](https://arxiv.org/abs/2606.02246) | [HF](https://huggingface.co/datasets/Ego-METAS/Ego-METAS) |
| Furhat Egocentric Dataset | 2026 | 20 seq. / ~25 min | Robot-ego face/body tracking, re-ID | [Paper](https://arxiv.org/abs/2606.03694) | N/A |

### Entries

- [⭐️] **Ego4D** (2022) — ~3,670 h; AR, VQA, forecasting, many.
  [![arXiv](https://img.shields.io/badge/arXiv-2110.07058-b31b1b.svg)](https://arxiv.org/abs/2110.07058) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2110.07058) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/facebookresearch/Ego4d)

- [⭐️] **EPIC-KITCHENS-100** (2021) — 100 h of unscripted kitchen activity with 90K segments; the canonical egocentric action-recognition and anticipation benchmark.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://link.springer.com/article/10.1007/s11263-021-01531-2) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://epic-kitchens.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/epic-kitchens/epic-kitchens-100-annotations)

- **ChildLens** (2026) — 108.58 h of child-worn egocentric video and audio from 62 children for activity analysis in everyday home behavior.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://link.springer.com/article/10.3758/s13428-026-02982-6) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://www.eva.mpg.de/comparative-cultural-psychology/technical-development/childlens/) [![Data](https://img.shields.io/badge/Data-DOI-blue.svg)](https://doi.org/10.17617/4.fe)

- **EgoScale** (2026) — 20k+ h labeled manipulation (paper); Action, dexterous transfer.
  [![arXiv](https://img.shields.io/badge/arXiv-2602.16710-b31b1b.svg)](https://arxiv.org/abs/2602.16710) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2602.16710)

  **World In Your Hands** (2025) - 1000+ h of labeled human manipulation data; Action, Vision-Langauge Annotations; VLA traininig.
  [![arXiv](https://img.shields.io/badge/arXiv-2512.24310-b31b1b.svg)](https://arxiv.org/abs/2512.24310) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://wiyh.tars-ai.com/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/tars-robotics/World-In-Your-Hands) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/projectaria/aria-everyday-activities)

- **EgoCampus** (2025) — ~32 h / campus paths (paper); Gaze, pedestrian ego.
  [![arXiv](https://img.shields.io/badge/arXiv-2512.07668-b31b1b.svg)](https://arxiv.org/abs/2512.07668) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2512.07668) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/ComputerVisionRutgers/EgoCampus)

- **CogDrive (EyeCue)** (2026) — Augmented multi-scenario driving dataset paired with the EyeCue gaze-empowered ego-video framework for driver cognitive-distraction detection (reported 74.38% accuracy).
  [![arXiv](https://img.shields.io/badge/arXiv-2605.07859-b31b1b.svg)](https://arxiv.org/abs/2605.07859)

- **AEA** (2024) — 143 seq. / ~7.3 h; Everyday activities, Aria.
  [![arXiv](https://img.shields.io/badge/arXiv-2402.13349-b31b1b.svg)](https://arxiv.org/abs/2402.13349) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2402.13349) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/projectaria/aria-everyday-activities)

- **EgoSurgery (Phase / Tool / HTS)** (2024) — Open-surgery ego video with companion phase, tool, and hand-tool segmentation releases for phase recognition, instrument analysis, and dense surgical interaction understanding.
  [![arXiv](https://img.shields.io/badge/arXiv-2405.19644-b31b1b.svg)](https://arxiv.org/abs/2405.19644) [![arXiv](https://img.shields.io/badge/arXiv-2406.03095-b31b1b.svg)](https://arxiv.org/abs/2406.03095) [![arXiv](https://img.shields.io/badge/arXiv-2503.18755-b31b1b.svg)](https://arxiv.org/abs/2503.18755) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Fujiry0/EgoSurgery)

- **EgoExo-Fitness** (2024) — 32 h of synchronized egocentric and exocentric fitness video with temporal boundaries, sub-step annotations, action comments, and quality scores for full-body action understanding.
  [![arXiv](https://img.shields.io/badge/arXiv-2406.08877-b31b1b.svg)](https://arxiv.org/abs/2406.08877) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/iSEE-Laboratory/EgoExo-Fitness) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/Lymann/EgoExo-Fitness)

- **E³ (Exploring Embodied Emotion)** (2024) — 50+ h; Emotion, multimodal ego.
  [![Paper](https://img.shields.io/badge/Paper-NeurIPS24-b31b1b.svg)](https://proceedings.neurips.cc/paper_files/paper/2024/hash/d611d5c0251d9680f869c5d2c46c6fcd-Abstract-Datasets_and_Benchmarks_Track.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Exploring-Embodied-Emotion-official/E3)

- **EGOFALLS** (2023) — Fall samples / AV; Fall detection.
  [![arXiv](https://img.shields.io/badge/arXiv-2309.04579-b31b1b.svg)](https://arxiv.org/abs/2309.04579) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://www.dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/HO5GE3)

- **Epic-Sounding-Object** (2023) — 3.2K short clips; Audio-visual localization.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2023/html/Huang_Egocentric_Audio-Visual_Object_Localization_CVPR_2023_paper.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/WikiChao/Ego-AV-Loc)

- **HoloAssist** (2023) — 169 h; Interactive assistants.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_HoloAssist_an_Egocentric_Human_Interaction_Dataset_for_Interactive_AI_Assistants_ICCV_2023_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_HoloAssist_an_Egocentric_Human_Interaction_Dataset_for_Interactive_AI_Assistants_ICCV_2023_paper.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Ember-HoloAssist/holoassist-release)

- **WEAR** (2023) — ~19 h outdoor sports; Activity + IMU.
  [![arXiv](https://img.shields.io/badge/arXiv-2304.05088-b31b1b.svg)](https://arxiv.org/abs/2304.05088) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://mariusbock.github.io/wear/)

- **N-EPIC-KITCHENS** (2022) — Event + RGB subset; Action, neuromorphic.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2022/html/Plizzari_E2GOMOTION_Motion_Augmented_Event_Stream_for_Egocentric_Action_Recognition_CVPR_2022_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://openaccess.thecvf.com/content/CVPR2022/html/Plizzari_E2GOMOTION_Motion_Augmented_Event_Stream_for_Egocentric_Action_Recognition_CVPR_2022_paper.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/EgocentricVision/N-EPIC-Kitchens)

- **Ego-Deliver** (2021) — 5,360 videos; Delivery ego analysis.
  [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://egodeliver.github.io/EgoDeliver_Dataset/)

- **HOMAGE** (2021) — 30 h / compositional; Home activities.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2021/html/Rai_Home_Action_Genome_Cooperative_Compositional_Action_Understanding_CVPR_2021_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://openaccess.thecvf.com/content/CVPR2021/html/Rai_Home_Action_Genome_Cooperative_Compositional_Action_Understanding_CVPR_2021_paper.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/nishantrai18/homage)

- **MECCANO** (2021) — ~55 h industrial; HOI, ego.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/WACV2021/html/Ragusa_The_MECCANO_Dataset_Understanding_Human-Object_Interactions_From_Egocentric_Videos_in_WACV_2021_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://iplab.dmi.unict.it/MECCANO/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/fpv-iplab/MECCANO)

- **EGO-CH** (2020) — 27+ h, cultural sites; Visitor behavior, POI tasks.
  [![arXiv](https://img.shields.io/badge/arXiv-2002.00899-b31b1b.svg)](https://arxiv.org/abs/2002.00899)

- **EgoCom** (2020) — 38.5 h conversation; Multiperson ego dialog.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.1109/TPAMI.2020.3025105) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/facebookresearch/EgoCom-Dataset)

- **LEMMA** (2020) — Multi-view activities; Multi-agent tasks.
  [![arXiv](https://img.shields.io/badge/arXiv-2007.15781-b31b1b.svg)](https://arxiv.org/abs/2007.15781) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://sites.google.com/view/lemma-activity) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Buzz-Beater/LEMMA)

- **Charades-Ego** (2018) — Paired ego / exo; Alignment, actions.
  [![arXiv](https://img.shields.io/badge/arXiv-1804.09626-b31b1b.svg)](https://arxiv.org/abs/1804.09626) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/1804.09626)

- **EGTEA Gaze+** (2018) — 28 h cooking; Gaze + action recognition.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_ECCV_2018/html/Yin_Li_In_the_Eye_ECCV_2018_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://cbs.ic.gatech.edu/fpv/)

- **EgoGesture** (2017) — 2K+ videos / 24K samples; Gesture recognition.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.1109/TMM.2018.2808769) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://nlpr.ia.ac.cn/iva/yfzhang/datasets/egogesture.html)

- **Stanford ECM** (2017) — 31 hours, augmented with heart rate and accelerometer, 23–24 daily activity categories; action & activity recognition.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2017/html/Nakamura_Jointly_Learning_Energy_CVPR_2017_paper.html)

- **THU-READ** (2017) — 1,920 clips (8 subjects × 40 actions × 3 reps × 2 modalities), RGB-D from helmet-mounted sensor; action & activity recognition.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.1109/ICIP.2017.8296915) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://ivg.au.tsinghua.edu.cn/dataset/THU_READ.php)

- **PEV (UTokyo Paired Ego-Video)** (2016) — 1,226 pairs of first-person clips, synchronous dyadic conversations, 8 interaction categories, 6 subjects; action & activity recognition.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2016/html/Yonetani_Recognizing_Micro-Actions_and_CVPR_2016_paper.html)

- **FPPA** (2015) — 5 subjects, 5 daily actions, egocentric video with hand and gaze cues; action & activity recognition.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_iccv_2015/html/Zhou_Temporal_Perception_and_ICCV_2015_paper.html)

- **JPL-Interaction** (2013) — 84 videos, 7 activity types (4 positive, 1 neutral, 2 negative interactions), 320×240@30 fps; action & activity recognition.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2013/html/Ryoo_First-Person_Activity_Recognition_2013_CVPR_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](http://michaelryoo.com/jpl-interaction.html)

- **ADL** (2012) — ~10 h, 20 participants; ADL recognition, objects.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.1109/CVPR.2012.6248010) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://www.csee.umbc.edu/~hpirsiav/papers/ADLdataset/)

- **Social Interactions** (2012) — 8 social events, ~60 hours, head-mounted cameras, multiple participants per event; action & activity recognition.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.1109/CVPR.2012.6247805) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://cbs.ic.gatech.edu/fpv/)

- **EgoAction** (2011) — First-person sports videos (skateboarding, skiing, cycling, etc; action & activity recognition.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.1109/CVPR.2011.5995406)

- **Ego-METAS** (2026) — 100+ h of untrimmed multimodal egocentric video (RGB, audio, gaze, IMU, monochrome) curated from Ego-Exo4D, CMU-MMAC, and CaptainCook4D with unified splits, pre-extracted features, and baseline sensor-routing policies for online energy-efficient temporal action segmentation.
  [![arXiv](https://img.shields.io/badge/arXiv-2606.02246-b31b1b.svg)](https://arxiv.org/abs/2606.02246) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://maria-sanvil.github.io/Ego-METAS-website/) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/Ego-METAS/Ego-METAS)

- **Furhat Egocentric Dataset** (2026) — 20 sequences (~25 min) of close-range multi-party interactions captured from a Furhat social robot's egocentric camera with amodal face/body boxes and consistent identities for multi-person tracking and re-identification in HRI; available on request under a Data Usage Agreement.
  [![arXiv](https://img.shields.io/badge/arXiv-2606.03694-b31b1b.svg)](https://arxiv.org/abs/2606.03694)

- *Ego-Exo4D — see [3D Scene Understanding & Localization](#-3d-scene-understanding--localization)*
- *EgoExoLearn — see [Procedural Activities & Skill Learning](#-procedural-activities--skill-learning)*

### Benchmarks built on these datasets

| Benchmark | Capability | Primary data | Official link | Notes |
|-----------|------------|--------------|---------------|-------|
| E³ (Exploring Embodied Emotion) | Emotion recognition, classification, localization, reasoning | E³ | [GitHub](https://github.com/Exploring-Embodied-Emotion-official/E3) | Standalone |
| EGOFALLS | Fall detection (visual + audio) | EGOFALLS | [Dataverse](https://www.dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/HO5GE3) | Standalone |
| EgoExo-Fitness | Action localization, cross-view verification, skill determination | EgoExo-Fitness | [GitHub](https://github.com/iSEE-Laboratory/EgoExo-Fitness) | Dataset+benchmark |
| Ego4D | Action, forecasting, VQA, narration, … | Ego4D | [Site](https://ego4d-data.org/) | Suite |
| EPIC-KITCHENS-100 | Action recognition, detection, anticipation, … | EPIC-KITCHENS-100 | [Site](https://epic-kitchens.github.io/) | Suite |
| EgoGesture | Egocentric hand gesture recognition | EgoGesture | [Site](https://nlpr.ia.ac.cn/iva/yfzhang/datasets/egogesture.html) | Standalone |
| Ego-METAS | Online energy-efficient temporal action segmentation | Ego-Exo4D / CMU-MMAC / CaptainCook4D | [HF](https://huggingface.co/datasets/Ego-METAS/Ego-METAS) | Standalone |

## ✋ Hand–Object Interaction, Dexterity & 3D

> This section focuses on egocentric hands, dexterous manipulation, object interaction, tracking, and dense 3D understanding around the body and manipulated objects.

### Datasets at a glance

| Name | Year | Scale | Key tasks | Paper | Link |
|------|------|-------|-----------|-------|------|
| ⭐ AssemblyHands | 2023 | 3M images / hands | 3D hand pose, assembly | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Ohkawa_AssemblyHands_Towards_Egocentric_Activity_Understanding_via_3D_Hand_Pose_Estimation_CVPR_2023_paper.html) | [Site](https://assemblyhands.github.io/) |
| ⭐ HOI4D | 2022 | 2.4M frames / 4K seq. | 4D HOI | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_HOI4D_A_4D_Egocentric_Dataset_for_Category-Level_Human-Object_Interaction_CVPR_2022_paper.html) | [Site](https://hoi4d.github.io/) |
| ⭐ FPHA | 2018 | 1.2K seq. hand action | Hand pose + action | [Paper](https://openaccess.thecvf.com/content_cvpr_2018/html/Garcia-Hernando_First-Person_Hand_Action_CVPR_2018_paper.html) | [Site](https://guiggh.github.io/publications/first-person-hands/) |
| EgoTouch | 2026 | 1,891 episodes / 208 tasks | Tactile HOI, vision-to-touch | [Paper](https://arxiv.org/abs/2605.13083) | [HF](https://huggingface.co/datasets/zhenyuxie-zhzh/EgoTouch_hdf5) |
| DexGloveHOI | 2026 | 3.5 h / 100K+ samples | Vision-IMU 3D hand tracking | [Paper](https://arxiv.org/abs/2605.21714) | N/A |
| EgoEVHands | 2026 | 5,419 annotated seq. | Stereo event 3D hand pose, gesture | [Paper](https://arxiv.org/abs/2605.12297) | [GitHub](https://github.com/ZJUWang01/EgoEV-HandPose) |
| HRDexDB | 2026 | 1.4K grasping trials | Dexterous grasping, tactile, ego streams | [Paper](https://arxiv.org/abs/2604.14944) | [HF](https://huggingface.co/datasets/hahahataeyun/hrdexdb) |
| TouchMoment | 2026 | 4,021 videos / 8,456 touch moments | Contact moment detection | [Paper](https://arxiv.org/abs/2604.12343) | N/A |
| EgoFun3D | 2026 | 271 egocentric videos | Interactive 3D objects, function templates | [Paper](https://arxiv.org/abs/2604.11038) | [Site](https://3dlg-hcvc.github.io/EgoFun3D/) |
| SHOW3D | 2026 | In-the-wild ego-exo HOI | 3D hand-object annotations | [Paper](https://arxiv.org/abs/2603.28760) | N/A |
| FEEL | 2026 | Force-sync kitchen ego video | Physical action understanding | [Paper](https://arxiv.org/abs/2603.15847) | [Site](https://www.cs.umd.edu/~edessale/feel) |
| EgoEMG | 2026 | 41 participants / 10+ h | EMG + vision hand pose | [Paper](https://arxiv.org/abs/2605.05712) | [GitHub](https://github.com/zhenqis123/EgoEMG) |
| EgoDex | 2025 | 829 h / 30K trajectories | Dexterous manipulation, pose | [Paper](https://arxiv.org/abs/2505.11709) | [GitHub](https://github.com/apple/ml-egodex) |
| EgoPoints | 2025 | Point tracks + synthetic | Tracking in ego video | [Paper](https://arxiv.org/abs/2412.04592) | [GitHub](https://github.com/AhmadDarKhalil/EgoPoints) |
| EgoObjects | 2023 | 9.2K+ videos | Detection, instance seg | [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Zhu_EgoObjects_A_Large-Scale_Egocentric_Dataset_for_Fine-Grained_Object_Understanding_ICCV_2023_paper.html) | [GitHub](https://github.com/facebookresearch/EgoObjects) |
| ENIGMA-51 | 2023 | 22 h industrial | Fine-grained behavior | [Paper](https://arxiv.org/abs/2309.14809) | [Site](https://fpv-iplab.github.io/ENIGMA-51/) |
| POV-Surgery | 2023 | ~88K frames, 53 seq. (synth.) | Surgical hand–tool pose, segmentation | [Paper](https://arxiv.org/abs/2307.10387) | [Site](https://batfacewayne.github.io/POV_Surgery_io/) |
| VOST | 2023 | 713 videos | VOS, transforming objects | [Paper](https://arxiv.org/abs/2212.06200) | [Site](https://www.vostdataset.org/) |
| EgoBody | 2022 | 125 seq. / multi-view | Body pose, interaction | [Paper](https://arxiv.org/abs/2112.07642) | [Site](https://egobody.ethz.ch/) |
| EgoHOS | 2022 | 11K+ images | Hand–object segmentation | [Paper](https://arxiv.org/abs/2208.03826) | [GitHub](https://github.com/owenzlz/EgoHOS) |
| EgoPAT3D | 2022 | 1M+ frames RGB-D | 3D action target prediction | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Egocentric_Prediction_of_Action_Target_in_3D_CVPR_2022_paper.html) | [Site](https://ai4ce.github.io/EgoPAT3D/) |
| Touch and Go | 2022 | 12K+ vis–tactile frames | Vision + touch | [Paper](https://arxiv.org/abs/2211.12498) | [Site](https://touch-and-go.github.io/) |
| VISOR | 2022 | EPIC + masks / relations | Segmentation, HOI | [Paper](https://arxiv.org/abs/2209.13064) | [Site](https://epic-kitchens.github.io/VISOR) |
| H2O | 2021 | 100K+ frames | Two-hand interaction | [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Kwon_H2O_Two_Hands_Manipulating_Objects_for_First_Person_Interaction_Recognition_ICCV_2021_paper.html) | [Site](https://h2odataset.ethz.ch/) |
| TREK-150 | 2021 | 150 EPIC seq. | Object tracking | [Paper](https://arxiv.org/abs/2108.13665) | [Site](https://machinelearning.uniud.it/datasets/trek150/) |
| You2Me | 2020 | 14 seq., chest-mounted GoPro | Body pose via ego–exo interaction | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Ng_You2Me_Inferring_Body_Pose_in_Egocentric_Video_via_First_and_CVPR_2020_paper.html) | [GitHub](https://github.com/facebookresearch/you2me) |
| EgoDexter | 2017 | ~3.2K frames, 4 seq. | Hand tracking under occlusion | [Paper](https://arxiv.org/abs/1704.02201) | [Site](https://handtracker.mpi-inf.mpg.de/projects/OccludedHands/EgoDexter.htm) |
| EgoHands | 2015 | 4.8K labeled frames | Hand detection / boxes | [Paper](https://openaccess.thecvf.com/content_iccv_2015/html/Bambach_Lending_A_Hand_ICCV_2015_paper.html) | [Site](http://vision.soic.indiana.edu/projects/egohands/) |
| BEOID | 2014 | 58 videos, 6 environments, 34 object interaction classes, ~30 fps | hand–object interaction, dexterity & 3d | [Paper](https://doi.org/10.5244/C.28.30) | [Site](https://data.bris.ac.uk/data/dataset/3wats8ruq1sp52hq3bo8dkzul3) |
| EDSH | 2013 | 2 videos (~5 min each), pixel-level hand segmentation, egocentric daily activities | hand–object interaction, dexterity & 3d | [Paper](https://openaccess.thecvf.com/content_cvpr_2013/html/Li_Pixel-Level_Hand_Detection_2013_CVPR_paper.html) | [Site](http://www.cs.cmu.edu/~kkitani/datasets/) |
| Handled Objects | 2009 | 11 object categories, multiple grasp sequences, RGB + depth from wearable camera | hand–object interaction, dexterity & 3d | [Paper](https://doi.org/10.1109/CVPRW.2009.5204360) | N/A |
| EventEgoHands | 2026 | 48 clips / 129.6K frames | RGB+event hand detection | [Paper](https://arxiv.org/abs/2606.10790) | [GitHub](https://github.com/SynthSyntax/EventEgoHands) |
| EgoTactile | 2026 | ~6 h / 768 clips / 63 objects | Grasp pressure from ego video | [Paper](https://arxiv.org/abs/2606.09243) | [Site](https://egotactile.github.io/) |
| EgoDex-R | 2026 | 4.3M RGB-D frames / 5.6K seq. | Dexterous manipulation, hand-object pose | [Paper](https://arxiv.org/abs/2606.08057) | N/A |
| HA-Ego-1K | 2026 | ~24 h / 484 multi-view clips | Manipulation, 6-cam ego + IMU | N/A | [HF](https://huggingface.co/datasets/humanarchive/HA-Ego-1K) |

### Entries

- [⭐️] **AssemblyHands** (2023) — 3M egocentric hand images on top of Assembly101 for detailed 3D hand pose estimation during assembly.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2023/html/Ohkawa_AssemblyHands_Towards_Egocentric_Activity_Understanding_via_3D_Hand_Pose_Estimation_CVPR_2023_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://openaccess.thecvf.com/content/CVPR2023/html/Ohkawa_AssemblyHands_Towards_Egocentric_Activity_Understanding_via_3D_Hand_Pose_Estimation_CVPR_2023_paper.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/facebookresearch/assemblyhands-toolkit)

- [⭐️] **HOI4D** (2022) — 2.4M RGB-D frames with object poses, hand poses, interaction regions, and motion segmentation for category-level 4D HOI.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_HOI4D_A_4D_Egocentric_Dataset_for_Category-Level_Human-Object_Interaction_CVPR_2022_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_HOI4D_A_4D_Egocentric_Dataset_for_Category-Level_Human-Object_Interaction_CVPR_2022_paper.html)

- [⭐️] **FPHA** (2018) — 1,175 RGB-D sequences with 3D hand pose and action labels; a foundational first-person hand-action benchmark.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2018/html/Garcia-Hernando_First-Person_Hand_Action_CVPR_2018_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://openaccess.thecvf.com/content_cvpr_2018/html/Garcia-Hernando_First-Person_Hand_Action_CVPR_2018_paper.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/guiggh/hand_pose_action)

- **EgoTouch** (2026) — 1,891 bimanual hand-object interaction episodes across 208 manipulation tasks with synchronized egocentric and wrist RGB video, 3D hand pose, and dense tactile pressure maps.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.13083-b31b1b.svg)](https://arxiv.org/abs/2605.13083) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://jianyi2004.github.io/TouchAnything-Website/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Jianyi2004/TouchAnything) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/zhenyuxie-zhzh/EgoTouch_hdf5)

- **DexGloveHOI** (2026) — 3.5 h / 100K+ synchronized egocentric vision-IMU samples with MoCap 3D hand-pose ground truth for dexterous hand-object interaction tracking; no official public data page was found.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.21714-b31b1b.svg)](https://arxiv.org/abs/2605.21714)

- **EgoEVHands** (2026) — 5,419 real-world stereo event-camera egocentric sequences with dense 2D/3D hand keypoints across 38 gesture classes; the official repository currently says code, models, and dataset links are to be uploaded.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.12297-b31b1b.svg)](https://arxiv.org/abs/2605.12297) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/ZJUWang01/EgoEV-HandPose)

- **HRDexDB** (2026) — 1.4K dexterous human and robotic hand grasping trials with synchronized multi-view video, egocentric video streams, tactile signals, and 3D motion.
  [![arXiv](https://img.shields.io/badge/arXiv-2604.14944-b31b1b.svg)](https://arxiv.org/abs/2604.14944) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/hahahataeyun/hrdexdb)

- **TouchMoment** (2026) — 4,021 egocentric videos with 8,456 annotated hand-object contact moments for frame-precise touch detection.
  [![arXiv](https://img.shields.io/badge/arXiv-2604.12343-b31b1b.svg)](https://arxiv.org/abs/2604.12343)

- **EgoFun3D** (2026) — 271 egocentric interaction videos with paired 3D geometry, 2D/3D segmentation, articulation labels, and function-template annotations.
  [![arXiv](https://img.shields.io/badge/arXiv-2604.11038-b31b1b.svg)](https://arxiv.org/abs/2604.11038) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://3dlg-hcvc.github.io/EgoFun3D/) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/3dlg-hcvc/EgoFun3D)

- **SHOW3D** (2026) — In-the-wild ego-exo capture of hands interacting with objects, with 3D hand-object annotations from a marker-less multi-camera system.
  [![arXiv](https://img.shields.io/badge/arXiv-2603.28760-b31b1b.svg)](https://arxiv.org/abs/2603.28760)

- **FEEL** (2026) — Force-sync kitchen ego video; Physical action understanding.
  [![arXiv](https://img.shields.io/badge/arXiv-2603.15847-b31b1b.svg)](https://arxiv.org/abs/2603.15847) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2603.15847)

- **EgoEMG** (2026) — 10+ h of synchronized bilateral EMG, IMU, egocentric RGB, external RGB-D, and mocap-derived hand pose across 41 participants and 60 gesture classes.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.05712-b31b1b.svg)](https://arxiv.org/abs/2605.05712) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/zhenqis123/EgoEMG)

- **EgoDex** (2025) — 829 h / 30K trajectories; Dexterous manipulation, pose.
  [![arXiv](https://img.shields.io/badge/arXiv-2505.11709-b31b1b.svg)](https://arxiv.org/abs/2505.11709) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2505.11709) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/apple/ml-egodex)

- **EgoPoints** (2025) — Point tracks + synthetic; Tracking in ego video.
  [![arXiv](https://img.shields.io/badge/arXiv-2412.04592-b31b1b.svg)](https://arxiv.org/abs/2412.04592) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2412.04592) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/AhmadDarKhalil/EgoPoints)

- **EgoObjects** (2023) — 9.2K+ videos; Detection, instance seg.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/ICCV2023/html/Zhu_EgoObjects_A_Large-Scale_Egocentric_Dataset_for_Fine-Grained_Object_Understanding_ICCV_2023_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://openaccess.thecvf.com/content/ICCV2023/html/Zhu_EgoObjects_A_Large-Scale_Egocentric_Dataset_for_Fine-Grained_Object_Understanding_ICCV_2023_paper.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/facebookresearch/EgoObjects)

- **ENIGMA-51** (2023) — 22 h industrial; Fine-grained behavior.
  [![arXiv](https://img.shields.io/badge/arXiv-2309.14809-b31b1b.svg)](https://arxiv.org/abs/2309.14809) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://fpv-iplab.github.io/ENIGMA-51/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/fpv-iplab/ENIGMA-51)

- **POV-Surgery** (2023) — ~88K frames, 53 seq. (synth.); Surgical hand–tool pose, segmentation.
  [![arXiv](https://img.shields.io/badge/arXiv-2307.10387-b31b1b.svg)](https://arxiv.org/abs/2307.10387) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://batfacewayne.github.io/POV_Surgery_io/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/BatFaceWayne/POV_Surgery)

- **VOST** (2023) — 713 videos; VOS, transforming objects.
  [![arXiv](https://img.shields.io/badge/arXiv-2212.06200-b31b1b.svg)](https://arxiv.org/abs/2212.06200) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://www.vostdataset.org/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/yka-dl/VOST)

- **EgoBody** (2022) — 125 seq. / multi-view; Body pose, interaction.
  [![arXiv](https://img.shields.io/badge/arXiv-2112.07642-b31b1b.svg)](https://arxiv.org/abs/2112.07642) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://egobody.ethz.ch/)

- **EgoHOS** (2022) — 11K+ images; Hand–object segmentation.
  [![arXiv](https://img.shields.io/badge/arXiv-2208.03826-b31b1b.svg)](https://arxiv.org/abs/2208.03826) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/owenzlz/EgoHOS)

- **EgoPAT3D** (2022) — 1M+ frames RGB-D; 3D action target prediction.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Egocentric_Prediction_of_Action_Target_in_3D_CVPR_2022_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Egocentric_Prediction_of_Action_Target_in_3D_CVPR_2022_paper.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/ai4ce/EgoPAT3D)

- **Touch and Go** (2022) — 12K+ vis–tactile frames; Vision + touch.
  [![arXiv](https://img.shields.io/badge/arXiv-2211.12498-b31b1b.svg)](https://arxiv.org/abs/2211.12498) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://touch-and-go.github.io/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/fredfyyang/Touch-and-Go)

- **VISOR** (2022) — EPIC + masks / relations; Segmentation, HOI.
  [![arXiv](https://img.shields.io/badge/arXiv-2209.13064-b31b1b.svg)](https://arxiv.org/abs/2209.13064) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://epic-kitchens.github.io/VISOR) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/epic-kitchens/VISOR)

- **H2O** (2021) — 100K+ frames; Two-hand interaction.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/ICCV2021/html/Kwon_H2O_Two_Hands_Manipulating_Objects_for_First_Person_Interaction_Recognition_ICCV_2021_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://openaccess.thecvf.com/content/ICCV2021/html/Kwon_H2O_Two_Hands_Manipulating_Objects_for_First_Person_Interaction_Recognition_ICCV_2021_paper.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/taeinkwon/h2odataset)

- **TREK-150** (2021) — 150 EPIC seq; Object tracking.
  [![arXiv](https://img.shields.io/badge/arXiv-2108.13665-b31b1b.svg)](https://arxiv.org/abs/2108.13665) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://machinelearning.uniud.it/datasets/trek150/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/matteo-dunnhofer/TREK-150-toolkit)

- **You2Me** (2020) — 14 seq., chest-mounted GoPro; Body pose via ego–exo interaction.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_CVPR_2020/html/Ng_You2Me_Inferring_Body_Pose_in_Egocentric_Video_via_First_and_CVPR_2020_paper.html) [![arXiv](https://img.shields.io/badge/arXiv-1904.09882-b31b1b.svg)](https://arxiv.org/abs/1904.09882) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/facebookresearch/you2me)

- **EgoDexter** (2017) — ~3.2K frames, 4 seq; Hand tracking under occlusion.
  [![arXiv](https://img.shields.io/badge/arXiv-1704.02201-b31b1b.svg)](https://arxiv.org/abs/1704.02201) [![Project](https://img.shields.io/badge/Project-Link-blue.svg)](https://handtracker.mpi-inf.mpg.de/projects/OccludedHands/EgoDexter.htm)

- **EgoHands** (2015) — 4.8K labeled frames; Hand detection / boxes.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_iccv_2015/html/Bambach_Lending_A_Hand_ICCV_2015_paper.html) [![Project](https://img.shields.io/badge/Project-Link-blue.svg)](http://vision.soic.indiana.edu/projects/egohands/)

- **BEOID** (2014) — 58 videos, 6 environments, 34 object interaction classes, ~30 fps; hand–object interaction, dexterity & 3d.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.5244/C.28.30) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://data.bris.ac.uk/data/dataset/3wats8ruq1sp52hq3bo8dkzul3)

- **EDSH** (2013) — 2 videos (~5 min each), pixel-level hand segmentation, egocentric daily activities; hand–object interaction, dexterity & 3d.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2013/html/Li_Pixel-Level_Hand_Detection_2013_CVPR_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](http://www.cs.cmu.edu/~kkitani/datasets/)

- **Handled Objects** (2009) — 11 object categories, multiple grasp sequences, RGB + depth from wearable camera; hand–object interaction, dexterity & 3d.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.1109/CVPRW.2009.5204360)

- **EventEgoHands** (2026) — 48 egocentric clips (~1.2 h, 129.6K frames) pairing RGB with synthetic event streams (synthesized from EgoHands via v2e) and 393K hand bounding boxes for RGB-event hand detection under motion blur and low light.
  [![arXiv](https://img.shields.io/badge/arXiv-2606.10790-b31b1b.svg)](https://arxiv.org/abs/2606.10790) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/SynthSyntax/EventEgoHands)

- **EgoTactile** (2026) — ~6 h (768 clips, 319K frames) of head- and neck-mounted egocentric video of 12 participants grasping 63 everyday objects with synchronized 162-taxel pressure-glove supervision and a bare-hand transfer subset for full-hand grasp pressure estimation; the dataset currently sits under an anonymous ICML-submission account.
  [![arXiv](https://img.shields.io/badge/arXiv-2606.09243-b31b1b.svg)](https://arxiv.org/abs/2606.09243) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://egotactile.github.io/) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/icml-2026-submission/EgoTactile)

- **EgoDex-R** (2026) — 4.3M egocentric RGB-D frames across 5,600 manipulation sequences (1,000+ objects, 200+ daily task categories) with MANO hand poses, 6-DoF object trajectories, reconstructed meshes, and contact annotations, introduced in the EgoAERO paper; distinct from Apple's EgoDex.
  [![arXiv](https://img.shields.io/badge/arXiv-2606.08057-b31b1b.svg)](https://arxiv.org/abs/2606.08057)

- **HA-Ego-1K** (2026) — ~24 h of privacy-redacted six-camera + IMU egocentric video (484 multi-view clips across 22 real-world work scenarios such as workshops, construction, and factories) captured with the head-worn Human Archive GSI Cap for dexterous-manipulation and long-horizon task research; gated access (CC BY-NC 4.0), no paper yet.
  [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://humanarchive.ai) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/humanarchive/HA-Ego-1K)

### Benchmarks built on these datasets

| Benchmark | Capability | Primary data | Official link | Notes |
|-----------|------------|--------------|---------------|-------|
| TouchMoment | Frame-precise hand-object contact moment detection | TouchMoment | [Paper](https://arxiv.org/abs/2604.12343) | Standalone |
| EgoFun3D | Interactive 3D object modeling and function-template inference | EgoFun3D | [Site](https://3dlg-hcvc.github.io/EgoFun3D/) | Dataset+benchmark |
| EgoEMG | EMG-to-pose, vision-to-pose, and EMG+vision fusion | EgoEMG | [GitHub](https://github.com/zhenqis123/EgoEMG) | Dataset+benchmark |
| EgoTouch / TouchAnything | Vision-to-touch prediction for bimanual HOI | EgoTouch | [HF](https://huggingface.co/datasets/zhenyuxie-zhzh/EgoTouch_hdf5) | Dataset+benchmark |
| DexGloveHOI | Vision-IMU 3D hand tracking under HOI occlusion | DexGloveHOI | [Paper](https://arxiv.org/abs/2605.21714) | Dataset+benchmark |
| EgoEVHands | Stereo event 3D hand pose and gesture recognition | EgoEVHands | [GitHub](https://github.com/ZJUWang01/EgoEV-HandPose) | Dataset+benchmark |
| AssemblyHands | Egocentric 3D hand pose | Assembly101 | [Site](https://assemblyhands.github.io/) | Standalone |
| VISOR | Video object segmentation, hand–object relations | EPIC-KITCHENS | [Site](https://epic-kitchens.github.io/VISOR) | Standalone |
| TREK-150 | Egocentric single-object tracking | EPIC-KITCHENS | [Site](https://machinelearning.uniud.it/datasets/trek150/) | Standalone |
| EggHand | Egocentric 3D hand pose forecasting | EgoExo4D | [Paper](https://arxiv.org/abs/2605.07642) | Method benchmark |
| FPHA | Hand action + 3D hand pose | FPHA | [Site](https://guiggh.github.io/publications/first-person-hands/) | Standalone |
| EgoTactile | Full-hand grasp pressure estimation from ego video | EgoTactile | [Site](https://egotactile.github.io/) | Dataset+benchmark |
| EventEgoHands | Multimodal RGB-event egocentric hand detection | EventEgoHands (from EgoHands) | [GitHub](https://github.com/SynthSyntax/EventEgoHands) | Dataset+benchmark |

## 📋 Procedural Activities & Skill Learning

> Datasets centered on step structure, instructional execution, assembly, or skill transfer from egocentric experience are grouped here.

### Datasets at a glance

| Name | Year | Scale | Key tasks | Paper | Link |
|------|------|-------|-----------|-------|------|
| EgoVerse | 2026 | 1,362 h / ~80K episodes | Robot learning, manipulation skills | [Paper](https://arxiv.org/abs/2604.07607) | [Site](https://egoverse.ai/) |
| EgoLive | 2026 | Large-scale real-world task routines | Robot manipulation learning | [Paper](https://arxiv.org/abs/2604.23570) | N/A |
| EgoMAGIC | 2026 | 3,355 videos / 50 medical tasks | Field medicine, action detection | [Paper](https://arxiv.org/abs/2604.22036) | [Zenodo](https://doi.org/10.5281/zenodo.19239154) |
| HumanEgo | 2026 | Minutes-per-task Aria demonstrations | Human-to-robot policy learning | [Paper](https://arxiv.org/abs/2605.24934) | [Site](https://humanego-ai.github.io/) |
| EgoSPT | 2026 | 11,515 episodes / 112 task folders | Spatially prompted manipulation trajectories | [Paper](https://arxiv.org/abs/2605.20085) | [HF](https://huggingface.co/datasets/JackYFL233/EgoSPT) |
| Ego-EXTRA | 2026 | 50 h / 15K+ VQA | Expert-trainee assistance | [Paper](https://openaccess.thecvf.com/content/WACV2026/html/Ragusa_Ego-EXTRA_video-language_Egocentric_Dataset_for_EXpert-TRAinee_assistance_WACV_2026_paper.html) | [Site](https://fpv-iplab.github.io/Ego-EXTRA/) |
| GM-100 | 2026 | 100+ tasks / 13K+ trajectories | Robot manipulation, embodied evaluation | [Paper](https://arxiv.org/abs/2601.11421) | [Site](https://www.rhos.ai/research/gm-100) |
| SABER | 2026 | 100+ h / 44.8K samples | Retail VLA adaptation | [Paper](https://arxiv.org/abs/2605.09613) | [Site](https://dreamvu.ai/saber/) |
| EgoYC2 / Exo2EgoDVC | 2025 | ~43 h cooking | Dense captioning, procedural | [Paper](https://arxiv.org/abs/2311.16444) | [GitHub](https://github.com/ut-vision/Exo2EgoDVC) |
| EgoExoLearn | 2024 | 120 h ego+exo | Procedural, async views | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_EgoExoLearn_A_Dataset_for_Bridging_Asynchronous_Ego-_and_Exo-centric_View_CVPR_2024_paper.html) | [GitHub](https://github.com/OpenGVLab/EgoExoLearn) |
| IndustReal | 2024 | ~6 h industrial | Procedure steps, errors | [Paper](https://openaccess.thecvf.com/content/WACV2024/html/Schoonbeek_IndustReal_A_Dataset_for_Procedure_Step_Recognition_Handling_Execution_Errors_WACV_2024_paper.html) | [Site](https://timschoonbeek.github.io/industreal.html) |
| Assembly101 | 2022 | 513 h multiview | Assembly, procedure | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Sener_Assembly101_A_Large-Scale_Multi-View_Video_Dataset_for_Understanding_Procedural_Activities_CVPR_2022_paper.html) | [Site](https://assembly-101.github.io/) |
| EgoProceL | 2022 | 62 videos / 16 tasks | Procedure learning | [Paper](https://arxiv.org/abs/2207.10883) | [Site](https://sid2697.github.io/egoprocel/) |
| EPIC-Tent | 2019 | 7+ h, tent assembly | Procedural, dual HMD + gaze | [Paper](https://openaccess.thecvf.com/content_ICCVW_2019/html/EPIC/Jang_EPIC-Tent_An_Egocentric_Video_Dataset_for_Camping_Tent_Assembly_ICCVW_2019_paper.html) | [Site](https://data.bris.ac.uk/data/dataset/2ite3tu1u53n42hjfh3886sa86) |
| CMU-MMAC | 2011 | 25 subjects, 5 cooking recipes | procedural activities & skill learning | [Paper](https://publications.ri.cmu.edu/guide-to-the-carnegie-mellon-university-multimodal-activity-cmu-mmac-database) | [Site](http://kitchen.cs.cmu.edu/) |
| GTEA Gaze | 2011 | 17 meal preparation sessions, 7 cooking activities, gaze tracking annotations | procedural activities & skill learning | [Paper](https://doi.org/10.1007/978-3-642-33718-5_23) | [Site](https://cbs.ic.gatech.edu/fpv/) |
| EgoProactive / Pro²Bench | 2026 | 700 recordings (22–55 min) / 42K eval instances | Proactive procedural assistance | [Paper](https://arxiv.org/abs/2606.04970) | [HF](https://huggingface.co/datasets/facebook/wearable-ai) |

### Entries

- **EgoVerse** (2026) — 1,362 h of egocentric human demonstrations spanning ~80K episodes and 1,965 tasks for robot learning from human manipulation experience.
  [![arXiv](https://img.shields.io/badge/arXiv-2604.07607-b31b1b.svg)](https://arxiv.org/abs/2604.07607) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://egoverse.ai/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/GaTech-RL2/EgoVerse)

- **EgoLive** (2026) — Large-scale annotated egocentric recordings of real-world human task routines for robot manipulation learning.
  [![arXiv](https://img.shields.io/badge/arXiv-2604.23570-b31b1b.svg)](https://arxiv.org/abs/2604.23570)

- **EgoMAGIC** (2026) — 3,355 egocentric field-medicine videos covering 50 medical tasks, with released medical training data and an action-detection challenge.
  [![arXiv](https://img.shields.io/badge/arXiv-2604.22036-b31b1b.svg)](https://arxiv.org/abs/2604.22036) [![Site](https://img.shields.io/badge/Zenodo-DOI-blue.svg)](https://doi.org/10.5281/zenodo.19239154)

- **HumanEgo** (2026) — Minutes-per-task human egocentric demonstrations collected with Aria glasses for zero-shot human-to-robot manipulation-policy learning via interaction-centric spatial representations.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.24934-b31b1b.svg)](https://arxiv.org/abs/2605.24934) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://humanego-ai.github.io/)

- **EgoSPT** (2026) — 11,515 processed egocentric manipulation episodes for spatially prompted visual trajectory prediction, with RGB video, end-effector poses, gripper widths, and valid-frame masks.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.20085-b31b1b.svg)](https://arxiv.org/abs/2605.20085) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/JackYFL233/EgoSPT)

- **Ego-EXTRA** (2026) — 50 h of unscripted expert-trainee egocentric procedural assistance across bike workshop, kitchen, bakery, and assembly scenarios, with dialogue transcripts and 15K+ VQA sets.
  [![Paper](https://img.shields.io/badge/Paper-WACV26-b31b1b.svg)](https://openaccess.thecvf.com/content/WACV2026/html/Ragusa_Ego-EXTRA_video-language_Egocentric_Dataset_for_EXpert-TRAinee_assistance_WACV_2026_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://fpv-iplab.github.io/Ego-EXTRA/)

- **GM-100** (2026) — 100+ detail-oriented robot manipulation tasks with 13K+ teleoperated trajectories and robot first-person camera views for embodied skill evaluation.
  [![arXiv](https://img.shields.io/badge/arXiv-2601.11421-b31b1b.svg)](https://arxiv.org/abs/2601.11421) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://www.rhos.ai/research/gm-100) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/yuz1wan/GM-X)

- **SABER** (2026) — 100+ h of natural in-store retail activity with head-mounted egocentric video, 360-degree exocentric video, and 44.8K action samples for VLA adaptation.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.09613-b31b1b.svg)](https://arxiv.org/abs/2605.09613) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://dreamvu.ai/saber/) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/DreamVu/SABER-10K)

- **EgoYC2 / Exo2EgoDVC** (2025) — ~43 h cooking; Dense captioning, procedural.
  [![arXiv](https://img.shields.io/badge/arXiv-2311.16444-b31b1b.svg)](https://arxiv.org/abs/2311.16444) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2311.16444) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/ut-vision/Exo2EgoDVC)

- **EgoExoLearn** (2024) — 120 h ego+exo; Procedural, async views.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_EgoExoLearn_A_Dataset_for_Bridging_Asynchronous_Ego-_and_Exo-centric_View_CVPR_2024_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_EgoExoLearn_A_Dataset_for_Bridging_Asynchronous_Ego-_and_Exo-centric_View_CVPR_2024_paper.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/OpenGVLab/EgoExoLearn) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/hyf015/EgoExoLearn)

- **IndustReal** (2024) — ~6 h industrial; Procedure steps, errors.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/WACV2024/html/Schoonbeek_IndustReal_A_Dataset_for_Procedure_Step_Recognition_Handling_Execution_Errors_WACV_2024_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://timschoonbeek.github.io/industreal.html)

- **Assembly101** (2022) — 513 h multiview; Assembly, procedure.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2022/html/Sener_Assembly101_A_Large-Scale_Multi-View_Video_Dataset_for_Understanding_Procedural_Activities_CVPR_2022_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://openaccess.thecvf.com/content/CVPR2022/html/Sener_Assembly101_A_Large-Scale_Multi-View_Video_Dataset_for_Understanding_Procedural_Activities_CVPR_2022_paper.html)

- **EgoProceL** (2022) — 62 videos / 16 tasks; Procedure learning.
  [![arXiv](https://img.shields.io/badge/arXiv-2207.10883-b31b1b.svg)](https://arxiv.org/abs/2207.10883) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://sid2697.github.io/egoprocel/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Sid2697/EgoProceL-egocentric-procedure-learning)

- **EPIC-Tent** (2019) — 7+ h, tent assembly; Procedural, dual HMD + gaze.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_ICCVW_2019/html/EPIC/Jang_EPIC-Tent_An_Egocentric_Video_Dataset_for_Camping_Tent_Assembly_ICCVW_2019_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://data.bris.ac.uk/data/dataset/2ite3tu1u53n42hjfh3886sa86) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/youngkyoonjang/EPIC_Tent2019)

- **CMU-MMAC** (2011) — 25 subjects, 5 cooking recipes; procedural activities & skill learning.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://publications.ri.cmu.edu/guide-to-the-carnegie-mellon-university-multimodal-activity-cmu-mmac-database) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](http://kitchen.cs.cmu.edu/)

- **GTEA Gaze** (2011) — 17 meal preparation sessions, 7 cooking activities, gaze tracking annotations; procedural activities & skill learning.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.1007/978-3-642-33718-5_23) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://cbs.ic.gatech.edu/fpv/)

- **EgoProactive / Pro²Bench** (2026) — 700 Ray-Ban Meta smart-glasses recordings (22–55 min each) of cooking, crafts, DIY, and tutorial sessions with per-decision-point interrupt/silent labels and Out-of-Plan deviation-recovery annotations for proactive procedural assistance; Pro²Bench unifies five existing egocentric benchmarks into 42K evaluation and 250K training instances.
  [![arXiv](https://img.shields.io/badge/arXiv-2606.04970-b31b1b.svg)](https://arxiv.org/abs/2606.04970) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/facebook/wearable-ai)

- *Ego-Exo4D — see [3D Scene Understanding & Localization](#-3d-scene-understanding--localization)*
- *HowToDIV — see [VLMs, Instructions & QA](#-vlms-instructions--qa)*
- *ADT (Aria Digital Twin) — see [3D Scene Understanding & Localization](#-3d-scene-understanding--localization)*

### Benchmarks built on these datasets

| Benchmark | Capability | Primary data | Official link | Notes |
|-----------|------------|--------------|---------------|-------|
| HumanEgo | Zero-shot human-to-robot manipulation from egocentric video | HumanEgo | [Site](https://humanego-ai.github.io/) | Dataset+benchmark |
| EgoSPT / SP-VTP | Spatially prompted visual trajectory prediction for manipulation | EgoSPT | [HF](https://huggingface.co/datasets/JackYFL233/EgoSPT) | Dataset+benchmark |
| Ego-EXTRA | Expert-trainee procedural assistance and VQA | Ego-EXTRA | [Site](https://fpv-iplab.github.io/Ego-EXTRA/) | Dataset+benchmark |
| EgoMAGIC | Field-medicine action detection | EgoMAGIC | [Zenodo](https://doi.org/10.5281/zenodo.19239154) | Dataset+benchmark |
| GM-100 | Detail-oriented robot manipulation evaluation | GM-100 | [Site](https://www.rhos.ai/research/gm-100) | Dataset+benchmark |
| TAVIS | Active-vision imitation learning on humanoid robots (GR1T2, Reachy2) in IsaacLab; TAVIS-Head + TAVIS-Hands suites with the GALT anticipatory-gaze metric | Simulation-only (no real-data release) | [Paper](https://arxiv.org/abs/2605.07943) | Standalone benchmark |
| EgoProactive / Pro²Bench | Proactive intervention timing and Out-of-Plan recovery guidance | EgoProactive + Ego4D / EPIC-KITCHENS / Ego-Exo4D / HoloAssist / HowTo100M | [HF](https://huggingface.co/datasets/facebook/wearable-ai) | Dataset+benchmark |

## 🗺️ 3D Scene Understanding & Localization

> These datasets emphasize geometry, localization, scene graphs, multiview capture, or machine-perception tasks grounded in ego video.

### Datasets at a glance

| Name | Year | Scale | Key tasks | Paper | Link |
|------|------|-------|-----------|-------|------|
| ⭐ Ego-Exo4D | 2024 | 1,286+ h ego+exo | Skilled activity, many tasks | [Paper](https://arxiv.org/abs/2311.18259) | [Site](https://ego-exo4d-data.org/) |
| PRISM | 2026 | 270K samples / 11.8M frames | Retail embodied VLM, spatial reasoning | [Paper](https://arxiv.org/abs/2603.29281) | [HF](https://huggingface.co/datasets/DreamVu/PRISM-100K) |
| EgoTraj | 2026 | 10.7 h / 1.15M frames | Egocentric trajectory prediction | [Paper](https://arxiv.org/abs/2605.19004) | [GitHub](https://github.com/yehiahmad/EgoTraj) |
| AIST-Living | 2026 | Egocentric video + GT motion in scanned env. | Global pose, localization | [Paper](https://arxiv.org/abs/2605.20889) | [Site](https://deguchihiroyuki.github.io/Map-Mono-Ego-Project/) |
| ADT (Aria Digital Twin) | 2023 | 200 seq., 2 scenes | Egocentric 3D perception | [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Pan_Aria_Digital_Twin_A_New_Benchmark_Dataset_for_Egocentric_3D_ICCV_2023_paper.html) | [Site](https://www.projectaria.com/datasets/adt/) |
| PVSG | 2023 | 400 vids, ~150K frames | Panoptic video scene graph (ego + third-person) | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Yang_Panoptic_Video_Scene_Graph_Generation_CVPR_2023_paper.html) | [Site](https://jingkang50.github.io/PVSG/) |
| DR(eye)VE | 2018 | ~6 h driving, 555K frames | Gaze prediction, driving ego video | [Paper](https://arxiv.org/abs/1705.03854) | [Site](http://aimagelab.ing.unimore.it/dreyeve) |
| EgoCart | 2018 | Retail RGB-D, 9 videos | Indoor / cart localization | [Paper](https://doi.org/10.1109/TCSVT.2019.2941040) | [Site](https://iplab.dmi.unict.it/EgocentricShoppingCartLocalization/) |
| IU ShareView | 2018 | 9 paired ego video sets | Person seg / ID across synchronized wearers | [Paper](https://openaccess.thecvf.com/content_ECCV_2018/html/Mingze_Xu_Joint_Person_Segmentation_ECCV_2018_paper.html) | [Site](http://vision.soic.indiana.edu/firstthird-eccv2018/) |
| OST | 2017 | 57 sequences, 55 subjects, ~15 min/video, egocentric object search tasks, eye-tracking ground truth | 3d scene understanding & localization | [Paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Zhang_Deep_Future_Gaze_CVPR_2017_paper.html) | [GitHub](https://github.com/Mengmi/deepfuturegaze_gan) |
| OVO-S-Bench | 2026 | 348 videos / 1,680 Q / 30 task types | Streaming spatial intelligence QA | [Paper](https://arxiv.org/abs/2606.03890) | [Site](https://internlm.github.io/OVO-S-Bench/) |

### Entries

- [⭐️] **Ego-Exo4D** (2024) — 1,286+ h of paired first- and third-person skilled activity with multiview geometry and a broad benchmark suite.
  [![arXiv](https://img.shields.io/badge/arXiv-2311.18259-b31b1b.svg)](https://arxiv.org/abs/2311.18259) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://arxiv.org/abs/2311.18259)

- **PRISM** (2026) — 270K-sample multi-view retail video SFT corpus with egocentric, exocentric, and 360-degree views for embodied VLM spatial, physical, and action reasoning.
  [![arXiv](https://img.shields.io/badge/arXiv-2603.29281-b31b1b.svg)](https://arxiv.org/abs/2603.29281) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://dreamvu.ai/prism/) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/DreamVu/PRISM-100K)

- **EgoTraj** (2026) — 10.7 h / 1.15M frames of Meta Quest Pro egocentric urban navigation with synchronized RGB, 6DoF head pose, gaze, and scene annotations for trajectory forecasting; the GitHub README says the dataset and dashboard will be released after publication.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.19004-b31b1b.svg)](https://arxiv.org/abs/2605.19004) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/yehiahmad/EgoTraj)

- **AIST-Living** (2026) — Dataset introduced with Map-Mono-Ego that pairs monocular egocentric video with ground-truth human motion in a pre-scanned 3D environment for globally consistent pose estimation.
  [![arXiv](https://img.shields.io/badge/arXiv-2605.20889-b31b1b.svg)](https://arxiv.org/abs/2605.20889) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://deguchihiroyuki.github.io/Map-Mono-Ego-Project/)

- **ADT (Aria Digital Twin)** (2023) — 200 seq., 2 scenes; Egocentric 3D perception.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/ICCV2023/html/Pan_Aria_Digital_Twin_A_New_Benchmark_Dataset_for_Egocentric_3D_ICCV_2023_paper.html) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://www.projectaria.com/datasets/adt/) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/projectaria/aria-digital-twin)

- **PVSG** (2023) — 400 vids, ~150K frames; Panoptic video scene graph (ego + third-person).
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2023/html/Yang_Panoptic_Video_Scene_Graph_Generation_CVPR_2023_paper.html) [![arXiv](https://img.shields.io/badge/arXiv-2311.17058-b31b1b.svg)](https://arxiv.org/abs/2311.17058) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://jingkang50.github.io/PVSG/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/LilyDaytoy/OpenPVSG)

- **DR(eye)VE** (2018) — ~6 h driving, 555K frames; Gaze prediction, driving ego video.
  [![arXiv](https://img.shields.io/badge/arXiv-1705.03854-b31b1b.svg)](https://arxiv.org/abs/1705.03854) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](http://aimagelab.ing.unimore.it/dreyeve) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/ndrplz/dreyeve)

- **EgoCart** (2018) — Retail RGB-D, 9 videos; Indoor / cart localization.
  [![Paper](https://img.shields.io/badge/Paper-DOI-b31b1b.svg)](https://doi.org/10.1109/TCSVT.2019.2941040) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://iplab.dmi.unict.it/EgocentricShoppingCartLocalization/)

- **IU ShareView** (2018) — 9 paired ego video sets; Person seg / ID across synchronized wearers.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_ECCV_2018/html/Mingze_Xu_Joint_Person_Segmentation_ECCV_2018_paper.html) [![arXiv](https://img.shields.io/badge/arXiv-1803.11217-b31b1b.svg)](https://arxiv.org/abs/1803.11217) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](http://vision.soic.indiana.edu/firstthird-eccv2018/)

- **OST** (2017) — 57 sequences, 55 subjects, ~15 min/video, egocentric object search tasks, eye-tracking ground truth; 3d scene understanding & localization.
  [![Paper](https://img.shields.io/badge/Paper-Link-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2017/html/Zhang_Deep_Future_Gaze_CVPR_2017_paper.html) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/Mengmi/deepfuturegaze_gan)

- **OVO-S-Bench** (2026) — 1,680 fully human-annotated questions over 348 continuous egocentric streams (indoor walkthroughs, daily activities, outdoor tours, and driving from nine sources) spanning 30 task types across four hierarchical levels, from instantaneous perception to allocentric mapping, for streaming spatial intelligence in multimodal LLMs.
  [![arXiv](https://img.shields.io/badge/arXiv-2606.03890-b31b1b.svg)](https://arxiv.org/abs/2606.03890) [![Site](https://img.shields.io/badge/Site-Link-blue.svg)](https://internlm.github.io/OVO-S-Bench/) [![Code](https://img.shields.io/badge/Code-GitHub-black.svg)](https://github.com/InternLM/OVO-S-Bench) [![🤗](https://img.shields.io/badge/%F0%9F%A4%97-Dataset-yellow.svg)](https://huggingface.co/datasets/JoeLeelyf/OVO-S-Bench)

- *Ego-1K — see [Video Generation & World-Model Pretraining](#-video-generation--world-model-pretraining)*

### Benchmarks built on these datasets

| Benchmark | Capability | Primary data | Official link | Notes |
|-----------|------------|--------------|---------------|-------|
| Ego-Exo4D | Ego–exo skill understanding, many tasks | Ego-Exo4D | [Site](https://ego-exo4d-data.org/) | Suite |
| EgoTraj | Egocentric multimodal trajectory forecasting | EgoTraj | [GitHub](https://github.com/yehiahmad/EgoTraj) | Dataset+benchmark |
| EgoProx | Egocentric 3D proximity reasoning VQA | ADT / EgoExo4D | [Site](https://lijinzhao30.github.io/Egoprox/) | Standalone |
| Map-Mono-Ego | Map-grounded global human pose estimation | AIST-Living | [Site](https://deguchihiroyuki.github.io/Map-Mono-Ego-Project/) | Dataset+benchmark |
| ADT (Aria Digital Twin) | Egocentric 3D machine perception | ADT | [Aria](https://www.projectaria.com/datasets/adt/) | Dataset+benchmark |
| OVO-S-Bench | Streaming spatial intelligence over continuous ego video | Nine egocentric video sources | [Site](https://internlm.github.io/OVO-S-Bench/) | Standalone |

## 🛠️ Tools & Libraries

| Name | Description | Link |
|------|-------------|------|
| Ego4D CLI | Official downloader and tooling for accessing Ego4D releases. | [GitHub](https://github.com/facebookresearch/Ego4d) |
| HOMIE-toolkit | Toolkit released with Ropedia Xperience-10M for large-scale multimodal ego data. | [GitHub](https://github.com/Ropedia/HOMIE-toolkit) |
| AssemblyHands Toolkit | Official toolkit for the AssemblyHands benchmark. | [GitHub](https://github.com/facebookresearch/assemblyhands-toolkit) |
| TREK-150 Toolkit | Toolkit for the TREK-150 egocentric tracking benchmark. | [GitHub](https://github.com/matteo-dunnhofer/TREK-150-toolkit) |

## 🔗 Related Awesome Lists

- [Awesome-Egocentric](https://github.com/EgoAlpha/Awesome-Egocentric)
- [awesome-egocentric-vision](https://github.com/Sid2697/awesome-egocentric-vision)
- [Awesome-Egocentric-and-Exocentric-Vision](https://github.com/ayiyayi/Awesome-Egocentric-and-Exocentric-Vision)

## 🤝 Contributing

1. Add or update the dataset, benchmark, or survey directly in the matching section of `README.md`.
2. Keep primary entries unique: one full entry under one topic, cross-links everywhere else.
3. Preserve newest-to-oldest ordering inside each topic block, with flagship entries kept at the top.
4. Follow the detailed checklist in [CONTRIBUTING.md](CONTRIBUTING.md) before opening a PR.

## License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). See [LICENSE](LICENSE).
