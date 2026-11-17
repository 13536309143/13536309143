<p align="center">
  <img src="assets/header.svg" width="100%" alt="JJ Wang — Mechanical Engineering · Graphics, Digital Twins and Multimodal Learning">
</p>

<p align="center">
  <a href="#selected-work">代表项目 / Selected Work</a> &nbsp; · &nbsp;
  <a href="#research">研究方向 / Research</a> &nbsp; · &nbsp;
  <a href="https://github.com/13536309143?tab=repositories">全部仓库 ↗</a>
</p>

## Hi, I'm JJ Wang.

机械工程背景，来自**广东工业大学**。关注**工业三维可视化、数字孪生与多模态学习**，从几何与语义建模、GPU 渲染，到设备退化预测与实验验证，探索算法在工业场景中的实现。

Mechanical engineering at Guangdong University of Technology. I work on industrial 3D visualization, digital twins, and multimodal learning, connecting modeling and algorithms with engineering implementation.

<a id="selected-work"></a>

## 代表项目 · Selected Work

### 01 / Industrial Semantic LOD
**工业三维模型轻量化与 GPU 驱动渲染**

连接零件级语义分析、结构感知的 Cluster LOD 构建与 Vulkan 渲染，结合 GPU 层次遍历、可见性筛选和按需几何加载。

`C++` `Vulkan` `Mesh Shader` `PointNeXt` `PointCLIP V2`

[源代码 ↗](https://github.com/13536309143/Industrial-Semantic-LOD) · [有限公开对比](https://github.com/13536309143/Industrial-Semantic-LOD/blob/main/docs/experiments/key-comparisons.md) · [运行指南](https://github.com/13536309143/Industrial-Semantic-LOD/blob/main/docs/guides/end-to-end.md)

---

### 02 / MERA-PHM
**维护事件感知的多模态预测与可审计 Agent 协作**

将维护历史与图像、文本、数值证据结合，按证据有效性选择预测专家，输出退化预测、校准区间与证据溯源。Agent 通过工具读取预测与证据，生成可追溯的报告。

`Python` `ExtraTrees` `PyTorch` `Conformal Prediction` `Agent Tools`

[源代码 ↗](https://github.com/13536309143/mera-phm) · [中文技术手册](https://github.com/13536309143/mera-phm/blob/main/docs/technical-manual.zh-CN.md) · [实验索引](https://github.com/13536309143/mera-phm/blob/main/experiments/README.md)

---

### 03 / GlyphWeave · 字织
**融合笔画细节与空间结构的手写字符识别**

结合笔画梯度、层级卷积、空间注意力与多尺度融合，识别汉字、英文字母和数字共 **7,247 类**。项目公开测试集包含 870,895 张图像，Top-1 准确率为 **95.95%**；评估协议与分类别结果见仓库说明。

`PyTorch` `CNN` `Spatial Attention` `CUDA / MPS`

[源代码 ↗](https://github.com/13536309143/GlyphWeave) · [中文说明与评估](https://github.com/13536309143/GlyphWeave/blob/main/README.zh-CN.md) · [模型与实验记录](https://github.com/13536309143/GlyphWeave/releases/tag/v1.0.0)

---

### 04 / Multi-Branch Multimodal Prognostics
**多分支融合与来源隔离的退化预测评估**

从信号图像、维护文本与数值历史预测下次检修的退化程度。比较不同模态组合，并通过来源隔离检查重复历史对评估的影响；公开 **500 条实验结果记录**、模型权重与验证工具。

`PyTorch` `Feature Fusion` `Source-isolated Evaluation`

[源代码 ↗](https://github.com/13536309143/multi-branch-multimodal-prognostics) · [评估与验证](https://github.com/13536309143/multi-branch-multimodal-prognostics/blob/main/docs/validation.md) · [模型与完整实验](https://github.com/13536309143/multi-branch-multimodal-prognostics/releases/tag/v1.0.0)

<a id="research"></a>

## 研究方向 · Research

- **图形学与渲染** — 工业三维模型、语义与结构感知 LOD、GPU 驱动渲染。
- **数字孪生与工业仿真** — 工业系统建模、状态映射、虚实交互与可视化。
- **多模态深度学习** — 图像、文本与数值信息融合，设备退化预测与来源隔离评估。

<p align="center">
  <sub>JJ WANG · MECHANICAL ENGINEERING</sub><br>
  <a href="https://github.com/13536309143?tab=repositories">Explore the code ↗</a>
</p>
