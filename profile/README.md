<div align="center">

# MirrorMeTech Robotics

**English** | [简体中文](https://github.com/mirrormerobotics/.github/blob/main/profile/README.zh-CN.md)

Publishing open-source SDKs, tools, robot model assets, and technical materials for MirrorMe robot development, simulation, reinforcement learning, education, and integration.

[Repositories](https://github.com/orgs/mirrormerobotics/repositories) · [Robot SDK](https://github.com/mirrormerobotics/mirrorme_robot_sdk) · [Robot Models](https://github.com/mirrormerobotics/BPX) · [Developer Resources](#developer-resources) · [Contact](#contact)

</div>

---

## About

MirrorMeTech Robotics focuses on intelligent robotics and related technologies, with an emphasis on making core capabilities accessible to developers, educators, researchers, and partners.

This GitHub organization is the public entry point for MirrorMe Robot SDK, model-specific reinforcement-learning training, robot model assets, visual-programming tools, and early-stage deployment integrations. Please follow the documentation in each repository and use all hardware and software safely and in compliance with applicable regulations.

---

## Open Source Projects

| Project | Description |
| --- | --- |
| **[mirrorme_robot_sdk](https://github.com/mirrormerobotics/mirrorme_robot_sdk)** | Unified C++ and Python SDK for MirrorMe robots, currently covering BPX, BPX-Pro, and BPW. Provides state-query, motion-control, and joint-control APIs according to model support, with support for additional models planned. |
| **[mirrorme_rl_train](https://github.com/mirrormerobotics/mirrorme_rl_train)** | Open BPX reinforcement-learning baseline using Isaac Lab and RSL-RL PPO for simulation training, evaluation, and TorchScript/ONNX policy export. Physical-robot deployment is out of scope. |
| **[bpx-mindplus-extension](https://github.com/mirrormerobotics/bpx-mindplus-extension)** | BPX blocks and extension-building tools for Mind+ Python mode, designed for visual programming, education, and demonstrations on 64-bit Windows 10/11. |
| **[BPX](https://github.com/mirrormerobotics/BPX)** | Official standard BPX model assets in [STEP CAD](https://github.com/mirrormerobotics/BPX/tree/master/step), [URDF](https://github.com/mirrormerobotics/BPX/tree/master/bpx), [MuJoCo MJCF](https://github.com/mirrormerobotics/BPX/tree/master/mjcf), and [USD](https://github.com/mirrormerobotics/BPX/tree/master/usd) formats, with [Simplified Chinese documentation](https://github.com/mirrormerobotics/BPX/blob/master/README.zh-CN.md). |
| **[BPX-Pro](https://github.com/mirrormerobotics/BPX-Pro)** | Official BPX-Pro model assets in [STEP CAD](https://github.com/mirrormerobotics/BPX-Pro/tree/master/step), [URDF](https://github.com/mirrormerobotics/BPX-Pro/tree/master/bpxPro), [MuJoCo MJCF](https://github.com/mirrormerobotics/BPX-Pro/tree/master/mjcf), and [USD](https://github.com/mirrormerobotics/BPX-Pro/tree/master/usd) formats, with [Simplified Chinese documentation](https://github.com/mirrormerobotics/BPX-Pro/blob/master/README.zh-CN.md). |
| **[BPW](https://github.com/mirrormerobotics/BPW)** | Official BPW model assets, currently available as a [STEP CAD](https://github.com/mirrormerobotics/BPW/tree/master/step) assembly, with [Simplified Chinese documentation](https://github.com/mirrormerobotics/BPW/blob/master/README.zh-CN.md). URDF, MuJoCo MJCF, and USD models are not currently included. |
| **[robot-mirrorme-bpx](https://github.com/mirrormerobotics/robot-mirrorme-bpx)** | Safety-first BPX Robonix deployment with pinned models, offline validation, and no-motion, replay, fake-state, and SDK read-only profiles. |
| **[primitive-mirrorme-bpx-quadruped-rbnx](https://github.com/mirrormerobotics/primitive-mirrorme-bpx-quadruped-rbnx)** | State-only BPX Robonix adapter for odometry and ROS 2 joint states, with SDK, replay, and fake backends plus containerized tests. |

MirrorMe Robot SDK replaces the BPX-only **[bpx_sdk_open](https://github.com/mirrormerobotics/bpx_sdk_open)**. The legacy SDK is linked here for existing BPX projects; new integrations should use MirrorMe Robot SDK.

The Robonix repositories are early-stage and intentionally read-only for hardware-backed use. They do not currently provide a production motion-command path, mapping, localization, or autonomous navigation.

---

<a id="developer-resources"></a>

## Developer Resources

- Start with **[mirrorme_robot_sdk](https://github.com/mirrormerobotics/mirrorme_robot_sdk)** to connect to and program a supported MirrorMe robot. Check the [product support matrix](https://github.com/mirrormerobotics/mirrorme_robot_sdk/blob/master/README.md#project-scope-and-product-support) for model-specific APIs and firmware requirements. BPW currently supports state queries and motion control, but not joint-level control.
- Use **[mirrorme_rl_train](https://github.com/mirrormerobotics/mirrorme_rl_train)** to train, evaluate, and export BPX locomotion policies in Isaac Lab.
- Use **[bpx-mindplus-extension](https://github.com/mirrormerobotics/bpx-mindplus-extension)** for visual block programming.
- Use **[BPX](https://github.com/mirrormerobotics/BPX)** or **[BPX-Pro](https://github.com/mirrormerobotics/BPX-Pro)** for mechanical CAD review with STEP and for URDF, MuJoCo MJCF, or USD workflows. Keep the published directory layout intact so asset references continue to resolve.
- Use **[BPW](https://github.com/mirrormerobotics/BPW)** for STEP mechanical CAD assembly review. Only STEP assets are currently provided; URDF, MuJoCo MJCF, and USD models are not included.
- Start with **[robot-mirrorme-bpx](https://github.com/mirrormerobotics/robot-mirrorme-bpx)** when evaluating the Robonix integration and review its safety, validation, and hardware acceptance documentation before use.
- Review each repository's `LICENSE`, `NOTICE`, version notes, platform requirements, and known limitations before integration or redistribution.

---

<a id="contact"></a>

## Contact

- Website: [mirrormetech.com](https://www.mirrormetech.com/cn/)
- Technical support: [support@mirrormetech.com](mailto:support@mirrormetech.com)
- Education and university collaboration: [education@mirrormetech.com](mailto:education@mirrormetech.com)
- Purchasing and partnerships: [partner@mirrormetech.com](mailto:partner@mirrormetech.com)
- Repository questions and bug reports: use the **Issues** page of the relevant repository

---
