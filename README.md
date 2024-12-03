# LLM_Edge_Inference_Separation_Architecture
Collection of popular literature

![image](https://github.com/user-attachments/assets/cbc1e41a-42da-4ba7-9d09-bbed4f8258e6)

## 📒Introduction
Edge Inference, Edge Intelligence, Collaborative DNN Inference, Distributed Computing

### 📖Collection of popular literature
<div id="Trending-LLM-VLM-Topics"></div>  

|Date|Title|Paper|Code|Recom|
|:---:|:---:|:---:|:---:|:---:|   
|2024.01| 🔥[DistServe] DistServe: Disaggregating Prefill and Decoding for Goodput-optimized Large Language Model Serving|[[docs]](https://arxiv.org/abs/2401.09670) | [[DistServe]](https://github.com/LLMServe/DistServe) | ⭐️⭐️ | 
|2023.11| 🔥[Splitwise] Splitwise: Efficient Generative LLM Inference Using Phase Splitting|[[report]](https://arxiv.org/abs/2311.18677) | | ⭐️⭐️ | 
|2024.01| 🔥[TetriInfer] Inference without Interference:Disaggregate LLM Inference for Mixed Downstream Workloads|[[pdf]](https://arxiv.org/abs/2401.11181) | | ⭐️⭐️ | 
|2024.06| 🔥[MemServe] MemServe: Context Caching for Disaggregated LLM Serving with Elastic Memory Pool|[[pdf]](https://arxiv.org/abs/2406.17565) | | ⭐️⭐️ | 
|2024.06|🔥[**Mooncake**] Mooncake: A KVCache-centric Disaggregated Architecture for LLM Serving(@Moonshot AI) |[[pdf]](https://github.com/kvcache-ai/Mooncake/blob/main/Mooncake-v1.pdf) | [[Mooncake]](https://github.com/kvcache-ai/Mooncake) ![](https://img.shields.io/github/stars/kvcache-ai/Mooncake.svg?style=social)|⭐️⭐️ |    
|2024.02|🔥[ChunkAttention] ChunkAttention: Efficient Self-Attention with Prefix-Aware KV Cache and Two-Phase Partition| [[pdf]](https://arxiv.org/abs/2402.15220) | [[ChunkAttention]](https://github.com/microsoft/chunk-attention) |⭐️⭐️ |  
|2023.08| 🔥[SARATHI] SARATHI: Efficient LLM Inference by Piggybacking Decodes with Chunked Prefills|[[pdf]](https://arxiv.org/abs/2308.16369) | | ⭐️ | 
|2024.05| 🔥[Galaxy] Galaxy: A Resource-Efficient Collaborative Edge AI System for In-situ Transformer Inference|[[pdf]](https://arxiv.org/abs/2405.17245) | | ⭐️ | 


## 📖 Contents' from [Awesome-LLM-Inference](#https://github.com/DefTruth/Awesome-LLM-Inference?tab=readme-ov-file)
* 📖[Trending LLM/VLM Topics](#Trending-LLM-VLM-Topics)🔥🔥🔥
* 📖[DP/MP/PP/TP/SP/CP Parallelism](#DP-MP-PP-TP-SP-CP)🔥🔥🔥
* 📖[LLM Algorithmic/Eval Survey](#LLM-Algorithmic-Eval-Survey)
* 📖[LLM Train/Inference Framework/Design](#LLM-Train-Inference-Framework)
* 📖[Weight/Activation Quantize/Compress](#Weight-Activation-Quantize-Compress)🔥
* 📖[Continuous/In-flight Batching](#Continuous-In-flight-Batching)
* 📖[IO/FLOPs-Aware/Sparse Attention](#IO-FLOPs-Aware-Attention-Sparse)🔥
* 📖[KV Cache Scheduling/Quantize/Dropping](#KV-Cache-Scheduling-Quantize-Dropping)🔥
* 📖[Prompt/Context Compression](#Context-Compression)🔥
* 📖[Long Context Attention/KV Cache Optimization](#Long-Context-Attention-KVCache)🔥🔥
* 📖[Early-Exit/Intermediate Layer Decoding](#Early-Exit)
* 📖[Parallel Decoding/Sampling](#Parallel-Decoding-Sampling)🔥
* 📖[Structured Prune/KD/Weight Sparse](#Structured_Pruning_KD_Weight_Sparse)
* 📖[Mixture-of-Experts(MoE) LLM Inference](#Mixture_of_Experts_LLM_Inference)🔥
* 📖[CPU/NPU/FPGA/Mobile Inference](#CPU-Single-GPU-Inference)
* 📖[Non Transformer Architecture](#Non-Transformer-Architecture)🔥
* 📖[GEMM/Tensor Cores/WMMA/Parallel](#GEMM-Tensor-Cores-WMMA)  
* 📖[VLM/Position Embed/Others](#Others)

* 
<!--
<div align='center'>
  <img width="450" height="250" alt="v02" src="https://github.com/DefTruth/LLMs-Inference-Papers/assets/31974251/bb136842-8054-4599-8bfe-36c36f0e997f">  
<a href="https://star-history.com/#DefTruth/Awesome-LLM-Inference&Date">
  <picture align='center'>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=DefTruth/Awesome-LLM-Inference&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=DefTruth/Awesome-LLM-Inference&type=Date" />
    <img width="350" height="250" alt="Star History Chart" src="https://api.star-history.com/svg?repos=DefTruth/Awesome-LLM-Inference&type=Date" />
  </picture>
</a>
</div>
-->

