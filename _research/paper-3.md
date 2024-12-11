---
title: "Multimodal Contextualized Support for Enhancing Video Retrieval System"
collection: research
category: papers
permalink: /research/paper-3
date: 2024-07-20
venue: 'Melia Da Nang Beach Resort, Vietnam'
---

This paper presents the outcomes of our efforts to develop a system incorporating various methods for a video retrieval competition. Initially intended for submission to a lifelog conference, the system shows potential for significant improvement through temporal alignment and video graph representation. As a result, we are currently refining the system to enhance its efficiency and performance. [***Read more***](/research/paper-3)

**Abstract** \\
Current video retrieval systems, especially those used in competitions, primarily focus on querying individual keyframes or images rather than encoding an entire clip or video segment. However, queries often describe an action or event over a series of frames, not a specific image. This results in insufficient information when analyzing a single frame, leading to less accurate query results. Moreover, extracting embeddings solely from images (keyframes) does not provide enough information for models to encode higher-level, more abstract insights inferred from the video. These models tend to only describe the objects present in the frame, lacking a deeper understanding. In this work, we propose a system that integrates the latest methodologies, introducing a novel pipeline that extracts multimodal data, and incorporate information from multiple frames within a video, enabling the model to abstract higher-level information that captures latent meanings, focusing on what can be inferred from the video clip, rather than just focusing on object detection in one single image. 

**Information**
- Arxiv: [view](https://arxiv.org/abs/2412.07584)
- Repository: [view]()

**Citation**
```cite
@misc{nguyenle2024multimodalcontextualizedsupportenhancing,
      title={Multimodal Contextualized Support for Enhancing Video Retrieval System}, 
      author={Quoc-Bao Nguyen-Le and Thanh-Huy Le-Nguyen},
      year={2024},
      eprint={2412.07584},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2412.07584}, 
}
```