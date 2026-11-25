<h1 align="center">Hi, I'm Yunfei Bi</h1>

<p align="center">
  <b>Robot learning</b> &nbsp;·&nbsp; <b>Control theory</b> &nbsp;·&nbsp; <b>Simulation for autonomous driving</b>
</p>

<p align="center">
  <a href="https://bi-yunfei.github.io/"><img src="https://img.shields.io/badge/Website-bi--yunfei.github.io-2e62e8?style=for-the-badge" alt="Personal website"></a>
  <a href="https://bi-yunfei.github.io/zh/"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87%E4%B8%BB%E9%A1%B5-bi--yunfei.github.io%2Fzh-e57a12?style=for-the-badge" alt="中文主页"></a>
  <a href="mailto:yunfei.bi@tum.de"><img src="https://img.shields.io/badge/Email-yunfei.bi%40tum.de-555555?style=for-the-badge" alt="Email yunfei.bi@tum.de"></a>
</p>

I am a master's student in Mechatronics, Robotics and Biomechanical Engineering at the [Technical University of Munich (TUM)](https://www.tum.de/en/), after a B.Sc. in Vehicle Engineering at [Tongji University](https://en.tongji.edu.cn/). My interests include **robot learning**, **control theory** and **simulation for autonomous driving**. I wrote my master's thesis at Prof. Schoellig's [Learning Systems and Robotics Lab](https://www.ce.cit.tum.de/lsy/home/) and my semester thesis at Prof. Althoff's [Cyber-Physical Systems Group](https://www.ce.cit.tum.de/cps/home/), both at TUM. I was a research intern at [Siemens](https://www.siemens.com/) Technology in Garching and a working student at [Agile Robots SE](https://www.agile-robots.com/).

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

<table>
<tr>
<td width="320" align="center" valign="top">
<a href="https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/"><img src="assets/hrc.gif" width="300" alt="UR10e robot collaborating with a person"></a>
<br><br>
<a href="https://www.ce.cit.tum.de/lsy/home/"><img src="assets/logos/lsy_tum.png" height="54" alt="Learning Systems and Robotics Lab, TUM"></a>
</td>
<td valign="top">

**[Learning Trustworthy Human-Robot Collaboration Policies from Human-Human Demonstrations](https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/)**<br>
<sub>Master's thesis · Learning Systems and Robotics Lab, TUM · 2026</sub>

<img src="https://img.shields.io/badge/Paper-coming%20soon-d73a49?style=flat-square" alt="Paper coming soon"> <a href="https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/"><img src="https://img.shields.io/badge/Project-page-2e62e8?style=flat-square" alt="Project page"></a>

- **Learning from human-human videos:** hand skeletons of both people drive and condition a diffusion policy; exchanging roles also teaches roles with no robot demonstration.
- **Embodiment-feasibility safety layer:** X-Diffusion's robot-versus-human discriminator, read at every control cycle and calibrated on successful runs, stops the robot before motions its gripper cannot perform.
- **Results:** 18/20 successes on a UR10e with five robot demonstrations (5/20 robot-only); in 13,860 simulated runs, 98.3&nbsp;% and 100&nbsp;% of the infeasible runs stopped, at most 0.6&nbsp;% of the feasible ones.

</td>
</tr>
<tr>
<td width="320" align="center" valign="top">
<a href="https://bi-yunfei.github.io/agv-formation/"><img src="assets/agv_formation.gif" width="300" alt="Simulated AGV formation during a safety stop: without coupling (grey) the formation tears apart, with the cascade coupling (blue) the other vehicles wait"></a>
<br><br>
<a href="https://www.siemens.com/"><img src="assets/logos/siemens.png" height="54" alt="Siemens AG"></a>
</td>
<td valign="top">

**[Delay-Tolerant Formation Tracking for Multi-AGV Systems via Reference-Shift Coupling](https://bi-yunfei.github.io/agv-formation/)**<br>
<sub>arXiv preprint 2026 · research internship at Siemens Technology Center Garching, 2025</sub>

<a href="https://arxiv.org/abs/2611.32409"><img src="https://img.shields.io/badge/arXiv-2611.32409-b31b1b?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv 2611.32409"></a> <a href="https://github.com/Yunfei-Bi8/AGV-2026/tree/release"><img src="https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="Code on GitHub"></a> <a href="https://bi-yunfei.github.io/agv-formation/"><img src="https://img.shields.io/badge/Project-page-2e62e8?style=flat-square" alt="Project page"></a>

- **Cascade design:** delayed Wi-Fi data only shift each AGV's own reference, so stability holds for every bounded delay and any directed, switching graph.
- **Verified:** reviewed Lyapunov proofs and 4,894 high-fidelity simulation runs; no failure up to 4&nbsp;s latency and 12 vehicles, formation error &minus;47&nbsp;% after a safety stop.

</td>
</tr>
<tr>
<td width="320" align="center" valign="top">
<a href="https://github.com/Yunfei-Bi8/CommonRoad-Game"><img src="assets/commonroad_game.gif" width="230" alt="CommonRoad-Game simulation with an autonomous and a human-driven vehicle"></a>
<br><br>
<a href="https://www.ce.cit.tum.de/cps/home/"><img src="assets/logos/cps.png" height="54" alt="Cyber-Physical Systems Group, TUM"></a>
</td>
<td valign="top">

**[CommonRoad-Game: A Human-in-the-Loop Simulation Framework for Autonomous Driving](https://arxiv.org/abs/2607.01382)**<br>
<sub><b>Yunfei Bi</b>, Youran Wang · semester thesis · Cyber-Physical Systems Group, TUM · 2026</sub>

<a href="https://arxiv.org/abs/2607.01382"><img src="https://img.shields.io/badge/arXiv-2607.01382-b31b1b?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv 2607.01382"></a> <a href="https://github.com/Yunfei-Bi8/CommonRoad-Game"><img src="https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="Code on GitHub"></a> <img src="https://img.shields.io/badge/First%20author-2026-555555?style=flat-square" alt="First author, 2026">

- **Human in the loop:** a lightweight simulator tightly integrated with [CommonRoad](https://commonroad.in.tum.de/) for testing motion planners with human drivers.
- **Time synchronisation:** simulation time aligned with wall-clock time; drift 402&nbsp;ms → 1.5&nbsp;ms.
- **Reproducible scenarios:** recorded driving logs become test cases; IDM and sampling-based planners are integrated.

</td>
</tr>
</table>

## Experience

<table>
<tr>
<td width="200" align="center"><a href="https://www.agile-robots.com/"><img src="assets/logos/agile_robots.png" height="46" alt="Agile Robots SE"></a></td>
<td><b>Agile Robots SE</b>, Munich · working student, foundation models for robotics<br><sub>05/2026 – 10/2026 · VLA post-training and inference acceleration</sub></td>
</tr>
<tr>
<td width="200" align="center"><a href="https://www.ce.cit.tum.de/lsy/home/"><img src="assets/logos/lsy_tum.png" height="46" alt="Learning Systems and Robotics Lab, TUM"></a></td>
<td><b>Learning Systems and Robotics Lab, TUM</b> · master's thesis and teaching assistant<br><sub>03/2026 – present · trustworthy human-robot collaboration; TA for Advanced Robot Learning and Decision Making</sub></td>
</tr>
<tr>
<td width="200" align="center"><a href="https://www.siemens.com/"><img src="assets/logos/siemens.png" height="46" alt="Siemens AG"></a></td>
<td><b>Siemens AG</b>, Technology Center Garching · research intern<br><sub>08/2025 – 11/2025 · Lyapunov-based formation control of mobile robots</sub></td>
</tr>
<tr>
<td width="200" align="center"><a href="https://www.ce.cit.tum.de/cps/home/"><img src="assets/logos/cps.png" height="46" alt="Cyber-Physical Systems Group, TUM"></a></td>
<td><b>Cyber-Physical Systems Group, TUM</b> · semester thesis<br><sub>07/2025 – 01/2026 · CommonRoad-Game, human-in-the-loop simulation for autonomous driving</sub></td>
</tr>
</table>

<p align="center"><sub>More on <a href="https://bi-yunfei.github.io/">bi-yunfei.github.io</a> · <a href="mailto:yunfei.bi@tum.de">yunfei.bi@tum.de</a></sub></p>
