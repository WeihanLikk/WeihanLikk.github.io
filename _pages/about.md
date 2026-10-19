---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Weihan Li (黎维瀚), a PhD student at [Georgia Tech CSE](https://cse.gatech.edu/), advised by Prof. [Anqi Wu](https://sites.google.com/view/brainml/home). Previously, I was an undergraduate at Zhejiang University, working with Prof. [Gang Pan](https://scholar.google.com/citations?user=NWqnXNEAAAAJ&hl=en). My CV is available [here](https://weihanlikk.github.io/assets/cv_weihan.pdf).

## Research

<div class="research-blurb" markdown="1">
I work on **robot learning for dexterous manipulation**: teaching multi-fingered robot hands to perform bimanual manipulation skills learned from human demonstrations, in simulation and on real hardware. I have built the full pipeline, from human motion capture through retargeting to reinforcement-learning training in simulation, and run it on different dexterous robot hands. Videos are on the [Robot Demos](/demos/) page.
</div>

Before moving to robotics, I worked on modeling communication across multiple brain regions and on analyzing animal behavior from pose and video.

<div class="interest-row"><span class="interest-label">Current</span>
<span class="tag tag--current">Dexterous Manipulation</span>
<span class="tag tag--current">Bimanual Robot Skills</span>
<span class="tag tag--current">Learning from Human Demonstrations</span>
<span class="tag tag--current">Sim-to-Real Transfer</span>
</div>
<div class="interest-row"><span class="interest-label">Previously</span>
<span class="tag">Multi-Region Brain Communication</span>
<span class="tag">Animal Behavior Analysis</span>
</div>

## Publications

See also my [Google Scholar](https://scholar.google.com/citations?user=qW4_NR4AAAAJ&hl=zh-CN&oi=ao) profile.

<!--
  Teaser figures: put one image per paper in /images/papers/ using the file names below
  (PNG or JPG; ~800px wide is plenty). If a file is missing, that paper is shown without a figure.
-->

<div class="pub-list">

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/resifuse.png" title="Click to enlarge"><img src="/images/papers/resifuse.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">Learning When Visual Context Matters for Mouse Behavior Analysis</div>
    <div class="pub__authors"><b>Weihan Li</b>, Jingyang Ke, Qinheng Pu, Yule Wang, Chengrui Li, Anqi Wu</div>
    <div class="pub__venue">NeurIPS 2026</div>
    <div class="pub__desc">Frames with large quantization residuals in a pose-based motion encoder are where visual context helps most; ResiFuse adds video features only on those frames and outperforms pose- and video-based baselines on most tasks across three mouse behavior datasets.</div>
    <div class="pub__links"><a href="https://arxiv.org/pdf/2603.07279">Paper</a><a href="https://github.com/BRAINML-GT/ResiFuse">Code</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/mice.png" title="Click to enlarge"><img src="/images/papers/mice.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">MICE: Multi-animal Interaction Context Encoder — A Hierarchical Foundation Model for Mouse Behavior</div>
    <div class="pub__authors">Yen-Shuo Su, <b>Weihan Li</b>, Anqi Wu</div>
    <div class="pub__venue">NeurIPS 2026<span class="pub__award">Spotlight</span></div>
    <div class="pub__desc">A hierarchical self-supervised foundation model for mouse behavior, pretrained jointly on six mouse-pose datasets with one to four animals; a Perceiver-style social encoder lets a single checkpoint handle any group size, matching or exceeding prior keypoint-based baselines.</div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/qdmouse4m.png" title="Click to enlarge"><img src="/images/papers/qdmouse4m.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">QDMouse4M: A Multi-View 3D Mouse Spontaneous Behavior Dataset with Quantum-Dot Markers</div>
    <div class="pub__authors">Jingyang Ke, Amartya Pradhan, Xueling Zhang, <b>Weihan Li</b>, Anqi Wu, Jeffrey E. Markowitz</div>
    <div class="pub__venue">NeurIPS 2026 · Evaluations and Datasets Track</div>
    <div class="pub__desc">A six-view dataset of freely moving mice with over four million frames, whose 2D and 3D keypoint labels come from subdermal quantum-dot fluorescence markers; used to benchmark markerless 2D/3D pose estimation and downstream spontaneous-behavior analysis.</div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/behaviorvlm.png" title="Click to enlarge"><img src="/images/papers/behaviorvlm.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">BehaviorVLM: Unified Finetuning-Free Behavioral Understanding with Vision-Language Reasoning</div>
    <div class="pub__authors">Jingyang Ke<sup>*</sup>, <b>Weihan Li</b><sup>*</sup>, Amartya Pradhan, Jeffrey Markowitz, Anqi Wu</div>
    <div class="pub__venue">Preprint</div>
    <div class="pub__desc">A unified framework for animal pose estimation and behavioral understanding that guides pretrained vision-language models through explicit, verifiable reasoning steps, with no task-specific finetuning and minimal human labeling.</div>
    <div class="pub__meta"><sup>*</sup>Equal contribution</div>
    <div class="pub__links"><a href="https://arxiv.org/pdf/2603.12176">Paper</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/facrnn.png" title="Click to enlarge"><img src="/images/papers/facrnn.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">A Factorized Low-Rank RNN Framework for Uncovering Independent Neural Latent Dynamics and Connectivity</div>
    <div class="pub__authors">Chengrui Li, Yunmiao Wang, Yule Wang, <b>Weihan Li</b>, Dieter Jaeger, Anqi Wu</div>
    <div class="pub__venue">ICML 2026<span class="pub__award">Spotlight</span></div>
    <div class="pub__desc">FacRNN, a generative low-rank RNN framework that encourages group-wise independence among latent dynamics, yielding more disentangled and interpretable latent trajectories and low-rank connectivity.</div>
    <div class="pub__links"><a href="https://arxiv.org/pdf/2511.13899">Paper</a><a href="https://github.com/JerrySoybean/facrnn">Code</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/migvis.png" title="Click to enlarge"><img src="/images/papers/migvis.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">Uncovering Semantic Selectivity of Latent Groups in Higher Visual Cortex with Mutual Information-Guided Diffusion</div>
    <div class="pub__authors">Yule Wang, Joseph Yu, Chengrui Li, <b>Weihan Li</b>, Anqi Wu</div>
    <div class="pub__venue">ICLR 2026</div>
    <div class="pub__desc">MIG-Vis infers group-wise disentangled neural latent subspaces from macaque IT cortex and uses mutual-information-guided diffusion to visualize the visual-semantic features each latent group encodes.</div>
    <div class="pub__links"><a href="https://proceedings.iclr.cc/paper_files/paper/2026/file/b7216f4a324864e1f592c18de4d83d10-Paper-Conference.pdf">Paper</a><a href="https://github.com/BRAINML-GT/MIG-Vis">Code</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/adm.png" title="Click to enlarge"><img src="/images/papers/adm.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">Learning Time-Varying Multi-Region Brain Communications via Scalable Markovian Gaussian Processes</div>
    <div class="pub__authors"><b>Weihan Li</b>, Yule Wang, Chengrui Li, Anqi Wu</div>
    <div class="pub__venue">ICML 2025<span class="pub__award">Oral</span></div>
    <div class="pub__desc">The Adaptive Delay Model combines Gaussian processes with state-space models to learn multi-region brain communication with time-varying delays, using parallel-scan inference to scale to long recordings.</div>
    <div class="pub__links"><a href="https://openreview.net/pdf?id=pOAEfqa26i">Paper</a><a href="https://github.com/BRAINML-GT/Adaptive-Delay-Model">Code</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/benediff.png" title="Click to enlarge"><img src="/images/papers/benediff.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">Exploring Behavior-Relevant and Disentangled Neural Dynamics with Generative Diffusion Models</div>
    <div class="pub__authors">Yule Wang, Chengrui Li, <b>Weihan Li</b>, Anqi Wu</div>
    <div class="pub__venue">NeurIPS 2024</div>
    <div class="pub__desc">BeNeDiff identifies behavior-relevant, disentangled neural subspaces and uses video diffusion models to generate behavior videos that reveal what each neural factor encodes.</div>
    <div class="pub__links"><a href="https://arxiv.org/abs/2410.09614">Paper</a><a href="https://github.com/BRAINML-GT/BeNeDiff">Code</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/mrmgp.png" title="Click to enlarge"><img src="/images/papers/mrmgp.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">Multi-Region Markovian Gaussian Process: An Efficient Method to Discover Directional Communications Across Multiple Brain Regions</div>
    <div class="pub__authors"><b>Weihan Li</b>, Chengrui Li, Yule Wang, Anqi Wu</div>
    <div class="pub__venue">ICML 2024</div>
    <div class="pub__desc">Builds a linear dynamical system that mirrors a multi-output Gaussian process with explicit frequencies and phase delays, revealing communication directions across brain regions and separating oscillatory communication into frequency bands at linear cost.</div>
    <div class="pub__links"><a href="https://arxiv.org/abs/2402.02686">Paper</a><a href="https://github.com/WeihanLikk/MRM-GP">Code</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/poglm.png" title="Click to enlarge"><img src="/images/papers/poglm.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">A Differentiable Partially Observable Generalized Linear Model with Forward-Backward Message Passing</div>
    <div class="pub__authors">Chengrui Li, <b>Weihan Li</b>, Yule Wang, Anqi Wu</div>
    <div class="pub__venue">ICML 2024</div>
    <div class="pub__desc">A differentiable partially observable GLM that enables pathwise gradients, paired with a forward–backward message-passing variational model, for learning neural connectivity in the presence of hidden neurons.</div>
    <div class="pub__links"><a href="https://arxiv.org/abs/2402.01263">Paper</a><a href="https://github.com/JerrySoybean/poglm">Code</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/vis.png" title="Click to enlarge"><img src="/images/papers/vis.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">Forward χ<sup>2</sup> Divergence Based Variational Importance Sampling</div>
    <div class="pub__authors">Chengrui Li, Yule Wang, <b>Weihan Li</b>, Anqi Wu</div>
    <div class="pub__venue">ICLR 2024<span class="pub__award">Spotlight</span></div>
    <div class="pub__desc">Variational importance sampling that directly estimates and maximizes the log-likelihood of latent variable models, using a proposal obtained by minimizing the forward χ<sup>2</sup> divergence.</div>
    <div class="pub__links"><a href="https://arxiv.org/abs/2311.02516">Paper</a><a href="https://github.com/JerrySoybean/vis">Code</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/hdpp.png" title="Click to enlarge"><img src="/images/papers/hdpp.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">Online Neural Sequence Detection with Hierarchical Dirichlet Point Process</div>
    <div class="pub__authors"><b>Weihan Li</b>, Yu Qi, Gang Pan</div>
    <div class="pub__venue">NeurIPS 2022</div>
    <div class="pub__desc">A hierarchical Dirichlet point process that detects neural sequences online with particle filters and introduces new sequence types on the fly, without specifying their number in advance.</div>
    <div class="pub__links"><a href="https://proceedings.neurips.cc/paper_files/paper/2022/hash/2c3b636b64ca1dfdae3e096e4deeaa42-Abstract-Conference.html">Paper</a><a href="https://github.com/WeihanLikk/Hierarchical-Dirichlet-Point-Process">Code</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub__thumb"><a href="/images/papers/embc2021.png" title="Click to enlarge"><img src="/images/papers/embc2021.png" alt="" loading="lazy" onerror="this.closest('.pub__thumb').remove()"></a></div>
  <div class="pub__body">
    <div class="pub__title">Efficient Point-Process Modeling of Spiking Neurons for Neuroprosthesis</div>
    <div class="pub__authors"><b>Weihan Li</b><sup>*</sup>, Cunle Qian<sup>*</sup>, Yu Qi, Yiwen Wang, Yueming Wang, Gang Pan</div>
    <div class="pub__venue">EMBC 2021</div>
    <div class="pub__desc">A spiking neuron point-process model that takes spike times as input to model nonlinear spike transformations between cortical areas (PMd to M1), and can run on low-energy neuromorphic hardware for neuroprostheses.</div>
    <div class="pub__meta"><sup>*</sup>Equal contribution</div>
    <div class="pub__links"><a href="https://ieeexplore.ieee.org/document/9630019">Paper</a></div>
  </div>
</div>

</div>

## Service

**Reviewer**: NeurIPS, ICML, ICLR
