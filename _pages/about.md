---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<section class="home-hero">
  <p class="home-hero__eyebrow">Shwai He</p>
  <h1 class="home-hero__title">Efficient, Adaptive, and Multimodal Foundation Models</h1>
  <p class="home-hero__lead">I build methods and systems that make large models more scalable, economical, and deployable without giving up capability.</p>
  <div class="home-hero__meta">
    <span>Ph.D. Candidate, University of Maryland</span>
    <span>Student Researcher, ByteDance</span>
    <span>Qualcomm Innovation Fellowship, 2025</span>
  </div>
</section>

<p align="justify" style="line-height:1.5; margin-bottom:4px; text-align:justify;">
I am a Ph.D. candidate in Computer Science at the University of Maryland, College Park, advised by <a href="https://www.ang-li.com/" target="_blank">Prof. Ang Li</a>. I am currently a Student Researcher at ByteDance and previously worked at Tencent AI Lab and JD Explore Academy, where I focused on efficient model training and large-scale natural language systems.
</p>

<p align="justify" style="line-height:1.5; margin-bottom:4px; text-align:justify;">
My research focuses on building the next generation of efficient, scalable, and adaptive foundation models. I study how computation, parameters, and modalities interact inside large models to uncover the principles that govern their capacity, redundancy, and generalization. Based on these insights, I develop methods for model compression, adaptive inference, parameter-efficient fine-tuning, and modality-aware optimization, with the goal of making powerful models substantially more efficient without sacrificing capability.
</p>

<p align="justify" style="line-height:1.5; margin-bottom:4px; text-align:justify;">
I further explore system- and hardware-aware techniques that make these advances practical in real-world deployment. More recently, I have been extending this line of work to unified multimodal architectures that dynamically coordinate shared and specialized computation across language and vision. Broadly, my goal is to bridge model understanding, algorithm design, and efficient deployment, enabling foundation models that are not only larger and stronger, but also more economical, reliable, and widely usable.
</p>

