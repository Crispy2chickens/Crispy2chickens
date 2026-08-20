# Hi, I'm Jolie 👋

**AI & Embedded Engineer · Stanford**

Most of my work has been on the AI side: agentic RAG pipelines, custom vision models, and the web stack that let users interact with them. Recently, I explored embedded systems and worked with firmware and sensors. I'll work at whatever layer a project needs. I learn fast, and when I'm given a task I've never done before, I'll figure it out. I'm always open to collaborating.

---

### Projects

#### Project Centinela

AI platform that generates custom, runnable Jupyter notebooks for conservation orgs from satellite imagery requests. I built the planner and coder agents: a two-stage RAG pipeline that retrieves relevant cells from a curated Planet Labs notebook library, then uses Claude to assemble them into a coherent, variable-normalized notebook grounded in real APIs. The planner runs per-step retrieval in parallel (notebook search + Planet docs) across all workflow steps. Also wired the Next.js frontend to Convex and implemented the edit mode of the chat sidebar (one of its two modes, alongside Q&A), which lets users revise the workflow live.

<a href="https://planet-agent.vercel.app/" target="_blank">Live demo →</a>

---

#### Laser Guitar

A guitar with six laser beams instead of strings, running bare metal on a MangoPi MQ-Pro (RISC-V) for Stanford's CS107E. Break a beam and the note rings out over I2S while the neck lights up with a traveling LED wave. Built with Angelisa Wang, who owned the circuit layout and the LED and rotary modules. I owned the audio: a plucked-string synth with harmonics and decay. Polyphony is also supported, which needed double buffering and fixed-point math. I also laser-cut the body, 3D-printed the sensor housings, and ported the firmware synth into a browser demo (Three.js + AudioWorklet).

<a href="https://laser-guitar.vercel.app/" target="_blank">Live demo →</a>

---

#### Handwritten Chinese Character Recognition (HCCR)

Custom **ResNet101** and **DenseNet121** with CBAM and SE attention modules, trained on the CASIA HWDB1.1 dataset (200 classes).

- 96.2% test accuracy with DenseNet121
- CBAM cut convergence time by ~30% for DenseNet but hurt ResNet — interesting architecture-dependent tradeoff
- Full preprocessing pipeline + GUI for real-time handwriting inference

<a href="https://hccr-gui.vercel.app/" target="_blank">Live demo →</a>

---

### Tech stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-%23283272.svg?style=for-the-badge&logo=riscv&logoColor=white)
![SQL](https://img.shields.io/badge/sql-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/next.js-black?style=for-the-badge&logo=next.js&logoColor=white)
![Three.js](https://img.shields.io/badge/three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![WebGL](https://img.shields.io/badge/webgl-%23990000.svg?style=for-the-badge&logo=webgl&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase&logoColor=white)
![Convex](https://img.shields.io/badge/convex-%23F3694C.svg?style=for-the-badge&logo=convex&logoColor=white)
![Linux](https://img.shields.io/badge/linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black)

---

### Contact

jteo0814@gmail.com
