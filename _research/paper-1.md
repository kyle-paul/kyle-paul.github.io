---
title: "RotCAtt-TransUNet++: Novel Deep Neural Network for Sophisticated Cardiac Segmentation"
collection: research
category: papers
permalink: /research/paper-1
date: 2024-08-15
venue: 'Melia Da Nang Beach Resort, Vietnam'
---

[This paper](https://github.com/kyle-paul/RotCAtt-TransUNet-plusplus) was presented at the International Conference on Multimedia Analysis and Pattern Recognition (MAPR) 2024. It is available through IEEE, Arxiv, and the conference proceedings. Two versions of the paper are available on Arxiv (the second version is recommended). For more detailed information, you can view my [video presentation](/talks/mapr) from the conference.Additionally, this work has attracted interest from a [Aston PhD student](/talks/phd) in UK, who is eager to collaborate and gain access to the research in the future. [***Read more***](/research/paper-1)

**Abstract** \\
Cardiovascular disease remains a predominant global health concern, responsible for a significant portion of mortality worldwide. Accurate segmentation of cardiac medical imaging data is pivotal in mitigating fatality rates associated with cardiovascular conditions. However, existing state-of-the-art (SOTA) neural networks, including both CNN-based and Transformer-based approaches, exhibit limitations in practical applicability due to their inability to effectively capture inter-slice connections alongside intra-slice information. This deficiency is particularly evident in datasets featuring intricate, long-range details along the z-axis, such as coronary arteries in axial views. Additionally, SOTA methods fail to differentiate non-cardiac components from myocardium in segmentation, leading to the "spraying" phenomenon. To address these challenges, we present RotCAtt-TransUNet++, a novel architecture tailored for robust segmentation of complex cardiac structures. Our approach emphasizes modeling global contexts by aggregating multiscale features with nested skip connections in the encoder. It integrates transformer layers to capture interactions between patches and employs a rotatory attention mechanism to capture connectivity between multiple slices (inter-slice information). Additionally, a channel-wise cross-attention gate guides the fused multi-scale channel-wise information and features from decoder stages to bridge semantic gaps. Experimental results demonstrate that our proposed model outperforms existing SOTA approaches across four cardiac datasets and one abdominal dataset. Importantly, coronary arteries and myocardium are annotated with near-perfect accuracy during inference. An ablation study shows that the rotatory attention mechanism effectively transforms embedded vectorized patches in the semantic dimensional space, enhancing segmentation accuracy.

**Information**
- IEEE version: [view](https://ieeexplore.ieee.org/document/10660759/)
- Arxiv version 1 (6 pages): [view](https://arxiv.org/abs/2409.05280v1)
- Arxiv version 2 (11 pages): [view](https://arxiv.org/abs/2409.05280v2)
- Code repository: [view](https://github.com/kyle-paul/RotCAtt-TransUNet-plusplus)
- Slide presentation: [view](https://drive.google.com/file/d/11xyR8JpEheDu_ReHQwDMSGWLa5kjKcmQ/view)
- Conference poster: [view](https://drive.google.com/file/d/1Y3TW2CqJSxAwb3eiyyiyDMSdvlZkiiGr/view)
- Manual proceedings: [view](https://mapr.uit.edu.vn/sites/default/files/uploads/2024fullprocessding.pdf)


**Citation**
```cite
@misc{nguyenle2024rotcatttransunetnoveldeepneural,
      title={RotCAtt-TransUNet++: Novel Deep Neural Network for Sophisticated Cardiac Segmentation}, 
      author={Quoc-Bao Nguyen-Le and Tuan-Hy Le and Anh-Triet Do and Quoc-Huy Trinh},
      year={2024},
      eprint={2409.05280},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2409.05280}, 
}
```