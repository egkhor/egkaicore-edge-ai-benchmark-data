# EGKAICore Edge AI Benchmark Data

This repository contains raw benchmark data supporting the empirical
edge AI feasibility evaluation reported in the manuscript:

"Privacy Preserving Edge AI for IoT Using a Risk and Cost Framework
for Data Boundary Control Confidentiality Lifetime and Model Feasibility"

## Dataset

The dataset contains repeated benchmark measurements obtained using
EGKAICore on a physical iPhone test device.

The reported measurements include:

- Time to first token (TTFT)
- Generated token count
- Steady-state token generation rate
- Peak memory usage

## Phi-3.5 Mini

The Phi-3.5 Mini benchmark consists of four repeated runs.

| Run | TTFT (s) | Tokens | Steady-state (tok/s) |
|---|---:|---:|---:|
| 1 | 0.155 | 325 | 22.5 |
| 2 | 0.157 | 338 | 21.8 |
| 3 | 0.159 | 348 | 21.1 |
| 4 | 0.161 | 361 | 20.6 |
| Mean | 0.158 | 343 | 21.5 |
| Range | 0.155–0.161 | 325–361 | 20.6–22.5 |

Peak memory observed during the evaluation was 1.24 GB.

## Scope

This dataset represents a bounded empirical feasibility evaluation
performed on one physical test device using one edge AI platform and
the specified model configuration. It should not be interpreted as
a representative benchmark of all devices, models, or applications.

## Data availability

The data are publicly available in this repository.

## License

The dataset is provided for research and academic use.
