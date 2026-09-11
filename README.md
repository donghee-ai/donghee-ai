<div align="center">

# DongHee Kim · 김동희

### Physical AI · Edge AI · Robotics

I work on physical AI, on-device inference, and robotics software.

`Vision · Language · Action` &nbsp;·&nbsp; `On-device inference` &nbsp;·&nbsp; `Robotics systems`

[![GitHub](https://img.shields.io/badge/GitHub-donghee--ai-181717?style=flat-square&logo=github)](https://github.com/donghee-ai)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-danny1002-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/danny1002)
[![Email](https://img.shields.io/badge/Email-danny20049090%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:danny20049090@gmail.com)

</div>

---

## What I build

My projects cover **robotics, on-device inference, and systems engineering**. They include model measurements on edge devices, perception-to-action pipelines, deployment tools, and embedded communication software.

<table>
<tr>
<td width="33%" valign="top">

**Physical AI**

Vision-language-action pipelines, imitation learning, and bimanual robot integration.

</td>
<td width="33%" valign="top">

**Edge AI**

Model benchmarking, CPU/GPU-constrained inference, local agents, and device telemetry.

</td>
<td width="33%" valign="top">

**Reliable systems**

Off-target tests, artifact rollout and rollback, hardware abstraction, and operations tooling.

</td>
</tr>
</table>

## Selected work

<table>
<tr>
<td width="50%" valign="top">

### [Project Jetson](https://github.com/donghee-ai/project-jetson)

**A local personal agent running on Jetson Orin NX.**

The repository compares 13 model and quantization configurations. Memory, power, context-depth, and tool-calling measurements led to a Qwen3-8B setup used by Life Trainer, which combines cross-device activity rollups, a local MCP agent, Slack interaction, and systemd services.

`Jetson Orin NX` `Qwen3-8B` `llama.cpp` `MCP` `SQLite` `Python`

[Architecture & measurements →](https://github.com/donghee-ai/project-jetson#readme)

</td>
<td width="50%" valign="top">

### [Health Care Bot](https://github.com/donghee-ai/health_care_bot)

**A health-coach robot for rep counting and PTZ person tracking on Arduino UNO Q.**

MoveNet Thunder INT8 runs on the QRB2210 CPU. A two-axis ST3215 gimbal tracks the user, while a single Docker container and process also serve live video, telemetry, exercise controls, and a security mode.

`Arduino UNO Q` `MoveNet` `LiteRT` `OpenCV` `Docker` `TypeScript`

[Real-hardware demos →](https://github.com/donghee-ai/health_care_bot#readme)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [PAI](https://github.com/donghee-ai/PAI)

**A team project in which a language command triggers a bimanual trash-gathering policy.**

The full pipeline connects YOLO perception, an LLM intent gate, and a LeRobot ACT policy over WebSocket and ZMQ. My contribution covers the language component, the `rollout_with_zmq_task` LeRobot adapter, and three-window orchestration. The Vision component is credited in the repository to [@yeounhyeok](https://github.com/yeounhyeok).

`LeRobot` `ACT` `YOLO` `ZMQ` `SO-101` `Jetson AGX Thor`

[Watch the real-hardware demo →](https://github.com/donghee-ai/PAI#readme)

</td>
<td width="50%" valign="top">

### [Job Radar](https://github.com/donghee-ai/job-radar)

**A personal dashboard that collects openings from eight technology companies.**

Each source uses a documented collection method: Greenhouse, Ashby, Workday interception, internal APIs, or browser automation. The result is published as a static dashboard with GitHub Actions and Pages.

`Python` `Playwright` `Beautiful Soup` `GitHub Actions` `GitHub Pages`

[Open the live dashboard →](https://donghee-ai.github.io/job-radar/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ROS 2 Release Rollout](https://github.com/donghee-ai/ros2-release-rollout)

**A lightweight release system for deploying and rolling back prebuilt ROS 2 artifacts without rebuilding on the target.**

Packages a release with its manifest and SHA-256 checksums, validates the target environment, and changes the active version through a `current` symlink. The target uses Python's standard library and an installed ROS runtime; it does not rebuild the artifact.

`ROS 2 Jazzy` `Python` `C++` `colcon` `SHA-256`

[Follow the release pipeline →](https://github.com/donghee-ai/ros2-release-rollout#readme)

</td>
<td width="50%" valign="top">

### [nRF24L01+ Link](https://github.com/donghee-ai/nrf24l01-link)

**A 1:N half-duplex radio link built directly on ATmega328P registers—without the RF24 library.**

Implements a layered driver, a synchronized 100 ms slot schedule, and lockup recovery. A host-side radio simulator runs the firmware logic through 87 C checks and 10 Python tests without radio hardware.

`C` `ATmega328P` `nRF24L01+` `SPI` `TDD` `Off-target testing`

[Explore the protocol design →](https://github.com/donghee-ai/nrf24l01-link#readme)

</td>
</tr>
</table>

## Core toolkit

| | |
|:--|:--|
| **Languages** | Python · C · C++ · TypeScript · Shell |
| **Robotics & AI** | ROS 2 · PyTorch · LeRobot · OpenCV · YOLO · LiteRT · llama.cpp |
| **Edge & embedded** | NVIDIA Jetson · Arduino UNO Q · ATmega328P · serial and radio protocols |
| **Systems** | Docker · Linux · GitHub Actions · SQLite · ZMQ · WebSocket |

## Recognition

**19th of 261 teams** — 2026 SW중심대학 디지털 경진대회 AI부문<br>
Macro F1 **0.7946** on AI Agent Behavior Inference · [Repository](https://github.com/donghee-ai/2026-sw-univ-competition-ai)

---

<div align="center">

**B.S. in AI Applications · Hansung University**

Open to conversations about Physical AI, edge inference, and robotics engineering.

</div>
