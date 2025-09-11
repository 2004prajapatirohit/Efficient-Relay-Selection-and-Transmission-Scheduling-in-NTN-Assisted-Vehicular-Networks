# Efficient Relay Selection and Transmission Scheduling in Non-Terrestrial Assisted Vehicular Networks

This repository contains the implementation and simulations from the paper **“Efficient Relay Selection and Transmission Scheduling in Non-Terrestrial Assisted Vehicular Networks.”**  
The project introduces a **hybrid vehicular communication framework** that integrates **Vehicle-to-Vehicle (V2V)** links, **UAV-assisted relays**, and **LEO satellite fallback** to ensure robust, low-latency, and high-throughput connectivity in dynamic environments.

---

## 🚗 Overview
Millimeter-wave (mmWave) communication provides high data rates for vehicular networks but suffers from frequent blockages due to:
- **Large buildings & urban structures**
- **Adverse weather conditions**
- **UAV limitations (battery, range, regulations)**
- **Line-of-sight (LoS) issues in V2V**

To address these challenges, we propose:
- A **three-layer communication framework** (V2V + UAV + Satellite).
- **Reinforcement learning-based optimization** for relay selection and transmission scheduling.
- **Satellite fallback mechanisms** to maintain reliable communication under failures.

---

## 🔑 Key Contributions
- Designed and implemented a **hybrid vehicular communication framework** integrating V2V, UAV-assisted relays, and LEO satellite fallback.  
- Optimized **relay selection and transmission scheduling** using reinforcement learning (DQN, PPO), significantly reducing latency and improving throughput compared to traditional methods like TDMA and JRDS.  
- Incorporated **LEO satellite fallback mechanisms** to maintain seamless communication when V2V and UAV links are obstructed due to **large buildings, adverse weather, UAV range/battery issues, or LoS failures**.  
- Conducted **extensive simulations** on a two-lane highway scenario, demonstrating up to **7.5% higher throughput** and **6.27% fewer time slots** with PPO compared to baseline methods.

---

## 📊 Results
- **PPO-based scheduling** achieved near-optimal performance with:
  - Up to **206.8 Gbps average throughput**  
  - Up to **91.4% reduction in best-case transmission time**  
- **UAV relays** improved coverage and reduced delays.  
- **Satellite fallback** ensured full data delivery when terrestrial and aerial links failed.  

---

## 🛠️ Technologies & Methods
- **Reinforcement Learning (RL):** Deep Q-Networks (DQN), Proximal Policy Optimization (PPO)  
- **Constraint Programming (CP)** for validation  
- **Dynamic Scheduling** for efficient time-slot allocation  
- **Simulation Framework:** Vehicular mobility models, UAV deployment, and LEO satellite links  

---

