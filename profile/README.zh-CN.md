<div align="center">

# MirrorMeTech Robotics

[English](https://github.com/mirrormerobotics/.github/blob/main/profile/README.md) | **简体中文**

为 MirrorMe 机器人开发、仿真、强化学习、教育和系统集成提供开源 SDK、工具、机器人模型资源与技术资料。

[全部仓库](https://github.com/orgs/mirrormerobotics/repositories) · [机器人 SDK](https://github.com/mirrormerobotics/mirrorme_robot_sdk) · [机器人模型](https://github.com/mirrormerobotics/BPX) · [开发者资源](#开发者资源) · [联系我们](#联系我们)

</div>

---

## 关于我们

MirrorMeTech Robotics 专注于智能机器人及相关技术，致力于以清晰、可复用的方式向开发者、教育工作者、研究人员和合作伙伴开放核心能力。

本 GitHub 组织是 MirrorMe Robot SDK、面向特定机型的强化学习训练、机器人模型资源、图形化编程工具和早期部署集成的公开入口。请遵循各仓库的文档，在符合适用法规并确保安全的前提下使用相关软硬件。

---

## 开源项目

| 项目 | 简介 |
| --- | --- |
| **[mirrorme_robot_sdk](https://github.com/mirrormerobotics/mirrorme_robot_sdk)** | 面向 MirrorMe 多款机器人的统一 C++ 与 Python SDK，目前覆盖 BPX、BPX-Pro 和 BPW；按机型提供状态查询、运动控制和关节控制接口，后续将持续扩展机型支持。 |
| **[mirrorme_rl_train](https://github.com/mirrormerobotics/mirrorme_rl_train)** | 基于 Isaac Lab 和 RSL-RL PPO 的 BPX 开源强化学习基线，覆盖仿真训练、评估以及 TorchScript/ONNX 策略导出，不包含实体机器人部署。 |
| **[bpx-mindplus-extension](https://github.com/mirrormerobotics/bpx-mindplus-extension)** | 面向 Mind+ Python 模式的 BPX 积木与扩展构建工具，适用于图形化编程、教学和演示，目前支持 64 位 Windows 10/11。 |
| **[BPX](https://github.com/mirrormerobotics/BPX)** | 标准 BPX 官方模型资源，提供 [STEP CAD](https://github.com/mirrormerobotics/BPX/tree/master/step)、[URDF](https://github.com/mirrormerobotics/BPX/tree/master/bpx)、[MuJoCo MJCF](https://github.com/mirrormerobotics/BPX/tree/master/mjcf) 和 [USD](https://github.com/mirrormerobotics/BPX/tree/master/usd) 格式，附[中文说明](https://github.com/mirrormerobotics/BPX/blob/master/README.zh-CN.md)。 |
| **[BPX-Pro](https://github.com/mirrormerobotics/BPX-Pro)** | BPX-Pro 官方模型资源，提供 [STEP CAD](https://github.com/mirrormerobotics/BPX-Pro/tree/master/step)、[URDF](https://github.com/mirrormerobotics/BPX-Pro/tree/master/bpxPro)、[MuJoCo MJCF](https://github.com/mirrormerobotics/BPX-Pro/tree/master/mjcf) 和 [USD](https://github.com/mirrormerobotics/BPX-Pro/tree/master/usd) 格式，附[中文说明](https://github.com/mirrormerobotics/BPX-Pro/blob/master/README.zh-CN.md)。 |
| **[BPW](https://github.com/mirrormerobotics/BPW)** | BPW 官方模型资源，目前仅提供 [STEP CAD](https://github.com/mirrormerobotics/BPW/tree/master/step) 装配模型，附[中文说明](https://github.com/mirrormerobotics/BPW/blob/master/README.zh-CN.md)。暂未提供 URDF、MuJoCo MJCF 和 USD 模型。 |
| **[robot-mirrorme-bpx](https://github.com/mirrormerobotics/robot-mirrorme-bpx)** | 安全优先的 BPX Robonix 部署，包含固定版本模型、离线验证，以及无运动、状态回放、模拟状态和 SDK 只读配置。 |
| **[primitive-mirrorme-bpx-quadruped-rbnx](https://github.com/mirrormerobotics/primitive-mirrorme-bpx-quadruped-rbnx)** | 只读状态型 BPX Robonix 适配器，提供里程计、ROS 2 关节状态、SDK/回放/模拟后端及容器化测试。 |

MirrorMe Robot SDK 用于替代原仅支持 BPX 的 **[bpx_sdk_open](https://github.com/mirrormerobotics/bpx_sdk_open)**。此处保留旧版 SDK 链接供既有 BPX 项目参考，新项目请使用 MirrorMe Robot SDK。

Robonix 相关仓库仍处于早期阶段，实体硬件接入目前有意限制为只读模式，尚不提供生产级运动指令、建图、定位或自主导航能力。

---

<a id="开发者资源"></a>

## 开发者资源

- 连接和开发受支持的 MirrorMe 机器人，请从 **[mirrorme_robot_sdk](https://github.com/mirrormerobotics/mirrorme_robot_sdk)** 开始，并查阅[机型支持表](https://github.com/mirrormerobotics/mirrorme_robot_sdk/blob/master/README.zh-CN.md#项目定位与机型支持)确认目标机型的可用接口和固件要求。BPW 当前支持状态查询和运动控制，暂不支持关节级控制。
- 在 Isaac Lab 中训练、评估和导出 BPX 运动策略，请使用 **[mirrorme_rl_train](https://github.com/mirrormerobotics/mirrorme_rl_train)**。
- 图形化积木编程，请使用 **[bpx-mindplus-extension](https://github.com/mirrormerobotics/bpx-mindplus-extension)**。
- 使用 STEP 查看和评审机械装配，或开展 URDF、MuJoCo MJCF、USD 工作流时，请使用 **[BPX](https://github.com/mirrormerobotics/BPX)** 或 **[BPX-Pro](https://github.com/mirrormerobotics/BPX-Pro)**，并保持仓库原有目录结构以确保资源引用有效。
- 查看和评审 BPW 的机械装配，请使用 **[BPW](https://github.com/mirrormerobotics/BPW)**；当前仅提供 STEP 模型，暂未提供 URDF、MuJoCo MJCF 或 USD 模型。
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
