<div align="center">

# MirrorMeTech Robotics

[English](https://github.com/mirrormerobotics/.github/blob/main/profile/README.md) | **简体中文**

为 BPX 开发、仿真、教育和系统集成提供开源工具、机器人模型资源与技术资料。

[全部仓库](https://github.com/orgs/mirrormerobotics/repositories) · [BPX SDK](https://github.com/mirrormerobotics/bpx_sdk_open) · [机器人模型](https://github.com/mirrormerobotics/BPX) · [开发者资源](#开发者资源) · [联系我们](#联系我们)

</div>

---

## 关于我们

MirrorMeTech Robotics 专注于智能机器人及相关技术，致力于以清晰、可复用的方式向开发者、教育工作者、研究人员和合作伙伴开放核心能力。

本 GitHub 组织是 BPX SDK、机器人模型资源、图形化编程工具和早期部署集成的公开入口。请遵循各仓库的文档，在符合适用法规并确保安全的前提下使用相关软硬件。

---

## 开源项目

| 项目 | 简介 |
| --- | --- |
| **[bpx_sdk_open](https://github.com/mirrormerobotics/bpx_sdk_open)** | 面向实体机器人的 C++ 与 Python SDK，提供状态查询、运动控制及 12 自由度关节控制接口，适用于遥测、应用开发和科研。 |
| **[bpx-mindplus-extension](https://github.com/mirrormerobotics/bpx-mindplus-extension)** | 面向 Mind+ Python 模式的 BPX 积木与扩展构建工具，适用于图形化编程、教学和演示，目前支持 64 位 Windows 10/11。 |
| **[BPX](https://github.com/mirrormerobotics/BPX)** | 标准 BPX 官方模型资源，提供 [URDF](https://github.com/mirrormerobotics/BPX/tree/master/bpx)、[MuJoCo MJCF](https://github.com/mirrormerobotics/BPX/tree/master/mjcf) 和 [USD](https://github.com/mirrormerobotics/BPX/tree/master/usd) 格式。 |
| **[BPX-Pro](https://github.com/mirrormerobotics/BPX-Pro)** | BPX-Pro 官方模型资源，提供 [URDF](https://github.com/mirrormerobotics/BPX-Pro/tree/master/bpxPro)、[MuJoCo](https://github.com/mirrormerobotics/BPX-Pro/tree/master/mujoco) 和 [USD](https://github.com/mirrormerobotics/BPX-Pro/tree/master/usd) 格式。 |
| **[robot-mirrorme-bpx](https://github.com/mirrormerobotics/robot-mirrorme-bpx)** | 安全优先的 BPX Robonix 部署，包含固定版本模型、离线验证，以及无运动、状态回放、模拟状态和 SDK 只读配置。 |
| **[primitive-mirrorme-bpx-quadruped-rbnx](https://github.com/mirrormerobotics/primitive-mirrorme-bpx-quadruped-rbnx)** | 只读状态型 BPX Robonix 适配器，提供里程计、ROS 2 关节状态、SDK/回放/模拟后端及容器化测试。 |

Robonix 相关仓库仍处于早期阶段，实体硬件接入目前有意限制为只读模式，尚不提供生产级运动指令、建图、定位或自主导航能力。

---

<a id="开发者资源"></a>

## 开发者资源

- 连接和开发实体 BPX 机器人，请从 **[bpx_sdk_open](https://github.com/mirrormerobotics/bpx_sdk_open)** 开始。
- 图形化积木编程，请使用 **[bpx-mindplus-extension](https://github.com/mirrormerobotics/bpx-mindplus-extension)**。
- URDF、MuJoCo 或 USD 工作流，请使用 **[BPX](https://github.com/mirrormerobotics/BPX)** 或 **[BPX-Pro](https://github.com/mirrormerobotics/BPX-Pro)**，并保持仓库原有目录结构以确保资源引用有效。
- 评估 Robonix 集成时，请从 **[robot-mirrorme-bpx](https://github.com/mirrormerobotics/robot-mirrorme-bpx)** 开始，并在使用前阅读安全、验证及硬件验收文档。
- 集成或再分发前，请检查对应仓库的 `LICENSE`、`NOTICE`、版本说明、平台要求和已知限制。

---

<a id="联系我们"></a>

## 联系我们

- 官方网站：[mirrormetech.com](https://www.mirrormetech.com/cn/)
- 技术支持：[support@mirrormetech.com](mailto:support@mirrormetech.com)
- 高校及教育合作：[education@mirrormetech.com](mailto:education@mirrormetech.com)
- 购买咨询与商务合作：[partner@mirrormetech.com](mailto:partner@mirrormetech.com)
- 仓库问题与缺陷反馈：请使用对应仓库的 **Issues** 页面

---
