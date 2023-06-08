### 简介
在我看来没有进行总结和组织，等于没有真正读懂文献的意义。从2023.06.01开始记录我所阅读过的论文，希望这样的过程中我能留下点笔记方便以后自己去回忆。



### 论文阅读目录
#### Physics-Informed Neural Networks

| 已完成 | 年份 | 论文名 | 简介 | 引用 |
| ----- | ----- | ------------------------------------------------------------ | -------------------------------- | ------------------------- |
| ✅ | 2020 | [Learning Trajectories of Hamiltonian Systems with Neural Networks](https://arxiv.org/abs/2204.05077) | 使用额外的估计连续时间轨迹来增强 Hamiltonian 神经网络,证明它在低采样率和噪声采样下的有效性。| [![citaitons](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1c9488198aff2fffbbe06aafe45d330a4ddb775a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Learning-Trajectories-of-Hamiltonian-Systems-with-Haitsiukevich-Ilin/1c9488198aff2fffbbe06aafe45d330a4ddb775a)|
|  | 2020 | [Hamiltonian Generative Networks](https://arxiv.org/abs/1909.13789) | Hamiltonian生成网络是一种生成模型，能够从像素级的观测中推断出抽象的状态，并且根据哈密顿方程来展开学习到的哈密顿动力学。| ![citaitons](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F80beec251b5d9f4f78fca2ea2016cf9d763b844c%3Ffields%3DcitationCount) |
|  | 2020 | [LagNetViP A Lagrangian Neural Network for Video Prediction](https://arxiv.org/pdf/2010.12932) |LagNetViP是一种视频预测模型，能够从学习到的物理量的表示中显式地构造运动方程，并且同时学习低维的状态表示和系统拉格朗日量。| ![citations](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd53fbc2bd3adba8fd9d0df1aa7d852e0e20d53ac%3Ffields%3DcitationCount) |
|  | 2020 | [Simplifying Hamiltonian and Lagrangian Neural Networks via Explicit Constraints](https://arxiv.org/abs/2010.13581) | 提出了一种简化哈密顿神经网络和拉格朗日神经网络的方法，通过在笛卡尔坐标系中显式地引入约束条件，来学习系统的哈密顿量或拉格朗日量。 | ![citations](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb639d2c614219f3de1e6a21091a1ad8d443916e8%3Ffields%3DcitationCount) |
|  | 2020 | [Unsupervised learning of lagrangian dynamics from images for prediction and control](https://dl.acm.org/doi/10.5555/3495724.3496625) | 提出了一种无监督的神经网络模型，能够从图像中学习拉格朗日动力学，并且利用可解释性来提高预测和控制的效果。 | ![citations](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F45dde4ce5dc531ded482d1fa6048445141a41905%3Ffields%3DcitationCount) |
|  | 2020 | [Variational Learning of Euler–Lagrange Dynamics from Data](https://arxiv.org/abs/2112.12619) | 论文提出了一种从图像数据中学习欧拉-拉格朗日动力学的无监督方法，利用变分反向误差分析来提取广义坐标和拉格朗日量。 | ![citations](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F550db29f3020335931ff4292a8f2c15c9276859a%3Ffields%3DcitationCount) |
| ✅ | 2021 | [Neural Symplectic Form Learning Hamiltonian Equations on General Coordinate Systems](https://openreview.net/forum?id=4h4oqp-ATxb) | 论文提出了一种使用神经网络从数据中学习辛形式的模型，从而提供了一种从一般坐标系表示的数据中学习哈密顿方程的方法。 | ![citations](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff6ff2f5a64a4a6c47d00db328cd712d497f44d56%3Ffields%3DcitationCount) |




### 后记
[李沐](https://github.com/mli/paper-reading)的视频给了我这个灵感去记录自己的文献阅读过程，这个仓库的readme文件的排版参考了他的相应[仓库](https://github.com/mli/paper-reading)。以下几点是我个人认为比较重要的:

> 1.给每篇论文一个文件夹。内含一篇markdown笔记、论文PDF、任意链接资料。使用目录结构来整理论文。
> 2.笔记内容应包括:题目、作者、摘要概述、亮点思维、问题疑问、要点总结等，写作、链接、粗体等格式着重体现。
> 3.创建TODO列表,标记想要阅读的论文以及记录心得，citation使用了[shields](https://shields.io/)。
