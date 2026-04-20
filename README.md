# 🧠 Cliff Walking using Reinforcement Learning  

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)   ![Gymnasium](https://img.shields.io/badge/Gymnasium-RL-orange)   ![NumPy](https://img.shields.io/badge/NumPy-Scientific-green?logo=numpy)   ![License](https://img.shields.io/badge/License-MIT-lightgrey)  

---

## 📌 Overview  

This project implements the classic **Cliff Walking Problem** using **Reinforcement Learning (RL)** techniques. It compares **SARSA (on-policy)** and **Q-Learning (off-policy)** to demonstrate differences in learning behavior, risk handling, and policy optimization.

The agent learns to navigate a grid world from a start state to a goal state while avoiding a high-penalty cliff.

---

## 🧩 Problem Statement  

- Grid-based environment  
- Fixed **start** and **goal** positions  
- A “cliff” region with heavy negative reward  
- Objective: Learn an optimal navigation policy  

---
## 🎥 Agent Learning Visualization  

![Cliff Walking RL](https://raw.githubusercontent.com/Ishu335/Cliff-Walking/26ceb24d58ab0908f0f23993ab8fa73d0006cc92/img/cliff_walking_rl.gif)

## 📊 Environment Visualization  

![Cliff Walking](https://upload.wikimedia.org/wikipedia/commons/6/6a/Cliff_Walking_Problem.png)

---

## ⚙️ Algorithms Implemented  

### 🔹 SARSA (On-Policy Learning)  
- Learns from actual actions taken  
- Produces **safer policies**  
- Avoids cliff region  

### 🔹 Q-Learning (Off-Policy Learning)  
- Learns from optimal future actions  
- Produces **optimal but riskier paths**  
- Moves closer to cliff  

---

## 🛠️ Tech Stack  

- **Python**  
- **NumPy**  
- **Gymnasium (CliffWalking-v1)**  

---

## 📂 Project Structure  

```bash
Cliff-Walking/
MODEL /
      │── SARSA.py          # SARSA implementation
      │── Q_learning.py     # Q-Learning implementation
      │── train.py          # Training loop

IMF /
     │── CLIFF_WALKING.GIF          
     │── CLIFF_WALKIING_RL.GIF
│── README.md
