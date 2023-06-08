### 简介
在我看来没有进行总结和组织，等于没有真正读懂文献的意义。从2023.06.01开始记录我所阅读过的论文，希望这样的过程中我能留下点笔记方便以后自己去回忆。



### 论文阅读目录
#### Physics-Informed Neural Networks
| 已完成 | 年份 | 论文名 | 简介 | 引用 |
| ----- | ----- | ------------------------------------------------------------ | -------------------------------- | ------------------------- |
| ✅ | 2020 | [Learning Trajectories of Hamiltonian Systems with Neural Networks](https://arxiv.org/abs/2204.05077) | 使用额外的估计连续时间轨迹来增强 Hamiltonian 神经网络| [![citaitons](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1c9488198aff2fffbbe06aafe45d330a4ddb775a%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Learning-Trajectories-of-Hamiltonian-Systems-with-Haitsiukevich-Ilin/1c9488198aff2fffbbe06aafe45d330a4ddb775a)|
|  | 2020 | [Hamiltonian Generative Networks](https://arxiv.org/abs/1909.13789) | 从像素级观测中推断出抽象的状态，并且根据哈密顿方程来展开学习到的动力学。| ![citaitons](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F80beec251b5d9f4f78fca2ea2016cf9d763b844c%3Ffields%3DcitationCount) |
|  | 2020 | [LagNetViP A Lagrangian Neural Network for Video Prediction](https://arxiv.org/pdf/2010.12932) |LagNetViP是一种视频预测模型，能够从学习到的物理量的表示中显式地构造运动方程| ![citations](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd53fbc2bd3adba8fd9d0df1aa7d852e0e20d53ac%3Ffields%3DcitationCount) |
|  | 2020 | [Simplifying Hamiltonian and Lagrangian Neural Networks via Explicit Constraints](https://arxiv.org/abs/2010.13581) | 通过在笛卡尔坐标系中显式地引入约束条件，来学习系统的哈密顿量或拉格朗日量。 | ![citations](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb639d2c614219f3de1e6a21091a1ad8d443916e8%3Ffields%3DcitationCount) |
|  | 2020 | [Unsupervised learning of lagrangian dynamics from images for prediction and control](https://dl.acm.org/doi/10.5555/3495724.3496625) | 从图像中学习拉格朗日动力学，并且利用可解释性来提高预测和控制的效果。 | ![citations](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F45dde4ce5dc531ded482d1fa6048445141a41905%3Ffields%3DcitationCount) |
|  | 2020 | [Variational Learning of Euler–Lagrange Dynamics from Data](https://arxiv.org/abs/2112.12619) | 利用变分反向误差分析来提取广义坐标和拉格朗日量。 | ![citations](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F550db29f3020335931ff4292a8f2c15c9276859a%3Ffields%3DcitationCount) |
| ✅ | 2021 | [Neural Symplectic Form Learning Hamiltonian Equations on General Coordinate Systems](https://openreview.net/forum?id=4h4oqp-ATxb) | 使用神经网络从数据中学习辛形式，从而提供了一种从一般坐标系表示的数据中学习哈密顿方程的方法。 | ![citations](https://img.shields.io/badge/dynamic/json?label=citations&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff6ff2f5a64a4a6c47d00db328cd712d497f44d56%3Ffields%3DcitationCount) |

---

#### Computer Vision - Transformer
| 已完成 | 年份 | 论文名 | 简介 | 引用 |
| ----- | ----- | ------------------------------------------------------------ | -------------------------------- | ------------------------- |
| ✅ | 2020 | [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929.pdf) | Transformer杀入CV界                   |![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7b15fa1b8d413fbe14ef7a97f651f47f5aff3903%3Ffields%3DcitationCount)|
| ✅ | 2021 | [Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/abs/2103.14030.pdf) | 多层次的Vision Transformer                   | ![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc8b25fab5608c3e033d34b4483ec47e68ba109b7%3Ffields%3DcitationCount)|
| ✅ | 2021 | [Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/abs/2111.06377.pdf) | BERT的CV版             |![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc1962a8cf364595ed2838a097e9aa7cd159d3118%3Ffields%3DcitationCount)| 

---

#### AI for new areas
| 已完成 | 年份 | 论文名 | 简介 | 引用 |
| ----- | ----- | ------------------------------------------------------------ | -------------------------------- | ------------------------- |
| | 2016 | [AlphaGo](https://storage.googleapis.com/deepmind-media/alphago/AlphaGoNaturePaper.pdf) | 强化学习出圈                 |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F846aedd869a00c09b40f1f1f35673cb22bc87490%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Mastering-the-game-of-Go-with-deep-neural-networks-Silver-Huang/846aedd869a00c09b40f1f1f35673cb22bc87490)  |
|   | 2021 | [AlphaFold 2](https://www.nature.com/articles/s41586-021-03819-2.pdf) | 原子级别精度的蛋白质3D结构预测       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdc32a984b651256a8ec282be52310e6bd33d9815%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Highly-accurate-protein-structure-prediction-with-Jumper-Evans/dc32a984b651256a8ec282be52310e6bd33d9815)  |
|  | 2021 | [Codex](https://arxiv.org/pdf/2107.03374.pdf) | 使用注释生成代码       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Facbdbf49f9bc3f151b93d9ca9a06009f4f6eb269%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Evaluating-Large-Language-Models-Trained-on-Code-Chen-Tworek/acbdbf49f9bc3f151b93d9ca9a06009f4f6eb269)  |
| ✅ | 2021 | [Advancing mathematics by guiding human intuition with AI](https://www.nature.com/articles/s41586-021-04086-x.pdf) | 分析不同数学物体之前的联系来帮助发现新定理         |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff672b8fb430606fee0bb368f16603531ce1e90c4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Advancing-mathematics-by-guiding-human-intuition-AI-Davies-Velickovic/f672b8fb430606fee0bb368f16603531ce1e90c4)  |
| ✅ | 2022 | [AlphaCode](https://storage.googleapis.com/deepmind-media/AlphaCode/competition_level_code_generation_with_alphacode.pdf) | 媲美一般程序员的编程解题水平       |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5cbe278b65a81602a864184bbca37de91448a5f5%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Competition-Level-Code-Generation-with-AlphaCode-Li-Choi/5cbe278b65a81602a864184bbca37de91448a5f5)  |

### 后记
[李沐](https://github.com/mli/paper-reading)的视频给了我这个灵感去记录自己的文献阅读过程，这个仓库的readme文件的排版参考了他的相应[仓库](https://github.com/mli/paper-reading)。以下几点是我个人认为比较重要的:

> 1.给每篇论文一个文件夹。内含一篇markdown笔记、论文PDF、任意链接资料。使用目录结构来整理论文。
> 2.笔记内容应包括:题目、作者、摘要概述、亮点思维、问题疑问、要点总结等，写作、链接、粗体等格式着重体现。
> 3.创建TODO列表,标记想要阅读的论文以及记录心得，citation使用了[shields](https://shields.io/)。
