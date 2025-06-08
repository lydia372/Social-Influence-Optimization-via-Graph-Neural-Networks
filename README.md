# 🗳️ Social Influence Optimization via Graph Neural Networks(CNN)

This project models how voter preferences evolve over time in a social network, based on influence from friends who share common hobbies. It simulates voting behavior, tests influencer strategies, and analyzes network influence using spectral graph theory.

> **Author**: Liu Yichuan  
> **Institution**: National University of Singapore (NUS)  

---

## 📌 Overview

The project aims to explore how individual opinions in a social network stabilize through peer influence. It includes:

- Construction of a social graph based on shared hobbies
- Simulation of vote stabilization over multiple days
- Testing of influencer-based intervention strategies
- Identification of the most influential nodes using spectral analysis

---

## 🛠 Technologies Used

- **Python** (Jupyter Notebook)
- **NetworkX** – graph modeling
- **NumPy, Pandas** – data processing
- **Matplotlib** – visualization
- **Spectral Graph Theory** – influence scoring

---

## 🧪 Key Scenarios & Findings

### 1. **Initial Voting Outcome (No Influence)**
- Party-A: 2010 voters  
- Party-B: 1986 voters  
- Neutral: 4 voters  
- Stabilization in: 3 days

### 2. **With Two Influencers (Party-B)**
- Party-A: 1970  
- Party-B: 2029  
- Neutral: 1  
- Stabilization in: 3 days

### 3. **Targeted Influencer Strategy (Party-A)**
- Best Hobby-Type: `hobby_movie` of Type 3  
- Party-A: 3669  
- Party-B: 331  
- Neutral: 0  
- Stabilization in: 1 day

### 4. **Top 10 Influential Voters**
- Identified using spectral influence score from Laplacian eigen-decomposition

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `A0292159W_LiuYichuan_BT3017.ipynb` | Full Jupyter notebook with code, simulation, and visualizations |
| `BT3107 Project Report_LiuYichuan.pdf` | Summary report outlining methodology and results |
| `README.md` | Project documentation |

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/voter-influence-simulation.git
   cd voter-influence-simulation
