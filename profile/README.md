<div align="center">

# MirrorMeTech Robotics

**English** | [简体中文](https://github.com/mirrormerobotics/.github/blob/main/profile/README.zh-CN.md)

Publishing open-source tools, robot model assets, and technical materials for BPX development, simulation, education, and integration.

[Repositories](https://github.com/orgs/mirrormerobotics/repositories) · [BPX SDK](https://github.com/mirrormerobotics/bpx_sdk_open) · [Robot Models](https://github.com/mirrormerobotics/BPX) · [Developer Resources](#developer-resources) · [Contact](#contact)

</div>

---

## About

MirrorMeTech Robotics focuses on intelligent robotics and related technologies, with an emphasis on making core capabilities accessible to developers, educators, researchers, and partners.

This GitHub organization is the public entry point for the BPX SDK, robot model assets, visual-programming tools, and early-stage deployment integrations. Please follow the documentation in each repository and use all hardware and software safely and in compliance with applicable regulations.

---

## Open Source Projects

| Project | Description |
| --- | --- |
| **[bpx_sdk_open](https://github.com/mirrormerobotics/bpx_sdk_open)** | C++ and Python SDK for physical robot control, telemetry, and research, with state-query, motion-control, and 12-DOF joint-control APIs. |
| **[bpx-mindplus-extension](https://github.com/mirrormerobotics/bpx-mindplus-extension)** | BPX blocks and extension-building tools for Mind+ Python mode, designed for visual programming, education, and demonstrations on 64-bit Windows 10/11. |
| **[BPX](https://github.com/mirrormerobotics/BPX)** | Official standard BPX model assets in [URDF](https://github.com/mirrormerobotics/BPX/tree/master/bpx), [MuJoCo MJCF](https://github.com/mirrormerobotics/BPX/tree/master/mjcf), and [USD](https://github.com/mirrormerobotics/BPX/tree/master/usd) formats. |
| **[BPX-Pro](https://github.com/mirrormerobotics/BPX-Pro)** | Official BPX-Pro model assets in [URDF](https://github.com/mirrormerobotics/BPX-Pro/tree/master/bpxPro), [MuJoCo](https://github.com/mirrormerobotics/BPX-Pro/tree/master/mujoco), and [USD](https://github.com/mirrormerobotics/BPX-Pro/tree/master/usd) formats. |
| **[robot-mirrorme-bpx](https://github.com/mirrormerobotics/robot-mirrorme-bpx)** | Safety-first BPX Robonix deployment with pinned models, offline validation, and no-motion, replay, fake-state, and SDK read-only profiles. |
| **[primitive-mirrorme-bpx-quadruped-rbnx](https://github.com/mirrormerobotics/primitive-mirrorme-bpx-quadruped-rbnx)** | State-only BPX Robonix adapter for odometry and ROS 2 joint states, with SDK, replay, and fake backends plus containerized tests. |

The Robonix repositories are early-stage and intentionally read-only for hardware-backed use. They do not currently provide a production motion-command path, mapping, localization, or autonomous navigation.

---

<a id="developer-resources"></a>

## Developer Resources

- Start with **[bpx_sdk_open](https://github.com/mirrormerobotics/bpx_sdk_open)** to connect to and program a physical BPX robot.
- Use **[bpx-mindplus-extension](https://github.com/mirrormerobotics/bpx-mindplus-extension)** for visual block programming.
- Use **[BPX](https://github.com/mirrormerobotics/BPX)** or **[BPX-Pro](https://github.com/mirrormerobotics/BPX-Pro)** for URDF, MuJoCo, and USD workflows. Keep the published directory layout intact so asset references continue to resolve.
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
