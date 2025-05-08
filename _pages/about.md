---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD Candidate at University of California, Riverside. Prior to the PhD study in Computer Science, I obtained MS and BS degrees from Columbia University and Peking University.

News
======
- Mar 2025: Gave a talk at the Las Vegas, NV (PPoPP 2025).  
- June. 2023: I gave a talk at International Conference on Supercomputing 2023.
- April. 2023: A paper was accepted at International Conference on Supercomputing 2023.

Education
======

- **Ph.D. in Computer Science** (Sep. 2022 – Present)  
  University of California, Riverside (UCR)  
  *Advisor:* Prof. Zizhong Chen

- **M.S. in Electrical Engineering** (Sep. 2020 – May 2022)  
  Columbia University

- **B.S. in Computer Science** (Sep. 2016 – Jul. 2020)  
  **B.S. in Economics (Double Major)**  
  Peking University

---

Research Experience
======

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

Selected Publications
=====================

<p><a href="https://scholar.google.com/citations?user=MFWUo10AAAAJ&hl=zh-CN&oi=ao" target="_blank">Full list in Google Scholar</a></p> -->

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <div style="min-width: 200px; font-weight: bold; color: #333; white-space: nowrap;">
    SC '24
  </div>
  <div>
    Jinyang Liu*, Jiannan Tian*, <strong>Shixun Wu</strong>*, Sheng Di, Boyuan Zhang, Robert Underwood, Yafan Huang, Jiajun Huang, Kai Zhao, Guanpeng Li, Dingwen Tao, Zizhong Chen, Franck Cappello.<br>
    <em>High-ratio Scientific Lossy Compression on GPUs with Optimized Multi-level Interpolation.</em><br>
    <a href="https://arxiv.org/abs/2312.05492" target="_blank">arXiv preprint arXiv:2312.05492 (2023)</a>. (*: Co-first authors)
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <div style="min-width: 200px; font-weight: bold; color: #333; white-space: nowrap;">
    PPoPP '25
  </div>
  <div>
    <strong>Shixun Wu</strong>, Yujia Zhai, Jinyang Liu, Jiajun Huang, Zizhe Jian, Sheng Di, Franck Cappello, Zizhong Chen.<br>
    <em>TurboFFT: Co-Designed High-Performance and Fault-Tolerant Fast Fourier Transform on GPUs.</em><br>
    <a href="https://dl.acm.org/doi/10.1145/3710848.3710853" target="_blank">PPoPP '2025: ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming 2025</a>.
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <div style="min-width: 200px; font-weight: bold; color: #333; white-space: nowrap;">
    SC '24
  </div>
  <div>
    Jinyang Liu*, Jiannan Tian*, <strong>Shixun Wu</strong>*, Sheng Di, Boyuan Zhang, Robert Underwood, Yafan Huang, Jiajun Huang, Kai Zhao, Guanpeng Li, Dingwen Tao, Zizhong Chen, Franck Cappello.<br>
    <em>cuSZ-I: High-Fidelity Error-Bounded Lossy Compression for Scientific Data on GPUs.</em><br>
    <a href="https://www.computer.org/csdl/proceedings-article/sc/2024/529100a158/21HUVd8CAPC" target="_blank">2024 SC24: International Conference for High Performance Computing, Networking, Storage and Analysis</a>.
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <div style="min-width: 200px; font-weight: bold; color: #333; white-space: nowrap;">
    Cluster '24
  </div>
  <div>
    <strong>Shixun Wu</strong>*, Yitong Ding*, Yujia Zhai, Jinyang Liu, Jiajun Huang, Zizhe Jian, Huangliang Dai, Sheng Di, Bryan Wong, Zizhong Chen, Franck Cappello.<br>
    <em>FT K-means: A High-Performance K-means on GPU with Fault Tolerance.</em><br>
    <a href="https://www.computer.org/csdl/proceedings-article/cluster/2024/587100a322/21HPtzEXyCY" target="_blank">2024 IEEE International Conference on Cluster Computing (CLUSTER)</a>.
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <div style="min-width: 200px; font-weight: bold; color: #333; white-space: nowrap;">
    HPDC '23
  </div>
  <div>
    <strong>Shixun Wu</strong>*, Yujia Zhai*, Jiajun Huang, Zizhe Jian, Zizhong Chen.<br>
    <em>FT-GEMM: A Fault Tolerant High Performance GEMM Implementation on x86 CPUs.</em><br>
    <a href="https://dl.acm.org/doi/10.1145/3588195.3595947" target="_blank">The 32nd ACM International Symposium on High-Performance Parallel and Distributed Computing, Orlando, FL, USA, June 21–23, 2023</a>. DOI: 10.1145/3588195.3595947.
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <div style="min-width: 200px; font-weight: bold; color: #333; white-space: nowrap;">
    ICS '23
  </div>
  <div>
    <strong>Shixun Wu</strong>*, Yujia Zhai*, Jinyang Liu, Jiajun Huang, Zizhe Jian, Bryan Wong, Zizhong Chen.<br>
    <em>Anatomy of High-Performance GEMM with Online Fault Tolerance on GPUs.</em><br>
    <a href="https://dl.acm.org/doi/10.1145/3577193.3593715" target="_blank">The 37th ACM International Conference on Supercomputing, Orlando, FL, USA, June 21–23, 2023</a>. DOI: 10.1145/3577193.3593715.
  </div>
</div>



<!-- Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
