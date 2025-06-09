# Stanford CS234 Assignment 1

This repository contains the implementation for Assignment 1 of Stanford's CS234: Reinforcement Learning. This project implements **Policy Iteration** and **Value Iteration** algorithms for solving the FrozenLake environment using OpenAI Gym. It supports both deterministic and stochastic environments.


## 🚀 Setup Instructions

### 1. Create and activate a virtual environment

On macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```
On Windows:

```bash
python -m venv venv
venv\Scripts\activate
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```

## ▶️ Run the Code

Run the following script to execute value and policy iteration:
```bash
python vi_and_pi.py
```


## ✅ Expected Output
```bash
-------------------------
Beginning Policy Iteration
-------------------------

...

Episode reward: 1.000000


-------------------------
Beginning Value Iteration
-------------------------

...

Episode reward: 1.000000
```

During the process, you should see an intelligent path from Start (S) to Goal (G), avoiding holes (H). If the agent is stepping into holes, something’s wrong. If you see Episode reward: 1.0 repeatedly, that means the agent successfully reaches the goal every time.
