---
title: "开源资源"
date: 2026-05-16
weight: 5
description: "URT-SimReal 多模态混合数据集——面向6G智能城市轨道交通研究"
---

## URT-SimReal 数据集

**URT-SimReal** 是一个面向 **6G 智能城市轨道交通（URT）系统**研究的真实+仿真三维空间环境和多波段无线信道的多模态混合数据集。

![数据集方法](/images/dataset-method.jpg)

### 数据集特点

| 指标 | 数值/描述 |
|------|-----------|
| **CSI 记录数** | 316,026 条 |
| **覆盖环境** | 11 类典型轨道交通场景（封闭隧道、高架桥、车站枢纽等） |
| **频段覆盖** | Sub-6 GHz (1.8 / 3.5 / 5.6 GHz) 至毫米波 (28 / 39.5 / 60 GHz) |
| **数据类型** | 3D点云 (.ply) · RGB图像 (.png) · 环境语义标签 (.json) · 无线信道状态信息 (.h5) |
| **许可证** | CC BY 4.0 |
| **DOI** | [10.5281/zenodo.19920829](https://doi.org/10.5281/zenodo.19920829) |
| **版本** | 1.0.0 |

![数据集结构](/images/dataset-structure.png)

### 信道参数

每条 CSI 记录包含完整的无线信道参数：
- 路径损耗（Path Loss）
- 均方根时延扩展（RMS Delay Spread）
- 平均超量时延 / 最大超量时延
- 莱斯 K 因子（Rician K-factor）
- 相干带宽（Coherence Bandwidth）
- 多径分量（TOA、幅度、相位）

### 应用场景

- **通感一体化（ISAC）**算法基准测试
- 环境感知的信道预测
- 大型基础模型（Foundation Model）的训练数据
- 城市轨道交通无线通信系统设计与优化

### 获取数据集

数据集由**姜烨（Ye Jiang）**维护，可通过 Zenodo 获取。数据格式包括 .h5（信道数据）、.ply（点云）、.png（RGB 图像）和 .json（语义标注），方便研究者直接使用。

<a href="https://doi.org/10.5281/zenodo.19920829" class="btn btn-primary" target="_blank">
  <i class="fa-solid fa-download me-2"></i>访问数据集 (Zenodo)
</a>

![场景展示](/images/scen-intro.png)
