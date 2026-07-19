# Scaling & Efficiency

_31 papers · updated 2026-07-19 06:53 UTC_

[← Back to index](../README.md)

## 2026-07

### Trajectory-Aware Flow Matching for Topology Optimisation
**Shusheng Xiao, Jinshuai Bai, Hyogu Jeong, Yunfei Xi, Yilin Gui, YuanTong Gu**  
`cs.LG` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14652) · [pdf](https://arxiv.org/pdf/2607.14652v1)

A flow matching framework conditions on volume-fraction-indexed optimisation states to generate feasible structural topologies without iterative solvers or inference-time guidance.

### SmartRAG: Native Graph-Based RAG for Mobile Device
**Zhihan Jiang, Meng Li, Shenghao Liu, Keran Li, Ruiben Zhou, Xianjun Deng et al.**  
`cs.AI` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14661) · [pdf](https://arxiv.org/pdf/2607.14661v1)

An on-device assistant pairs a continually learning entity recognizer with a provenance-preserving knowledge graph, invoking the local LLM only for high-value semantic steps.

### Selectivity Drives Efficiency: Dataset Pruning for Visual Place Recognition
**Tong Jin, Yunpeng Liu, Shuyu Hu, Chun Yuan, Song Wang, Feng Lu**  
`cs.CV` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14897) · [pdf](https://arxiv.org/pdf/2607.14897v1)

Prunes visual place recognition training data at the place level using intra-place diversity and inter-place similarity rather than per-image scoring.

### Seeing the End at Step Zero: Accelerating Diffusion MLLMs via MLP Sparsity-Aware Truncation
**Qicheng Zhao, Qi Sun, Zheyu Yan**  
`cs.AI` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14557) · [pdf](https://arxiv.org/pdf/2607.14557v1)

Training-free method detects output length from first-step MLP activation sparsity to truncate padding in diffusion multimodal models, raising throughput substantially.

### Reflex: Real-Time VLA Control through Streaming Inference
**Yuanchun Guo, Bingyan Liu**  
`cs.RO` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14695) · [pdf](https://arxiv.org/pdf/2607.14695v1)

Partitions attention context into static, sliding, and dynamic regions for O(1) cache updates, enabling real-time streaming inference for flow matching robot policies.

### PolyQ: Codesigning End-to-End Quantization Framework for Scalable Edge CPU LLM Inference
**Hyunwoo Oh, Suyeon Jang, Hanning Chen, KyungIn Nam, Sanggeon Yun, Ryozo Masukawa et al.**  
`cs.LG` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14618) · [pdf](https://arxiv.org/pdf/2607.14618v1)

Compiler and quantization co-design assigning per-channel bit-widths and clustering channels into homogeneous blocks for efficient CPU-only LLM inference.

### On-Policy Delta Distillation
**Byeongho Heo, Jaehui Hwang, Sangdoo Yun, Dongyoon Han**  
`cs.LG` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.15161) · [pdf](https://arxiv.org/pdf/2607.15161v1)

On-policy distillation uses the teacher-minus-base logit difference as reward, improving reasoning transfer on math, science, and code benchmarks.

### NIFA: Nonlinear IMC enhanced FPGA for efficient ML inference
**Jiajun Hu, Ruthwik Reddy Sunketa, Lei Zhao, Archit Gajjar, Luca Buonanno, Aman Arora**  
`cs.AR` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.15123) · [pdf](https://arxiv.org/pdf/2607.15123v1)

An FPGA architecture replaces IMC analog-to-digital converters with content-addressable memories to handle nonlinear and dynamic matrix operations for Transformer inference.

### MagicPrompt: Ultra-Lightweight Prompt Tuning for Video Generation
**Yinhan Zhang, Dinwei Tan, Xianghao Kong, Yue Ma, Yeying Jin, Anyi Rao**  
`cs.CV` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14595) · [pdf](https://arxiv.org/pdf/2607.14595v1)

Soft-prompt tuning with dual-space reward feedback adapts video diffusion models using under one percent trainable parameters.

### LongStraw: Long-Context RL Beyond 2M Tokens under a Fixed GPU Budget
**Changhai Zhou, Kieran Liu, Yuhua Zhou, Qian Qiao, Jun Gao, Harry Zhang et al.**  
`cs.LG` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14952) · [pdf](https://arxiv.org/pdf/2607.14952v1)

Provides an execution stack enabling million-token reinforcement learning post-training on fixed GPU budgets by replaying response branches separately.

### Long-Context Fine-Tuning with Limited VRAM
**Vladimir Fedosov, Aleksandr Sazhin, Artemiy Grinenko, Frank Woernle**  
`cs.AI` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.15105) · [pdf](https://arxiv.org/pdf/2607.15105v1)

Hierarchical global attention with segment-wise backpropagation and tiered KV offloading enables 16K-token QLoRA fine-tuning on a 16GB consumer GPU.

### Language Identification via Compositional Data Analysis: A Linear-Time Classifier Based on Log-Ratio Geometry
**Paul-Andrei Pogăcean, Sanda-Maria Avram**  
`cs.CL` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.15238) · [pdf](https://arxiv.org/pdf/2607.15238v1)

Centered log-ratio transforms of character and bigram frequencies enable linear-time language identification across six languages without neural models.

### In-Place Tokenizer Expansion for Pre-trained LLMs
**Jimmy T. H. Smith, Tarek Dakhran, Alberto Cabrera, Simon S. Lee, Paul Pak, Aditya Tadimeti et al.**  
`cs.CL` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.15232) · [pdf](https://arxiv.org/pdf/2607.15232v1)

Extends a pretrained model's tokenizer in place by continuing BPE merges and initializing new embeddings from sub-token means.

### ExaGEMM: Exploration Framework for CPU-Driven ML Inference via Associative In-Register Computing for Low-Bit GEMM
**Hyunwoo Oh, Suyeon Jang, Hanning Chen, Sanggeon Yun, Ryozo Masukawa, Mohsen Imani**  
`cs.AR` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14622) · [pdf](https://arxiv.org/pdf/2607.14622v1)

Design-space exploration framework co-designing SIMD ISA extensions and register-resident lookup-table kernels for low-bit matrix multiplication on CPUs.

### Data Driven Block Replacement Scheduling
**Aniruddhan Ganesaraman, VIdyadhar Kulkarni**  
`cs.LG` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.15229) · [pdf](https://arxiv.org/pdf/2607.15229v1)

Bandit and survival-analysis algorithms learn cost-optimal joint machine replacement intervals from censored failure data with logarithmic regret.

### D-cut: Adaptive Verification Depth Pruning for Batched Speculative Decoding
**Tianyu Liu, Yuhao Shen, Rui Cen, Junhan Shi, Jiebin Zhang, Guangshuo Qin et al.**  
`cs.CL` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14647) · [pdf](https://arxiv.org/pdf/2607.14647v1)

Adaptive cross-request draft pruning with a runtime cost model concentrates verification budget on likely-accepted tokens under high batch concurrency.

### Cross-Layer Error Compensation and Finite-Sample Feature-Statistics Matching for Extreme Low-Bit Quantization of Large Language Models
**Ryona Noda**  
`cs.NE` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14630) · [pdf](https://arxiv.org/pdf/2607.14630v1)

Post-training quantization method that models cross-layer error propagation and matches feature statistics to preserve accuracy at extreme low bit-widths.

### CASP: Learning-Augmented Offline Approximation with Verifiable Certificates and Bounded-Loss PAC Guarantees
**Haifeng Li, Mo Hai**  
`cs.LG` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14545) · [pdf](https://arxiv.org/pdf/2607.14545v1)

Learning-augmented optimization prunes search space using verifier-checked certificates, yielding bounded loss classes and sample-complexity guarantees independent of prediction quality.

### A Modern Multimodal Assistant on a 6 GB 2011 GPU: Stage-Validated, All-GPU CUDA Inference for Fermi
**A. C. Opus, J. Q. Lu**  
`cond-mat.other` · 2026-07-16 · [abs](https://arxiv.org/abs/2607.14568) · [pdf](https://arxiv.org/pdf/2607.14568v1)

Full-GPU CUDA inference engine ports a multimodal assistant to 2011-era Fermi hardware, with stage-validated kernels and 8-bit weights outperforming 4-bit.

### TMallGS: Scaling Unified Feature and Sequence Modeling for Generative E-commerce Search
**Zhentao Song, Yufeng Gao, Xing Fang, Jing Wang, Guangxin Song, Bokang Wang et al.**  
`cs.IR` · 2026-07-15 · [abs](https://arxiv.org/abs/2607.13398) · [pdf](https://arxiv.org/pdf/2607.13398v1)

Transformer ranking architecture for Tmall search with field-adaptive tokenization and gating tailored to heterogeneous CTR features.

### Self-Evolving Agent Harnesses via Gated Semantic Quality-Diversity
**Xiaotian Luo, Fengxingyu Wang, Chuanrui Hu, Dizhan Xue, Yafeng Deng**  
`cs.CL` · 2026-07-15 · [abs](https://arxiv.org/abs/2607.13683) · [pdf](https://arxiv.org/pdf/2607.13683v1)

Evolves LLM agent harnesses by having a model propose patches while deterministic code owns measurement and significance testing, archived by pathology rather than task.

### Real-Time Detection of Charge Jumps in Superconducting Qubits with a Convolutional Neural Network
**Daniel Gaytan-Villarreal, Peter Meiring, Daniel Baxter, Daniel Bowring, Grace Bratrud, Matteo Cremonesi et al.**  
`quant-ph` · 2026-07-15 · [abs](https://arxiv.org/abs/2607.14293) · [pdf](https://arxiv.org/pdf/2607.14293v1)

A dilated causal CNN deployed on FPGA detects superconducting qubit charge jumps online at 6.19 microsecond latency, matching offline chi-squared efficiency.

### PReM: Learning What to Preserve and When to Refresh for Context Compression
**Bohan Yu, Lei Shen, Chenxi Zhou, Chen Han, Junlin Liu, Wenbo Su et al.**  
`cs.CL` · 2026-07-15 · [abs](https://arxiv.org/abs/2607.14327) · [pdf](https://arxiv.org/pdf/2607.14327v1)

Context compression framework keeps long context as internal layer-wise KV memory and learns when to refresh selections during generation.

### GFlowRL: Scaling Distribution-Matching RL to Large Language Models
**Xiaodong Liu, Michael Xu, Jack W. Stokes, Paul Smolensky, Doug Burger, Jianfeng Gao**  
`cs.CL` · 2026-07-15 · [abs](https://arxiv.org/abs/2607.13394) · [pdf](https://arxiv.org/pdf/2607.13394v1)

Replaces GFlowNet's learned partition function with an in-batch Monte Carlo estimate, making distribution-matching RL stable at large language model scale.

### Constraint-Driven Model Optimization: An Industry Framework for Selecting Compression and Acceleration Techniques in Modern Machine Learning Systems
**Dhruv Shivkant, Saket Mohanty, Utkarsh Wadhwa**  
`cs.LG` · 2026-07-15 · [abs](https://arxiv.org/abs/2607.13735) · [pdf](https://arxiv.org/pdf/2607.13735v1)

Framework maps quantization, pruning, distillation, and PEFT choices to five deployment constraint dimensions via a prescriptive decision procedure.

### No Attention, No Problem: DPU-Aware Attention Approximation in Modern YOLO on FPGA
**Suraj Karki, Qazi Arbab Ahmed, Thorsten Jungeblut**  
`cs.AR` · 2026-07-14 · [abs](https://arxiv.org/abs/2607.13106) · [pdf](https://arxiv.org/pdf/2607.13106v1)

FPGA deployment of attention-based YOLO detectors using DPU-compatible operator substitutions, benchmarked across eight accelerator configurations and six datasets.

### Less Experts, Faster Decoding: Cost-Aware Speculative Decoding for Mixture-of-Experts
**Jincheng Xie, Runheng Liu, Heyan Huang, Yawen Ling, Hanbin Dai, Yu Zheng et al.**  
`cs.CL` · 2026-07-14 · [abs](https://arxiv.org/abs/2607.12696) · [pdf](https://arxiv.org/pdf/2607.12696v1)

Speculative decoding that factors predicted expert activation cost into draft selection, avoiding expert scattering in mixture-of-experts inference.

### Full-Pipeline Inference Optimization for MiMo-V2.5 Series: Pushing Hybrid SWA Efficiency to the Limit
**Xiaomi MiMo Team, Anqi Liu, Aoxin Ma, Bo Chen, Bo Yang, Chen Wang et al.**  
`cs.AR` · 2026-07-14 · [abs](https://arxiv.org/abs/2607.13095) · [pdf](https://arxiv.org/pdf/2607.13095v1)

Production serving optimizations for hybrid sliding-window attention plus MoE and multimodal models, covering KV cache placement, distributed caching, and affinity routing.

### Score-Only Distillation for Compact Dense Retrieval
**Kirill Dubovikov, Martin Takac, Salem Lahlou**  
`cs.IR` · 2026-07-13 · [abs](https://arxiv.org/abs/2607.11465) · [pdf](https://arxiv.org/pdf/2607.11465v1)

A compact retriever is distilled from teacher score vectors alone, recovering half the quality gap while encoding several times faster.

### Extending LLM Context via Associative Recurrent Memory
**Gleb Kuzmin, Ivan Rodkin, Aydar Bulatov, Yuri Kuratov, Lyudmila Rvanova, Mikhail Katkov et al.**  
`cs.CL` · 2026-07-13 · [abs](https://arxiv.org/abs/2607.11614) · [pdf](https://arxiv.org/pdf/2607.11614v1)

Associative recurrent memory plus curriculum training extends LLM context at constant memory and 30% fewer FLOPs.

### DP-Splat: Bayesian Nonparametric Complexity Control for Gaussian Splatting
**Aqi Dong**  
`cs.CV` · 2026-07-12 · [abs](https://arxiv.org/abs/2607.10912) · [pdf](https://arxiv.org/pdf/2607.10912v1)

A Dirichlet-process prior lets Gaussian splatting adapt its component count to scene complexity with closed-form variational updates and truncation bounds.
