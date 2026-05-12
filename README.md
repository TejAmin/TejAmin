<div align="center">

# 👋 Hey, I'm Tej Deepak Amin

### Control Systems & ML Engineer · MPC · Reinforcement Learning · Vehicle Dynamics

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tej-amin3103)
[![TU Dortmund](https://img.shields.io/badge/TU%20Dortmund-003DA0?style=for-the-badge&logo=academia&logoColor=white)](https://www.tu-dortmund.de)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tej310302@gmail.com)

</div>

---

## 🧑‍💻 About Me

I'm an **MSc student in Automation & Robotics at TU Dortmund** (GPA: 1.65) and a **Research Assistant at the Lamarr Institute for Machine Learning and AI**, specializing in advanced control strategies for autonomous and safety-critical systems.

My research focuses on bridging **Model Predictive Control (MPC)** with **deep reinforcement learning** for vehicle dynamics and trajectory optimization. I develop control-oriented models and benchmarking pipelines that combine rigorous optimization theory with modern learning-based approaches.

- 🔭 Currently: **Research Assistant @ Lamarr Institute** — control-oriented modeling, ML benchmarking & advanced control for dynamic systems
- 🚗 Research Focus: **MPC-RL Integration, Vehicle Dynamics, Autonomous Driving, Constrained Optimal Control**
- 🤖 ML Expertise: **Deep RL (SAC, PPO), CNNs, LSTMs, Transformers** for control and time-series prediction
- 🎯 Goal: R&D in **intelligent mobility, autonomous systems & next-gen vehicle stability control**
- 📍 Based in: **Dortmund, Germany**
- 🏏 Fun fact: Huge cricket fan!

---

## 🛠️ Tech Stack

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB/Simulink-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

### Control & Optimization
![MPC](https://img.shields.io/badge/Model%20Predictive%20Control-1A1A2E?style=flat-square)
![CasADi](https://img.shields.io/badge/CasADi-4B0082?style=flat-square)
![RL](https://img.shields.io/badge/Deep%20RL%20(SAC%2FPPO)-FF6B6B?style=flat-square)
![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-00D4AA?style=flat-square)
![State Space](https://img.shields.io/badge/State--Space%20Modeling-34495E?style=flat-square)

### Tools & Platforms
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![ANSYS](https://img.shields.io/badge/ANSYS%20Maxwell-FFB71B?style=flat-square)
![Typhoon HIL](https://img.shields.io/badge/Typhoon%20HIL-00897B?style=flat-square)

### Embedded & Communication
![Embedded](https://img.shields.io/badge/ARM%20%7C%20PIC%20%7C%20AVR-333333?style=flat-square&logo=arm&logoColor=white)
![CAN](https://img.shields.io/badge/CAN%2FCANopen-FF6600?style=flat-square)
![Protocols](https://img.shields.io/badge/SPI%20%7C%20I2C%20%7C%20UART%20%7C%20UDP%2FTCP-0078D4?style=flat-square)

---

## 🚀 Featured Projects

### 🔴 Deep Reinforcement Learning for Autonomous Obstacle Avoidance *(Master's Project)*
> Developed **Soft Actor-Critic (SAC)** agent using Stable-Baselines3 for high-speed highway obstacle avoidance with kinematic bicycle model. Designed custom **HighwayObstacleEnv** with curriculum learning, EMA action smoothing, Gaussian obstacle repulsion, and adaptive reward shaping. Implemented **parallel training infrastructure** using SubprocVecEnv and GPU acceleration (Kaggle/Colab). RL agent achieves **~80-85% of MPC performance** with significantly faster inference. Currently exploring **MPC-RL hybrid architectures** (MPC-guided RL, safety filters, hierarchical control) and **imitation learning** techniques (Behavioral Cloning, DAgger, GAIL).

`Python` `PyTorch` `Deep RL (SAC)` `Stable-Baselines3` `Curriculum Learning` `Imitation Learning` `Parallel Training`

[![Repo](https://img.shields.io/badge/GitHub-RL__ObstacleAvoidance-181717?style=flat-square&logo=github)](https://github.com/TejAmin/APC_ObstacleAvoidance_P1.2)

---

### 🔵 Nonlinear MPC for Autonomous Highway Driving *(Master's Project)*
> Formulated a **constrained nonlinear optimal control problem** for autonomous navigation using kinematic bicycle model with CasADi. Implemented full **MPC framework** with lateral & longitudinal dynamics, collision avoidance constraints, and real-time trajectory optimization. System handles dynamic obstacle scenarios while maintaining vehicle stability at high speeds. Used as **benchmark baseline** for RL comparison study.

`Python` `CasADi` `MPC` `Nonlinear Optimization` `Vehicle Dynamics` `Constrained Control`

[![Repo](https://img.shields.io/badge/GitHub-MPC__ObstacleAvoidance-181717?style=flat-square&logo=github)](https://github.com/TejAmin/APC_ObstacleAvoidance_P1.2)

---

### 🟡 Solar Flare Prediction using Ensemble ML
> Developed **physics-informed ML models** for binary solar flare prediction using SDO/HMI SHARP parameters (726 samples, heavily imbalanced). Implemented **LightGBM ensemble** with GroupKFold CV, SMOTE oversampling, and engineered features from magnetic field parameters. Achieved **ROC-AUC ~0.71** and **True Skill Statistic (TSS) ~0.48**, significantly outperforming baseline models. Applied uncertainty quantification techniques for reliable probabilistic forecasting.

`Python` `LightGBM` `SMOTE` `Feature Engineering` `Imbalanced Learning` `Time-Series` `Uncertainty Quantification`

---

### 🟣 Data-based Modeling of Slug Flow Crystallization with UQ
> Built predictive models for a crystallization process using **NARX neural networks**. Applied unsupervised ML for time-series clustering and implemented **Conformalized Quantile Regression (CQR)** for real-time uncertainty quantification with distribution-free coverage guarantees.

`Python` `TensorFlow/Keras` `NARX` `CQR` `Scikit-learn` `Time-Series Forecasting` `Uncertainty Quantification`

[![Repo](https://img.shields.io/badge/GitHub-SFC__Modeling__ANN-181717?style=flat-square&logo=github)](https://github.com/TejAmin/SFC_Modeling_Using_ANN)

---

### 🟢 Wireless EV Charging Coil Optimization *(B.Tech Thesis)*
> Designed and optimized coil structures for **dynamic wireless power transfer in EVs** using ANSYS Maxwell. Evaluated multiple geometries for efficiency, alignment tolerance, and manufacturability — validated with a working prototype achieving >85% efficiency.

`ANSYS Maxwell` `Power Electronics` `MATLAB` `PCB Prototyping` `3D Printing` `FEA`

---

### 🟠 Line Follower Robot — Autonomous Navigation
> Built an autonomous robot using **PID control and IR sensors** on Arduino. Programmed real-time motor control in C/C++, designed chassis in SolidWorks, and fabricated using laser cutting and 3D printing.

`Arduino` `C/C++` `PID` `SolidWorks` `Embedded Systems`

---

## 💼 Experience

| Role | Organisation | Period |
|------|-------------|--------|
| 🔬 Research Assistant | Lamarr Institute for ML & AI, Dortmund | May 2025 – Present |
| 🏎️ Team Captain — Vehicle Dynamics | Etros Solareon Racing (Solar-Powered Hybrid EV) | 2023 – 2024 |
| 🏎️ Team Lead — Vehicle Dynamics | Etros Solareon Racing | 2020 – 2024 |
| ⚙️ Instrumentation Intern | Reliance Industries Ltd. (Dahej) | May – Jul 2023 |
| 💾 Embedded Systems Intern | Microchip Inc. | May – Jul 2023 |

---

## 🎓 Education

| Degree | Institution | GPA/CGPA | Period |
|--------|------------|----------|--------|
| 🎓 M.Sc. Automation & Robotics | TU Dortmund University, Germany | 1.65 | 2024 – Present |
| 🎓 B.Tech Mechatronics Engineering | SRM Institute of Science & Technology, India | 9.23/10 | 2020 – 2024 |

**Relevant Coursework:** Nonlinear Control Systems, Advanced Process Control, Model Predictive Control, Machine Learning, Deep Learning, Reinforcement Learning, Vehicle Dynamics, Embedded Systems

---

## 📊 GitHub Stats

<div align="center">

![Tej's GitHub Stats](https://github-readme-stats.vercel.app/api?username=TejAmin&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=TejAmin&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🏆 Highlights & Achievements

- 🔬 **Research Assistant** — Lamarr Institute for Machine Learning & AI (2025 – Present)
- 🎓 **M.Sc. Automation & Robotics** — TU Dortmund *(GPA: 1.65, in progress)*
- 🎓 **B.Tech Mechatronics** — SRM Institute *(CGPA: 9.23/10, 2024)*
- 🏅 **Academic Excellence Award** — SRM IST *(2021, 2022, 2023 — merit scholarship)*
- 🏎️ **Team Captain** — Etros Solareon Racing (Solar-Powered Hybrid EV, 3 years)
- 📜 **NPTEL Certification** — Control Systems Engineering

---

## 📫 Let's Connect

I'm passionate about advancing intelligent control systems and always open to discussions on:
- Advanced Control Systems (MPC, Adaptive Control, Robust Control)
- Reinforcement Learning for Robotics & Autonomous Systems
- Vehicle Dynamics & Motion Planning
- Control-ML Integration & Hybrid Approaches

Feel free to reach out for collaborations, research discussions, or opportunities!

<div align="center">

*"Engineering is the art of making what you want from what you have."*

![Visitor Count](https://komarev.com/ghpvc/?username=TejAmin&color=0078D4&style=flat-square)

</div>
