# Project1_Matan‑Maor &nbsp;🚗  
**Physics‑Informed Neural Networks for Vehicle Dynamics**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](#license)  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/maorgreshler/Project1_Matan-Maor/blob/main/NN_shared_in_colab.ipynb)

---

## 📜 Abstract
The project investigates how well a pure neural network (Multi‑Layer Perceptron) and a **hybrid model** that fuses an MLP with the kinematic *Ackermann* equations can predict aggressive car‑motion “drift” trajectories.  
Ground‑truth labels come from a high‑fidelity **Single‑Track Drift (STD)** model. Surprisingly, the standalone NN consistently outperforms the physics‑guided variant, indicating that oversimplified physical priors can **hurt** prediction accuracy in highly dynamic regimes.

---

## 🎯 Project Goals
1. **Create datasets** that pair vehicle states ➜ next‑state deltas  
2. **Train & tune**:  
   - *Baseline* MLP  
   - *Physics‑Informed* MLP + Ackermann residuals  
3. **Compare performance** against STD ground‑truth  
4. **Interpret results** and outline next research steps

---

## 📑 How to Cite
If you use this repository, **please cite both our work and the CommonRoad vehicle‑model toolbox**:

```bibtex
@misc{greshler2025project1,
  author       = {Maor Greshler and Matan Bokris},
  title        = {Physics-Informed Neural Networks for Vehicle Dynamics},
  year         = {2025},
  url          = {https://github.com/maorgreshler/Project1_Matan-Maor}
}

@techreport{althoff2020vehicle,
  author       = {Matthias Althoff and Georg Würsching},
  title        = {CommonRoad: Vehicle Models (Version 2020a)},
  institution  = {Technical University of Munich},
  year         = {2020},
  url          = {https://gitlab.lrz.de/tum-cps/commonroad-vehicle-models/-/blob/master/vehicleModels_commonRoad.pdf}
}
```
---

## 🙏 Acknowledgements

- **CommonRoad** for open‑sourcing reference vehicle models and solvers.  
- Our advisor **Yaniv Hasidof** for guidance throughout the project.  
- The Technion Control, Robotics & Machine Learning Laboratory for computational resources.

---

*Built with ❤️ by Maor Greshler & Matan Bokris – Technion ECE, 2025.*
