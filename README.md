
# RobustCP-Survey
> For **Robust Vehicular Cooperative Perception: A Survey of Fusion Strategies under Incomplete, Unreliable, and Adversarial Conditions**.

This repository organizes the literature according to the survey structure and provides supplementary evidence supporting the R1–R3 robustness assessments.

**Paper-link note.** The literature entries use direct archival or preprint links (DOI/publisher pages, CVF, IEEE Xplore, ACM, OpenReview, ICLR Proceedings, USENIX, HAL, or arXiv). **💻** denotes a verified public code repository; `-` means that no public repository was verified in this pass.

**Organization note.** To avoid duplication, each cited paper is listed once under the section where it is primarily discussed in the current survey. Cross-section citations remain in the paper itself.

**Maintenance note.** Bibliography numbers are intentionally omitted because this repository is designed to grow over time. Stable identifiers such as paper titles, DOI/arXiv/OpenReview links, and BibTeX keys should be used for maintenance instead of manuscript reference numbers.

## 📖 Table of Contents

- [Papers](#-papers)
  - [Related surveys](#related-surveys)
  - [Incomplete collaborative information](#incomplete-collaborative-information)
  - [Unreliable collaborative information](#unreliable-collaborative-information)
  - [Adversarial collaborative information](#adversarial-collaborative-information)
  - [Datasets and evaluation](#datasets-and-evaluation)
  - [Cross-cutting references](#cross-cutting-references)
- [Supplementary R1–R3 evidence tables](#-supplementary-r1r3-evidence-tables)

---

## 📚 Papers

## Related surveys

### 2.2 Surveys on V2X-Enabled Cooperative Driving and Perception

| Name | Link | Code |
| --- | --- | --- |
| Collaborative perception in autonomous driving: Methods, datasets, and challenges | [📄](https://arxiv.org/abs/2301.06262) | [💻](https://github.com/CatOneTwo/Collaborative-Perception-in-Autonomous-Driving) |
| A survey and framework of cooperative perception: From heterogeneous singleton to hierarchical cooperation | [📄](https://doi.org/10.1109/TITS.2024.3436012) | - |
| A survey on cooperative architectures and maneuvers for connected and automated vehicles | [📄](https://doi.org/10.1109/COMST.2021.3138275) | - |
| Towards the next level of vehicle automation through cooperative driving: A roadmap from planning and control perspective | [📄](https://doi.org/10.1109/TIV.2024.3363873) | - |
| Collaborative sensing and communication for intelligent connected vehicles: A comprehensive survey | [📄](https://doi.org/10.1109/COMST.2025.3626504) | - |
| Cooperative perception for automated driving: A survey of algorithms, applications, and future directions | [📄](https://doi.org/10.1109/JPROC.2025.3608874) | - |
| Vehicle-to-everything cooperative perception for autonomous driving | [📄](https://doi.org/10.1109/JPROC.2025.3600903) | - |
| Roadside multimodal sensor fusion for 3-d object detection: A review | [📄](https://doi.org/10.1109/JSEN.2026.3699674) | - |
| Collaborative perception datasets for autonomous driving: A review | [📄](https://arxiv.org/abs/2504.12696) | [💻](https://github.com/frankwnb/Collaborative-Perception-Datasets-for-Autonomous-Driving) |
| Multi-agent embodied autonomous driving: From v2x information exchange to shared world models | [📄](https://arxiv.org/abs/2606.13840) | - |

### 2.3 Surveys on Robust Cooperative Perception

| Name | Link | Code |
| --- | --- | --- |
| A survey on intermediate fusion methods for collaborative perception categorized by real world challenges | [📄](https://doi.org/10.1109/IV55156.2024.10588382) | - |
| Cooperative safety intelligence over v2x networks: A survey | [📄](https://doi.org/10.1109/COMST.2026.3723946) | - |
| Collaborative vehicular perception against adversarial attacks: Overview, challenges, and potential solutions | [📄](https://doi.org/10.1109/MWC.2026.3659078) | - |
| Perception and sensing for autonomous vehicles under adverse weather conditions: A survey | [📄](https://doi.org/10.1016/j.isprsjprs.2022.12.021) | - |
| Robustness-aware 3d object detection in autonomous driving: A review and outlook | [📄](https://doi.org/10.1109/TITS.2024.3439557) | - |
| Uncertainty quantification for safe and reliable autonomous vehicles: A review of methods and applications | [📄](https://doi.org/10.1109/TITS.2025.3532803) | - |
| Progressive bird’s eye view perception for safety-critical autonomous driving: A comprehensive survey | [📄](https://arxiv.org/abs/2508.07560) | - |
| A systematic review of adversarial attacks and defenses for deep reinforcement learning in autonomous vehicle applications | [📄](https://doi.org/10.1109/TITS.2026.3666151) | - |
| Adversarial attacks on autonomous driving systems in the physical world: A survey | [📄](https://doi.org/10.1109/TIV.2024.3484152) | - |
| Multimodal fusion on low-quality data: A comprehensive survey | [📄](https://doi.org/10.1016/j.inffus.2026.104437) | - |
| Enhancing trust management system for connected autonomous vehicles using machine learning methods: A survey | [📄](https://arxiv.org/abs/2505.07882) | [💻](https://github.com/octoberzzzzz/ML-based-TMS-CAV-Survey) |

## Incomplete collaborative information

### 4.1.1 Communication-Efficient Selective Sharing

| Name | Link | Code |
| --- | --- | --- |
| F-Cooper: Feature based cooperative perception for autonomous vehicle edge computing system using 3d point clouds | [📄](https://doi.org/10.1145/3318216.3363300) | - |
| V2VNet: Vehicle-to-vehicle communication for joint perception and prediction | [📄](https://arxiv.org/abs/2008.07519) | - |
| Where2comm: Communication-efficient collaborative perception via spatial confidence maps | [📄](https://openreview.net/forum?id=dLL4KXzKUpS) | [💻](https://github.com/MediaBrain-SJTU/where2comm) |
| Who2com: Collaborative perception via learnable handshake communication | [📄](https://arxiv.org/abs/2003.09575) | [💻](https://github.com/GT-RIPL/MultiAgentPerception) |
| When2com: Multi-agent perception via communication graph grouping | [📄](https://arxiv.org/abs/2006.00176) | [💻](https://github.com/GT-RIPL/MultiAgentPerception) |
| Learning distilled collaboration graph for multi-agent perception | [📄](https://openreview.net/forum?id=ZRcjSOmYraB) | [💻](https://github.com/ai4ce/DiscoNet) |
| How2comm: Communication-efficient and collaboration-pragmatic multi-agent perception | [📄](https://openreview.net/forum?id=Dbaxm9ujq6) | [💻](https://github.com/ydk122024/How2comm) |
| Autocast: Scalable infrastructure-less cooperative perception for distributed collaborative driving | [📄](https://arxiv.org/abs/2112.14947) | - |
| Point cluster: A compact message unit for communication-efficient collaborative perception | [📄](https://openreview.net/forum?id=54XlM8Clkg) | - |
| Is discretization fusion all you need for collaborative perception? | [📄](https://arxiv.org/abs/2503.13946) | [💻](https://github.com/sidiangongyuan/ACCO) |
| CoCMT: Communication-efficient cross-modal transformer for collaborative perception | [📄](https://openreview.net/forum?id=S1NrbfMS7T) | [💻](https://github.com/taco-group/COCMT) |
| QUEST: Query stream for practical cooperative perception | [📄](https://arxiv.org/abs/2308.01804) | - |
| Coopdetr: A unified cooperative perception framework for 3d detection via object query | [📄](https://arxiv.org/abs/2502.19313) | - |
| INSTINCT: Instance-level interaction architecture for query-based collaborative perception | [📄](https://arxiv.org/abs/2509.23700) | [💻](https://github.com/CrazyShout/INSTINCT) |
| Sparsealign: A fully sparse framework for cooperative object detection | [📄](https://arxiv.org/abs/2503.12982) | - |
| CoSDH: Communication-efficient collaborative perception via supply-demand awareness and intermediate-late hybridization | [📄](https://arxiv.org/abs/2503.03430) | [💻](https://github.com/Xu2729/CoSDH) |
| Enhancing cooperative lidar-based perception accuracy in vehicular edge networks | [📄](https://doi.org/10.1109/TITS.2025.3541265) | - |
| Occlusion-guided multi-modal fusion for vehicle-infrastructure cooperative 3d object detection | [📄](https://doi.org/10.1016/j.patcog.2024.110939) | - |
| Background fades, foreground leads: Curriculum-guided background pruning for efficient foreground- centric collaborative perception | [📄](https://arxiv.org/abs/2510.19250) | - |
| Efficient and robust collaborative perception via cross-vehicle spatio-temporal feature selecting | [📄](https://doi.org/10.1109/TITS.2025.3611530) | - |
| CoLC: Communication-efficient collaborative perception with LiDAR completion | [📄](https://arxiv.org/abs/2603.00682) | [💻](https://github.com/CatOneTwo/CoLC) |
| WaveComm: Lightweight communication for collaborative perception via wavelet feature distillation | [📄](https://arxiv.org/abs/2603.13365) | [💻](https://github.com/erdemtbao/WaveComm) |
| mmCooper: A multi-agent multi-stage communication-efficient and collaboration- robust cooperative perception framework | [📄](https://arxiv.org/abs/2501.12263) | - |
| Cost: Efficient collaborative perception from unified spatiotemporal perspective | [📄](https://arxiv.org/abs/2508.00359) | [💻](https://github.com/tzhhhh123/CoST) |
| Cooptrack: Exploring end-to-end learning for efficient cooperative sequential perception | [📄](https://arxiv.org/abs/2507.19239) | [💻](https://github.com/zhongjiaru/CoopTrack) |
| End-to-end autonomous driving through v2x cooperation | [📄](https://arxiv.org/abs/2404.00717) | [💻](https://github.com/AIR-THU/UniV2X) |
| Comamba: Real-time cooperative perception unlocked with state-space models | [📄](https://arxiv.org/abs/2409.10699) | - |
| COOPMamba: Efficient vehicle-to-vehicle cooperative perception based on 3-d point clouds | [📄](https://doi.org/10.1109/JSEN.2026.3682367) | [💻](https://github.com/npunancy/coopmamba) |
| Pragmatic communication in multi-agent collaborative perception | [📄](https://arxiv.org/abs/2401.12694) | [💻](https://github.com/PhyllisH/PragComm) |
| InfoCom: Kilobyte-scale communication-efficient collaborative perception with information bottleneck | [📄](https://arxiv.org/abs/2512.10305) | [💻](https://github.com/fengxueguiren/InfoCom) |
| Rate-distortion optimized pragmatic communication for collaborative perception | [📄](https://openreview.net/forum?id=920RxFvsMx) | - |
| WhisperNet: A scalable solution for bandwidth-efficient collaboration | [📄](https://arxiv.org/abs/2603.01708) | - |
| Focalcomm: Hard instance-aware multi-agent perception | [📄](https://arxiv.org/abs/2512.13982) | [💻](https://github.com/scdrand23/FocalComm) |
| Select2Col: Leveraging spatial-temporal importance of semantic information for efficient collaborative perception | [📄](https://doi.org/10.1109/TVT.2024.3390414) | [💻](https://github.com/huangqzj/Select2Col) |
| Directed-CP: Directed collaborative perception for connected and autonomous vehicles via proactive attention | [📄](https://arxiv.org/abs/2409.08840) | - |
| Adaptive interaction and cooperative perception enhancement for connected and autonomous vehicles in challenging v2x environments | [📄](https://doi.org/10.1109/TVT.2026.3725185) | - |
| Sparsecoop: Cooperative perception with kinematic-grounded queries | [📄](https://arxiv.org/abs/2512.06838) | [💻](https://github.com/wang-jh18-SVM/SparseCoop) |
| Map4comm: A map-aware collaborative perception framework with efficient-bandwidth information fusion | [📄](https://doi.org/10.1016/j.inffus.2025.103567) | - |
| Vicooper: Communication-efficient vehicle-infrastructure cooperative 3-d object detection leveraging roadside hd point cloud background map priors | [📄](https://doi.org/10.1109/JIOT.2025.3624814) | - |
| Scomcp: Task-oriented semantic communication for collaborative perception | [📄](https://arxiv.org/abs/2507.00895) | - |

### 4.1.2 Lossy and Interrupted Collaboration

| Name | Link | Code |
| --- | --- | --- |
| Learning for vehicle-to-vehicle cooperative perception under lossy communication | [📄](https://doi.org/10.1109/TIV.2023.3260040) | - |
| Interruption-aware cooperative perception for V2X communication-aided autonomous driving | [📄](https://ieeexplore.ieee.org/document/10457955/) | - |
| V2v cooperative perception with adaptive communication loss for autonomous driving | [📄](https://doi.org/10.1109/TITS.2025.3582601) | - |
| Robust and efficient cooperative perception under vehicle-to-vehicle communication impairments | [📄](https://doi.org/10.1109/TMC.2026.3668902) | - |
| Multitask collaborative perception for vehicle-to-everything considering impaired communication | [📄](https://doi.org/10.1109/TIM.2025.3548801) | - |
| Extended visibility of autonomous vehicles via optimized cooperative perception under imperfect communication | [📄](https://doi.org/10.1016/j.trc.2025.105350) | - |
| V2x-jepa: Self-supervised multiagent joint embedding predictive architecture for robust vehicle-to-everything perception | [📄](https://doi.org/10.1109/JIOT.2026.3660030) | - |

### 4.2.1 Unavailable Collaborators

| Name | Link | Code |
| --- | --- | --- |
| SiCP: Simultaneous individual and cooperative perception for 3D object detection in connected and automated vehicles | [📄](https://doi.org/10.1109/IROS58592.2024.10801398) | [💻](https://github.com/DarrenQu/SiCP) |
| Perception balance with uncertainty-guided fusion and proposal-wise mixture-of-experts for robust multi-agent 3d object detection | [📄](https://doi.org/10.1016/j.eswa.2026.131311) | - |
| Facilitating heterogeneous sensor information cooperation in multi-agent perception system, Information Sciences 749 (2026) 123529 | [📄](https://doi.org/10.1016/j.ins.2026.123529) | [💻](https://github.com/byzhaoAI/DisCo) |

### 4.2.2 Missing Sensing Modalities

| Name | Link | Code |
| --- | --- | --- |
| Bm2cp: Efficient collaborative perception with lidar-camera modalities | [📄](https://openreview.net/forum?id=uJqxFjF1xWp) | [💻](https://github.com/byzhaoAI/BM2CP) |
| Caml: Collaborative auxiliary modality learning for multi-agent systems | [📄](https://openreview.net/forum?id=OhUu5PlRkF) | - |
| Simo: Single-modality-operable multimodal collaborative perception | [📄](https://openreview.net/forum?id=h0iRgjTmVs) | [💻](https://github.com/dempsey-wen/SiMO) |

### 4.3 Fusion under Residual Evidence Gaps after Fusion

| Name | Link | Code |
| --- | --- | --- |
| Communication-efficient collaborative perception via information filling with codebook | [📄](https://arxiv.org/abs/2405.04966) | [💻](https://github.com/PhyllisH/CodeFilling) |
| Real-time identification of cooperative perception necessity in road traffic scenarios | [📄](https://doi.org/10.1016/j.trc.2026.105547) | - |
| Multi-robot scene completion: Towards task-agnostic collaborative perception | [📄](https://openreview.net/forum?id=hW0tcXOJas2) | [💻](https://github.com/coperception/star) |
| CORE: Cooperative reconstruction for multi-agent perception | [📄](https://arxiv.org/abs/2307.11514) | [💻](https://github.com/zllxot/CORE) |
| Generative map priors for collaborative BEV semantic segmentation | [📄](https://openaccess.thecvf.com/content/CVPR2025/html/Fu_Generative_Map_Priors_for_Collaborative_BEV_Semantic_Segmentation_CVPR_2025_paper.html) | - |
| Integrated optimization for vehicle trajectory reconstruction under cooperative perception environment, Transporta- tion Research Part C: Emerging Technologies 184 (2026) 105522 | [📄](https://doi.org/10.1016/j.trc.2026.105522) | [💻](https://github.com/Purdue-CART-Lab/CP-TrajRecon-Opt) |
| Risk occupancy: A new and efficient paradigm through vehicle-road-cloud collaboration | [📄](https://arxiv.org/abs/2408.07367) | - |
| Cooperrisk: A driving risk quantification pipeline with multi-agent cooperative perception and prediction | [📄](https://arxiv.org/abs/2506.15868) | - |

## Unreliable collaborative information

### 5.1 Fusion under Spatial Unreliability

| Name | Link | Code |
| --- | --- | --- |
| Robust collaborative 3d object detection in presence of pose errors | [📄](https://arxiv.org/abs/2211.07214) | [💻](https://github.com/yifanlu0227/CoAlign) |
| Learning to communicate and correct pose errors | [📄](https://arxiv.org/abs/2011.05289) | [💻](https://github.com/yifanlu0227/CoAlign) |
| A cooperative perception system robust to localization errors | [📄](https://doi.org/10.1109/IV55152.2023.10186727) | - |
| RoCo: Robust collaborative perception by iterative object matching and pose adjustment | [📄](https://arxiv.org/abs/2408.00257) | [💻](https://github.com/HuangZhe885/RoCo) |
| EMIFF: Enhanced multi-scale image feature fusion for vehicle- infrastructure cooperative 3d object detection | [📄](https://arxiv.org/abs/2402.15272) | [💻](https://github.com/Bosszhe/EMIFF) |
| MamV2XCalib: V2X-based target-less infrastructure camera calibration with state space model | [📄](https://arxiv.org/abs/2507.23595) | [💻](https://github.com/zhuyaoye/MamV2XCalib) |
| V2VLoc: Robust GNSS-free collaborative perception via LiDAR localization | [📄](https://arxiv.org/abs/2511.14247) | [💻](https://github.com/wklin214-glitch/V2VLoc) |
| Cora: A collaborative robust architecture with hybrid fusion for efficient perception | [📄](https://doi.org/10.1609/aaai.v40i4.37274) | - |
| ERMVP: Communication-efficient and collaboration-robust multi-vehicle perception in challenging environments | [📄](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_ERMVP_Communication-Efficient_and_Collaboration-Robust_Multi-Vehicle_Perception_in_Challenging_Environments_CVPR_2024_paper.html) | [💻](https://github.com/Terry9a/ERMVP) |
| Collaboration-aware adversarial training for robust vehicle-to-everything cooperative perception | [📄](https://www.sciencedirect.com/science/article/pii/S0968090X26004109) | - |

### 5.2 Fusion under Temporal Unreliability

| Name | Link | Code |
| --- | --- | --- |
| Latency-aware collaborative perception | [📄](https://arxiv.org/abs/2207.08560) | [💻](https://github.com/MediaBrain-SJTU/SyncNet) |
| Asynchrony-robust collaborative perception via bird’s eye view flow | [📄](https://openreview.net/forum?id=UHIDdtxmVS) | [💻](https://github.com/MediaBrain-SJTU/CoBEVFlow) |
| V2xpnp: Vehicle-to-everything spatio-temporal fusion for multi-agent perception and prediction | [📄](https://arxiv.org/abs/2412.01812) | [💻](https://github.com/Zewei-Zhou/V2XPnP) |
| Cmp: Cooperative motion prediction with multi-agent communication | [📄](https://arxiv.org/abs/2403.17916) | - |
| CoDynTrust: Robust asynchronous collaborative perception via dynamic feature trust modulus | [📄](https://arxiv.org/abs/2502.08169) | [💻](https://github.com/CrazyShout/CoDynTrust) |
| TraF-Align: Trajectory-aware feature alignment for asynchronous multi-agent perception | [📄](https://arxiv.org/abs/2503.19391) | [💻](https://github.com/zhyingS/TraF-Align) |
| RAO++: Realistic real-time multi-vehicle collaboration on asynchronous sensors | [📄](https://doi.org/10.1145/3839235) | - |
| DATA: Domain-and-time alignment for high-quality feature fusion in collaborative perception | [📄](https://openaccess.thecvf.com/content/ICCV2025/html/Tian_DATA_Domain-And-Time_Alignment_for_High-Quality_Feature_Fusion_in_Collaborative_Perception_ICCV_2025_paper.html) | [💻](https://github.com/ChengchangTian/DATA) |
| Cooperative perception of multi-agents under the spatio-temporal drift issue | [📄](https://doi.org/10.1109/TITS.2025.3626365) | - |
| DRTF-CoP: A cooperative perception framework via dynamic reliability-aware temporal fusion | [📄](https://doi.org/10.1016/j.patcog.2026.114583) | - |
| Spatio-temporal adaptive refinement for bird’s eye view cooperative perception | [📄](https://doi.org/10.1016/j.neucom.2026.134057) | - |
| CATNet: Collaborative alignment and transformation network for cooperative perception | [📄](https://arxiv.org/abs/2603.05255) | - |
| CoAnchor: Robust collaborative perception under spatio-temporal misalignment via object-level anchors | [📄](https://arxiv.org/abs/2608.21055) | - |

### 5.3 Fusion under Observation-Level Unreliability

| Name | Link | Code |
| --- | --- | --- |
| Rcp-bench: Benchmarking robustness for collaborative perception under diverse corruptions | [📄](https://openaccess.thecvf.com/content/CVPR2025/html/Du_RCP-Bench_Benchmarking_Robustness_for_Collaborative_Perception_Under_Diverse_Corruptions_CVPR_2025_paper.html) | [💻](https://github.com/LuckyDush/RCP-Bench) |
| DenoiseCP-Net: Efficient collective perception in adverse weather via joint LiDAR-based 3d object detection and denoising | [📄](https://arxiv.org/abs/2507.06976) | - |
| V2x-r: Cooperative lidar-4d radar fusion with denoising diffusion for 3d object detection | [📄](https://arxiv.org/abs/2411.08402) | [💻](https://github.com/ylwhxht/V2X-R) |
| CoopDiff: A diffusion-guided approach for cooperation under corruptions | [📄](https://arxiv.org/abs/2603.01688) | - |
| HMS-SCP: Task-oriented multi-scale semantic communication for V2X cooperative perception | [📄](https://arxiv.org/abs/2608.14603) | - |
| Afformer: Adaptive feature fusion transformer for v2x cooperative perception under channel impairments | [📄](https://arxiv.org/abs/2605.01888) | - |
| Coop-WD: Cooperative perception with weighting and denoising for robust V2V communication | [📄](https://doi.org/10.1109/TITS.2026.3703542) | - |
| Enhancing collaborative perception through multi-scale contextual information integration | [📄](https://doi.org/10.1016/j.aap.2025.108367) | - |
| CoDS: Robust collaborative perception via expert-driven detection and BEV segmentation | [📄](https://arxiv.org/abs/2608.14085) | [💻](https://github.com/JinlongW128/CoDS) |

### 5.4.1 Domain and Model Incompatibility

| Name | Link | Code |
| --- | --- | --- |
| An extensible framework for open heterogeneous collaborative perception | [📄](https://openreview.net/forum?id=KkrDUGIASk) | [💻](https://github.com/yifanlu0227/HEAL) |
| Macp: Efficient model adaptation for cooperative perception | [📄](https://arxiv.org/abs/2310.16870) | [💻](https://github.com/PurdueDigitalTwin/MACP) |
| Coopre: Cooperative pretraining for v2x cooperative perception | [📄](https://arxiv.org/abs/2408.11241) | [💻](https://github.com/ucla-mobility/CooPre) |
| V2X-MAE: Decoder-free masked autoencoding with multi-view distillation for cooperative perception | [📄](https://doi.org/10.1016/j.aei.2026.105019) | - |
| Bridging the domain gap for multi-agent perception | [📄](https://arxiv.org/abs/2210.08451) | [💻](https://github.com/DerrickXuNu/MPDA) |
| Selective shift: Towards personalized domain adaptation in multi-agent collaborative perception | [📄](https://doi.org/10.1145/3746027.3754723) | - |
| Mdnet: Multimodal cooperative perception via spatial alignment of modal decision-making | [📄](https://doi.org/10.1109/JIOT.2025.3531145) | - |
| Agentalign: Misalignment-aware multi-agent perception for resilient cross-agent feature alignment | [📄](https://doi.org/10.1109/TITS.2026.3702538) | - |
| Avcpnet: An aav-vehicle collaborative perception network for 3-d object detection | [📄](https://doi.org/10.1109/TGRS.2025.3546669) | - |
| HyDRA: Hybrid domain-aware robust architecture for heterogeneous collaborative perception | [📄](https://arxiv.org/abs/2603.23975) | - |
| Toward robust collaborative 3-d object detection via two-stage cross-domain knowledge transfer in autonomous driving | [📄](https://doi.org/10.1109/TITS.2026.3710532) | - |
| STAMP: Scalable task- and model-agnostic collaborative perception | [📄](https://openreview.net/forum?id=8NdNniulYE) | [💻](https://github.com/taco-group/STAMP) |
| One is plenty: A polymorphic feature interpreter for immutable heterogeneous collaborative perception | [📄](https://arxiv.org/abs/2411.16799) | [💻](https://github.com/yuchen-xia/PolyInter) |
| NegoCollab: A common representation negotiation approach for heterogeneous collaborative perception | [📄](https://arxiv.org/abs/2510.27647) | [💻](https://github.com/scz023/NegoCollab) |
| You share beliefs, i adapt: Progressive heterogeneous collaborative perception | [📄](https://openaccess.thecvf.com/content/ICCV2025/html/Si_You_Share_Beliefs_I_Adapt_Progressive_Heterogeneous_Collaborative_Perception_ICCV_2025_paper.html) | [💻](https://github.com/sihaoo1/PHCP) |
| GT-Space: Enhancing heterogeneous collaborative perception with ground truth feature space | [📄](https://proceedings.iclr.cc/paper_files/paper/2026/hash/380a0b16a7e6f8c5010f798c9f2d3c61-Abstract-Conference.html) | - |
| Linking modality isolation in heterogeneous collaborative perception | [📄](https://arxiv.org/abs/2603.00609) | [💻](https://github.com/cxliu0314/CodeAlign) |

### 5.4.2 From Feature Fusion to Semantic Cooperative Reasoning

| Name | Link | Code |
| --- | --- | --- |
| V2x-unipool: Unifying multimodal perception and knowledge reasoning for autonomous driving | [📄](https://arxiv.org/abs/2506.02580) | [💻](https://github.com/snowwhite1016/V2X-UniPool) |
| V2x-vlm: End-to-end v2x cooperative autonomous driving through large vision-language models | [📄](https://arxiv.org/abs/2408.09251) | - |
| Colmdriver: Llm-based negotiation benefits cooperative autonomous driving | [📄](https://arxiv.org/abs/2503.08683) | [💻](https://github.com/cxliu0314/CoLMDriver) |
| Steering the future: Redefining intelligent transportation systems with foundation models | [📄](https://doi.org/10.23919/CHAIN.2024.100003) | - |

## Adversarial collaborative information

### 6.1 Fusion under Inference-Time Content Manipulation

| Name | Link | Code |
| --- | --- | --- |
| Adversarial attacks on multi-agent communication | [📄](https://openaccess.thecvf.com/content/ICCV2021/html/Tu_Adversarial_Attacks_on_Multi-Agent_Communication_ICCV_2021_paper.html) | - |
| Among us: Adversarially robust collaborative perception by consensus | [📄](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Among_Us_Adversarially_Robust_Collaborative_Perception_by_Consensus_ICCV_2023_paper.html) | [💻](https://github.com/coperception/ROBOSAC) |
| MADE: Malicious agent detection for robust multi-agent collaborative perception | [📄](https://doi.org/10.1109/IROS58592.2024.10801337) | - |
| Security-aware sensor fusion with mate: The multi-agent trust estimator | [📄](https://doi.org/10.1145/3719027.3765193) | - |
| A novel framework for robust collaborative perception against adversarial agents | [📄](https://hal.science/hal-05056870v2) | - |
| CP-Guard: Malicious agent detection and defense in collaborative bird’s eye view perception | [📄](https://arxiv.org/abs/2412.12000) | - |
| CP-Guard+: A new paradigm for malicious agent detection and defense in collaborative perception | [📄](https://openreview.net/forum?id=9MNzHTSDgh) | - |
| Pretend benign: A stealthy adversarial attack by exploiting vulnerabilities in cooperative perception | [📄](https://openaccess.thecvf.com/content/ICCV2025/html/Lin_Pretend_Benign_A_Stealthy_Adversarial_Attack_by_Exploiting_Vulnerabilities_in_ICCV_2025_paper.html) | - |
| From threat to trust: Exploiting attention mechanisms for attacks and defenses in cooperative perception | [📄](https://www.usenix.org/conference/usenixsecurity25/presentation/wang-chenyi) | [💻](https://github.com/WiSeR-Lab/SOMBRA_LUCIA) |
| GCP: Guarded collaborative perception with spatial-temporal aware malicious agent detection | [📄](https://doi.org/10.1109/TDSC.2026.3693684) | [💻](https://github.com/yihangtao/GCP) |
| All vehicles can lie: Efficient adversarial defense in fully untrusted-vehicle collaborative perception via pseudo-random bayesian inference | [📄](https://openaccess.thecvf.com/content/CVPR2026/html/Yu_All_Vehicles_Can_Lie_Efficient_Adversarial_Defense_in_Fully_Untrusted-Vehicle_CVPR_2026_paper.html) | - |
| Visual adversarial attack on vision-language models for autonomous driving, Machine Intelligence Research 23 (2026) 823–840 | [📄](https://doi.org/10.1007/s11633-026-1667-4) | - |

### 6.2 Fusion under Metadata and Communication Attacks

| Name | Link | Code |
| --- | --- | --- |
| Advgps: Adversarial gps for multi-agent perception attack | [📄](https://arxiv.org/abs/2401.17499) | [💻](https://github.com/jinlong17/AdvGPS) |
| Cp-freezer: Latency attacks against vehicular cooperative perception | [📄](https://arxiv.org/abs/2508.01062) | [💻](https://github.com/WiSeR-Lab/CP-FREEZER) |

### 6.3 Training-Time Manipulation

| Name | Link | Code |
| --- | --- | --- |
| BadMDA: Towards backdoor injection during domain adaptation to collapse multi-agent perception | [📄](https://doi.org/10.1145/3746027.3754780) | - |

### 6.4 Cross-Cutting Defense-Aware and Adaptive Attacks

| Name | Link | Code |
| --- | --- | --- |
| Learning mutual view information graph for adaptive adversarial collaborative perception | [📄](https://arxiv.org/abs/2602.19596) | [💻](https://github.com/yihangtao/MVIG) |
| Adversarial trust poisoning in vehicular collaborative perception | [📄](https://arxiv.org/abs/2605.22122) | - |
| Cp-uniguard: A unified, probability-agnostic, and adaptive framework for malicious agent detection and defense in multi-agent embodied perception systems | [📄](https://doi.org/10.1109/TMC.2026.3650980) | [💻](https://github.com/CP-Security/CP-uniGuard) |

### 6.5 Summary and Open Challenges

| Name | Link | Code |
| --- | --- | --- |
| From stealthy data fabrication to unsafe driving: Realistic scenario attacks on collaborative perception | [📄](https://arxiv.org/abs/2605.01301) | - |
| On data fabrication in collaborative vehicular perception: Attacks and countermeasures | [📄](https://arxiv.org/abs/2309.12955) | - |

## Datasets and evaluation

### 7.1 Datasets and Simulators

| Name | Link | Code |
| --- | --- | --- |
| OPV2V: An open benchmark dataset and fusion pipeline for perception with vehicle-to-vehicle communication | [📄](https://arxiv.org/abs/2109.07644) | [💻](https://github.com/DerrickXuNu/OpenCOOD) |
| V2X-Sim: Multi-agent collaborative perception dataset and benchmark for autonomous driving | [📄](https://arxiv.org/abs/2202.08449) | [💻](https://github.com/ai4ce/V2X-Sim) |
| V2X-ViT: Vehicle-to-everything cooperative perception with vision transformer | [📄](https://arxiv.org/abs/2203.10638) | [💻](https://github.com/DerrickXuNu/v2x-vit) |
| DAIR-V2X: A large-scale dataset for vehicle- infrastructure cooperative 3D object detection | [📄](https://arxiv.org/abs/2204.05575) | [💻](https://github.com/AIR-THU/DAIR-V2X) |
| V2V4Real: A real-world large-scale dataset for vehicle-to-vehicle cooperative perception | [📄](https://arxiv.org/abs/2303.07601) | [💻](https://github.com/ucla-mobility/V2V4Real) |
| V2X-Seq: A large- scale sequential dataset for vehicle-infrastructure cooperative perception and forecasting | [📄](https://arxiv.org/abs/2305.05938) | [💻](https://github.com/AIR-THU/DAIR-V2X-Seq) |
| V2X-Real: A large-scale dataset for vehicle-to-everything cooperative perception | [📄](https://arxiv.org/abs/2403.16034) | - |
| Rcooper: A real-world large-scale dataset for roadside cooperative perception | [📄](https://arxiv.org/abs/2403.10145) | [💻](https://github.com/AIR-THU/DAIR-RCooper) |
| Urbaning-v2x: A large-scale multi-vehicle, multi-infrastructure dataset across multiple intersections for cooperative perception | [📄](https://openreview.net/forum?id=iSwIkUqyqf) | [💻](https://github.com/thi-ad/UrbanIng-V2X) |
| Inscope: A new real-world 3d infrastructure-side collaborative perception dataset for open traffic scenarios | [📄](https://arxiv.org/abs/2407.21581) | [💻](https://github.com/xf-zh/InScope) |
| V2x-radar: A multi-modal dataset with 4d radar for cooperative perception | [📄](https://arxiv.org/abs/2411.10962) | [💻](https://github.com/yanglei18/V2X-Radar) |
| CATS-V2V: A real-world vehicle-to-vehicle cooperative perception dataset with complex adverse traffic scenarios | [📄](https://arxiv.org/abs/2511.11168) | - |
| M3CAD: Towards generic cooperative autonomous driving benchmark | [📄](https://arxiv.org/abs/2505.06746) | [💻](https://github.com/zhumorui/M3CAD) |
| Griffin: Aerial-ground cooperative detection and tracking dataset and benchmark | [📄](https://arxiv.org/abs/2503.06983) | [💻](https://github.com/wang-jh18-SVM/Griffin) |
| CRUISE: Cooperative reconstruction and editing in V2X scenarios using gaussian splatting | [📄](https://arxiv.org/abs/2507.18473) | [💻](https://github.com/SainingZhang/CRUISE) |
| Roadside-cooperative autonomous driving: From data platform to vision-language end-to-end reasoning | [📄](https://arxiv.org/abs/2608.21032) | - |
| Coopernaut: End-to-end driving with cooperative perception for networked vehicles | [📄](https://arxiv.org/abs/2205.02222) | [💻](https://github.com/UT-Austin-RPL/Coopernaut) |
| RAMACoDrive: A real-time asynchronous framework for cooperative perception with realistic V2X communication | [📄](https://doi.org/10.1109/TMC.2026.3664934) | [💻](https://github.com/UJS-IDT/RAMACoDrive) |

### 7.2 Robustness Testing Protocols

| Name | Link | Code |
| --- | --- | --- |
| From virtual environments to real-world trials: Emerging trends in autonomous driving | [📄](https://doi.org/10.1109/TITS.2026.3679248) | - |
| CoRTSG: A general and effective framework of risky testing scenario generation for cooperative perception in mixed traffic | [📄](https://doi.org/10.1016/j.aap.2025.108163) | [💻](https://github.com/RadetzkyLi/CoRTSG) |
| Generating risk scenarios adverse to cooperative vehicle-infrastructure perception: An optimization-based framework | [📄](https://doi.org/10.1016/j.aap.2026.108742) | - |

### 7.3 Downstream Task Coverage

| Name | Link | Code |
| --- | --- | --- |
| Adver-city: Open-source multi-modal dataset for collaborative perception under adverse weather conditions | [📄](https://arxiv.org/abs/2410.06380) | [💻](https://github.com/QUARRG/Adver-City) |
| Collaborative multi-object tracking with conformal uncertainty propagation | [📄](https://arxiv.org/abs/2303.14346) | [💻](https://github.com/susanbao/mot_cup) |
| Collaborative semantic occupancy prediction with hybrid feature fusion in connected automated vehicles | [📄](https://arxiv.org/abs/2402.07635) | - |
| UniMM-V2X: Moe-enhanced multi-level fusion for end-to-end cooperative autonomous driving | [📄](https://doi.org/10.1609/aaai.v40i11.37870) | [💻](https://github.com/Souig/UniMM-V2X) |
| Laco: Adaptive latent communication for collaborative driving | [📄](https://arxiv.org/abs/2605.22504) | - |
| CooperDrive: Enhancing driving decisions through cooperative perception | [📄](https://arxiv.org/abs/2604.14454) | - |
| Physics-informed trajectory prediction for autonomous driving under missing observation | [📄](https://doi.org/10.24963/ijcai.2024/756) | - |
| Predict and resist: Long-term accident anticipation under sensor noise | [📄](https://doi.org/10.1609/aaai.v40i1.37045) | - |
| LATTE: A real-time lightweight attention-based traffic accident anticipation engine | [📄](https://doi.org/10.1016/j.inffus.2025.103173) | [💻](https://github.com/icypear/LATTE) |

## Cross-cutting references

### 8.5 Deployment-Level Validation and Assurance

| Name | Link | Code |
| --- | --- | --- |
| From optimizable to interactable: Mixed digital twin-empowered testing of vehicle-infrastructure cooperation systems | [📄](https://doi.org/10.1016/j.trc.2026.105977) | - |

---

## 📎 Supplementary R1–R3 Evidence Tables

> **Important:** R1–R3 are evidence descriptors rather than method-quality scores. The Baselines column was checked against accessible original/official paper text, appendices, archival pages, or author-maintained sources. Where exact baseline names were not exposed by the accessible source, this is stated explicitly rather than inferred. R1–R3 locator fields have been populated from accessible original/official papers. When reliable numeric section labels were not exposed by the accessible version, named method/experiment sections are reported instead of guessed numbering.

### Supplementary Table S2-A — Incomplete collaborative information

| Method | Venue / Year | Condition subtype | Fusion stage | Assessment target / signal | Adaptive response | R1 evidence | R2 evidence | R3 evidence | Baselines |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Where2comm | NeurIPS-2022 | Selective sharing | Intermediate | Evidence availability / relevance: Spatial-confidence proxy and budget | Select agents and regions | P — Spatial confidence is used as an incompleteness/relevance proxy; the survey notes that such proxies are not independently validated as measures of incompleteness.<br>Source locator: Sec. 4.2; Fig. 6 | E — The proxy and budget directly determine agent/region selection.<br>Source locator: Secs. 4.3–4.4; Fig. 2; Alg. 1 | E — Survey Table 3 codes R3=E.<br>Source locator: Sec. 5.2; Figs. 3–5; App. Table 3 | No Collaboration; Late Fusion; When2com; V2VNet; V2X-ViT; DiscoNet |
| CoSDH | CVPR-2025 | Selective sharing | Hybrid | Evidence demand / supply: Supply–demand proxies | Region selection and hybrid collaboration | P — Supply–demand signals are treated as incompleteness proxies; the survey notes that these proxies are not independently validated as measures of incompleteness.<br>Source locator: Sec. 3.3; Fig. 2 | E — Supply–demand proxies directly drive region selection and hybrid collaboration.<br>Source locator: Secs. 3.3–3.5; Figs. 2–4 | E — Survey Table 3 codes R3=E.<br>Source locator: Secs. 4.2–4.4; Table 1; Fig. 5; Tables 2–3 | No Fusion; Early Fusion; Late Fusion; When2com; F-Cooper; AttFuse; V2VNet; DiscoNet; V2X-ViT; Where2comm; CoAlign |
| CoST | ICCV-2025 | Selective sharing | Intermediate | Evidence redundancy / relevance: Saliency and temporal-change proxies | Suppress redundant transmission | P — Saliency and temporal-change signals are proxy-level evidence rather than an independently validated incompleteness estimate in the survey coding.<br>Source locator: Sec. 3.2; Alg. 1 | E — The proxies directly suppress redundant transmission.<br>Source locator: Secs. 3.2–3.3; Alg. 1; Figs. 2, 4 | E — Survey Table 3 codes R3=E.<br>Source locator: Secs. 4.3, 4.5–4.6; Table 1; Figs. 5–6 | No Fusion; Early Fusion; Late Fusion; DiscoNet; V2VNet; V2X-ViT; Where2comm; AttFusion (OPV2V); CoBEVT; TransIFF; What2comm |
| PragComm | TPAMI-2026 | Selective sharing | Intermediate | Task utility / evidence relevance: Task-utility proxy | Select messages, representations, and collaborators | P — Task utility is used as a proxy; Sec. 4.4 notes that it is not independently validated as a measure of incompleteness.<br>Source locator: Method sections “Pragmatic Message Selection” and “Pragmatic Collaborator Selection” | E — Task-utility estimates directly drive message, representation, and collaborator selection.<br>Source locator: Method section “Pragmatic Collaboration” (message selection / representation / collaborator selection) | E — Survey Table 3 codes R3=E.<br>Source locator: Experimental evaluation on V2V4Real, OPV2V, and V2X-Sim2.0; perception–communication trade-off results | No Collaboration; V2X-ViT; Where2comm |
| WhisperNet | CVPR-2026 | Selective sharing | Intermediate | Receiver information need: Receiver-utility proxy | Issue dynamic collaborative requests | P — Receiver utility is coded as a proxy-level assessment rather than independently validated incompleteness evidence.<br>Source locator: Secs. 3.2–3.3; Figs. 3–4 | E — Receiver utility directly triggers dynamic collaborative requests.<br>Source locator: Secs. 3.3–3.4; Figs. 3–5 | E — Survey Table 3 codes R3=E.<br>Source locator: Secs. 4.2–4.3; Tables 2–5 | OPV2V intermediate-fusion baseline; Where2comm; ERMVP; CoSDH; F-Cooper; V2VNet; V2X-ViT |
| CoLC | CVPR-2026 | Selective sharing | Early | Task-relevant content: Foreground-importance proxy | Sparse transmission and completion | P — Foreground importance is a proxy for task-relevant evidence need rather than an independently validated completeness estimate.<br>Source locator: Sec. 4.1; Fig. 2 | E — Foreground-importance estimates directly drive sparse transmission and completion.<br>Source locator: Secs. 4.1–4.2.2; Figs. 2–4 | E — Survey Table 3 codes R3=E.<br>Source locator: Secs. 5.2–5.3; Table 1; Fig. 5; Tables 2–4 | No Fusion; Late Fusion; V2VNet; DiscoNet; AttFusion; V2X-ViT; Where2comm; CoBEVT; ERMVP |
| V2X-INCOP | T-IV-2024 | Communication loss | Intermediate | Message availability: Observed interruption and temporal history | Predict unavailable features | E — Message interruption is directly observed; Sec. 4.4 explicitly identifies this as sufficient R1 evidence.<br>Source locator: Sec. III; Fig. 2; Table I | E — Observed interruption and temporal history directly trigger feature prediction.<br>Source locator: Sec. IV; Figs. 3–4 | E — Survey Table 3 codes R3=E.<br>Source locator: Sec. V; Tables II–III; Figs. 6, 9 | Individual perception; F-Cooper; V2X-ViT; Where2comm; V2VNet; DiscoNet; Kalman filter |
| AccBEV | T-ITS-2025 | Communication loss | Intermediate | Channel loss / feature availability: Channel-loss proxy | Adapt fusion and recover affected features | P — Channel loss is represented through a proxy; the survey codes the condition assessment as partial evidence.<br>Source locator: Method section on adaptive communication-loss modeling | E — The channel-loss proxy directly drives fusion adaptation and feature recovery.<br>Source locator: Method section on adaptive fusion / recovery under communication loss | E — Survey Table 3 codes R3=E.<br>Source locator: Experiments section; communication-loss / SNR robustness comparisons | CVT (No Fusion); CoBEVT; Where2comm; AttFuse; DiscoNet; fixed-SNR variants |
| V2X-JEPA | IoTJ-2026 | Communication loss | Intermediate | Feature reliability under loss: Reliability-attention proxy | Masking-based learning and spatial fusion | P — Reliability attention is proxy-level condition evidence in the survey coding.<br>Source locator: Method section on cooperative masking and grid spatial-attention fusion | E — Reliability attention is directly linked to masking-based learning and spatial fusion.<br>Source locator: Method section on masking-driven training and grid spatial-attention fusion | P — Survey Table 3 codes R3=P.<br>Source locator: Experiments on OPV2V and DAIR-V2X; packet-loss robustness experiment (20% loss) | V2X-ViT; CoCa3D; CooPre |
| SiCP | IROS-2024 | Collaborator loss | Intermediate | Collaborator availability: Received-feature presence | Cooperative fusion or ego-only inference | E — Received-feature presence directly observes collaborator availability; Sec. 4.4 identifies this as sufficient R1 evidence.<br>Source locator: Secs. I-A, III-A; Figs. 1(c), 2 | E — Feature presence directly switches between cooperative fusion and ego-only inference.<br>Source locator: Sec. III-A; Figs. 2–3 | P — Survey Table 3 codes R3=P; Sec. 4.4 notes that endpoint-only/limited stress tests provide partial evidence.<br>Source locator: Secs. IV-A–IV-B; Tables I–II | PointPillars; Late Fusion; F-Cooper; AttFuse; V2X-ViT; CoBEVT |
| ICPB | ESWA-2026 | Collaborator loss | Hybrid | Collaborative uncertainty: Epistemic-uncertainty proxy | Balance individual and CP | P — Epistemic uncertainty is treated as a proxy rather than a directly validated measure of collaborator-loss incompleteness.<br>Source locator: Sec. “Proposed methods”; Fig. 2 | E — The uncertainty proxy directly balances individual and cooperative perception.<br>Source locator: Sec. “Proposed methods”; Fig. 2 | E — Survey Table 3 codes R3=E.<br>Source locator: Sec. “Experiments”; main quantitative comparisons | Single-agent baseline; collaboration-tuned CP baseline(s) (exact method names not exposed in accessible publisher text) |
| DisCo | Inf. Sci.-2026 | Collaborator loss | Intermediate | Agent availability / configuration: Dynamic agent configuration | Adapt to joining or exiting agents | P — Dynamic agent configuration is coded as partial R1 evidence in Table 3; independent condition-validation details are not reported in the survey table.<br>Source locator: Sec. “Instantiation methodology”; Fig. 1(d); MFI/MFP modules | E — Dynamic agent configuration directly changes collaboration as agents join or exit.<br>Source locator: Sec. “Instantiation methodology”; MFP projection pool / dynamic network adaptation | E — Survey Table 3 codes R3=E.<br>Source locator: Sec. “Experiments”; Sec. “Discussion: enhancing the performance of previous methods” | Classic CP methods adapted under the DisCo paradigm; single-agent / heterogeneous configurations (exact method names not exposed in accessible publisher text) |
| CAML | NeurIPS-2025 | Missing modality | Intermediate | Modality availability (prespecified): Prespecified reduced-modality setting | Distill full-modality knowledge | – — The reduced-modality condition is prespecified rather than assessed at runtime; Table 3 reports no explicit R1 evidence.<br>Source locator: Sec. 3; Figs. 1–2 | P — The response is predefined/partially linked to the condition rather than driven by a runtime assessment.<br>Source locator: Sec. 3; Fig. 2 | P — Survey Table 3 codes R3=P.<br>Source locator: Secs. 5.1–5.2; Figs. 3–5; Table 1 | AML; FCN |
| SiMO | ICLR-2026 | Missing modality | Intermediate | Modality availability: Observed modality availability | Adapt fusion to remaining branches | E — Modality availability is explicitly observed before adapting fusion.<br>Source locator: Sec. 3.3; Fig. 2(b) | E — Observed modality availability directly changes fusion over the surviving branches.<br>Source locator: Secs. 3.3–3.4.2; Figs. 2–3 | E — Survey Table 3 codes R3=E.<br>Source locator: Sec. 4.2; Tables 1–2; Fig. 4 | BM2CP; BEVFusion + Pyramid Fusion / RD; UniBEV + CNW + Modality Dropout / RD; AttFusion; HEAL (Pyramid Fusion) |

### Supplementary Table S2-B — Unreliable collaborative information

| Method | Venue / Year | Condition subtype | Fusion stage | Assessment target / signal | Adaptive response | R1 evidence | R2 evidence | R3 evidence | Baselines |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CoAlign | ICRA-2023 | Spatial | Intermediate | Spatial alignment: Cross-agent geometric-consistency proxy | Feature alignment | P — Geometric consistency guides correction but is not independently validated against ground-truth condition/residual error in Sec. 5.5.<br>Source locator: Sec. IV-C; Fig. 3 | E — The consistency proxy directly drives feature alignment.<br>Source locator: Secs. IV-C–IV-D; Figs. 2–3 | E — Survey Table 4 codes R3=E.<br>Source locator: Sec. V-C; Tables I–II; Figs. 4–5 | Attentive Fusion; Cooper; F-Cooper; V2VNet; FPV-RCNN; DiscoNet; V2X-ViT; MASH; Robust V2VNet |
| RoCo | ACM MM-2024 | Spatial | Late | Pose / spatial residual: Object-correspondence residuals | Iterative matching and pose refinement | E — Sec. 5.5 states that correspondence-based pose residuals are evaluated, supporting sufficient R1 evidence.<br>Source locator: Secs. 4.2.2–4.3; Figs. 3–4, 7 | E — Correspondence residuals directly drive iterative matching and pose refinement.<br>Source locator: Sec. 4.3; Figs. 3–4 | E — Survey Table 4 codes R3=E.<br>Source locator: Sec. 5.3; Table 1; Sec. 5.5; Table 4; Fig. 7 | F-Cooper; FPV-RCNN; V2VNet; Self-Att; V2X-ViT; CoAlign; CoBEVFlow |
| CoRA | AAAI-2026 | Spatial | Hybrid | Spatial displacement / semantic relevance: Semantic-relevance proxy | Object-level correction with feature fusion | P — Semantic relevance guides correction but is not independently validated against the targeted spatial error in Sec. 5.5.<br>Source locator: Method section: object-level correction branch / semantic relevance | E — The proxy directly drives object-level correction with feature fusion.<br>Source locator: Method section: feature-level fusion + object-level correction branches | E — Survey Table 4 codes R3=E.<br>Source locator: Experiments section; pose-error / extreme-scenario comparison | Single-Vehicle; CoAlign; Where2comm; ERMVP; CoSDH; V2X-ViT |
| SyncNet | ECCV-2022 | Temporal | Intermediate | Temporal freshness / delay: Delay and temporal context | Predict current collaborative features | E — Sec. 5.5 identifies explicit delay/temporal information as sufficient R1 evidence.<br>Source locator: Sec. 3.1; Fig. 2 | E — Delay and temporal context directly drive prediction of current collaborative features.<br>Source locator: Sec. 3.2; Figs. 3–5; Alg. 1 | E — Survey Table 4 codes R3=E.<br>Source locator: Sec. 4.3; Figs. 6–9; Table 1 | No Collaboration; DiscoNet (latency-unaware); Late Collaboration + Kalman Filter; V2VNet; Transformer-based fusion |
| CoBEVFlow | NeurIPS-2023 | Temporal | Intermediate | Temporal motion inconsistency: BEV motion discrepancy | Flow-based feature warping | E — Sec. 5.5 treats explicit temporal information/motion discrepancy as sufficient R1 evidence.<br>Source locator: Sec. 3 (BEV-flow formulation / temporal offset modeling) | E — BEV motion discrepancy directly drives flow-based feature warping.<br>Source locator: Sec. 3 (BEV-flow-based feature reassignment and alignment) | E — Survey Table 4 codes R3=E.<br>Source locator: Sec. 4; IRV2V and DAIR-V2X quantitative / asynchrony-robustness experiments | Single; Late Fusion; V2VNet; V2X-ViT; DiscoNet; Where2comm; Where2comm + SyncNet |
| TraF-Align | CVPR-2025 | Temporal | Intermediate | Temporal alignment: Trajectory and historical-feature proxies | Motion-aware temporal alignment | P — Trajectory and historical-feature cues are proxy-level assessment signals in the survey coding.<br>Source locator: Secs. 3.3–3.4; Fig. 3 | E — The proxies directly drive motion-aware temporal alignment.<br>Source locator: Secs. 3.3–3.4; Figs. 3–4 | E — Survey Table 4 codes R3=E.<br>Source locator: Sec. 4.2; Table 1; Fig. 5 | SyncNet; FFNet; CoBEVFlow |
| MGMP | T-ITS-2026 | Temporal | Intermediate | Spatiotemporal consistency: Multi-frame and multi-agent context | Joint spatio-temporal aggregation | P — Multi-frame and multi-agent context is used as a proxy rather than an independently validated temporal-error estimate.<br>Source locator: Method section: multi-frame / multi-agent motion-context modeling | E — The context directly drives joint spatio-temporal aggregation.<br>Source locator: Method section: multi-grained motion prediction and spatiotemporal aggregation | E — Survey Table 4 codes R3=E.<br>Source locator: Experiments on V2XSet, OPV2V, and DAIR-V2X; main quantitative comparisons | State-of-the-art CP baselines on V2XSet, OPV2V, and DAIR-V2X (exact method names not exposed in accessible publisher text) |
| V2X-R | CVPR-2025 | Observation | Intermediate | Observation quality under weather: Weather-resilient radar evidence | Guide diffusion-based LiDAR restoration | P — Radar evidence guides restoration but is not coded as an independently validated observation-quality estimate.<br>Source locator: Secs. 4.1, 4.3; Fig. 5 | E — Radar evidence directly guides diffusion-based LiDAR restoration.<br>Source locator: Secs. 4.2–4.3; Fig. 4 | E — Survey Table 4 codes R3=E.<br>Source locator: Secs. 5.3–5.4; Tables 4–5; Fig. 2(b) | V2X-ViT; AttFuse; Where2comm; SCOPE; CoBEVT; CoAlign; AdaFusion; SiCP |
| Coop-WD | T-ITS-2026 | Observation | Intermediate | Source / observation reliability: Vehicle-level reliability proxy | Weighting and conditional diffusion denoising | P — Sec. 5.5 states that reliability maps/proxies guide fusion but are not independently validated against ground-truth conditions or residual errors.<br>Source locator: Sec. IV-B; Fig. 4 | E — The reliability proxy directly drives weighting and conditional diffusion denoising.<br>Source locator: Sec. IV-B; Figs. 3–4 | E — Survey Table 4 codes R3=E.<br>Source locator: Sec. V; Tables I–III | Single AV; Coop (CNN-based AE + distortion-in-loop); Coop-W; Coop-D |
| CoDS | ACM MM-2026 | Observation | Intermediate | Fusion quality / reliability: Collaborative-reliability proxy | Adaptive detection–segmentation fusion | P — Sec. 5.5 treats the collaborative-reliability map as proxy-level R1 evidence without independent condition validation.<br>Source locator: Sec. 3 (Collaborative Reliability Map, CoRM) | E — The reliability proxy directly drives adaptive detection–segmentation fusion.<br>Source locator: Sec. 3 (CoRM-guided S-MoE and BTCI modules) | E — Survey Table 4 codes R3=E.<br>Source locator: Sec. 4 (experiments on OPV2V/V2V4Real under multi-source noise) | AttFuse; CoAlign; CoBEVT; single-task / multi-task comparison variants |
| MPDA | ICRA-2023 | Representation | Intermediate | Representation compatibility: Cross-agent domain-discrepancy proxy | Representation adaptation | P — Cross-agent domain discrepancy is coded as proxy-level representation-compatibility evidence.<br>Source locator: Sec. III; Fig. 2; Sec. III-A (Learnable Feature Resizer) | E — The discrepancy proxy directly drives representation adaptation.<br>Source locator: Sec. III; Fig. 2; Learnable Resizer + Sparse Cross-Domain Transformer | E — Survey Table 4 codes R3=E.<br>Source locator: Sec. IV; V2XSet quantitative comparison / ablation tables | No Fusion; Late Fusion; V2X-ViT; V2X-ViT (fine-tuned); V2X-ViT + Resizer |
| HEAL | ICLR-2024 | Representation | Intermediate | Representation compatibility: Agent-specific representation difference | Heterogeneous feature alignment | P — Representation difference is used to guide alignment but is not independently validated as a calibrated compatibility estimate.<br>Source locator: Method section: unified feature space / backward alignment | E — Representation differences directly guide heterogeneous feature alignment.<br>Source locator: Method section: Pyramid Fusion + backward alignment | P — Sec. 5.5 states that HEAL has limited heterogeneity configurations/fixed settings rather than systematic multi-severity evaluation.<br>Source locator: Experiments on OPV2V-H and DAIR-V2X; heterogeneous-agent integration comparisons | F-Cooper; AttFusion; DiscoNet; V2X-ViT; CoBEVT; HM-ViT |
| STAMP | ICLR-2025 | Representation | Intermediate | Representation compatibility: Task- and model-specific representations | Shared protocol-space adaptation | P — Task/model-specific representation differences act as proxy-level compatibility evidence.<br>Source locator: Secs. 3.2–3.3; Fig. 1 | E — The representation signal directly motivates adaptation into a shared protocol space.<br>Source locator: Secs. 3.2–3.4; Fig. 1 | P — Sec. 5.5 states that STAMP is evaluated on selected heterogeneity configurations/fixed settings, supporting only partial R3 evidence.<br>Source locator: Secs. 4.2–4.4; Tables 2–4; Figs. 3–4 | Late Fusion; Calibrator; End-to-End Training; HEAL |
| PHCP | ICCV-2025 | Representation | Intermediate | Representation compatibility: Cross-agent domain discrepancy | Few-shot online adapter adaptation | E — Table 4 codes cross-agent domain discrepancy as sufficient R1 evidence for PHCP.<br>Source locator: Sec. 3 (PHCP framework / inference-time feature-domain discrepancy) | E — The discrepancy directly triggers few-shot online adapter adaptation.<br>Source locator: Sec. 3 (few-shot adapter self-training); framework figure | P — Sec. 5.5 states that PHCP has limited heterogeneity configurations/fixed corruption settings, supporting partial R3 evidence.<br>Source locator: Sec. 4.3; Tables 1–2 | Direct Fusion; F-Cooper; CoBEVT; AttFusion; V2X-ViT; HEAL |
| AgentAlign | T-ITS-2026 | Representation | Intermediate | Cross-modal representation compatibility: Cross-modal consistency and depth-variation proxies | Align and reweight heterogeneous-agent features | P — Sec. 5.5 states that cross-modal consistency signals guide correction/fusion but are not independently validated against ground-truth conditions or residual errors.<br>Source locator: Sec. 3.3; Fig. 3 | E — The proxies directly drive feature alignment and reweighting.<br>Source locator: Secs. 3.3–3.4; Figs. 2–3 | P — Sec. 5.5 states that AgentAlign has limited heterogeneity configurations/fixed settings, supporting partial R3 evidence.<br>Source locator: Secs. 4.2–4.3; Tables 1–3 | Cross-agent feature-alignment / CP baselines under misalignment (exact method names not exposed in accessible publisher text) |

### Supplementary Table S2-C — Adversarial collaborative information

| Method | Venue / Year | Condition subtype | Fusion stage | Assessment target / signal | Adaptive response | R1 evidence | R2 evidence | R3 evidence | Baselines |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ROBOSAC | ICCV-2023 | Inference-time | Intermediate | Cross-agent consistency: Subset consensus | Select consistent collaborators | E — Sec. 6.5 states that ROBOSAC evaluates attacker/trust estimates against known attack states, supporting R1=E.<br>Source locator: Sec. 3; Fig. 1 (hypothesize-and-verify consensus) | E — Subset consensus directly drives collaborator selection.<br>Source locator: Sec. 3 (ROBOSAC sampling / consensus verification) | P — Sec. 6.5 states that ROBOSAC lacks systematic task-level evaluation across controlled severity levels, hence R3=P.<br>Source locator: Experiments section; success-rate and mAP evaluations under attacks | Upper-bound++; PGD-trained white-box defense; C&W on PGD-trained black-box defense; Lower-bound (individual perception); No Defense |
| MADE | IROS-2024 | Inference-time | Intermediate | Consistency / anomaly evidence: Output and reconstruction consistency | Remove malicious agents | E — Sec. 6.5 states that MADE evaluates attacker/trust estimates against known attack states, supporting R1=E.<br>Source locator: Method section: double-hypothesis test with match-loss and collaborative-reconstruction statistics | E — Consistency assessment directly removes malicious agents.<br>Source locator: Method section: semi-supervised anomaly detection and malicious-agent removal | E — Sec. 6.5 states that MADE reports task retention across multiple attack strengths, attacker counts, or temporal settings.<br>Source locator: Experiments on V2X-Sim and DAIR-V2X; comparison with baseline defenses / Oracle | Oracle defender; ROBOSAC; no-defense / attacked-CP reference |
| CP-Guard | AAAI-2025 | Inference-time | Intermediate | Cross-agent consistency: Collaborative consistency | Detect and eliminate malicious agents | P — Sec. 6.5 states that consistency signals drive defense but condition-identification performance against attack labels is not independently reported.<br>Source locator: Method; Collaborative Consistency Loss Verification; Eqs. (2)–(5) | E — Collaborative consistency directly drives detection and elimination of malicious agents.<br>Source locator: Method; Algorithm 1 (PASAC) | P — Sec. 6.5 states that CP-Guard lacks systematic task-level evaluation across controlled severity levels, hence R3=P.<br>Source locator: Quantitative Evaluation; Table 1; Fig. 3; Ablation Table 2 | Upper bound; Lower bound; No Defense; ROBOSAC; PASAC (ours) |
| CP-Guard+ | arXiv-2025 | Inference-time | Intermediate | Malicious-source separability: Feature separability | Classify and remove malicious agents | E — Sec. 6.5 states that CP-Guard+ evaluates attacker/trust estimates against known attack states, supporting R1=E.<br>Source locator: Method section: feature-level detector / Dual-Centered Contrastive Loss (DCCLoss) | E — Feature separability directly drives classification and removal of malicious agents.<br>Source locator: Method section: malicious-feature classification and removal | E — Sec. 6.5 states that CP-Guard+ reports task retention across multiple attack strengths, attacker counts, or temporal settings.<br>Source locator: Quantitative Results; Tables 1–2 | Upper-bound; MADE; ROBOSAC; No Defense |
| Dao–Malis | IV-2025 | Inference-time | Late | Object-message validity: Trusted-RSU validation | Filter suspicious object messages | P — Sec. 6.5 states that validation signals drive defense but condition-identification performance against attack labels is not independently reported.<br>Source locator: Method section: trusted-RSU / object-message validation | E — Trusted-RSU validation directly filters suspicious object messages.<br>Source locator: Method section: validation-driven filtering of suspicious object messages | E — Sec. 6.5 states that Dao–Malis reports task retention across multiple attack strengths, attacker counts, or temporal settings.<br>Source locator: Experiments / evaluation section; adversarial object-message comparison | Adversarial-defense comparison baselines not exposed in accessible HAL metadata; PDF-level verification required |
| MATE | CCS-2025 | Inference-time | Late | Source trust: Bayesian trust estimation | Trust-weighted object fusion | E — Sec. 6.5 states that MATE evaluates attacker/trust estimates against known attack states, supporting R1=E.<br>Source locator: Secs. 5.2–6.4; Figs. 4–5 | E — Bayesian trust estimates directly drive trust-weighted object fusion.<br>Source locator: Sec. 7; Figs. 4–5 | P — Sec. 6.5 states that MATE lacks systematic task-level evaluation across controlled severity levels, hence R3=P.<br>Source locator: Secs. 8.1–8.4; Tables 1–2; Figs. 8–9; App. Figs. 16–18 | Benign (unattacked) reference; No Security |
| LUCIA | USENIX Sec.-2025 | Content / defense-aware | Intermediate | Feature trustworthiness: Attention trustworthiness | Suppress adversarial features | E — Sec. 6.5 states that LUCIA evaluates attacker/trust estimates against known attack states, supporting R1=E.<br>Source locator: Defense section: LUCIA trustworthiness-aware attention mechanism | E — Attention trustworthiness directly suppresses adversarial feature contributions.<br>Source locator: Defense section: trustworthiness-aware feature suppression / attention reweighting | E — Sec. 6.5 states that LUCIA reports task retention across multiple attack strengths, attacker counts, or temporal settings.<br>Source locator: Evaluation; Tables 4–5 (TOR/MOR defense); Table 3 attack context | ROBOSAC; undefended CP; victim CP models including Attentive Fusion, CoAlign, Where2comm, and V2VAM |
| GCP | TDSC-2026 | Inference-time | Intermediate | Anomaly evidence: Spatial–temporal anomalies | Detect and suppress malicious agents | E — Sec. 6.5 states that GCP evaluates attacker/trust estimates against known attack states, supporting R1=E.<br>Source locator: Secs. IV-B–IV-D; Fig. 3 | E — Spatial–temporal anomaly evidence directly drives detection and suppression of malicious agents.<br>Source locator: Secs. IV-A–IV-D; Fig. 3 | E — Sec. 6.5 states that GCP reports task retention across multiple attack strengths, attacker counts, or temporal settings.<br>Source locator: Sec. V-B; Tables I–II; Fig. 5 | ROBOSAC; MADE; No Defense; Upper-bound; Lower-bound |
| CP-UniGuard | TMC-2026 | Inference-time | Intermediate | Cross-agent consistency: Adaptive consistency | Detect and remove malicious sources | P — Sec. 6.5 states that consistency signals drive defense but condition-identification performance against attack labels is not independently reported.<br>Source locator: Sec. 4.2; Eqs. (14)–(20) | E — Adaptive consistency directly drives malicious-source detection and removal.<br>Source locator: Secs. 4.1–4.3; Alg. 2 | P — Sec. 6.5 states that CP-UniGuard lacks systematic task-level evaluation across controlled severity levels, hence R3=P.<br>Source locator: Sec. 5.2; Tables 1–2; Figs. 2–4 | Upper-bound++; PGD-trained white-box defense; ROBOSAC; C&W-on-PGD-trained black-box defense; Lower-bound; No Defense |
| PRBI | CVPR-2026 | Inference-time | Intermediate | Temporal consistency / source trust: Temporal discrepancy and Bayesian inference | Identify untrusted vehicles | E — Sec. 6.5 states that PRBI evaluates attacker/trust estimates against known attack states, supporting R1=E.<br>Source locator: Method section: temporal perceptual discrepancy + Bayesian inference; supplementary Sec. 1 (Hypothesis Verification Experiments) | E — Temporal discrepancy and Bayesian inference directly identify untrusted vehicles.<br>Source locator: Method section: pseudo-random grouping and Bayesian malicious-vehicle identification | E — Sec. 6.5 states that PRBI reports task retention across multiple attack strengths, attacker counts, or temporal settings.<br>Source locator: Experiments section; main defense comparisons; supplementary Sec. 1 | Upper-Bound (no attack); attack-only / no-defense reference; Lower-Bound (single vehicle); ROBOSAC; PASAC; fusion-backbone comparisons (Mean/Max/Sum/V2VNet/DiscoNet) |

---

## 🤝 Contributing

Corrections, archival paper links, verified code repositories, and evidence-locator updates are welcome. For R1–R3 updates, please provide the exact section, table, figure, appendix, or page in the original paper supporting the proposed change.

## 📝 Citation

Please cite the associated survey if you use this literature organization or evidence matrix. Replace the following placeholder with the final archival citation after publication.

```bibtex
@article{xuRobustCPSurvey2026,
  title   = {Robust Vehicular Cooperative Perception: A Survey of Fusion Strategies under Incomplete, Unreliable, and Adversarial Conditions},
  author  = {Xu, Qian and Gao, Shang and Zhang, Jiaxun and Xie, Yumu and Liu, Xingcheng and Xu, Chengzhong and Li, Zhenning},
  year    = {2026},
  note    = {Archival publication information to be updated}
}
```
