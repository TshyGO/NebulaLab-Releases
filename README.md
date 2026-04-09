<div align="center">

[🇨🇳 简体中文](./README.md) | [🇺🇸 English](./README_EN.md)

<img src="https://raw.githubusercontent.com/TshyGO/NebulaGraph-Releases/main/assets/nebula-hero-academic.png" alt="Nebula Graph Workflow Graphic" width="420" style="border-radius: 12px; margin-top: 10px;" />

<h1><img src="https://raw.githubusercontent.com/TshyGO/NebulaGraph-Releases/main/assets/logo.png" width="48" style="vertical-align: middle; margin-right: 4px;" />Nebula Graph</h1>

**面向科研场景的数据处理工作站：集成数据清洗、特征预处理、批量执行与 Origin 格式交互的桌面端应用。**


[![Latest Release](https://img.shields.io/github/v/release/TshyGO/NebulaGraph-Releases?display_name=tag&sort=semver&style=for-the-badge&color=2e4c70)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows-0A66C2?style=for-the-badge&logo=windows)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)
[![Channel](https://img.shields.io/badge/Channel-Alpha-C97A1A?style=for-the-badge)](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest)

*主要用于规范化多组同类科研数据的预处理流程，减少实验数据向图表转化过程中的重复性手动操作。*

[📥 获取安装包](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest) &nbsp;&nbsp;•&nbsp;&nbsp; [📄 发版记录](https://github.com/TshyGO/NebulaGraph-Releases/releases)

</div>

---

## 🔬 设计定位

Nebula Graph 旨在满足**组级数据（Group-level Data）**和**多谱图序列**的处理需求。在实验科学中，数据通常具有同构特征，本项目将重点前移至“数据预处理（Data Preparation）”环节，确立了如下标准的转化工作流：

`载入 (Import)` &nbsp;➔&nbsp; `归类 (Group)` &nbsp;➔&nbsp; `清洗 (Cleanse)` &nbsp;➔&nbsp; `批处理 (Batch Process)` &nbsp;➔&nbsp; `可视化 (Visualize)` &nbsp;➔&nbsp; `导出 (Export)`

---

## 📐 核心功能特征

<table>
  <tr>
    <td><div align="center"><b>预处理导向</b></div></td>
    <td>在进行图表绘制前，提供针对数据矩阵的处理环境，支持数据的清洗、裁剪与归一化计算，确保用于作图的数据具有较高的信噪比与一致性。</td>
  </tr>
  <tr>
    <td><div align="center"><b>组级映射计算</b></div></td>
    <td>操作单元可提升至目录层级或组层级。针对某一特定样本的处理流可以快速复写至同组数据集，避免单次重复运算。</td>
  </tr>
  <tr>
    <td><div align="center"><b>分支独立控制</b></div></td>
    <td>在统一批量处理流水线的框架内，允许个别具有明显偏离特征的样本剥离原有管线，引入独立的算法逻辑进行计算。</td>
  </tr>
  <tr>
    <td><div align="center"><b>本地化执行</b></div></td>
    <td>作为独立的 Windows 桌面应用编译运行，所有运算发生于本地处理器，确保原始实验数据的保密性及访问的连续性。</td>
  </tr>
</table>

---

## 📝 标准操作步骤

1. **环境准备**：从 [Releases 页面](https://github.com/TshyGO/NebulaGraph-Releases/releases/latest) 下载执行程序，在 Windows 工作站完成部署。
2. **数据载入**：批量导入由各分析仪器输出的宽表或测试结果（格式支持 `.csv`, `.txt`, `.xlsx` 等）。
3. **策略映射**：侦测数据字段规则，构建针对当前组别的数据剔除与插值策略。
4. **模型预览**：调取可视化模块对预处理后的数据分布进行初步论证。
5. **资产导出**：将处理完备的成组数据统一投至 Origin 等第三方科学绘图软件进行最终呈现（支持 `.opju` 等原生格式）。

---

## 🔮 研发规划路线

项目目前基于基础计算引擎运行，后续版本的演进重点如下：

- **Workflow 社区机制 (Phase 2):** 构建基于本地应用集成的共享方案（依托 Supabase 架构），实现实验及绘图模板的上传与检索复用。
- **智能化解析介入:** 试验引入推演引擎，用于自适应识别表头分布或提供对部分杂乱数据集结构规整的可行性建议。
- **OriginLab 拓展协同:** 从基础的序列导出，向提供更多样性的图象图层与样式热传导互链发展。

---

## 📦 获取与分发声明

> **受支持的执行环境要求：** Windows 10 / Windows 11 (x64) 架构

| 部署形态 | 适用环境 | 说明 |
| :--- | :--- | :--- |
| `NebulaGraph-*-setup.exe` | **常规安装桌面客户端** | 标准的安装引导程序，包含了应用内后台校验与自我更新逻辑。 |
| `NebulaGraph-*.msi` | **域控分发 / 统一配置** | 提供更为底层的安装方式，适应局域网内科研仪器工作站环境静默分发。 |

*(注：发版列表中附带的 `.sig` 以及 `latest.json` 属于更新检索校验机制依赖的内部资产缓存包，在手工下载时请忽略)*
