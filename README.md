# Awesome Agentic Manufacturing

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A curated list of 164 peer-reviewed studies on LLM-based agentic AI in manufacturing, from the scoping review by Moradzadeh Farid and Shafiee (2026).

**Tags:** task type · agent organisation·decision engine · human authority · test setting — defined in [codebook.md](codebook.md).

**Data:** [`screened_records.csv`](screened_records.csv) (all 815 screened records with decisions and reasons) · [`included_studies.csv`](included_studies.csv) (coding of the included studies).

## Taxonomy

Each study is coded along three connected taxonomies: what it does in manufacturing, how the agentic system is built, and how it is evaluated.

<p align="center"><img src="figures/application-taxonomy.png" width="420" alt="Manufacturing-application taxonomy"><br><em>Applications: manufacturing function, task type and operational scope</em></p>

<p align="center"><img src="figures/design-taxonomy.png" width="900" alt="Agentic-design taxonomy"><br><em>Agentic design: organisation, decision engine, grounding, tools, verification and human authority</em></p>

<p align="center"><img src="figures/evaluation-taxonomy.png" width="900" alt="Evaluation taxonomy"><br><em>Evaluation: scope, methodology and analysis</em></p>

<p align="center"><img src="figures/design-distribution.png" width="900" alt="Agent organisation, decision engine and human authority across 164 studies"><br><em>How the 164 systems are organised, who decides, and who authorises the action</em></p>

## Contents

