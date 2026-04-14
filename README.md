<div align="center">

<img src="./assets/logo.png" alt="Nebula Lab logo" width="92" />

# Nebula Lab

**面向科研数据预处理、批处理执行与 Origin 交接的 Windows 桌面工作站**

从原始实验数据到最终作图前的数据资产整理，统一完成导入、归组、清洗、批量执行与导出。

[🇨🇳 简体中文](./README.md) · [🇺🇸 English](./README_EN.md)

[![Latest Release](https://img.shields.io/github/v/release/TshyGO/NebulaLab-Releases?display_name=tag&sort=semver&style=for-the-badge&color=2e4c70)](https://github.com/TshyGO/NebulaLab-Releases/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows-0A66C2?style=for-the-badge&logo=windows)](https://github.com/TshyGO/NebulaLab-Releases/releases/latest)
[![Channel](https://img.shields.io/badge/Channel-Alpha-C97A1A?style=for-the-badge)](https://github.com/TshyGO/NebulaLab-Releases/releases/latest)

[**📥 下载最新版本**](https://github.com/TshyGO/NebulaLab-Releases/releases/latest) &nbsp;&nbsp;•&nbsp;&nbsp; [**📄 查看发版记录**](https://github.com/TshyGO/NebulaLab-Releases/releases)

</div>

<p align="center">
  <img src="./assets/nebula-hero-academic.png" alt="Nebula Lab workflow overview" width="760" />
</p>

> **Nebula Lab 的定位：** 为组级数据（Group-level Data）和多谱图序列提供稳定、可重复的预处理流程，减少实验数据在进入 Origin 或其他绘图工具前的重复手工整理。

## 工作流概览

| 导入 | 归组 | 清洗 | 批处理 | 结果预览 | 导出 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `.csv` `.txt` `.xlsx` | 按目录、组别或样本集合组织 | 裁剪、归一化、异常值处理 | 同组策略复用与批量执行 | 快速检查分布与趋势 | 输出到 Origin / `.opju` |

## 核心能力

| 能力 | 说明 |
| :--- | :--- |
| 预处理优先 | 在正式作图前先统一数据质量与结构，减少后续分析和制图返工。 |
| 组级批量复用 | 将单一样本验证过的处理流程快速推广到同组数据集。 |
| 分支独立控制 | 允许异常样本脱离主流水线，单独应用不同算法逻辑。 |
| 本地桌面执行 | 作为独立 Windows 应用运行，原始实验数据无需离开本地设备。 |

## 典型使用步骤

1. 从 [Releases 页面](https://github.com/TshyGO/NebulaLab-Releases/releases/latest) 下载 `setup.exe` 或 `msi` 安装包。
2. 导入仪器输出的宽表、测试结果或批量实验数据文件。
3. 为当前数据组配置清洗、裁剪、归一化或插值策略。
4. 使用可视化模块快速检查预处理结果是否满足预期。
5. 将整理后的成组数据导出到 Origin 或其他科学绘图工具。

## 下载说明

> 支持系统：Windows 10 / Windows 11 (x64)

| 安装包 | 适用场景 | 说明 |
| :--- | :--- | :--- |
| `NebulaLab-*-setup.exe` | 常规桌面安装 | 推荐大多数用户使用，包含标准安装向导与应用更新逻辑。 |
| `NebulaLab-*.msi` | 统一部署 / 管理环境 | 适合实验室工作站、域控或需要静默分发的场景。 |

> `.sig` 与 `latest.json` 属于更新校验所需的内部资产，手动下载安装时可以忽略。

## 后续方向

- Workflow 社区模板共享与检索
- 更智能的数据结构识别与清洗建议
- 更完整的 OriginLab 互操作与导出能力
