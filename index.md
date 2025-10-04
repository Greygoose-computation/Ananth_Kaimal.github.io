---
layout: page
title: Welcome
permalink: /
---

#Hi, I'm Ananth


# 💻 My Projects

Welcome to my project showcase!  
Here you’ll find stories behind the systems, algorithms, and prototypes I’ve built — from drones and controllers to image recognition and acoustic communication systems.  

I’ve always loved the intersection of **hardware and algorithms** — where a well-tuned control loop or an optimized kernel suddenly brings something *to life*.

---

## 🚀 Model-Based Drone Flight Controller (Cyber-Physical System)

**Tech Stack:** MATLAB, Simulink, FreeRTOS, Embedded C, Simscape, Control Theory  

**GitHub:** [Control_systems_SSY285](https://github.com/Greygoose-computation/Control_systems_SSY285)

This project was part of my coursework in *Model-Based System Design*.  
I developed a **linearized steady-state flight model** of the *Crazyflie 2.0* drone, simulated it in MATLAB/Simscape, and implemented the controller on actual hardware using **FreeRTOS**.

What made it exciting was going full-circle — from system identification → simulation → embedded deployment → validation.  

Key Highlights:
- Designed state-space control loops for flight stability and attitude correction.  
- Used **MATLAB Embedded Coder** to flash control algorithms onto the drone’s MCU.  
- Developed a **memory-safe FreeRTOS firmware**, ensuring deterministic execution and inter-task synchronization using semaphores.  
- Achieved stable hover and trajectory tracking in indoor environments.

> 💡 *Takeaway:* Model-based workflows drastically shorten development cycles when paired with real-time firmware like FreeRTOS.

---

## 🎯 Image Recognition Kernel for Card Game

**Tech Stack:** Python, OpenCV, PyTorch, SIFT/SFT Algorithms, ML Integration  

A fun project that started as an experiment in computer vision — I built an **image recognition kernel** capable of identifying cards in a deck, even when they were *rotated, overlapped, or blurred.*

Key Highlights:
- Implemented a custom **SFT (Scale-invariant Feature Transform)** variant for image matching.  
- Augmented it with a **lightweight ML kernel** to enhance detection under motion blur or partial occlusion.  
- Used OpenCV for feature extraction and PyTorch for model training.  
- Developed a mini “card game” interface to test and visualize recognition performance.

> 💡 *Takeaway:* The project reinforced the power of combining classical vision algorithms with small-scale ML for robustness.

---

## 🔊 Acoustic Communication & Semi-Active Noise Cancelling System

**Tech Stack:** Signal Processing, OFDM, MATLAB, Embedded C  

This project explored **acoustic data transmission** and real-time noise suppression — two systems that at first seem unrelated but share deep DSP foundations.

Key Highlights:
- Designed an **OFDM-based acoustic modem** for near-field data transfer between transceivers.  
- Implemented **semi-active noise cancellation** using adaptive filters and real-time feedback loops.  
- Prototyped the system using MATLAB/Simulink, then deployed filter logic to a microcontroller.  

> 💡 *Takeaway:* Real-world acoustic systems live at the edge of DSP and control — timing precision is everything.

---

## 💧 MIMO Water Tank Control System

**Tech Stack:** MATLAB, Simulink, Linear Control Systems, Hardware-in-the-Loop (HIL)  

A classic control systems experiment that turned into a full MIMO project.  
I developed a **multi-input, multi-output (MIMO)** control setup for a dual-tank water system using multiple control strategies: **PI, LQ, LQI, and LQG controllers**.

Key Highlights:
- Modeled system dynamics and validated state-space equations in MATLAB.  
- Designed controllers in Simulink and tested them using a **HIL setup** connected to physical sensors and actuators.  
- Compared performance metrics (settling time, overshoot, noise immunity) across controller types.

> 💡 *Takeaway:* Seeing your theoretical controller stabilize a *real* system is one of the best feelings as a control engineer.

---

## 🦾 Robotics Hardware Systems @ Peer Robotics

**Roles:** Mechanical Engineer → Senior Engineer → Head of Hardware Design  
**Timeline:** Dec 2019 – July 2023  

Working at Peer Robotics was an incredible journey through robotics product development — from mechanical prototypes to system integration and patents.

### 🧩 Highlights:
- **ROB Mechanism (Patent Pending)** — Designed a palletized shop-floor movement system integrating mechanical and control subsystems.  
- **Coupling System (Patent Granted, No. 515984)** — Co-developed a compact, high-torque coupling for power transmission with <12 arcmin backlash.  
- Led system requirement engineering for auto-charging and payload-lift modules.  
- Established **hardware design and release workflows** for production.  
- Collaborated with supply chain and manufacturing teams to scale hardware delivery.

> 💡 *Takeaway:* Robotics is 10% code, 90% iteration. Every bug teaches you something mechanical, electrical, and human.

---

## ⚙️ Simulation & Modeling Side Projects

### 🧮 Finite Element Analysis (FEA) in MATLAB
Developed a MATLAB-based FEA solver for robotic structural members, validating stress and deflection under payload conditions.  

### 🏎️ Vehicle Dynamics (BAJA Project)
Led suspension design and dynamic simulation for Team Saksham International.  
We secured **10th place** at BAJA California 2019.

---

## 🧠 What I’m Exploring Next

- Real-time embedded ML for robotics  
- Edge computing with ROS2 and microcontrollers  
- Human–machine collaboration and adaptive control systems  

---

## 📬 Let’s Connect

If you’re working on robotics, embedded systems, or control algorithms — I’d love to connect!  

- GitHub: [@Greygoose-computation](https://github.com/Greygoose-computation)  
- LinkedIn: [Ananthakrishnan Girish Kaimal](https://linkedin.com/in/ananthakrishnan-k-235772b2)  
- Email: [specatak30@gmail.com](mailto:specatak30@gmail.com)

---

⭐ *Thanks for reading — if you found something interesting, check out my other repos or drop me a message!*
