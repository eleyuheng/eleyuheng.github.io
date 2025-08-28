---
title: "Project highlights"
permalink: /projects/
author_profile: true
---


### Real-Time Scheduling for Adaptive Embedded Applications
This series of study focuses on theory and algorithms about scheduling the adaptive applications running on embedded computing systems. Adaptive applications constitute an important class of embedded applications that are able to flexibly adjust their execution volume and quality to accommodate, or impact, the scarce resource usage in embedded computing scenarios. My work starts from a theory for optimal time-slack reclamation in dynamic scheduling of the imprecise-computation applications [[ASPDAC'08](https://doi.org/10.1109/ASPDAC.2008.4483993)], then extends to leakage power consieration when leveraging DVFS for quality optimization [[DAC'10](https://doi.org/10.1145/1837274.1837396)], which is further extended to multi-processor scheduling [[TC'12](https://doi.org/10.1109/TC.2012.194)] and thermal constraints [[DATE'14](https://doi.org/10.7873/DATE.2014.304)]. These works assume a monotonically increasing relationship between the application processing cycles and the execution quality, while explicitly specifying quality-cycle relationship is helpful for specific but meaningful cases. The work in [[CF'17](https://doi.org/10.1145/3075564.3075577), a CCF-C conference] deals with exponential quality functions, and wins the best paper award. This is followed by [[TC'20](https://doi.org/10.1109/TC.2020.2997242)], a milestone summary of the theoretical and algorithmic endeavor of the aforementioned problems. Subsequently, recent works turn to data-driven, or AI-based, scheduling approaches for the adaptive applications [[TCAD'22](https://doi.org/10.1109/TCAD.2022.3142188)], as well as instantiations from theoretical study to real-world applications, including adaptive stereo vision [[TECS'20](https://doi.org/10.1145/3372784)] and early-exit neural networks [[DATE'25](https://doi.org/10.23919/DATE64628.2025.10992707)].

![Adaptive Application Scheduling!](/images/AdaptiveApplications.png "Adaptive Application Scheduling")

### Embedded AI
Contemporary pathways to realize and optimize AI on embedded devices are model-level miniaturization, architecture-level reformation, and system-level operational decision-making. Most of my research focus on system-level optimization, leveraging the robustness of neural networks in terms of performance under various resource conditions. For example, reducing the number of invocations of deep reinforcement learning agent for embedded processing controlling could perform almost as well as full agent awakening [[TC'24](https://doi.org/10.1109/TC.2024.3465933)]; Co-considering DVFS when deciding early exits of a deep neural network could lead to both energy reduction and network performance improvement, compared to early-exit decision-makings that are system-agnostic [[DATE'25](https://doi.org/10.23919/DATE64628.2025.10992707)]. In addition, I am also into some model-level [[DAC'21](https://doi.org/10.1109/DAC18074.2021.9586109)] and architecture-level [[TCAD'22](https://doi.org/10.1109/TCAD.2022.3198246)] work to optimize AI for embedded computing.

![Embedded AI!](/images/EmbeddedAI.png "Embedded AI")

### AI-Assisted EDA
I also exploite the possibility of applying AI into Electronic Design Automation (EDA). My work scatters in different EDA stages, including LLM-based HLS, GNN-based placement and routing, verification, etc. But more to come. Stay tuned!

![AI-Assisted EDA!](/images/AIAssistedEDA.png "AI-Assisted EDA")
