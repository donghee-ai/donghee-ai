<div align="center">

# DongHee Kim · 김동희

### Physical AI Engineer

I build robots and edge AI systems that survive the jump from a demo to real hardware.

`Vision · Language · Action` &nbsp;·&nbsp; `On-device inference` &nbsp;·&nbsp; `Robotics systems`

[![GitHub](https://img.shields.io/badge/GitHub-donghee--ai-181717?style=flat-square&logo=github)](https://github.com/donghee-ai)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-danny1002-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/danny1002)
[![Email](https://img.shields.io/badge/Email-danny20049090%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:danny20049090@gmail.com)

</div>

---

## What I build

My work sits where **robotics, on-device inference, and systems engineering** meet. I measure models on the target device, connect perception to action, and build the deployment, testing, and recovery paths needed to keep the whole system running.

<table>
<tr>
<td width="33%" valign="top">

**Physical AI**

Vision-language-action pipelines, imitation learning, bimanual manipulation, and real-hardware integration.

</td>
<td width="33%" valign="top">

**Edge AI**

Measured model selection, CPU/GPU-constrained inference, privacy-first local agents, and device telemetry.

</td>
<td width="33%" valign="top">

**Reliable systems**

Off-target tests, artifact rollout and rollback, hardware abstraction, observability, and reproducible operations.

</td>
</tr>
</table>

## Selected work

<table>
<tr>
<td width="50%" valign="top">

### [Project Jetson](https://github.com/donghee-ai/project-jetson)

**A privacy-safe, always-on personal agent running on Jetson Orin NX.**

Benchmarked 13 model and quantization configurations, selected Qwen3-8B from real memory, power, context-depth, and tool-calling measurements, then built Life Trainer on top: cross-device activity rollups, a local MCP agent, Slack interaction, and systemd operations.

`Jetson Orin NX` `Qwen3-8B` `llama.cpp` `MCP` `SQLite` `Python`

[Architecture & measurements →](https://github.com/donghee-ai/project-jetson#readme)

</td>
<td width="50%" valign="top">

### [Health Care Bot](https://github.com/donghee-ai/health_care_bot)

**A health-coach robot running pose inference, rep counting, PTZ tracking, and a web app on one Arduino UNO Q.**

MoveNet Thunder INT8 runs on the NPU-less QRB2210 CPU while a two-axis ST3215 gimbal keeps the user framed. The same container serves live video, telemetry, exercise controls, and a security mode.

`Arduino UNO Q` `MoveNet` `LiteRT` `OpenCV` `Docker` `TypeScript`

[Real-hardware demos →](https://github.com/donghee-ai/health_care_bot#readme)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [PAI](https://github.com/donghee-ai/PAI)

**A language-directed bimanual robot that sweeps desk trash into a dustpan.**

Integrated YOLO perception, an LLM intent gate, and a LeRobot ACT policy across WebSocket and ZMQ channels. Added camera ownership boundaries, policy adapters, orchestration scripts, and dry-run verification for the Jetson AGX Thor + dual SO-101 setup.

`LeRobot` `ACT` `YOLO` `ZMQ` `SO-101` `Jetson AGX Thor`

[Watch the real-hardware demo →](https://github.com/donghee-ai/PAI#readme)

</td>
<td width="50%" valign="top">

### [Job Radar](https://github.com/donghee-ai/job-radar)

**A personal job tracker that unifies openings from eight technology companies.**

Uses the right acquisition path for each source—Greenhouse, Ashby, Workday interception, internal APIs, or browser automation—then publishes a zero-cost static dashboard through GitHub Actions and Pages.

`Python` `Playwright` `Beautiful Soup` `GitHub Actions` `GitHub Pages`

[Open the live dashboard →](https://donghee-ai.github.io/job-radar/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ROS 2 Release Rollout](https://github.com/donghee-ai/ros2-release-rollout)

**A lightweight release system for deploying and rolling back prebuilt ROS 2 artifacts without rebuilding on the target.**

Packages a self-contained release with its manifest and SHA-256 checksums, validates the target environment, and atomically switches the active version. The target needs only Python's standard library and its ROS runtime.

`ROS 2 Jazzy` `Python` `C++` `colcon` `SHA-256`

[Follow the release pipeline →](https://github.com/donghee-ai/ros2-release-rollout#readme)

</td>
<td width="50%" valign="top">

### [nRF24L01+ Link](https://github.com/donghee-ai/nrf24l01-link)

**A 1:N half-duplex radio link built directly on ATmega328P registers—without the RF24 library.**

Implements a layered driver, synchronized 100 ms slot schedule, lockup recovery, and static-memory operation. A host-side radio simulator runs the same firmware logic through 87 C checks and 10 Python tests without hardware.

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

**19th of 261 teams · Top 7%** — 2026 SW-Centered University Digital Competition, AI division<br>
Macro F1 **0.7946** on AI Agent Behavior Inference · [Repository](https://github.com/donghee-ai/2026-sw-univ-competition-ai)

---

<div align="center">

**B.S. in AI Applications · Hansung University**

Open to conversations about Physical AI, edge inference, and robotics engineering.

</div>
