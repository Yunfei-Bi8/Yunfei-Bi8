<p align="center">
  <a href="https://bi-yunfei.github.io/"><img src="https://img.shields.io/badge/Personal%20website-bi--yunfei.github.io-2e62e8?style=for-the-badge" alt="Personal website"></a>
  <a href="https://bi-yunfei.github.io/zh/"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87%E4%B8%BB%E9%A1%B5-bi--yunfei.github.io%2Fzh-e57a12?style=for-the-badge" alt="中文主页"></a>
</p>

## Hi, I'm Yunfei Bi

M.Sc. student in Mechatronics, Robotics and Biomechanical Engineering (MRBE) at the Technical University of Munich. I work on **robot learning**, in particular **learning from cross-embodiment data**, **human-robot interaction** and **simulation frameworks in robotics**, with diffusion policies and vision-language-action (VLA) models. Currently a working student on foundation models for robotics at [Agile Robots SE](https://www.agile-robots.com/).

**More on my website: [bi-yunfei.github.io](https://bi-yunfei.github.io/)**

## Research Highlights

### [Learning Trustworthy Human-Robot Collaboration Policies from Human-Human Demonstrations](https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/)

<sub>Master's thesis, Learning Systems and Robotics Lab, TUM, 2026 · paper to be submitted to IEEE RA-L</sub>

<a href="https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/"><img src="assets/hrc.gif" alt="UR10e robot collaborating with a person" width="400"></a>

- **HRC from human-human videos:** both people's hand skeletons are recovered from markerless RGB video; one hand drives the gripper, the partner's hand conditions a diffusion policy, and reading every video once per hand teaches both roles, including roles with no robot demonstration (zero-shot).
- **Embodiment-feasibility safety layer:** the number of forward-diffusion noise steps needed to explain an action chunk is a feasibility score learned from feasible actions alone; a calibrated threshold stops the robot before it attempts a motion its gripper cannot perform.
- **On a UR10e:** 18/20 successful runs vs. 5/20 robot-only; 13/20 and 14/20 in zero-shot roles; 19/20 infeasible motions stopped before contact.

[Project page](https://yunfei-bi8.github.io/Trustworthy-HRC-from-Human-human-videos/)

### [CommonRoad-Game: A Human-in-the-Loop Simulation Framework for Autonomous Driving](https://arxiv.org/abs/2607.01382)

<sub><b>Yunfei Bi</b>, Youran Wang · arXiv preprint, 2026 · semester thesis, Cyber-Physical Systems Group, TUM</sub>

<a href="https://github.com/Yunfei-Bi8/CommonRoad-Game"><img src="assets/commonroad_game.gif" alt="CommonRoad-Game simulation with an autonomous and a human-driven vehicle" width="400"></a>

- Lightweight human-in-the-loop simulator tightly integrated with [CommonRoad](https://commonroad.in.tum.de/), for testing motion planners with human drivers.
- Multi-threaded architecture aligns simulation time with wall-clock time (drift 402&nbsp;ms → 1.5&nbsp;ms) for deterministic interaction of autonomous and human-driven vehicles.
- Recorded driving logs become reproducible test scenarios; IDM and sampling-based planners are integrated.

[arXiv](https://arxiv.org/abs/2607.01382) · [Code](https://github.com/Yunfei-Bi8/CommonRoad-Game)

Contact: yunfei.bi@tum.de