- [Product and production-system design](#product-and-production-system-design)
- [Process planning and automation engineering](#process-planning-and-automation-engineering)
- [Production planning, scheduling and coordination](#production-planning-scheduling-and-coordination)
- [Process control and operational optimisation](#process-control-and-operational-optimisation)
- [Product and process quality](#product-and-process-quality)
- [Equipment and product health and maintenance](#equipment-and-product-health-and-maintenance)
- [Robotic task execution and human–robot collaboration](#robotic-task-execution-and-humanrobot-collaboration)
- [Logistics, inventory and supply chains](#logistics-inventory-and-supply-chains)
- [Safety, security and compliance](#safety-security-and-compliance)
- [Manufacturing data and knowledge services](#manufacturing-data-and-knowledge-services)

## Product and production-system design

- [Adaptive task planning and coordination in multi-agent manufacturing systems using large language models](https://doi.org/10.1016/j.rcim.2026.103245) — Lim et al., *Robotics and Computer-Integrated Manufacturing*, 2026 `OPT` `d·L` `HA2` `lab`
- [Adversarial Agentic LLM based optimization for factory layout and dispatching selection](https://doi.org/10.1016/j.procir.2026.03.308) — Pflüger et al., *Procedia CIRP*, 2026 `OPT` `c·O` `HA0` `simulation`
- [Agentic additive manufacturing alloy evaluation](https://doi.org/10.1016/j.addlet.2026.100355) — Pak et al., *Additive Manufacturing Letters*, 2026 `OPT` `d·L` `HA0` `offline`
- [An agentic-AI method for 2D legacy to 3D CAD model reconstruction](https://doi.org/10.1016/j.mfglet.2026.08.093) — Gyamenah et al., *Manufacturing Letters*, 2026 `GEN` `c·L` `HA0` `offline`
- [Code, Not Canvas: Multi-Agent Layout Generation Beyond Vision Models](https://doi.org/10.1109/ASP-DAC66049.2026.11420765) — Yang & Ren, *Proc. Asia and South Pacific Design Automation Conference…*, 2026 `GEN` `d·L` `HA0` `offline`
- [Cognitive 3D CAD model retrieval: a multi-agent system for intent-driven, cross-modal search](https://doi.org/10.1080/09544828.2026.2617799) — Lv et al., *Journal of Engineering Design*, 2026 `QA` `d·L` `HA0` `offline`
- [DUCTILE: Agentic Large Language Model Orchestration of Engineering Analysis in Product Development Design Practice](https://doi.org/10.1115/1.4072279) — Pradas-Gómez et al., *Journal of Mechanical Design*, 2026 `GEN` `a·L` `HA0` `industrial`
- [Data-driven meets knowledge-driven: an LLM‑agent framework for quality control in metal additive manufacturing](https://doi.org/10.1016/j.jii.2026.101182) — Li et al., *Journal of Industrial Information Integration*, 2026 `OPT` `a·S` `HA0` `offline`
- [Digital Product Development with Multi-agent Systems: A Premium Pen Creation Case Study](https://doi.org/10.1007/978-3-032-05748-8_35) — Gomes et al., *Lecture Notes in Networks and Systems*, 2026 `GEN` `c·L` `HA0` `no eval`
- [Enabling Non-Simulation Experts to Adapt Digital Twins during Production System Redesign using Agentic AI](https://doi.org/10.1145/3802463.3802479) — Schwede et al., *ICCMB 2026 - Proceedings of 2026 the 9th International Co…*, 2026 `GEN` `d·L` `HA0` `simulation`
- [From Text to Simulation: A Multi-Agent LLM Workflow for Automated Chemical Process Design](https://doi.org/10.1609/aaai.v40i35.40215) — Tian et al., *Proc. AAAI Conference on Artificial Intelligence*, 2026 `GEN` `c·L` `HA0` `simulation`
- [GenAI-Driven Multiagent Systems for Design to Manufacturing Workflows](https://doi.org/10.1016/j.procir.2026.05.359) — Känsälä et al., *Procedia CIRP*, 2026 `GEN` `c·L` `HA0` `offline`
- [Impromptu: An LLM-Driven Prompt-to-Hardware Circuit Prototyping Platform on a Cartesian Gantry](https://doi.org/10.1109/ROSE69181.2026.11570982) — Alesi et al., *2026 IEEE International Symposium on Robotic and Sensors…*, 2026 `GEN` `b·L` `HA2` `lab`
- [LLM Agent-driven Automated DFA Assessment with Fine-tuning and AAS-based RAG](https://doi.org/10.1016/j.rcim.2026.103325) — Liu et al., *Robotics and Computer-Integrated Manufacturing*, 2026 `VER` `a·L` `HA0` `offline`
- [LLM agents-driven layout generation for reconfigurable manufacturing systems](https://doi.org/10.1016/j.cirp.2026.03.015) — Wang et al., *CIRP Annals*, 2026 `GEN` `c·L` `HA0` `simulation`
- [LLM-based rigid-flexible collaborative fixture optimization design of near-net-shaped jet engine blade machining](https://doi.org/10.1016/j.jmapro.2026.06.060) — Liang et al., *Journal of Manufacturing Processes*, 2026 `GEN` `b·O` `HA0` `simulation`
- [Large language model-enabled multi-agent self-organised approach for personalised rehabilitation assistive devices design](https://doi.org/10.1080/00207543.2025.2509155) — Zhuang et al., *International Journal of Production Research*, 2026 `GEN` `d·L` `HA1` `offline`
- [Large language model-enhanced multi-agent framework for seamless design and manufacturing integration](https://doi.org/10.1016/j.jii.2026.101193) — Chung et al., *Journal of Industrial Information Integration*, 2026 `GEN` `c·S` `HA0` `offline`
- [Multi-Agent CAD Code Generation](https://doi.org/10.1145/3799902.3811067) — Liu et al., *Proceedings - SIGGRAPH 2026 Conference Papers*, 2026 `GEN` `c·L` `HA0` `offline`
- [Operationalising cognitive digital twins through a cognitive-function framework and GenAI tools](https://doi.org/10.1080/00207543.2026.2732141) — Liu et al., *International Journal of Production Research*, 2026 `GEN` `b·L` `HA1` `simulation`
- [Power Circuit AI: Designing Power Electronic Circuits for Motor Drives with Generative Artificial Intelligence](https://doi.org/10.1109/IDCD69431.2026.11519438) — Hetrich et al., *Proc. 2026 IEEE International Conference on Intelligent D…*, 2026 `GEN` `c·L` `HA0` `offline`
- [SAGE-QA: Shared-context agentic graph-enhanced question answering for scientific reasoning](https://doi.org/10.1557/s43579-026-01036-4) — Hsu & Buehler, *MRS Communications*, 2026 `QA` `d·L` `HA0` `offline`
- [SCHEMA-MINER^pro: Agentic AI for Ontology Grounding over LLM-Discovered Scientific Schemas in a Human-in-the-Loop Workflow](https://doi.org/10.1177/22104968261431521) — Sadruddin et al., *Semantic Web*, 2026 `QA` `a·L` `HA1` `offline`
- [Seek-BCD: A Domain-Specialized Evolutionary Large Language Model Agent for BCD Technology](https://doi.org/10.1109/ISPSD64561.2026.11553990) — Huang et al., *Proc. International Symposium on Power Semiconductor Devi…*, 2026 `OPT` `a·O` `HA0` `offline`
- [The Resource Friendly Experiment Agent](https://doi.org/10.1007/978-3-032-21154-5_36) — Müller & Knothe, *Lecture Notes in Mechanical Engineering*, 2026 `OPT` `c·L` `HA0` `simulation`
- [AI Agents for Enabling Autonomous Experiments at ORNL's HPC and Manufacturing User Facilities](https://doi.org/10.1145/3731599.3767592) — Rosendo et al., *Proc. SC '25 Workshops of the International Conference fo…*, 2025 `ACT` `d·O` `HA2` `simulation`
- [ChatBuilder: LLM-assisted Modular Robot Creation](https://doi.org/10.1109/IROS60139.2025.11247761) — Chen et al., *IEEE International Conference on Intelligent Robots and S…*, 2025 `GEN` `c·L` `HA0` `simulation`
- [ChatCAD: An MLLM-Guided Framework for Zero-shot CAD Drawing Restoration](https://doi.org/10.1109/ICASSP49660.2025.10890248) — Tang et al., *ICASSP, IEEE International Conference on Acoustics, Speec…*, 2025 `GEN` `c·L` `HA0` `offline`
- [From text to design: a framework to leverage LLM agents for automated CAD generation](https://doi.org/10.1017/pds.2025.10203) — Schüpbach et al., *Proc. Design Society*, 2025 `GEN` `a·L` `HA0` `offline`
- [GMFR-Coder: An LLM-Driven Approach to Code Generation for GNN-Based Machining Feature Recognition of Aircraft Structural Parts](https://doi.org/10.1109/ICEMCE68156.2025.11467062) — Xu et al., *2025 9th International Conference on Electrical, Mechanic…*, 2025 `GEN` `c·L` `HA0` `offline`
- [Intelligent OPC Engineer Assistant for Semiconductor Manufacturing](https://doi.org/10.1609/aaai.v39i22.34479) — Chen et al., *Proc. AAAI Conference on Artificial Intelligence*, 2025 `GEN` `c·O` `HA0` `simulation`
- [Knowledge-enhanced large language models for ideation to implementation: A new paradigm in product design](https://doi.org/10.1016/j.asoc.2025.113147) — Li et al., *Applied Soft Computing*, 2025 `GEN` `a·L` `HA0` `offline`
- [LLMto3D - Generation of parametric, 3D printable objects using large language models](https://doi.org/10.1177/14780771251353792) — Hizmi et al., *International Journal of Architectural Computing*, 2025 `GEN` `c·L` `HA0` `offline`
- [Multi-Agent Yield Analysis for Circuit Design](https://doi.org/10.1109/DAC63849.2025.11133334) — Qin et al., *Proceedings - Design Automation Conference*, 2025 `OPT` `d·O` `HA0` `simulation`
- [SceneGenAgent: Precise Industrial Scene Generation with Coding Agent](https://doi.org/10.18653/v1/2025.acl-long.873) — Xia et al., *Proc. Annual Meeting of the Association for Computational…*, 2025 `GEN` `b·L` `HA0` `simulation`
- [Smart product configurator applying large language models: the case of construction equipment machines](https://doi.org/10.1016/j.procir.2025.08.103) — Santos et al., *Procedia CIRP*, 2025 `OPT` `d·L` `HA0` `offline`
- [Towards agentic smart design: An industrial large model-driven human-in-the-loop agentic workflow for geometric modelling](https://doi.org/10.1016/j.asoc.2025.113920) — Zheng et al., *Applied Soft Computing*, 2025 `GEN` `c·L` `HA0` `offline`
- [The Heuristic Design Innovation Approach for Data-Integrated Large Language Model](https://doi.org/10.1007/978-3-031-60615-1_12) — Zhou et al., *Lecture Notes in Computer Science (including subseries Le…*, 2024 `GEN` `a·L` `HA0` `sandbox`

## Process planning and automation engineering

- [Closed-Loop Recovery Mechanism for Multi-agent Process Planning Under Manufacturing Constraints](https://doi.org/10.1007/978-981-92-3403-5_13) — Yin & Sun, *Lecture Notes in Computer Science*, 2027 `GEN` `c·L` `HA0` `offline`
- [An LLM-assisted multi-agent control framework for roll-to-roll manufacturing systems](https://doi.org/10.1016/j.jmsy.2026.04.005) — Li et al., *Journal of Manufacturing Systems*, 2026 `ACT` `c·O` `HA2` `simulation`
- [Design-on-Graph: A Graph Retrieval-Augmented Generation-Based Method to Support Manufacturing System Design](https://doi.org/10.1007/978-3-032-03550-9_27) — Song et al., *IFIP Advances in Information and Communication Technology*, 2026 `GEN` `d·L` `HA0` `offline`
- [Development of an LLM-Based Multi-Agent System for Sewing Sequence Planning](https://doi.org/10.1177/0887302X261487373) — Park & Kim, *Clothing and Textiles Research Journal*, 2026 `GEN` `c·L` `HA0` `offline`
- [Event-Structured LLM Planning for Continuous-Parameter Industrial Workflows](https://doi.org/10.1109/ICMTIM69588.2026.11525771) — Wei & Zhang, *2026 7th International Conference on Mechatronics Technol…*, 2026 `GEN` `b·L` `HA2` `offline`
- [GLaMP: A Grounded Language Model-Based Multiagent System for Long-Horizon Robotic Task Planning in Industrial Settings](https://doi.org/10.1109/TIE.2026.3713552) — H. Chen et al., *IEEE Transactions on Industrial Electronics*, 2026 `ACT` `c·S` `HA2` `lab`
- [H2A-BPMN: A Hierarchical and Hybrid Agent Framework for Industrial BPMN Automated Modeling](https://doi.org/10.1007/978-3-032-21171-2_10) — Xu et al., *Lecture Notes of the Institute for Computer Sciences, Soc…*, 2026 `GEN` `c·L` `HA0` `offline`
- [Human-Centered Development of a Multi-Agent AI System Based on Large Language Models for CNC Machine Tool Operation in Production](https://doi.org/10.1016/j.procir.2026.03.275) — Engert et al., *Procedia CIRP*, 2026 `QA` `d·L` `HA0` `lab`
- [IMAT-Print: Intention-Oriented Augmented Memory for Agentic Tiny-LLM in Electronic Additive Manufacturing](https://doi.org/10.1109/AIoTC71250.2026.11688658) — Q. Gao et al., *2026 5th International Conference on Artificial Intellige…*, 2026 `GEN` `b·L` `HA1` `offline`
- [TreeEvolve: LLM-Driven End-to-End Pipeline for IIoT-Enabled Process Optimization in Food Industry](https://doi.org/10.1109/ICWR69602.2026.11513348) — Mousavi et al., *International Conference on Web Research, ICWR*, 2026 `GEN` `c·O` `HA0` `simulation`
- [AutoMEX: Streamlining material extrusion with AI agents powered by large language models and knowledge graphs](https://doi.org/10.1016/j.matdes.2025.113644) — Fan et al., *Materials and Design*, 2025 `ACT` `a·L` `HA2` `lab`
- [Collaborative LLM agents for flexible software development of intelligent industrial robot control systems](https://doi.org/10.1007/s40747-025-02051-z) — Chen et al., *Complex and Intelligent Systems*, 2025 `GEN` `c·L` `HA1` `simulation`
- [Embodied intelligence in manufacturing: leveraging large language models for autonomous industrial robotics](https://doi.org/10.1007/s10845-023-02294-y) — Fan et al., *Journal of Intelligent Manufacturing*, 2025 `ACT` `b·L` `HA2` `simulation`
- [Rapid generation method of process routes based on multi-agent collaboration with LLMs](https://doi.org/10.1016/j.aei.2025.103733) — Xie et al., *Advanced Engineering Informatics*, 2025 `GEN` `c·S` `HA0` `offline`
- [ReACT - Gen AI Agents for Reasoning, Planning, and Testing in IEC 61499-Based Control Systems](https://doi.org/10.1109/IECON58223.2025.11221719) — Xavier et al., *IECON Proceedings (Industrial Electronics Conference)*, 2025 `ACT` `d·L` `HA1` `lab`
- [Shopfloor-Integrated Manufacturing Operation Planning through Agents](https://doi.org/10.1109/ETFA65518.2025.11205809) — Gerdes et al., *IEEE International Conference on Emerging Technologies an…*, 2025 `ACT` `a·O` `HA1` `lab`
- [Large language model based agent for process planning of fiber composite structures](https://doi.org/10.1016/j.mfglet.2024.03.010) — Holland & Chaudhari, *Manufacturing Letters*, 2024 `GEN` `a·L` `HA0` `offline`

## Production planning, scheduling and coordination

- [Implementation of an Orchestrated Multi-agent System for PPCP in Textile MSMEs: A Prompt Engineering Approach](https://doi.org/10.1007/978-3-032-30488-9_10) — da Silva et al., *Lecture Notes in Computer Science*, 2027 `OPT` `d·L` `HA0` `simulation`
- [A Large language model-based multi-agent manufacturing system for intelligent shopfloors](https://doi.org/10.1016/j.aei.2025.103888) — Zhao et al., *Advanced Engineering Informatics*, 2026 `OPT` `e·L` `HA2` `lab`
- [A memory-augmented LLM-driven method for autonomous merging of 3D printing work orders](https://doi.org/10.1016/j.procir.2025.08.194) — Liu et al., *Procedia CIRP*, 2026 `OPT` `a·L` `HA2` `simulation`
- [A4PS: Agentic AI-assisted advanced planning and scheduling with large language models for smart manufacturing](https://doi.org/10.1016/j.jmsy.2026.01.003) — Li et al., *Journal of Manufacturing Systems*, 2026 `GEN` `c·L` `HA1` `offline`
- [AI Agents in Industry 4.0: AAS–OPC UA–LLM Architecture as the Foundation of Intelligent Manufacturing Systems in the Context of Industrial Enterprise Implementation](https://doi.org/10.3390/app16115428) — Graul et al., *Applied Sciences (Switzerland)*, 2026 `ACT` `a·L` `HA1` `simulation`
- [Agentic LLM-based Contingency Management in Production Control](https://doi.org/10.1016/j.procir.2025.08.195) — May et al., *Procedia CIRP*, 2026 `OPT` `c·L` `HA2` `simulation`
- [Agentic Manufacturing Operations Management: Concept and First Prototype](https://doi.org/10.1016/j.procir.2026.05.280) — Oberle et al., *Procedia CIRP*, 2026 `ACT` `c·L` `HA1` `lab`
- [Agentic active Asset Administration Shell for circular manufacturing](https://doi.org/10.1016/j.jmsy.2026.07.011) — Li et al., *Journal of Manufacturing Systems*, 2026 `ACT` `d·L` `HA2` `sandbox`
- [An LLM-Driven Multi-Agent Evolution Framework for Solver Code Generation in Job Shop Scheduling](https://doi.org/10.3390/math14112010) — Sun et al., *Mathematics*, 2026 `GEN` `c·O` `HA0` `offline`
- [An industrial intelligent scheduling method and system based on agent clusters](https://doi.org/10.1117/12.3110757) — Yang et al., *Proc. SPIE - The International Society for Optical Engine…*, 2026 `DIA` `a·S` `HA0` `sandbox`
- [ConDA: A constraint discovery agent for cross-system optimization of manufacturing operations](https://doi.org/10.1016/j.jmsy.2026.09.001) — Zhang et al., *Journal of Manufacturing Systems*, 2026 `OPT` `d·O` `HA2` `simulation`
- [Coordination of LLM-Embodied Agents for manufacturing task allocation under constraints](https://doi.org/10.1016/j.jmsy.2026.04.028) — Ye & Li, *Journal of Manufacturing Systems*, 2026 `OPT` `e·L` `HA2` `simulation`
- [Dynamic reconfiguration in multi-robot agent systems using embedded language models](https://doi.org/10.1016/j.rcim.2026.103308) — Murdivien et al., *Robotics and Computer-Integrated Manufacturing*, 2026 `OPT` `d·S` `HA2` `lab`
- [Dynamic scheduling of wafer batch processing machines via reinforcement learning enhanced by expert-guided lightweight LLM](https://doi.org/10.1080/00207543.2025.2582768) — Xiang et al., *International Journal of Production Research*, 2026 `OPT` `c·O` `HA2` `simulation`
- [Human-Robot Collaborative Supply Chain Scheduling via Reinforcement Learning, Large Neighborhood Search, and Large Language Models](https://doi.org/10.1016/j.jii.2026.101152) — Zhang et al., *Journal of Industrial Information Integration*, 2026 `OPT` `c·O` `HA0` `offline`
- [Industrial mechanism-aware multi-agent collaboration of large language models for job shop scheduling optimization](https://doi.org/10.1016/j.cie.2026.112079) — Yan & Ji, *Computers and Industrial Engineering*, 2026 `GEN` `c·O` `HA0` `offline`
- [Intelligent Production Scheduling under Constraints Using LLMs for Industry 5.0](https://doi.org/10.5220/0014636600004055) — Abbes et al., *International Conference on Operations Research and Enter…*, 2026 `OPT` `b·L` `HA0` `offline`
- [KA-Graph: Knowledge-Aware Orchestration for Industrial Agent Services Under Knowledge Asymmetry](https://doi.org/10.1109/TSC.2026.3734284) — Zuo et al., *IEEE Transactions on Services Computing*, 2026 `QA` `c·L` `HA0` `offline`
- [LLM-Driven Multi-Agent Reinforcement Learning for Resilient AGV Dispatching Under Dynamic Disruptions in Smart Manufacturing](https://doi.org/10.1109/AIITA69518.2026.11567113) — Ma et al., *2026 6th International Conference on Artificial Intellige…*, 2026 `OPT` `b·O` `HA2` `simulation`
- [LLM-enhanced embodied multi-agent manufacturing system: A novel self-organizing production paradigm for embodied perception, embodied analysis and embodied decision](https://doi.org/10.1016/j.jmsy.2025.12.016) — Liu et al., *Journal of Manufacturing Systems*, 2026 `OPT` `e·S` `HA1` `lab`
- [Logic-Based Verification of Task Allocation for LLM-Enabled Multi-Agent Manufacturing Systems](https://doi.org/10.1109/WODES69290.2026.11598152) — Lim et al., *2026 18th International Workshop on Discrete Event System…*, 2026 `VER` `c·L` `HA1` `offline`
- [MARS: Multi-Agent Rescheduling Framework with Large Language Models for Human-Centric Manufacturing](https://doi.org/10.1016/j.jmsy.2026.07.015) — Park et al., *Journal of Manufacturing Systems*, 2026 `OPT` `c·O` `HA1` `offline`
- [Multitask fine-tuning agentic AI based collaborative scheduling for flexible manufacturing systems](https://doi.org/10.1016/j.jmsy.2026.04.022) — Gao et al., *Journal of Manufacturing Systems*, 2026 `OPT` `d·O` `HA2` `simulation`
- [Self-evolving digital twins in flexible manufacturing: A large language model-powered multi-agent approach](https://doi.org/10.1016/j.dte.2026.100099) — Gao et al., *Digital Engineering*, 2026 `MON` `d·L` `HA2` `simulation`
- [A Large Language Model-Enabled Control Architecture for Dynamic Resource Capability Exploration in Multi-Agent Manufacturing Systems](https://doi.org/10.1109/CASE58245.2025.11163802) — Lim & Kovalenko, *IEEE International Conference on Automation Science and E…*, 2025 `OPT` `b·L` `HA2` `simulation`
- [A blockchain-based LLM-driven energy-efficient scheduling system towards distributed multi-agent manufacturing scenario of new energy vehicles within the circular economy](https://doi.org/10.1016/j.cie.2025.110889) — Liu & Nie, *Computers and Industrial Engineering*, 2025 `OPT` `b·L` `HA2` `simulation`
- [ABCM: Agent-Based Complexity Management Method for Intelligent Manufacturing](https://doi.org/10.1145/3760269.3760353) — Kan et al., *Proc. 2025 5th International Conference on Automation Con…*, 2025 `DIA` `a·L` `HA0` `no eval`
- [Applying Large Language Models as Hybrid-Algorithm Experts for Job Shop Scheduling Problems](https://doi.org/10.1109/SMC58881.2025.11342734) — Zhang et al., *Conference Proceedings - IEEE International Conference on…*, 2025 `GEN` `c·O` `HA0` `offline`
- [Beyond Formal Semantics for Capabilities and Skills: Model Context Protocol in Manufacturing](https://doi.org/10.1109/ETFA65518.2025.11205601) — Vieira Da Silva et al., *IEEE International Conference on Emerging Technologies an…*, 2025 `ACT` `a·L` `HA2` `lab`
- [Chat with MES: LLM-driven user interface for manipulating garment manufacturing system through natural language](https://doi.org/10.1016/j.jmsy.2025.02.008) — Yuan et al., *Journal of Manufacturing Systems*, 2025 `ACT` `b·L` `HA2` `simulation`
- [Collaborative Problem-Solving with LLM: A Multi-agent System Approach to Solve Complex Tasks Using Autogen](https://doi.org/10.1007/978-3-031-73058-0_17) — Barbosa et al., *Communications in Computer and Information Science*, 2025 `OPT` `e·L` `HA2` `sandbox`
- [Comparison of E2E and Pipeline Conversational Architectures for Production Line Rebalancing](https://doi.org/10.1109/ICTAI66417.2025.00172) — Manssouri et al., *Proceedings - International Conference on Tools with Arti…*, 2025 `OPT` `b·O` `HA0` `offline`
- [Control Industrial Automation System with Large Language Model Agents](https://doi.org/10.1109/ETFA65518.2025.11205539) — Xia et al., *IEEE International Conference on Emerging Technologies an…*, 2025 `ACT` `d·L` `HA2` `offline`
- [Human-Understandable Communication for Industrial Multi-Robot Systems Using LLMs](https://doi.org/10.1016/j.ifacol.2025.09.490) — Murdivien & Um, *IFAC-PapersOnLine*, 2025 `ACT` `d·S` `HA2` `lab`
- [MASC: Large language model-based multi-agent scheduling chain for flexible job shop scheduling problem](https://doi.org/10.1016/j.aei.2025.103527) — Wang et al., *Advanced Engineering Informatics*, 2025 `OPT` `c·O` `HA2` `offline`
- [Retrieval-Augmented LLM-Driven Multi-Agent Optimization Framework for Intelligent Manufacturing Scheduling](https://doi.org/10.1109/HPCC67675.2025.00214) — Li et al., *Proceedings - 2025 27th IEEE International Conference on…*, 2025 `OPT` `c·O` `HA0` `offline`
- [Large Language Model-Enabled Multi-Agent Manufacturing Systems](https://doi.org/10.1109/CASE59546.2024.10711432) — Lim et al., *IEEE International Conference on Automation Science and E…*, 2024 `ACT` `d·L` `HA2` `simulation`

## Process control and operational optimisation

- [A Multi-Agent Framework for Step-Level Tool-Call Safety Evaluation in Industrial Control Systems](https://doi.org/10.1109/AIITA69518.2026.11567230) — Xue & He, *2026 6th International Conference on Artificial Intellige…*, 2026 `VER` `a·L` `HA2` `offline`
- [An autonomous AI Agent framework for dynamic assembly quality control via LLM-based heuristic evolution](https://doi.org/10.1016/j.aei.2026.105060) — Song et al., *Advanced Engineering Informatics*, 2026 `OPT` `b·O` `HA0` `offline`
- [Cognitive Supervisory Control with LLM Reasoning Agent for Fault-Tolerant Process Systems: A Digital Twin Perspective](https://doi.org/10.3390/pr14142298) — Papacharalampopoulos et al., *Processes*, 2026 `ACT` `b·O` `HA2` `simulation`
- [EcoLLM: A lightweight ReAct-SFT framework for document-driven LCI extraction and automated LCIA in metal additive manufacturing](https://doi.org/10.1016/j.jclepro.2026.148797) — Lin et al., *Journal of Cleaner Production*, 2026 `DIA` `a·L` `HA0` `offline`
- [Autonomous Industrial Control using an Agentic Framework with Large Language Models](https://doi.org/10.1016/j.ifacol.2025.07.170) — Vyas & Mercangöz, *IFAC-PapersOnLine*, 2025 `ACT` `c·L` `HA2` `lab`
- [Generative AI Multi-Agent System with Retrieval Augmented Generation for Real-Time Furnace Operation Support in Industrial Manufacturing](https://doi.org/10.1109/IECON58223.2025.11221518) — Provatidis et al., *IECON Proceedings (Industrial Electronics Conference)*, 2025 `MON` `d·S` `HA0` `offline`
- [IIoT-enabled digital twin for legacy and smart factory machines with LLM integration](https://doi.org/10.1016/j.jmsy.2025.03.022) — Gautam et al., *Journal of Manufacturing Systems*, 2025 `QA` `d·S` `HA1` `lab`
- [IM-Chat: A multi-agent LLM framework integrating tool-calling and diffusion modeling for knowledge transfer in injection molding industry](https://doi.org/10.1016/j.jmsy.2025.11.007) — Lee et al., *Journal of Manufacturing Systems*, 2025 `QA` `d·S` `HA0` `offline`
- [Knowledge-Driven Multi-Agent AI for Interpretable Yield Optimization in Semiconductor Manufacturing](https://doi.org/10.1109/AIHCIR67580.2025.11404861) — Geng et al., *2025 4th International Conference on Artificial Intellige…*, 2025 `DIA` `c·S` `HA0` `offline`
- [LLM-3D print: Large Language Models to monitor and control 3D printing](https://doi.org/10.1016/j.addma.2025.105027) — Jadhav et al., *Additive Manufacturing*, 2025 `ACT` `d·L` `HA2` `lab`
- [Leveraging LLM Agents and Digital Twins for Fault Handling in Process Plants](https://doi.org/10.1109/ETFA65518.2025.11205597) — M. S. Gill et al., *2025 IEEE 30th International Conference on Emerging Techn…*, 2025 `ACT` `c·L` `HA2` `simulation`
- [Voltage Anomaly Detection and Forecasting of Electrical Energy Consumption for Machine Tools using an AI-based Agent Framework](https://doi.org/10.1109/AIoT66900.2025.00107) — Chen et al., *Proceedings - 2025 IEEE Annual Congress on Artificial Int…*, 2025 `DIA` `d·S` `HA0` `offline`
- [LLM experiments with simulation: Large Language Model Multi-Agent System for Simulation Model Parametrization in Digital Twins](https://doi.org/10.1109/ETFA61755.2024.10710900) — Y. Xia et al., *2024 IEEE 29th International Conference on Emerging Techn…*, 2024 `OPT` `c·L` `HA0` `simulation`

## Product and process quality

- [FieldWorkArena: Agentic AI Benchmark for Real Field Work Tasks](https://doi.org/10.1007/978-3-032-31663-9_7) — Takahashi et al., *Lecture Notes in Computer Science*, 2027 `MON` `a·L` `HA0` `sandbox`
- [3DprintMIND: An AI-Agent system using large language models and dynamic manufacturing knowledge graphs for smart manufacturing](https://doi.org/10.1016/j.rcim.2025.103214) — Li et al., *Robotics and Computer-Integrated Manufacturing*, 2026 `DIA` `a·S` `HA1` `lab`
- [A compositional dual-hand action recognition method for LLM-driven assembly assistance](https://doi.org/10.1016/j.jmsy.2026.07.017) — Zheng et al., *Journal of Manufacturing Systems*, 2026 `MON` `a·S` `HA0` `offline`
- [Action-Oriented Programming and Automatic Agent Generation for Adaptive Data Collection in Decentralized Data Ecosystems](https://doi.org/10.3390/pr14101669) — Bayram et al., *Processes*, 2026 `DIA` `d·L` `HA0` `sandbox`
- [The 1% problem: LLM orchestration for rare event detection in manufacturing supply chains](https://doi.org/10.1016/j.ijpe.2026.110119) — Dang et al., *International Journal of Production Economics*, 2026 `DIA` `b·S` `HA0` `offline`
- [LLM-Based Overlay Issue Classification and Solution Optimization in Semiconductor Manufacturing](https://doi.org/10.1117/12.3050976) — Jee, *Proc. SPIE - The International Society for Optical Engine…*, 2025 `DIA` `a·S` `HA0` `simulation`
- [Near-Closed-Loop-Control in PV Manufacturing with Centralized Reasoning Agent: LLM and Semantic Kernel based Implementation](https://doi.org/10.1109/NAPS66256.2025.11272240) — Upadhyaya, *2025 57th North American Power Symposium, NAPS 2025*, 2025 `DIA` `d·L` `HA0` `offline`

## Equipment and product health and maintenance

- [A Multi-Agent and synergistic Knowledge Graph retrieval-augmented generation framework for intelligent maintenance](https://doi.org/10.1016/j.jmsy.2026.02.016) — Lin et al., *Journal of Manufacturing Systems*, 2026 `DIA` `c·L` `HA0` `offline`
- [Agentic Data Analysis for Intelligent Manufacturing: Benchmark-Driven Evaluation of Agentic vs. Direct LLM Approaches](https://doi.org/10.1016/j.procir.2025.09.043) — Farid et al., *Procedia CIRP*, 2026 `DIA` `a·L` `HA0` `offline`
- [An LLM-Enabled Human–Machine Collaborative Fault Diagnosis Framework via Industrial AI Agents](https://doi.org/10.1049/cim2.70080) — He et al., *IET Collaborative Intelligent Manufacturing*, 2026 `DIA` `a·S` `HA0` `offline`
- [An LLM-empowered collaborative multi-agent framework for intermittent demand forecasting of large-scale spare parts in smart manufacturing](https://doi.org/10.1016/j.knosys.2026.116334) — Xiong et al., *Knowledge-Based Systems*, 2026 `DIA` `c·S` `HA0` `offline`
- [CoLMAgent: A collaborative agentic AI system that integrates large and small models for industrial intelligent human–machine interactions](https://doi.org/10.1016/j.jmsy.2026.06.020) — Li et al., *Journal of Manufacturing Systems*, 2026 `DIA` `b·S` `HA0` `offline`
- [Cognitive-State-Driven LLM Decision Agent for Fault Diagnosis of Rotating Machinery Under Incomplete Evidence](https://doi.org/10.1109/SRSE70977.2026.11694870) — H. Zhou et al., *2026 8th International Conference on System Reliability a…*, 2026 `DIA` `b·S` `HA0` `offline`
- [Contextualizing Timed Automata via Knowledge Graphs for Agentic LLM-Based Fault Diagnosis](https://doi.org/10.1109/ACCESS.2026.3714676) — Westermann et al., *IEEE Access*, 2026 `DIA` `c·S` `HA0` `simulation`
- [Harnessing collective intelligence of multi-agent LLM systems for sensor failure reasoning in smart manufacturing](https://doi.org/10.1016/j.jii.2025.101012) — Gong et al., *Journal of Industrial Information Integration*, 2026 `DIA` `e·L` `HA0` `offline`
- [Hybrid agentic AI and multi-agent systems in smart manufacturing](https://doi.org/10.1016/j.jmsy.2026.04.002) — Farahani et al., *Journal of Manufacturing Systems*, 2026 `DIA` `d·S` `HA1` `offline`
- [A generative pre-trained transformer industrial bot to improve operators’ working experience in a small Industry 5.0 factory](https://doi.org/10.1007/s00170-025-15033-9) — Kiangala & Wang, *International Journal of Advanced Manufacturing Technology*, 2025 `QA` `a·L` `HA0` `offline`
- [Agentic AI for Intent-Based Industrial Automation](https://doi.org/10.1109/INDUSCON66435.2025.11241317) — Romero & Suyama, *2025 16th IEEE International Conference on Industry Appli…*, 2025 `OPT` `d·L` `HA2` `offline`
- [Bridging Industrial Expertise and XR with LLM-Powered Conversational Agents](https://doi.org/10.1109/DCOSS-IoT65416.2025.00158) — Tomkou et al., *Proceedings - 2025 21st International Conference on Distr…*, 2025 `QA` `d·S` `HA0` `offline`
- [Empowered Smart Manufacturing Based on an Intelligent Robotic Workcell Assistant](https://doi.org/10.1109/ARIS66143.2025.11163399) — Lin & Shih, *International Conference on Advanced Robotics and Intelli…*, 2025 `ACT` `d·L` `HA2` `lab`
- [Enhancing Efficiency in Manufacturing through Automated AI Agent-Based Bearing Defect Diagnostic System](https://doi.org/10.4271/2025-01-0158) — Chandrasekaran, *SAE Technical Papers*, 2025 `DIA` `d·S` `HA0` `offline`
- [Generative AI for Intelligent Manufacturing Virtual Assistants in the Semiconductor Industry](https://doi.org/10.1109/LRA.2025.3544506) — Lin et al., *IEEE Robotics and Automation Letters*, 2025 `QA` `b·S` `HA0` `industrial`
- [Probing a novel machine tool fault reasoning and maintenance service recommendation approach through data-knowledge empowered LLMs integrated with AR-assisted maintenance guidance](https://doi.org/10.1016/j.aei.2025.103460) — Liu et al., *Advanced Engineering Informatics*, 2025 `DIA` `e·S` `HA0` `lab`
- [Redefining Manufacturing Diagnostics: An Agentic Framework Leveraging LangGraph and ChatGPT-4](https://doi.org/10.1109/E-TEMS64751.2025.11239110) — Ahaneku et al., *IEEE European Technology and Engineering Management Summi…*, 2025 `DIA` `d·L` `HA0` `offline`
- [An experimental hybrid customized AI and generative AI chatbot human machine interface to improve a factory troubleshooting downtime in the context of Industry 5.0](https://doi.org/10.1007/s00170-024-13492-0) — Kiangala & Wang, *International Journal of Advanced Manufacturing Technology*, 2024 `QA` `a·L` `HA0` `offline`
- [Empowering digital twins with large language models for global temporal feature learning](https://doi.org/10.1016/j.jmsy.2024.02.015) — Sun et al., *Journal of Manufacturing Systems*, 2024 `DIA` `e·S` `HA0` `offline`

## Robotic task execution and human–robot collaboration

- [A Large-Language-Model-Enabled Robotic System with Application to Power Cable Manipulation](https://doi.org/10.1109/CPEEE69412.2026.11521580) — Shan & Cheah, *2026 16th International Conference on Power, Energy, and…*, 2026 `ACT` `a·L` `HA2` `lab`
- [Agentic AI for decentralized, natural-language communication and interaction between agents in self-organizing manufacturing systems](https://doi.org/10.1016/j.procir.2026.03.192) — Krüger et al., *Procedia CIRP*, 2026 `ACT` `e·L` `HA2` `simulation`
- [CCM-FCC: LLM-powered cognition-centered AI agent framework for proactive human-robot collaboration](https://doi.org/10.1016/j.rcim.2025.103145) — Ding et al., *Robotics and Computer-Integrated Manufacturing*, 2026 `ACT` `a·S` `HA2` `offline`
- [Decentralised task planning and motion coordination for scalable multi-robot collaborative manufacturing](https://doi.org/10.1016/j.rcim.2026.103255) — Yang et al., *Robotics and Computer-Integrated Manufacturing*, 2026 `OPT` `b·O` `HA2` `simulation`
- [Embodied AI Agent Framework for (Re)Programming Robotic Tasks in Flexible Assembly using LLMs and VLMs](https://doi.org/10.1016/j.procir.2025.08.187) — de Souza et al., *Procedia CIRP*, 2026 `ACT` `a·L` `HA2` `lab`
- [Embodied Intelligence Robots: Flexible Task Planning Framework and Multimodal Fusion Perception](https://doi.org/10.1109/THMS.2026.3703414) — Zhu et al., *IEEE Transactions on Human-Machine Systems*, 2026 `ACT` `d·S` `HA2` `lab`
- [LLM-Guided risk-sensitive reinforcement learning for smart factories in the scenario of human-robot symbiosis](https://doi.org/10.1016/j.eswa.2025.130093) — Wang & Zhou, *Expert Systems with Applications*, 2026 `ACT` `b·O` `HA2` `simulation`
- [Large Language Model and Knowledge Graph-Based Intelligent Control Framework for Smart Manufacturing](https://doi.org/10.1115/1.4071921) — Meng et al., *Journal of Computing and Information Science in Engineering*, 2026 `ACT` `a·S` `HA2` `lab`
- [Perception-decision-execution coordination mechanism driven dynamic autonomous collaboration method for human-like collaborative robot based on multimodal large language model](https://doi.org/10.1016/j.rcim.2025.103167) — Chen et al., *Robotics and Computer-Integrated Manufacturing*, 2026 `ACT` `c·S` `HA2` `lab`
- [VLAbot: A human Vision–Language–Action models interaction framework for robotic assembly](https://doi.org/10.1016/j.rcim.2026.103268) — Wang et al., *Robotics and Computer-Integrated Manufacturing*, 2026 `ACT` `c·S` `HA1` `lab`
- [HeRo: A State Machine-Based, Fault-Tolerant Framework for Heterogeneous Multi-Robot Collaboration](https://doi.org/10.1109/ICRA55743.2025.11128674) — R. Tang et al., *2025 IEEE International Conference on Robotics and Automa…*, 2025 `ACT` `b·O` `HA2` `simulation`
- [Large Language Models in Human-Robot Collaboration With Cognitive Validation Against Context-Induced Hallucinations](https://doi.org/10.1109/ACCESS.2025.3565918) — Ranasinghe et al., *IEEE Access*, 2025 `ACT` `c·L` `HA2` `lab`
- [Large language model-enabled cognitive agent for self-aware manufacturing](https://doi.org/10.1016/j.jmsy.2025.08.015) — Lou et al., *Journal of Manufacturing Systems*, 2025 `ACT` `a·S` `HA1` `lab`
- [Toward Co-Working with Autonomous Agents: Rethinking Operations of Automation Systems](https://doi.org/10.1109/ETFA65518.2025.11205572) — Kovacs et al., *IEEE International Conference on Emerging Technologies an…*, 2025 `ACT` `c·L` `HA1` `lab`
- [Towards a next-generation LLM empowered low-code programming industrial robotic system for human-centric smart manufacturing](https://doi.org/10.1016/j.jmsy.2025.10.012) — Dong et al., *Journal of Manufacturing Systems*, 2025 `ACT` `d·S` `HA1` `lab`
- [Enhancing Human-Robot Collaborative Assembly in Manufacturing Systems Using Large Language Models](https://doi.org/10.1109/CASE59546.2024.10711843) — J. Lim et al., *2024 IEEE 20th International Conference on Automation Sci…*, 2024 `ACT` `b·S` `HA2` `lab`
- [Innovating Robotic Garment Handling Through the Integration of Large Language Models and Behavior Trees](https://doi.org/10.1109/ROBIO64047.2024.10907326) — Ghidary et al., *IEEE International Conference on Robotics and Biomimetics…*, 2024 `ACT` `b·S` `HA2` `lab`
- [SortingBot: Leveraging Large Language Models and 3D Vision for Multi-Category Material Sorting](https://doi.org/10.1109/IEMCON62851.2024.11093526) — Li et al., *2024 IEEE 15th Annual Information Technology, Electronics…*, 2024 `ACT` `a·S` `HA2` `simulation`

## Logistics, inventory and supply chains

- [Agentic AI for the proactive identification of unforsseen disruptions in manufacturing supply chains](https://doi.org/10.1109/ICIICE69672.2026.11565206) — Nikolakis et al., *2026 International Conference on Integrated Intelligence…*, 2026 `MON` `c·S` `HA0` `offline`
- [Rethinking manufacturing agility assessment in the age of intelligent systems: a multi-agent skill-enhanced RAG framework for the digital manufacturing era](https://doi.org/10.1007/s00170-026-18700-7) — Ren, *International Journal of Advanced Manufacturing Technology*, 2026 `DIA` `d·S` `HA1` `no eval`
- [Exploring Decentralized Warehouse Management Using Large Language Models: A Proof of Concept](https://doi.org/10.3390/app15105734) — Berlec et al., *Applied Sciences (Switzerland)*, 2025 `OPT` `b·L` `HA2` `simulation`
- [Leveraging Multi-Agent System Powered by Large Language Model to Improve Transparency and Reliability in Automated Supply Chain Coordination](https://doi.org/10.24928/2025/0102) — Zhao et al., *Annual Conference of the International Group for Lean Con…*, 2025 `OPT` `c·L` `HA0` `offline`

## Safety, security and compliance

- [Designing an AI-Assisted Cyber Threat Intelligence Framework for Industry 4.0: A Human-in-the-Loop Design Science Approach](https://doi.org/10.3390/app16157646) — Albarrak & Jagtap, *Applied Sciences (Switzerland)*, 2026 `DIA` `c·L` `HA0` `offline`
- [SETTE: A Human-Centric Framework for Operator Safety Monitoring in Industry 5.0](https://doi.org/10.1016/j.procs.2026.02.415) — Bianchini et al., *Procedia Computer Science*, 2026 `VER` `c·L` `HA1` `no eval`
- [Scene graph enhanced retrieval-augmented generation for unsafe behavior detection in industry](https://doi.org/10.1016/j.jmsy.2026.05.014) — Laili et al., *Journal of Manufacturing Systems*, 2026 `MON` `e·S` `HA0` `offline`
- [Fusing a Slimming Network and Large Language Models for Intelligent Decision Support in Industrial Safety and Preventive Monitoring](https://doi.org/10.3390/electronics14234773) — Tian et al., *Electronics (Switzerland)*, 2025 `MON` `b·S` `HA0` `offline`
- [Ma-Shield: A Collaborative Verification Framework for Secure Multi-Agent Instruction Inspection in Industrial Processes](https://doi.org/10.1109/BDDM68348.2025.11442039) — Song et al., *2025 IEEE 3rd International Conference on Big Data and Da…*, 2025 `VER` `c·L` `HA0` `offline`

## Manufacturing data and knowledge services

- [Multi-agent Generative AI on Digital Twins: A Learning Feedback Loop Framework for Monitoring and Explainability](https://doi.org/10.1007/978-3-032-36547-7_6) — Tieu et al., *Communications in Computer and Information Science*, 2027 `QA` `d·L` `HA0` `lab`
- [Lifecycle-aware knowledge graphs with human-in-the-loop agentic retrieval for automotive manufacturing](https://doi.org/10.1016/j.aei.2026.105122) — Yang et al., *Advanced Engineering Informatics*, 2026 `QA` `b·L` `HA0` `offline`
- [ChatCNC: Conversational machine monitoring via large language model and real-time data retrieval augmented generation](https://doi.org/10.1016/j.jmsy.2025.01.018) — Jeon et al., *Journal of Manufacturing Systems*, 2025 `QA` `c·L` `HA0` `lab`
- [Digital Products Based on Large Language Models for the Exploration of Graph-Databases in Materials Science and Manufacturing](https://doi.org/10.1109/ICE/ITMC65658.2025.11106608) — Buschelberger et al., *Proc. 31st ICE IEEE/ITMC Conference on Engineering, Techn…*, 2025 `QA` `a·L` `HA0` `offline`
- [LLM-Based Text-to-SQL for SparkSQL Queries in Manufacturing Data Lakes: An Architecture for Industry 4.0](https://doi.org/10.1109/ISCMI67495.2025.11358579) — Caldeira et al., *Proc. International Conference on Soft Computing and Mach…*, 2025 `QA` `c·L` `HA0` `offline`
- [LLM-Enhanced Human–Machine Interaction for Adaptive Decision-Making in Dynamic Manufacturing Process Environments](https://doi.org/10.1109/ACCESS.2025.3549529) — Z. Keskin et al., *IEEE Access*, 2025 `QA` `d·L` `HA0` `simulation`

## Citation

```bibtex
@article{MoradzadehFarid2026agentic,
  author  = {Moradzadeh Farid, Nastaran and Shafiee, Sara},
  title   = {{LLM}-Based Agentic {AI} in Manufacturing: A Scoping Review of Applications, System Designs and Evaluation Practices},
  journal = {Machine Learning and Knowledge Extraction},
  year    = {2026},
  note    = {Under review}
}
```

Contributions are welcome via pull request. Licensed under the [MIT License](LICENSE).
