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
I am a Ph.D. candidate in Computer Science at the University of Maryland, College Park, advised by <a href="https://www.ang-li.com/" target="_blank">Prof. Ang Li</a>. I am currently a Student Researcher at ByteDance, with prior experience at Tencent AI Lab and JD Explore Academy, where I worked on efficient model training and large-scale natural language systems.
</p>

<p align="justify" style="line-height:1.5; margin-bottom:4px; text-align:justify;">
My research focuses on understanding and improving the structural efficiency and scalability of large foundation models. I start by analyzing how computation, parameters, and modalities interact within these models to uncover their structural patterns, redundancy, and inefficiencies. Based on these insights, I develop methods for model compression, adaptive inference, parameter-efficient fine-tuning, and modality-aware optimization, aiming to improve both efficiency and adaptability across diverse tasks and modalities.
</p>

<p align="justify" style="line-height:1.5; margin-bottom:4px; text-align:justify;">
I further explore system- and device-level optimizations to enable efficient inference across real-world hardware environments. In addition, I extend these principles to unified multimodal architectures that dynamically balance shared and specialized computation across language and vision. Broadly, my goal is to bridge model understanding, architectural efficiency, and practical deployment toward the next generation of scalable and reliable AI systems.
</p>

News
======
  \[01/2026\]: Capacity-Aware Inference is accepted by [ICLR 2026](https://iclr.cc/). \
  \[01/2026\]: Attention Drop is accepted by [TMLR](https://jmlr.org/tmlr/). \
  \[08/2025\]: Router-Tuning is accepted at [EMNLP 2025](https://2025.emnlp.org/). \
  \[05/2025\]: 🏆 Awarded the [Qualcomm Innovation Fellowship (QIF)](https://www.qualcomm.com/research/university-relations/innovation-fellowship/2025-north-america) North America for the proposal *“Less Attention, Much Faster: Toward a Future of Efficiency-Optimized Transformer Architectures.”* \
  \[03/2025\]: Our Holistic Study of MoE Compression is accepted by [TMLR](https://jmlr.org/tmlr/). \
  \[09/2024\]: Two papers accepted: (1) Efficient Attention at [NeurIPS 2024](https://neurips.cc/), and (2) Reformat Alignment at [EMNLP 2024](https://2024.emnlp.org/). \
  \[10/2023\]: Merging Experts into One is accepted by [EMNLP 2023](https://2023.emnlp.org/). \
  \[05/2023\]: PAD-Net is accepted by [ACL 2023](https://2023.aclweb.org/). \
  \[04/2023\]: NeuralSlice is accepted by [ICML 2023](https://icml.cc/). \
  \[10/2022\]: SparseAdapter is accepted by [EMNLP 2022](https://2022.emnlp.org/). \
  \[08/2022\]: SD-Conv is accepted by [WACV 2023](https://wacv2023.thecvf.com/). \
  \[07/2022\]: 🏆 Ranked 1st (Chinese<=>English, German<=>English, Czech<=>English, English=>Russian), 2nd (Russian=>English, Japanese=>English), and 3rd (English=>Japanese) in General Translation Task in [WMT 2022](https://statmt.org/wmt22/translation-task.html). \
  \[01/2022\]: One paper is accepted by [AAAI-22 KDF](https://aaai-kdf.github.io/kdf2022/).
  

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
1. __Shwai He__, Weilin Cai, Jiayi Huang, Ang Li, 
"***Capacity-Aware Inference: Mitigating the Straggler Effect in Mixture of Experts***", Proceedings of The Fourteenth International Conference on Learning Representations (__ICLR 2026__). [[Paper](https://arxiv.org/abs/2503.05066)] [[Code](https://github.com/CASE-Lab-UMD/Capacity-Aware-MoE)]
2. __Shwai He__\*, Guoheng Sun\*, Zheyu Shen, Ang Li, 
"***What Matters in Transformers? Not All Attention is Needed***", arXiv. [[Paper](https://arxiv.org/abs/2406.15786)] [[Code](https://github.com/CASE-Lab-UMD/LLM-Drop)]
3. Yibin Lei, __Shwai He__\*, Guoheng Sun\*, Ang Li, Andrew Yates, 
"***Making Large Language Models Efficient Dense Retrievers***", arXiv. [[Paper](https://arxiv.org/abs/2512.20612)] [[Code](https://github.com/Yibin-Lei/EffiR)]
4. __Shwai He__, Tao Ge, Guoheng Sun, Bowei Tian, Xiaoyang Wang, Dong Yu, 
"***Router-Tuning: A Simple and Effective Approach for Dynamic Depth***", Proceedings of The 2025 Conference on Empirical Methods in Natural Language Processing
(__EMNLP 2025__) [[Paper](https://arxiv.org/abs/2410.13184)] [[Code](https://github.com/CASE-Lab-UMD/Router-Tuning-Mixture-of-Depths)]
5. __Shwai He__\*, Daize Dong\*, Liang Ding, Ang Li, 
"***Towards Efficient Mixture of Experts: A Holistic Study of Compression Techniques***", Transactions on Machine Learning Research 
(__TMLR__). [[Paper](https://arxiv.org/abs/2406.02500)] [[Code](https://github.com/CASE-Lab-UMD/Unified-MoE-Compression)]
6. __Shwai He__, Run-Ze Fan, Liang Ding, Li Shen, Tianyi Zhou, Dacheng Tao, 
"***Merging Experts into One: Improving Computational Efficiency of Mixture of Experts***",
 Proceedings of The 2023 Conference on Empirical Methods in Natural Language Processing 
 (__EMNLP 2023 Oral__). [[Paper](https://aclanthology.org/2023.emnlp-main.907/)] [[Code](https://github.com/Shwai-He/MEO)]
7. __Shwai He__, Liang Ding, Daize Dong, Boan Liu, Fuqiang Yu, Dacheng Tao, 
"***PAD-Net: An Efficient Framework for Dynamic Networks***",
 Proceedings of The 61st Annual Meeting of the Association for Computational Linguistics (__ACL 2023__). [[Paper](https://aclanthology.org/2023.acl-long.803.pdf)] [[Code](https://github.com/Shwai-He/PAD-Net)]
8. __Shwai He__, Liang Ding, Daize Dong, Miao Zhang, Dacheng Tao, 
"***SparseAdapter: An Easy Approach for Improving the Parameter-Efficiency of Adapters***",
 Findings of The 2022 Conference on Empirical Methods in Natural Language Processing (__EMNLP 2022__). [[Paper](https://aclanthology.org/2022.findings-emnlp.160/)] [[Code](https://github.com/Shwai-He/SparseAdapter)]
9. __Shwai He__, Chenbo Jiang, Daize Dong, Liang Ding, "***SD-Conv: Towards the Parameter-Efficiency of Dynamic Convolution***", IEEE/CVF Winter Conference on Applications of Computer Vision, 2023 (__WACV 2023__). [[Paper](https://openaccess.thecvf.com/content/WACV2023/papers/He_SD-Conv_Towards_the_Parameter-Efficiency_of_Dynamic_Convolution_WACV_2023_paper.pdf)]
10. __Shwai He__, Shi Gu, "***Multi-modal Attention Network for Stock Movements Prediction***", The AAAI-22 Workshop on Knowledge Discovery from Unstructured Data in Financial Service (__KDF 2022__). [[Paper](https://aaai-kdf.github.io/kdf2022/assets/pdfs/KDF_22_paper_3.pdf)]
11. Chenbo Jiang, Jie Yang, __Shwai He__, Yu-Kun Lai and Lin Gao. "***NeuralSlice: Neural 3D Triangle Mesh Reconstruction via Slicing 4D Tetrahedral Meshes.***", Proceedings of the 40th International Conference on Machine Learning, 2023 (__ICML 2023__). [[Paper](https://proceedings.mlr.press/v202/jiang23j/jiang23j.pdf)] [[Code](https://github.com/IGLICT/NEURALSLICE)]
12. Changtong Zan, Keqin Peng, Liang Ding, Baopu Qiu, Boan Liu, __Shwai He__, Qingyu Lu, Zheng Zhang, Chuang
Liu, Weifeng Liu, Yibing Zhan and Dacheng Tao, "***Vega-MT: The JD Explore Academy Translation System for WMT***", The Conference on Machine Translation, 2022 (__WMT 2022__). [[Paper](https://aclanthology.org/2022.wmt-1.37/)] 