News
======
  \[04/2026\]: [EffiR](#pub-effir) was accepted to [ACL 2026](https://2026.aclweb.org/). \
  \[01/2026\]: [Capacity-Aware Inference](#pub-capacity-aware-inference) was accepted to [ICLR 2026](https://iclr.cc/). \
  \[01/2026\]: [Attention Drop](#pub-attention-drop) was accepted by [TMLR](https://jmlr.org/tmlr/). \
  \[08/2025\]: [Router-Tuning](#pub-router-tuning) was accepted at [EMNLP 2025](https://2025.emnlp.org/). \
  \[05/2025\]: 🏆 Awarded the [Qualcomm Innovation Fellowship (QIF)](https://www.qualcomm.com/research/university-relations/innovation-fellowship/2025-north-america) North America for the proposal *“Less Attention, Much Faster: Toward a Future of Efficiency-Optimized Transformer Architectures.”* \
  \[03/2025\]: [Our holistic study of MoE compression](#pub-moe-compression) was accepted by [TMLR](https://jmlr.org/tmlr/). \
  \[09/2024\]: Two papers accepted: (1) Efficient Attention at [NeurIPS 2024](https://neurips.cc/), and (2) Reformat Alignment at [EMNLP 2024](https://2024.emnlp.org/). \
  \[10/2023\]: [Merging Experts into One](#pub-meo) was accepted by [EMNLP 2023](https://2023.emnlp.org/). \
  \[05/2023\]: [PAD-Net](#pub-pad-net) was accepted by [ACL 2023](https://2023.aclweb.org/). \
  \[04/2023\]: [NeuralSlice](#pub-neuralslice) was accepted by [ICML 2023](https://icml.cc/). \
  \[10/2022\]: [SparseAdapter](#pub-sparseadapter) was accepted by [EMNLP 2022](https://2022.emnlp.org/). \
  \[08/2022\]: [SD-Conv](#pub-sd-conv) was accepted by [WACV 2023](https://wacv2023.thecvf.com/). \
  \[07/2022\]: 🏆 Ranked 1st (Chinese<=>English, German<=>English, Czech<=>English, English=>Russian), 2nd (Russian=>English, Japanese=>English), and 3rd (English=>Japanese) in the General Translation Task at [WMT 2022](https://statmt.org/wmt22/translation-task.html). \
  \[01/2022\]: One paper was accepted by [AAAI-22 KDF](https://aaai-kdf.github.io/kdf2022/).
  

Research Experience
======
<dl>
  <dt><img align="left" width="110" height="110" hspace="10" src="images/ByteDance_logo.jpg" /></dt>
  <dt>ByteDance Seed</dt>
  <d>05/2025 - Present</d><br>
  <dd>Student Researcher</dd>
  <dd>Multimodal Modeling</dd>
</dl>

<dl>
  <dt><img align="left" width="110" height="110" hspace="10" src="images/Tencent_logo.png" /></dt>
  <dt>Tencent AI Lab, Bellevue, WA</dt>
  <d>06/2024 - 08/2024</d><br>
  <dd>Research Intern</dd>
  <dd>Efficient ML</dd>
</dl>

<dl>
  <dt><img align="left" width="110" height="110" hspace="10" src="images/FDU_Logo.png" /></dt>
  <dt>IICS, Fudan University</dt>
  <d>07/2022 - 03/2023</d><br>
  <dd>Research Assistant</dd>
  <dd>AI for Protein, Computational Biology</dd>
</dl>

<dl>
  <dt><img align="left" width="110" height="110" hspace="10" src="images/JD_logo.png" /></dt>
  <dt>NLP Group, JD Explore Academy</dt>
  <d>02/2022 - 10/2022</d><br>
  <dd>Research Intern</dd>
  <dd>Machine Learning, Efficient Methods for NLP</dd>
</dl>


Selected Publications
======
<a id="pub-demystifying-pruning"></a>
1. __Shwai He__, Guoheng Sun, Haichao Zhang, Yun Fu, Ang Li,
"***Demystifying When Pruning Works via Representation Hierarchies***", arXiv. [[Paper](https://arxiv.org/abs/2603.24652)] [[Code](https://github.com/CASE-Lab-UMD/Pruning-on-Representations)]
<a id="pub-capacity-aware-inference"></a>
2. __Shwai He__, Weilin Cai, Jiayi Huang, Ang Li, 
"***Capacity-Aware Inference: Mitigating the Straggler Effect in Mixture of Experts***", Proceedings of the Fourteenth International Conference on Learning Representations (__ICLR 2026__). [[Paper](https://arxiv.org/abs/2503.05066)] [[Code](https://github.com/CASE-Lab-UMD/Capacity-Aware-MoE)]
<a id="pub-attention-drop"></a>
3. __Shwai He__\*, Guoheng Sun\*, Zheyu Shen, Ang Li, 
"***Uncovering the Redundancy in Transformers via a Unified Study of Layer Dropping***", Transactions on Machine Learning Research (__TMLR__). [[Paper](https://openreview.net/forum?id=1I7PCbOPfe)] [[Code](https://github.com/CASE-Lab-UMD/LLM-Drop)]
<a id="pub-effir"></a>
4. Yibin Lei, __Shwai He__\*, Ang Li, Andrew Yates,
"***Making Large Language Models Efficient Dense Retrievers***", Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics (__ACL 2026__). [[Paper](https://arxiv.org/abs/2512.20612)] [[Code](https://github.com/Yibin-Lei/EffiR)]
<a id="pub-router-tuning"></a>
5. __Shwai He__, Tao Ge, Guoheng Sun, Bowei Tian, Xiaoyang Wang, Dong Yu, 
"***Router-Tuning: A Simple and Effective Approach for Dynamic Depth***", Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing
(__EMNLP 2025__) [[Paper](https://arxiv.org/abs/2410.13184)] [[Code](https://github.com/CASE-Lab-UMD/Router-Tuning-Mixture-of-Depths)]
<a id="pub-moe-compression"></a>
6. __Shwai He__\*, Daize Dong\*, Liang Ding, Ang Li, 
"***Towards Efficient Mixture of Experts: A Holistic Study of Compression Techniques***", Transactions on Machine Learning Research (__TMLR__). [[Paper](https://arxiv.org/abs/2406.02500)] [[Code](https://github.com/CASE-Lab-UMD/Unified-MoE-Compression)]
<a id="pub-meo"></a>
7. __Shwai He__, Run-Ze Fan, Liang Ding, Li Shen, Tianyi Zhou, Dacheng Tao, 
"***Merging Experts into One: Improving Computational Efficiency of Mixture of Experts***",
 Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing 
 (__EMNLP 2023 Oral__). [[Paper](https://aclanthology.org/2023.emnlp-main.907/)] [[Code](https://github.com/Shwai-He/MEO)]
<a id="pub-pad-net"></a>
8. __Shwai He__, Liang Ding, Daize Dong, Boan Liu, Fuqiang Yu, Dacheng Tao, 
"***PAD-Net: An Efficient Framework for Dynamic Networks***",
 Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (__ACL 2023__). [[Paper](https://aclanthology.org/2023.acl-long.803.pdf)] [[Code](https://github.com/Shwai-He/PAD-Net)]
<a id="pub-sparseadapter"></a>
9. __Shwai He__, Liang Ding, Daize Dong, Miao Zhang, Dacheng Tao, 
"***SparseAdapter: An Easy Approach for Improving the Parameter-Efficiency of Adapters***",
 Findings of the 2022 Conference on Empirical Methods in Natural Language Processing (__EMNLP 2022__). [[Paper](https://aclanthology.org/2022.findings-emnlp.160/)] [[Code](https://github.com/Shwai-He/SparseAdapter)]
<a id="pub-sd-conv"></a>
10. __Shwai He__, Chenbo Jiang, Daize Dong, Liang Ding, "***SD-Conv: Towards the Parameter-Efficiency of Dynamic Convolution***", IEEE/CVF Winter Conference on Applications of Computer Vision, 2023 (__WACV 2023__). [[Paper](https://openaccess.thecvf.com/content/WACV2023/papers/He_SD-Conv_Towards_the_Parameter-Efficiency_of_Dynamic_Convolution_WACV_2023_paper.pdf)]
11. __Shwai He__, Shi Gu, "***Multi-modal Attention Network for Stock Movements Prediction***", the AAAI-22 Workshop on Knowledge Discovery from Unstructured Data in Financial Service (__KDF 2022__). [[Paper](https://aaai-kdf.github.io/kdf2022/assets/pdfs/KDF_22_paper_3.pdf)]
<a id="pub-neuralslice"></a>
12. Chenbo Jiang, Jie Yang, __Shwai He__, Yu-Kun Lai and Lin Gao. "***NeuralSlice: Neural 3D Triangle Mesh Reconstruction via Slicing 4D Tetrahedral Meshes.***", Proceedings of the 40th International Conference on Machine Learning, 2023 (__ICML 2023__). [[Paper](https://proceedings.mlr.press/v202/jiang23j/jiang23j.pdf)] [[Code](https://github.com/IGLICT/NEURALSLICE)]
13. Changtong Zan, Keqin Peng, Liang Ding, Baopu Qiu, Boan Liu, __Shwai He__, Qingyu Lu, Zheng Zhang, Chuang
Liu, Weifeng Liu, Yibing Zhan and Dacheng Tao, "***Vega-MT: The JD Explore Academy Translation System for WMT***", The Conference on Machine Translation, 2022 (__WMT 2022__). [[Paper](https://aclanthology.org/2022.wmt-1.37/)] 
