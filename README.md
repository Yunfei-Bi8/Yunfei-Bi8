<h1 align="center">Hi, I'm Yunfei Bi</h1>

<p align="center">
  <b>Robot learning</b> &nbsp;·&nbsp; <b>Control theory</b> &nbsp;·&nbsp; <b>Simulation for autonomous driving</b>
</p>

<p align="center">
  <a href="https://bi-yunfei.github.io/"><img src="https://img.shields.io/badge/Website-bi--yunfei.github.io-2e62e8?style=for-the-badge" alt="Personal website"></a>
  <a href="https://bi-yunfei.github.io/zh/"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87%E4%B8%BB%E9%A1%B5-bi--yunfei.github.io%2Fzh-e57a12?style=for-the-badge" alt="中文主页"></a>
  <a href="mailto:yunfei.bi@tum.de"><img src="https://img.shields.io/badge/Email-yunfei.bi%40tum.de-555555?style=for-the-badge" alt="Email yunfei.bi@tum.de"></a>
</p>

I am a master's student in Mechatronics, Robotics and Biomechanical Engineering at the [Technical University of Munich (TUM)](https://www.tum.de/en/), after a B.Sc. in Vehicle Engineering at [Tongji University](https://en.tongji.edu.cn/). My interests include **robot learning**, **control theory** and **simulation for autonomous driving**. I wrote my master's thesis at Prof. Schoellig's [Learning Systems and Robotics Lab](https://www.ce.cit.tum.de/lsy/home/) and my semester thesis at Prof. Althoff's [Cyber-Physical Systems Group](https://www.ce.cit.tum.de/cps/home/), both at TUM. I was a research intern at [Siemens](https://www.siemens.com/) Technology in Garching and am currently a working student at [Agile Robots SE](https://www.agile-robots.com/).

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS">
  <img src="https://img.shields.io/badge/LeRobot-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="LeRobot">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Linux-333333?style=flat-square&logo=linux&logoColor=white" alt="Linux">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

## Research Highlights

### [Learning Trustworthy Human-Robot Collaboration Policies from Human-Human Demonstrations](https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/)

<a href="https://www.ce.cit.tum.de/lsy/home/"><img src="assets/logos/lsy_tum.png" height="52" alt="Learning Systems and Robotics Lab, TUM"></a>

<sub>Master's thesis · Learning Systems and Robotics Lab, TUM · 2026</sub>

<img src="https://img.shields.io/badge/To%20be%20submitted%20to-IEEE%20RA--L-d73a49?style=for-the-badge" alt="To be submitted to IEEE RA-L"> <a href="https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/"><img src="https://img.shields.io/badge/Project-page-2e62e8?style=for-the-badge" alt="Project page"></a>

<a href="https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/"><img src="assets/hrc.gif" alt="UR10e robot collaborating with a person" width="440"></a>

- **Learning from human-human videos:** both people's hand skeletons from markerless RGB video drive and condition a diffusion policy; exchanging the roles teaches both sides of a task, including roles with no robot demonstration.
- **Embodiment-feasibility safety layer:** a diffusion-based feasibility score with a calibrated threshold stops the robot before motions its gripper cannot perform.
- **On a UR10e:** 18/20 successes with five robot demonstrations (5/20 robot-only), 13/20 in zero-shot roles, 19/20 infeasible motions stopped before contact.

---

### [CommonRoad-Game: A Human-in-the-Loop Simulation Framework for Autonomous Driving](https://arxiv.org/abs/2607.01382)

<a href="https://www.ce.cit.tum.de/cps/home/"><img src="assets/logos/cps.png" height="52" alt="Cyber-Physical Systems Group, TUM"></a>

<sub><b>Yunfei Bi</b>, Youran Wang · semester thesis · Cyber-Physical Systems Group, TUM · 2026</sub>

<a href="https://arxiv.org/abs/2607.01382"><img src="https://img.shields.io/badge/arXiv-2607.01382-b31b1b?style=for-the-badge&logo=arxiv&logoColor=white" alt="arXiv 2607.01382"></a> <a href="https://github.com/Yunfei-Bi8/CommonRoad-Game"><img src="https://img.shields.io/badge/Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code on GitHub"></a> <img src="https://img.shields.io/badge/First%20author-2026-555555?style=for-the-badge" alt="First author, 2026">

<a href="https://github.com/Yunfei-Bi8/CommonRoad-Game"><img src="assets/commonroad_game.gif" alt="CommonRoad-Game simulation with an autonomous and a human-driven vehicle" width="440"></a>

- **Human in the loop:** a lightweight simulator tightly integrated with [CommonRoad](https://commonroad.in.tum.de/) for testing motion planners with human drivers.
- **Time synchronisation:** a multi-threaded architecture aligns simulation time with wall-clock time; drift 402&nbsp;ms → 1.5&nbsp;ms.
- **Reproducible scenarios:** recorded driving logs become test cases; IDM and sampling-based planners are integrated.

---

### [Delay-Tolerant Formation Tracking for Multi-AGV Systems](https://bi-yunfei.github.io/agv-formation/)

<a href="https://www.siemens.com/"><img src="assets/logos/siemens.png" height="52" alt="Siemens AG"></a>

<sub>Research internship · Siemens Technology Center Garching · 2025 · technical report 2026</sub>

<img src="https://img.shields.io/badge/Technical%20report-2026-009999?style=for-the-badge" alt="Technical report, 2026"> <a href="https://bi-yunfei.github.io/agv-formation/"><img src="https://img.shields.io/badge/Project-page-2e62e8?style=for-the-badge" alt="Project page"></a>

<a href="https://bi-yunfei.github.io/agv-formation/"><img src="assets/agv_formation.gif" alt="Simulated AGV formation during a safety stop: without coupling (grey) the formation tears apart, with the cascade coupling (blue) the other vehicles wait" width="440"></a>

- **Cascade design:** delayed Wi-Fi data only shift each AGV's own reference, so stability holds for every bounded delay and any directed, switching communication graph.
- **On the robots:** C++ implementation with MQTT-based distributed communication, deployed in Docker.
- **Verified:** audited Lyapunov proofs and 4,894 high-fidelity simulation runs; no instability up to 4&nbsp;s latency and 12 vehicles, formation error &minus;47&nbsp;% after a safety stop.

## Experience

<a href="https://www.agile-robots.com/"><img src="assets/logos/agile_robots.png" height="40" alt="Agile Robots SE"></a>&nbsp;
<a href="https://www.siemens.com/"><img src="assets/logos/siemens.png" height="40" alt="Siemens AG"></a>&nbsp;
<a href="https://www.ce.cit.tum.de/lsy/home/"><img src="assets/logos/lsy_tum.png" height="40" alt="Learning Systems and Robotics Lab, TUM"></a>&nbsp;
<a href="https://www.ce.cit.tum.de/cps/home/"><img src="assets/logos/cps.png" height="40" alt="Cyber-Physical Systems Group, TUM"></a>

- **Agile Robots SE** · working student, foundation models for robotics: VLA post-training and inference acceleration · 05/2026 – present
- **TUM, Learning Systems and Robotics Lab** · master's thesis (03/2026 – present) and teaching assistant for Advanced Robot Learning and Decision Making (04/2026 – 05/2026)
- **Siemens AG, Technology Center Garching** · research intern, Lyapunov-based formation control of mobile robots · 08/2025 – 11/2025
- **TUM, Cyber-Physical Systems Group** · semester thesis, CommonRoad-Game · 07/2025 – 02/2026

<p align="center"><sub>More on <a href="https://bi-yunfei.github.io/">bi-yunfei.github.io</a> · <a href="mailto:yunfei.bi@tum.de">yunfei.bi@tum.de</a></sub></p>
