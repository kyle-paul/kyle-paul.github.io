---
title: "Computer graphics with computer vision"
collection: research
category: work
permalink: /research/work-1
date: 2024-11-25
---

The CTO of Gianty from **Tiger Funding** has shown interest in funding my software for use in universities as learning materials or in hospitals for experiments. However, I’ve decided to refine it further. Driven by my passion for computer graphics, I’ve embarked on building a **3D graphics engine** capable of simulating advanced physical properties like blood flow, heartbeats, and neuron activation. This engine has potential applications in **robotics training simulations** and aligns with global trends like **NVIDIA Omniverse**. My work bridges computer graphics and computer vision, exploring their applications in fields such as medical, robotics, and synthetic data. Delving into the **mathematical** and **physical modeling** behind these systems, I pursue this passion at my own pace, fueled by the joy of discovery and innovation. [***Read more***](/research/work-1)

**Vortex - my own graphic engine** \\
I have implemented the [**Vortex Engine**](https://github.com/kyle-paul/Vortex) in C++, aiming to make it renderer-backend-agnostic (e.g., OpenGL, Vulkan, etc). I strive to control every detail in my 3D scenes. Building upon my passionate [**ISEF project**](/talks/isef), which reconstructed **3D human anatomy** structures from medical volumetric data, I now focus on achieving real-time, lifelike simulations with **advanced physical properties**. For instance, I aim to simulate a beating heart or the **dynamic motion** of neurons in the brain. My ultimate goal is to simulate the dynamics of **cellular activity** and **blood flow** to enable comprehensive analysis and defect/anomaly detection. Below is a comparison of my previous work and my current one:

| ![](/assets/images/recent/brain.png){:style="width: 400px"} | ![](/assets/images/recent/cardiac.gif){:style="width: 400px"} |  

The right image shows my older ISEF project, which had limited control over the rendering process and physical properties, while the left image highlights my current work: I am trying to simulate advanced **physical properties** such as blood flow, heartbeats, neuron activation, and realistic surgical environments.

In addition, I am exploring **performance acceleration** in AI-driven computer graphics through [**CUDA** programming](https://github.com/kyle-paul/cusops), leveraging GPU capabilities. Check out my projects, including a [framework](https://github.com/kyle-paul/fast-vision-cpp) that integrates **ONNX**, **TensorRT**, and OpenVINO into a unified C++ codebase.

**Graphics and robotics** \\
I am also fascinated by physically based modeling and the magical math behind simulating **collisions**. Recently, I have been studying NVIDIA’s research on [6D Pose Estimation](https://nvlabs.github.io/FoundationPose/) and [6-DoF Tracking](https://bundlesdf.github.io/). By estimating **physical parameters** like forces, mass, and acceleration, I believe this knowledge can significantly advance **pose estimation** techniques.

| ![](/assets/images/recent/demo.png)  |

| ![](/assets/images/recent/physics.gif){:style="width: 400px"} | ![](/assets/images/recent/robot.gif){:style="width: 390px"} |

| ![](/assets/images/recent/arms.gif){:style="width: 800px"} |  

The first two GIFs showcase my engine, while the last one featuring **robotic arms** is from NVIDIA’s 6D Pose Estimation research.

I have noticed that robotics and **Deep Reinforcement Learning** are closely tied to computer graphics and computer vision, creating immense potential for progress in this field. In my engine, I am working to simulate the dynamics of robotic arms. With complete control over the simulated space, I can train models using **synthetic data—massively generating objects and scenarios** for pose estimation and reinforcement learning (similar to this [work](https://arxiv.org/pdf/2309.01324v2)). For instance, my [modern chess project](https://github.com/kyle-paul/modern-chess-3d) is an initial step toward combining computer graphics and reinforcement learning.

In the process of learning, I enjoy sharing my knowledge through a [seminar on physically based modeling](/talks/selab), where I explore the mathematical intuition and physics of particle systems.

**Graphics with computer vision** \\
Additionally, my current research with friends focuses on pose estimation for **camouflaged wildlife**. Since this is a novel task without existing datasets, we aim to **synthesize** large-scale data using my 3D engine, employing various camera perspectives, lighting conditions, and augmentation techniques to improve computer vision datasets and models in this domain. One [similar work](https://arxiv.org/pdf/2308.06701) inspired this effort. However, obtaining 3D wildlife models remains a challenge, and I am exploring methods like [Gaussian Splatting](https://arxiv.org/abs/2308.04079) to address this.

| ![](/assets/images/recent/camou.png){:style="width: 400px"} | ![](/assets/images/recent/gaussian.png){:style="width: 400px"} |  

Finally, my passion for computer graphics extends to solving real-world problems, such as **virtual try-on systems**. Imagine trying clothes on at home without visiting a store or physically wearing them! I aim to resolve this by leveraging my skills in graphics and [**Gaussian Splatting**](https://arxiv.org/pdf/2308.04079). In the future, I hope to create a system that models humans in 3D and automatically fits 3D mesh clothing onto them, enabling multi-view visualization. Below is an image inspired by the [GaussianBody](https://arxiv.org/pdf/2401.09720) project:

| ![](/assets/images/recent/clothes.png){:style="width: 800px"} |