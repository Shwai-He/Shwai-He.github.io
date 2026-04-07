---
permalink: /
title: "Biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

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
"***Demystifying When Pruning Works via Representation Hierarchies***", arXiv. <a class="pub-button" href="https://arxiv.org/abs/2603.24652">Paper</a> <a class="pub-button" href="https://github.com/CASE-Lab-UMD/Pruning-on-Representations">Code</a>
<a id="pub-sparse-unified-models"></a>
2. __Shwai He__, Chaorui Deng, Ang Li, Shen Yan,
"***Understanding and Harnessing Sparsity in Unified Multimodal Models***", arXiv. <a class="pub-button" href="https://arxiv.org/abs/2512.02351">Paper</a> <a class="pub-button" href="https://github.com/Shwai-He/SparseUnifiedModel">Code</a>
<a id="pub-capacity-aware-inference"></a>
3. __Shwai He__, Weilin Cai, Jiayi Huang, Ang Li, 
"***Capacity-Aware Inference: Mitigating the Straggler Effect in Mixture of Experts***", Proceedings of the Fourteenth International Conference on Learning Representations (__ICLR 2026__). <a class="pub-button" href="https://arxiv.org/abs/2503.05066">Paper</a> <a class="pub-button" href="https://github.com/CASE-Lab-UMD/Capacity-Aware-MoE">Code</a>
<a id="pub-attention-drop"></a>
4. __Shwai He__\*, Guoheng Sun\*, Zheyu Shen, Ang Li, 
"***Uncovering the Redundancy in Transformers via a Unified Study of Layer Dropping***", Transactions on Machine Learning Research (__TMLR__). <a class="pub-button" href="https://openreview.net/forum?id=1I7PCbOPfe">Paper</a> <a class="pub-button" href="https://github.com/CASE-Lab-UMD/LLM-Drop">Code</a>
<a id="pub-effir"></a>
5. Yibin Lei, __Shwai He__\*, Ang Li, Andrew Yates,
"***Making Large Language Models Efficient Dense Retrievers***", Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics (__ACL 2026__). <a class="pub-button" href="https://arxiv.org/abs/2512.20612">Paper</a> <a class="pub-button" href="https://github.com/Yibin-Lei/EffiR">Code</a>
<a id="pub-router-tuning"></a>
6. __Shwai He__, Tao Ge, Guoheng Sun, Bowei Tian, Xiaoyang Wang, Dong Yu, 
"***Router-Tuning: A Simple and Effective Approach for Dynamic Depth***", Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing
(__EMNLP 2025__) <a class="pub-button" href="https://arxiv.org/abs/2410.13184">Paper</a> <a class="pub-button" href="https://github.com/CASE-Lab-UMD/Router-Tuning-Mixture-of-Depths">Code</a>
<a id="pub-moe-compression"></a>
7. __Shwai He__\*, Daize Dong\*, Liang Ding, Ang Li, 
"***Towards Efficient Mixture of Experts: A Holistic Study of Compression Techniques***", Transactions on Machine Learning Research (__TMLR__). <a class="pub-button" href="https://arxiv.org/abs/2406.02500">Paper</a> <a class="pub-button" href="https://github.com/CASE-Lab-UMD/Unified-MoE-Compression">Code</a>
<a id="pub-meo"></a>
8. __Shwai He__, Run-Ze Fan, Liang Ding, Li Shen, Tianyi Zhou, Dacheng Tao, 
"***Merging Experts into One: Improving Computational Efficiency of Mixture of Experts***",
 Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing 
 (__EMNLP 2023 Oral__). <a class="pub-button" href="https://aclanthology.org/2023.emnlp-main.907/">Paper</a> <a class="pub-button" href="https://github.com/Shwai-He/MEO">Code</a>
<a id="pub-pad-net"></a>
9. __Shwai He__, Liang Ding, Daize Dong, Boan Liu, Fuqiang Yu, Dacheng Tao, 
"***PAD-Net: An Efficient Framework for Dynamic Networks***",
 Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (__ACL 2023__). <a class="pub-button" href="https://aclanthology.org/2023.acl-long.803.pdf">Paper</a> <a class="pub-button" href="https://github.com/Shwai-He/PAD-Net">Code</a>
<a id="pub-sparseadapter"></a>
10. __Shwai He__, Liang Ding, Daize Dong, Miao Zhang, Dacheng Tao, 
"***SparseAdapter: An Easy Approach for Improving the Parameter-Efficiency of Adapters***",
 Findings of the 2022 Conference on Empirical Methods in Natural Language Processing (__EMNLP 2022__). <a class="pub-button" href="https://aclanthology.org/2022.findings-emnlp.160/">Paper</a> <a class="pub-button" href="https://github.com/Shwai-He/SparseAdapter">Code</a>
<a id="pub-sd-conv"></a>
11. __Shwai He__, Chenbo Jiang, Daize Dong, Liang Ding, "***SD-Conv: Towards the Parameter-Efficiency of Dynamic Convolution***", IEEE/CVF Winter Conference on Applications of Computer Vision, 2023 (__WACV 2023__). <a class="pub-button" href="https://openaccess.thecvf.com/content/WACV2023/papers/He_SD-Conv_Towards_the_Parameter-Efficiency_of_Dynamic_Convolution_WACV_2023_paper.pdf">Paper</a>
12. __Shwai He__, Shi Gu, "***Multi-modal Attention Network for Stock Movements Prediction***", the AAAI-22 Workshop on Knowledge Discovery from Unstructured Data in Financial Service (__KDF 2022__). <a class="pub-button" href="https://aaai-kdf.github.io/kdf2022/assets/pdfs/KDF_22_paper_3.pdf">Paper</a>
<a id="pub-neuralslice"></a>
13. Chenbo Jiang, Jie Yang, __Shwai He__, Yu-Kun Lai and Lin Gao. "***NeuralSlice: Neural 3D Triangle Mesh Reconstruction via Slicing 4D Tetrahedral Meshes.***", Proceedings of the 40th International Conference on Machine Learning, 2023 (__ICML 2023__). <a class="pub-button" href="https://proceedings.mlr.press/v202/jiang23j/jiang23j.pdf">Paper</a> <a class="pub-button" href="https://github.com/IGLICT/NEURALSLICE">Code</a>
14. Changtong Zan, Keqin Peng, Liang Ding, Baopu Qiu, Boan Liu, __Shwai He__, Qingyu Lu, Zheng Zhang, Chuang
Liu, Weifeng Liu, Yibing Zhan and Dacheng Tao, "***Vega-MT: The JD Explore Academy Translation System for WMT***", The Conference on Machine Translation, 2022 (__WMT 2022__). <a class="pub-button" href="https://aclanthology.org/2022.wmt-1.37/">Paper</a> 
