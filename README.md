<p align="center">
  <img src="assets/header.svg" width="100%" alt="JJ Wang — Engineering, made visible. Graphics · Digital Twins · Multimodal Learning">
</p>

<p align="center">
  <a href="#about">关于我</a> &nbsp; / &nbsp;
  <a href="#selected-work">代表项目</a> &nbsp; / &nbsp;
  <a href="#research">研究方向</a> &nbsp; / &nbsp;
  <a href="https://github.com/13536309143?tab=repositories">全部仓库 ↗</a>
</p>

<br>

<a id="about"></a>

## About · 关于我

机械工程背景，来自**广东工业大学**。关注**工业三维可视化、数字孪生与多模态学习**，从几何与语义建模、GPU 渲染，到设备退化预测与实验验证，探索算法在工业场景中的实现。

Mechanical engineering at Guangdong University of Technology. I work on industrial 3D visualization, digital twins, and multimodal learning, connecting modeling and algorithms with engineering implementation.

<br>

<a id="selected-work"></a>

## Selected Work · 代表项目

<sub>从工业图形与 CAD 开发，到多模态预测与实验验证。</sub>

<br>

<a href="https://github.com/13536309143/Industrial-Semantic-LOD"><img src="assets/project-01.svg" width="100%" alt="Industrial Semantic LOD"></a>

**工业三维模型轻量化与 GPU 驱动渲染**

连接零件级语义分析、结构感知的 Cluster LOD 构建与 Vulkan 渲染，结合 GPU 层次遍历、可见性筛选和按需几何加载。

`C++` `Vulkan` `Mesh Shader` `PointNeXt` `PointCLIP V2`

[源代码 ↗](https://github.com/13536309143/Industrial-Semantic-LOD) · [有限公开对比](https://github.com/13536309143/Industrial-Semantic-LOD/blob/main/docs/experiments/key-comparisons.md) · [运行指南](https://github.com/13536309143/Industrial-Semantic-LOD/blob/main/docs/guides/end-to-end.md)

<br>

<a href="https://github.com/13536309143/AxisForge-CAD"><img src="assets/project-02.svg" width="100%" alt="AxisForge-CAD"></a>

**参数建模、装配配合与三维交互的 CAD 桌面项目**

以 Qt 工作台、文档事务、OCCT 几何内核、装配求解与 OpenGL 显示构成完整开发流程。支持九种参数实体、布尔并／差／交、八种装配配合、撤销／重做，以及 STEP、GLB、OBJ 文件交换。

项目提供 Windows 运行包、源码与构建测试流程，覆盖从建模交互、几何计算到部署发布的工程实现。

`C++17` `Qt Widgets` `OpenGL 3.3` `Open CASCADE` `CMake / CTest`

[源代码 ↗](https://github.com/13536309143/AxisForge-CAD) · [下载正式版](https://github.com/13536309143/AxisForge-CAD/releases/tag/v1.0.0) · [建模参数](https://github.com/13536309143/AxisForge-CAD/blob/main/docs/MODELING_PARAMETERS.md) · [装配配合](https://github.com/13536309143/AxisForge-CAD/blob/main/docs/MATES_AND_GRID.md) · [测试报告](https://github.com/13536309143/AxisForge-CAD/blob/main/docs/TESTING.md)

<a href="https://github.com/13536309143/AxisForge-CAD">
  <img src="https://raw.githubusercontent.com/13536309143/AxisForge-CAD/main/docs/images/workbench.png" width="100%" alt="AxisForge-CAD 工作台：参数建模、装配配合与三维视口">
</a>

<sub>AxisForge-CAD 工作台 · 参数建模 / 装配配合 / 三维交互</sub>

<br>

<a href="https://github.com/13536309143/mera-phm"><img src="assets/project-03.svg" width="100%" alt="MERA-PHM"></a>

**维护事件感知的多模态预测与可审计 Agent 协作**

将维护历史与图像、文本、数值证据结合，按证据有效性选择预测专家，输出退化预测、校准区间与证据溯源。Agent 通过工具读取预测与证据，生成可追溯的报告。

`Python` `ExtraTrees` `PyTorch` `Conformal Prediction` `Agent Tools`

[源代码 ↗](https://github.com/13536309143/mera-phm) · [中文技术手册](https://github.com/13536309143/mera-phm/blob/main/docs/technical-manual.zh-CN.md) · [实验索引](https://github.com/13536309143/mera-phm/blob/main/experiments/README.md)

<br>

<a href="https://github.com/13536309143/multi-branch-multimodal-prognostics"><img src="assets/project-04.svg" width="100%" alt="Multimodal Prognostics"></a>

**多分支融合与来源隔离的退化预测评估**

从信号图像、维护文本与数值历史预测下次检修的退化程度。比较不同模态组合，并通过来源隔离检查重复历史对评估的影响；公开 **500 条实验结果记录**、模型权重与验证工具。

`PyTorch` `Feature Fusion` `Source-isolated Evaluation`

[源代码 ↗](https://github.com/13536309143/multi-branch-multimodal-prognostics) · [评估与验证](https://github.com/13536309143/multi-branch-multimodal-prognostics/blob/main/docs/validation.md) · [模型与完整实验](https://github.com/13536309143/multi-branch-multimodal-prognostics/releases/tag/v1.0.0)

<br>

<a id="research"></a>

## Research · 研究方向

| 方向 | 关注的问题 | 工程实践 |
| :--- | :--- | :--- |
| **图形学与渲染** | 复杂工业模型的实时显示与几何组织 | Cluster LOD · Vulkan · GPU 驱动渲染 |
| **数字孪生与工业仿真** | 工业系统建模、虚实交互与三维可视化 | 参数建模 · 装配配合 · OpenGL |
| **多模态学习** | 异构证据融合与设备退化预测 | PyTorch · 证据溯源 · 来源隔离评估 |

<br>

---

<p align="center">
  <strong>JJ WANG</strong><br>
  <sub>MODELING &nbsp; / &nbsp; RENDERING &nbsp; / &nbsp; LEARNING</sub><br><br>
  <a href="https://github.com/13536309143?tab=repositories">Explore the repositories ↗</a>
</p>
