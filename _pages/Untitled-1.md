



---

```yaml
---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
```

## About Me

I am a Ph.D. student in Computer Science at the **University of California, Riverside**, advised by Prof. **Zizhong Chen**. 

Previously, I received my **M.S. in Electrical Engineering** from **Columbia University** and **B.S. in Computer Science** (with a **double major** in Economics) from **Peking University**.

My research interests lie broadly in **High-Performance Computing (HPC)**, **Reinforcement Learning**, **Fault Tolerance & Resilience in Deep Learning Systems**, **Parallel, Distributed & Heterogeneous Systems**, and **Lossy Compression & Data Management**.

---

## News

- **June 2023**: Gave a talk at the 37th ACM International Conference on Supercomputing (ICS 2023).  
- **April 2023**: Our work on high-performance and fault-tolerant GEMM on GPUs was accepted by ICS 2023.
- ...

*(若需要，你可在此处按时间顺序补充更多动态)*

---

## Education

- **Ph.D. in Computer Science** (Sep. 2022 – Present)  
  University of California, Riverside (UCR)  
  *Advisor:* Prof. Zizhong Chen

- **M.S. in Electrical Engineering** (Sep. 2020 – May 2022)  
  Columbia University

- **B.S. in Computer Science** (Sep. 2016 – Jul. 2020)  
  **B.S. in Economics (Double Major)**  
  Peking University

---

## Research Experience

1. **USC ISI / Argonne National Laboratory** (Jan. 2024 – Present)  
   *Los Angeles, CA / Lemont, IL*  
   **Scientific Workflow Applications on Resilient Metasystem**  
   *Mentors: Dr. Franck Cappello, Dr. Sheng Di, Dr. Krishnan Raghavan (ANL); Dr. Ewa Deelman (USC ISI)*  
   - Designed a Q-learning + GNN-based topology protocol (**DGRO**) that reduces network diameter by optimizing virtual rings over heterogeneous, failure-prone systems.  
   - Implemented a single-hop gossip-based failure detector, resilient to network jitter and churn, enabling decentralized membership monitoring across 20+ globally distributed sites.  
   - Deployed DGRO on the FABRIC testbed spanning Japan, Europe, Hawaii, and 15+ U.S. locations, demonstrating fast convergence and robustness at international scale.

2. **UCR / Lawrence Berkeley National Laboratory** (Sep. 2022 – Present)  
   *Riverside, CA*  
   **Data-driven Exascale Control of Optically Driven Excitations in Chemical and Material Systems**  
   *Mentor: Dr. Zizhong Chen*  
   - Designed and implemented in-kernel **ABFT GEMM** using tensor cores, achieving higher performance than **cuBLAS** while ensuring fault detection and correction under soft errors.  
   - Developed a fully GPU-resident **ABFT FFT** pipeline, outperforming **cuFFT**, and enabling error-resilient spectral analysis in scientific simulations.  
   - Proposed the first ABFT-enabled K-means clustering framework on GPUs, exceeding **cuML** performance with integrated resilience support.  
   - Innovated lightweight, low-overhead in-kernel fault tolerance mechanisms across linear algebra and ML workloads, demonstrating resilience-performance co-design in exascale systems.

3. **Nvidia** (Jun. 2024 – Sep. 2024)  
   *Santa Clara, CA*  
   **Compiler Optimization for OpenMP Target Offload on Heterogeneous GPU Architectures**  
   *Mentor: Dr. David Appelhans*  
   - Investigated performance bottlenecks of OpenMP target offload in SPEChpc 2021 on GH200/H200 GPUs.  
   - Developed compiler/runtime optimizations achieving up to 10× speedup without source code changes.  
   - Analyzed OpenMP vs. OpenACC performance and contributed optimized versions to SPEChpc 1.1.9.  
   - Work adopted by RWTH Aachen University, demonstrating both research impact and practical relevance.

4. **Columbia University / AI4Finance Foundation** (Aug. 2021 – Jul. 2022)  
   *New York, NY*  
   **ElegantRL: Massively Parallel Deep Reinforcement Learning Library**  
   *Mentors: Dr. Xiaoyang Liu, Dr. Xiaodong Wang*  
   - Developed multi-agent RL algorithms in **ElegantRL**, a popular RL library with ~4k GitHub stars.  
   - Co-led **ElegantRL_Solver**, a high-performance solver that outperforms Gurobi for dense MaxCut problems.

