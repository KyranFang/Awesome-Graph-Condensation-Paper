# Awesome-Graph-Condensation-Paper

## Introduction

The swift expansion of graph data presents considerable difficulties in terms of storage, transfer, and especially in the training of graph neural networks (GNNs). In response to these challenges, graph condensation (GC) has become a novel approach. GC aims to create a smaller but highly representative graph, allowing GNNs trained on this reduced graph to attain results that are on par with those trained on the original, larger graph. Although vanilla Graph Condensation has achieved very good results on some datasets, there are still some issues such as generalization, scalability, robustness, efficiency, and fairness. A variety of methods have already been proposed to address these existing problems. Therefore, we summarize the existing methods and organize them into this paper list.

## Paper List

### Survey

| Venue    | Paper                                                                                   | Links                                  |
| -------- | --------------------------------------------------------------------------------------- | -------------------------------------- |
| Arxiv'24 | A Survey on Graph Condensation                                                          | [paper](https://arxiv.org/abs/2402.02000) |
| Arxiv'24 | Graph Condensation: A Survey                                                            | [paper](https://arxiv.org/abs/2401.11720) |
| IJCAI'24 | A Comprehensive Survey on Graph Reduction: Sparsification, Coarsening, and Condensation | [paper](https://arxiv.org/abs/2402.03358) |

### Benchmarks

| Venue      | Paper                                                          | Links                                                                                   |
| ---------- | -------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| NeurIPS'24 | GC-Bench: An Open and Unified Benchmark for Graph Condensation | [paper](https://arxiv.org/abs/2407.00615) [library](https://github.com/RingBDStack/GC-Bench) |

### Conference and Journal Paper

| Venue              | Paper                                                                                          | Links                                                                     |
| ------------------ | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| ICLR'22            | Graph Condensation for Graph Neural Networks                                                   | [paper](https://arxiv.org/abs/2110.07580)                                    |
| KDD'22             | Condensing Graphs via One-Step Gradient Matching                                               | [paper](https://dl.acm.org/doi/abs/10.1145/3534678.3539429)                  |
| Arxiv'22           | Graph Condensation via Receptive Field Distribution Matching                                   | [paper](https://arxiv.org/abs/2206.13697)                                    |
| KDD'23             | Kernel Ridge Regression-Based Graph Dataset Distillation                                       | [paper](https://dl.acm.org/doi/10.1145/3580305.3599398)                      |
| NeuIPS'23          | Structure-free Graph Condensation: From Large-scale Graphs to Condensed Graph-free Data        | [paper](https://arxiv.org/abs/2306.02664)                                    |
| NeuIPS'23          | Does graph distillation see like vision dataset counterpart?                                   | [paper](https://arxiv.org/abs/2310.09192)                                    |
| NeurIPS'23         | Fair Graph Distillation                                                                        | [paper](https://openreview.net/forum?id=xW0ayZxPWs)                          |
| ICDM'23            | CaT: Balanced Continual Graph Learning with Graph Condensation                                 | [paper](https://arxiv.org/abs/2309.09455)                                    |
| Applied Science'23 | GCARe: Mitigating Subgroup Unfairness in Graph Condensation through Adversarial Regularization | [paper](https://www.mdpi.com/2076-3417/13/16/9166)                           |
| KBS'23             | Multiple Sparse Graphs Condensation                                                            | [paper](https://www.sciencedirect.com/science/article/pii/S0950705123006548) |
| Arxiv'23           | PUMA: Efficient Continual Graph Learning with Graph Condensation                               | [paper](https://arxiv.org/abs/2312.14439)                                    |
| Arxiv'23           | Faster Hyperparameter Search for GNNs via Calibrated Dataset Condensation                      | [paper](https://openreview.net/forum?id=ohQPU2G3r3C)                         |
| Arxiv'23           | FedGKD: Unleashing the Power of Collaboration in Federated Graph Neural Networks               | [paper](https://arxiv.org/abs/2309.09517)                                    |
| Arxiv'23           | Attend Who is Weak: Enhancing Graph Condensation via Cross-Free Adversarial Training           | [paper](https://arxiv.org/abs/2311.15772)                                    |
| ICML'24            | Navigating Complexity: Toward Lossless Graph Condensation via Expanding Window Matching        | [paper](https://arxiv.org/abs/2402.05011)                                    |
| ICML'24            | Graph Distillation with Eigenbasis Matching                                                    | [paper](https://arxiv.org/abs/2310.09202)                                    |
| ICLR'24            | Mirage: Model-Agnostic Graph Distillation for Graph Classification                             | [paper](https://arxiv.org/abs/2310.09486)                                    |
| KDD'24             | Graph Data Condensation via Self-expressive Graph Structure Reconstruction                     | [paper](https://arxiv.org/abs/2403.07294)                                    |
| KDD'24             | Self-Supervised Learning for Graph Dataset Condensation                                        | [paper](https://dl.acm.org/doi/10.1145/3637528.3671682)                      |
| KDD'24             | Graph Condensation for Open-World Graph Learning                                               | [paper](https://arxiv.org/abs/2405.17003)                                    |
| WWW'24             | EXGC: Bridging Efficiency and Explainability in Graph Condensation                             | [paper](https://arxiv.org/abs/2402.05962)                                    |
| WWW'24             | Fast Graph Condensation with Structure-based Neural Tangent Kernelpaper                        | [paper](https://arxiv.org/abs/2310.11046)                                    |
| ECCV'24            | GSTAM: Efficient Graph Distillation with Structural Attention-Matching                         | [paper](https://arxiv.org/abs/2408.16871)                                    |
| ICDE'24            | Graph Condensation for Inductive Node Representation Learning                                  | [paper](https://arxiv.org/abs/2307.15967)                                    |
| TKDE'24            | Heterogeneous Graph Condensation                                                               | [paper](https://ieeexplore.ieee.org/abstract/document/10423255)              |
| Arxiv'24           | Federated Graph Condensation with Information Bottleneck Principles                            | [paper](https://arxiv.org/abs/2405.03911)                                    |
| Arxiv'24           | Simple Graph Condensation                                                                      | [paper](https://arxiv.org/abs/2403.14951)                                    |
| Arxiv'24           | Two Trades is not Baffled: Condensing Graph via Crafting Rational Gradient Matching            | [paper](https://arxiv.org/abs/2402.04924)                                    |
| Arxiv'24           | Disentangled Condensation for Large-scale Graphs                                               | [paper](https://arxiv.org/pdf/2401.12231)                                    |
| Arxiv'24           | Rethinking and Accelerating Graph Condensation: A Training-Free Approach with Class Partition  | [paper](https://arxiv.org/abs/2405.13707)                                    |
| Arxiv'24           | RobGC: Towards Robust Graph Condensation                                                       | [paper](https://arxiv.org/abs/2406.13200)                                    |
| Arxiv'24           | Backdoor Graph Condensation                                                                    | [paper](https://arxiv.org/abs/2407.11025)                                    |
