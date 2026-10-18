# Codebook

Codes used in `included_studies.csv`. Multi-label fields are separated by `;`; binary fields are `1`/`0`.

## Selection (`screened_records.csv`)

`stage`: Deduplication, Title/abstract or Full text · `criterion`: C0 full text not retrievable · C1 publication type · C2 manufacturing relevance · C3 system-level agency · C4 system description

## Application

**`function_leaves`**

| Code | Function |
|---|---|
| `A1` | Generative product/CAD design, configuration and design reuse |
| `A2` | Design review, engineering analysis, DfX and compliance |
| `A3` | Electronics and semiconductor design automation |
| `A4` | Process, tooling and materials engineering |
| `A5` | Factory and work-cell layout, simulation models and experiments |
| `B1` | Operation planning and sequencing, incl. AM job and inspection-path planning |
| `B2` | Control, robot and NC program generation |
| `C1` | Scheduling-model/solver generation and static scheduling |
| `C2` | Dynamic scheduling and disruption management |
| `C3` | Task allocation and capability-based resource matching |
| `C4` | Operations management and MES/DT orchestration |
| `D1` | Closed-loop process/machine control and supervision |
| `D2` | Process-parameter optimisation |
| `D3` | Energy and environmental performance |
| `E1` | Inspection and defect detection |
| `E2` | Quality prediction and root-cause analysis |
| `F1` | Fault diagnosis and root-cause reasoning |
| `F2` | Predictive and prescriptive maintenance analytics |
| `G1` | NL-driven robot task planning and execution |
| `G2` | Human–robot collaboration and operator assistance |
| `G3` | Multi-robot coordination and reconfiguration |
| `H1` | Intralogistics and warehousing |
| `H2` | Supply-chain risk, supplier management and multi-site planning |
| `H3` | Inventory and demand forecasting |
| `I1` | Workplace safety monitoring and rule enforcement |
| `I2` | Action safety, plan verification and control-software testing |
| `I3` | Industrial cybersecurity |
| `J1` | NL data querying, integration and analytics |
| `J2` | Document/knowledge QA, decision explanation and operator assistance |
| `J3` | Knowledge engineering and verification |
| `K1` | Disassembly, remanufacturing and end-of-life |

**`task_type`** `GEN` generate · `OPT` plan and decide · `DIA` diagnose and analyse · `ACT` control and actuate · `QA` retrieve and answer · `MON` monitor and detect · `VER` verify and assure

**`operational_scope`** `OS1` device · `OS2` cell or line · `OS3` plant/MES · `OS4` enterprise · `OS5` manufacturing network · `OS6` product and engineering context

**`domain`** `Mach.` machining · `AM` additive · `Semi.` semiconductors/electronics · `Aero.` aerospace · `Auto.` automotive/EV/battery · `Proc.` process industries · `Text.` textile · `Disc.` other discrete · `Gen.` generic · `Adj.` manufacturing-adjacent

## Agentic design

**`agent_organisation`** `a` single agent, LLM-directed · `b` single LLM in a predefined workflow · `c` multi-agent fixed workflow · `d` hierarchical orchestrator · `e` negotiating or debating peers

**`decision_engine`** `L` LLM-led · `S` specialist-assisted (LLM combines trained models) · `O` engine-led (optimiser, RL policy, solver or controller decides)

**`grounding_memory`** `RAG` document retrieval · `KG` knowledge graph · `IM` industrial information model · `LD` live operational data · `SIM` simulation/digital twin · `SHR` shared state · `MEM` cross-run memory · `NONE`

**`tools_interfaces`** `CODE` code execution · `ENT` enterprise software/databases · `ENGT` engineering tools · `CTRL` industrial control · `ROB` robots and machines · `NONE` retrieval, analysis or checking only

**`runtime_verification`** `SELF` self-reflection · `CRIT` critic agent · `EXT` external checker · `HUM` human review · `NONE`

**`human_authority`** `HA0` advisory · `HA1` approval before execution · `HA2` autonomous execution

**`n_llm_agents`** number of LLM agents; `n` variable, `3+` at least three, `+RL` with RL agents

## Evaluation

**Scope** (assessed empirically): `S1` output quality · `S2` executability and constraint compliance · `S3` time and resource efficiency · `S4` reliability and robustness · `S5` safety, security and compliance · `S6` human–agent work · `S7` production impact

**`test_setting`** (README tag in brackets) `R0` none (`no eval`) · `R1` offline data (`offline`) · `R2` software sandbox (`sandbox`) · `R3` simulation/digital twin (`simulation`) · `R4` laboratory (`lab`) · `R5` industrial setting (`industrial`)

**`evaluation_data`** `Syn.` synthetic or author-built · `Ind.` industrial · `Pub.` public benchmark · `Lit.` literature-derived · `NA` none

**`evaluator`** `Code` · `Human` experts · `LLM` LLM judge · `Hyb.` hybrid · `NR` not reported · `NA` none

**`check_type`** `V1` compilation/schema · `V2` rules · `V3` formal · `V4` simulation · `V5` laboratory/hardware-in-the-loop · `V6` real equipment · `V0` applicable but absent · `--` not applicable

**`scale`** evaluated instances: `S` 1–50 · `S--M` 51–500 · `M` >500 · `NA`

**Other** `EM4_external_baseline` external comparator · `EM5_repeated_runs` repeated runs with dispersion · `backbone_comparison` several LLMs compared · `AN1` failure modes · `AN2` performance breakdown · `AN3` design attribution · `evaluation_target` component / agent system / system in operation · `borderline_inclusion`, `fine_tuned_llm`, `local_deployment`