---

## Publications

<p>
For the complete list, please visit my 
<a href="https://scholar.google.com/citations?user=MFWUo10AAAAJ&hl=en" target="_blank">Google Scholar</a>.
</p>

### Conference Papers

- **[PPoPP '25]**  
  **Shixun Wu**, Yujia Zhai, Jinyang Liu, Jiajun Huang, Zizhe Jian, Sheng Di, Franck Cappello, Zizhong Chen.  
  *TurboFFT: Co-Designed High-Performance and Fault-Tolerant Fast Fourier Transform on GPUs.*  
  <em>ACM Symposium on Principles and Practice of Parallel Programming (PPoPP), 2025.</em>  
  [[Paper]](https://doi.org/10.1145/3710848.3710853)

- **[Cluster '24]**  
  **Shixun Wu**\*, Yitong Ding\*, Yujia Zhai, Jinyang Liu, Jiajun Huang, Zizhe Jian, Huangliang Dai, Sheng Di, Bryan Wong, Zizhong Chen, Franck Cappello.  
  *FT K-means: A High-Performance K-means on GPU with Fault Tolerance.*  
  <em>2024 IEEE International Conference on Cluster Computing (CLUSTER).</em>  
  [[Paper]](https://www.computer.org/csdl/proceedings-article/cluster/2024/587100a322/21HPtzEXyCY)

- **[SC '24]**  
  Jinyang Liu\*, Jiannan Tian\*, **Shixun Wu**\*, Sheng Di, Boyuan Zhang, Robert Underwood, Yafan Huang, Jiajun Huang, Kai Zhao, Guanpeng Li, Dingwen Tao, Zizhong Chen, Franck Cappello.  
  *cuSZ-I: High-Fidelity Error-Bounded Lossy Compression for Scientific Data on GPUs.*  
  <em>SC24: International Conference for High Performance Computing, Networking, Storage and Analysis, 2024.</em>  
  [[Paper]](https://www.computer.org/csdl/proceedings-article/sc/2024/529100a158/21HUVd8CAPC)

- **[ICS '23]**  
  **Shixun Wu**\*, Yujia Zhai\*, Jinyang Liu, Jiajun Huang, Zizhe Jian, Bryan Wong, Zizhong Chen.  
  *Anatomy of High-Performance GEMM with Online Fault Tolerance on GPUs.*  
  <em>37th ACM International Conference on Supercomputing (ICS), 2023.</em>  
  [[Paper]](https://dl.acm.org/doi/10.1145/3577193.3593715)

- **[IPDPS '24]**  
  Zizhe Jian, Sheng Di, Jinyang Liu, Kai Zhao, Xin Liang, Haiying Xu, Robert Underwood, **Shixun Wu**, Jiajun Huang, Zizhong Chen, Franck Cappello.  
  *CliZ: Optimizing Lossy Compression for Climate Datasets with Adaptive Fine-tuned Data Prediction.*

- **[SIGMOD '24]**  
  Jinyang Liu, Sheng Di, Kai Zhao, Xin Liang, Sian Jin, Zizhe Jian, Jiajun Huang, **Shixun Wu**, Zizhong Chen, Franck Cappello.  
  *High-performance Effective Scientific Error-bounded Lossy Compression with Auto-tuned Multi-component Interpolation.*

- **[BigData '23]**  
  Jiajun Huang, Jinyang Liu, Sheng Di, Yujia Zhai, Zizhe Jian, **Shixun Wu**, Kai Zhao, Zizhong Chen, Yanfei Guo, Franck Cappello.  
  *Exploring Wavelet Transform Usages for Error-bounded Scientific Data Compression.*

- **[Allerton '23]**  
  Jeremy Johnston, Xiaoyang Liu, **Shixun Wu**, Xiaodong Wang.  
  *Downlink beamforming optimization via deep learning.*  
  <em>59th Annual Allerton Conference on Communication, Control, and Computing (Allerton), 2023.</em>

### Journal Papers

- **[IJHPCA '25]**  
  Balaprakash Prasanna, Krishnan Raghavan, Franck Cappello, Ewa Deelman, Anirban Mandal, Hongwei Jin, Imtiaz Mahmud, Komal Thareja, **Shixun Wu**, Pawel Zuk, Mariam Kiran, Zizhong Chen, Sheng Di, Kesheng Wu.  
  *SWARM: Reimagining Scientific Workflow Management Systems in a Distributed World.*  
  <em>International Journal of High Performance Computing Applications, 2025.</em>

- **[TSP '23]**  
  Jeremy Johnston, Xiaoyang Liu, **Shixun Wu**, Xiaodong Wang.  
  *A Curriculum Learning Approach to Optimization with Application to Downlink Beamforming.*  
  <em>IEEE Transactions on Signal Processing, 2023.</em>

### Poster Papers

- **[HPDC '23]**  
  **Shixun Wu**\*, Yujia Zhai\*, Jiajun Huang, Zizhe Jian, Zizhong Chen.  
  *FT-GEMM: A Fault Tolerant High Performance GEMM Implementation on x86 CPUs.*  
  <em>The 32nd ACM International Symposium on High-Performance Parallel and Distributed Computing (HPDC), 2023.</em>  
  [[Poster]](https://dl.acm.org/doi/10.1145/3588195.3595947)

### Workshop Papers

- **[SC '24 Workshop]**  
  Ewa Deelman, Prasanna Balaprakash, Mariam Kiran, Anirban Mandal, Krishnan Raghavan, Sheng Di, Franck Cappello, John Wu, Zizhong Chen, **Shixun Wu**, Hongwei Jin, Cong Wang, Imtiaz Mahmud, Komal Thareja, Erik Scott, Pawel Zuk, Aiden Hamade.  
  *SWARM: Scientific Workflow Applications on Resilient Metasystem.*

- **[ICLR '23 Workshop]**  
  Xiaoyang Liu, Zechu Li, **Shixun Wu**, Xiaodong Wang.  
  *Stationary Deep Reinforcement Learning With Quantum K-Spin Hamiltonian Regularization.*  
  <em>ICLR 2023 Workshop on Physics for Machine Learning, 2023.</em>

### arXiv (In Submission)
1. **Shixun Wu**, Sheng Di, Krishnan Ragahvan, Kesheng Wu, Ewa Deelman, Franck Cappello.  
   *DGRO: Diameter-Guided Ring Optimization for Integrated Research Infrastructure Membership.*

2. Huangliang Dai, **Shixun Wu**, Zizhong Chen.  
   *FT-Transformer.*

3. **Shixun Wu**, Zizhong Chen.  
   *TurboFNO: High-Performance Fourier Neural Operator with Fused FFT-GEMM-iFFT on GPU.*

4. **Shixun Wu**\*, Jinyang Liu\*, Jiannan Tian\*, Jinwen Pan\*, Sheng Di, Zizhong Chen, Franck Cappello.  
   *Optimizing GPU-Based Error-Bounded Lossy Compression with Advanced Interpolation and Synergistic Lossy-Lossless Scheme.*

---

## Professional Services

- Reviewer, **Parallel Computing**, 2025  
- SubReviewer, **ICS** (International Conference on Supercomputing), 2025  
- SubReviewer, **CCGrid** (International Symposium on Cluster, Cloud and Grid Computing), 2025  
- Reviewer, **GPGPU** (Workshop on General Purpose Processing Using GPU), 2025  
- Reviewer, **ICDCS** (International Conference on Distributed Computing Systems), 2025  
- SubReviewer, **IPDPS** (International Parallel and Distributed Processing Symposium), 2024, 2023  
- Reviewer, **Computing Surveys**, 2023  
- Reviewer, **Journal of Intelligent & Fuzzy Systems**, 2023  

---

## Projects Involved

- **DOE SWARM**: Scientific Workflow Applications on Resilient Metasystem  
- **DOE DECODE**: Data-driven Exascale Control of Optically Driven Excitations in Chemical and Material Systems  

---

## Teaching

- **Teaching Assistant**, CS161: Design & Architecture of Computer Systems, University of California, Riverside  
  - **Fall 2024**, **Spring 2024**

- **Teaching Assistant**, CS160: Concurrent Programming and Parallel Systems, University of California, Riverside  
  - **Fall 2023**

---

## Honors and Awards

- **NSF PPoPP Travel Grant** (Feb. 2025)  
- **Outstanding Teaching Award**, University of California, Riverside (May 2024)  
- **Third Prize**, UCRPC, University of California, Riverside (Nov. 2023)  
- **Distinguished Dean's Fellowship**, University of California, Riverside (Sep. 2022)  
- **Second Prize**, PKU ACM (2017, 2018)  
- **PKU May 4th Scholarship** (2017)

---
