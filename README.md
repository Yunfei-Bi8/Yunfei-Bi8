<p align="center">
  <a href="https://bi-yunfei.github.io/"><img src="https://img.shields.io/badge/Personal%20website-bi--yunfei.github.io-2e62e8?style=for-the-badge" alt="Personal website"></a>
  <a href="https://bi-yunfei.github.io/zh/"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87%E4%B8%BB%E9%A1%B5-bi--yunfei.github.io%2Fzh-e57a12?style=for-the-badge" alt="中文主页"></a>
</p>

## Hi, I'm Yunfei Bi

M.Sc. student in Mechatronics, Robotics and Biomechanical Engineering (MRBE) at the Technical University of Munich. My work spans three areas:

- **Robot learning:** imitation learning with diffusion policies and vision-language-action (VLA) models, learning from cross-embodiment human videos, human-robot collaboration (Learning Systems and Robotics Lab, TUM)
- **Control theory:** Lyapunov-based formation control of mobile robots under communication delays (research internship, Siemens)
- **Simulation for autonomous driving:** human-in-the-loop simulation for testing motion planners (Cyber-Physical Systems Group, TUM)

Currently a working student on foundation models for robotics at [Agile Robots SE](https://www.agile-robots.com/).

**More on my website: [bi-yunfei.github.io](https://bi-yunfei.github.io/)**

## Research Highlights

### [Learning Trustworthy Human-Robot Collaboration Policies from Human-Human Demonstrations](https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/)

<img src="https://img.shields.io/badge/To%20be%20submitted%20to-IEEE%20RA--L-d73a49?style=for-the-badge" alt="To be submitted to IEEE RA-L">

<sub>Master's thesis, Learning Systems and Robotics Lab, TUM, 2026</sub>

<a href="https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/"><img src="assets/hrc.gif" alt="UR10e robot collaborating with a person" width="400"></a>

- **HRC from human-human videos:** both people's hand skeletons are recovered from markerless RGB video; one hand drives the gripper, the partner's hand conditions a diffusion policy, and reading every video once per hand teaches both roles, including roles with no robot demonstration (zero-shot).
- **Embodiment-feasibility safety layer:** the number of forward-diffusion noise steps needed to explain an action chunk is a feasibility score learned from feasible actions alone; a calibrated threshold stops the robot before it attempts a motion its gripper cannot perform.
- **On a UR10e:** 18/20 successful runs vs. 5/20 robot-only; 13/20 and 14/20 in zero-shot roles; 19/20 infeasible motions stopped before contact.

[Project page](https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/)

### [CommonRoad-Game: A Human-in-the-Loop Simulation Framework for Autonomous Driving](https://arxiv.org/abs/2607.01382)

<a href="https://arxiv.org/abs/2607.01382"><img src="https://img.shields.io/badge/arXiv-2607.01382-b31b1b?style=for-the-badge&logo=arxiv&logoColor=white" alt="arXiv 2607.01382"></a> <img src="https://img.shields.io/badge/First%20author-2026-555555?style=for-the-badge" alt="First author, 2026">

<sub><b>Yunfei Bi</b>, Youran Wang · semester thesis, Cyber-Physical Systems Group, TUM</sub>

<a href="https://github.com/Yunfei-Bi8/CommonRoad-Game"><img src="assets/commonroad_game.gif" alt="CommonRoad-Game simulation with an autonomous and a human-driven vehicle" width="400"></a>

- Lightweight human-in-the-loop simulator tightly integrated with [CommonRoad](https://commonroad.in.tum.de/), for testing motion planners with human drivers.
- Multi-threaded architecture aligns simulation time with wall-clock time (drift 402&nbsp;ms → 1.5&nbsp;ms) for deterministic interaction of autonomous and human-driven vehicles.
- Recorded driving logs become reproducible test scenarios; IDM and sampling-based planners are integrated.

[arXiv](https://arxiv.org/abs/2607.01382) · [Code](https://github.com/Yunfei-Bi8/CommonRoad-Game)

### [Delay-Tolerant Formation Tracking for Multi-AGV Systems](https://bi-yunfei.github.io/agv-formation/)

<img src="https://img.shields.io/badge/Research%20internship-Siemens%20AG-009999?style=for-the-badge" alt="Research internship at Siemens AG"> <img src="https://img.shields.io/badge/Technical%20report-2026-555555?style=for-the-badge" alt="Technical report, 2026">

<sub>Research internship, Siemens Technology Center Garching, 2025 · technical report, 2026</sub>

<a href="https://bi-yunfei.github.io/agv-formation/"><img src="assets/agv_formation.gif" alt="Simulated AGV formation during a safety stop: without coupling (grey) the formation tears apart, with the cascade coupling (blue) the other vehicles wait" width="400"></a>

- **Cascade design:** delayed neighbour data from Wi-Fi only drive a filter that shifts each AGV's own reference; the tracking law never sees the network, so stability holds for every bounded delay and any directed, switching communication graph.
- **Theory:** strict Lyapunov function with explicit constants, delay-independent exponential and input-to-state estimates, and a formula for how much the coupling reduces the formation error; proofs audited and checked numerically.
- **Deployment and simulation:** ported to C++ on the robots with MQTT-based distributed communication and Docker; 4,894 paired high-fidelity simulation runs (vehicle dynamics, wheel loops, slip, LiDAR&ndash;odometry localisation, Wi-Fi loss) with no instability up to 4&nbsp;s latency and 12 vehicles; formation error &minus;47&nbsp;% after a safety stop.

[Project page](https://bi-yunfei.github.io/agv-formation/)

Contact: yunfei.bi@tum.de
