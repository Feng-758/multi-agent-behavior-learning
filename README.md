# Multi-Agent Cooperative Delivery System

This project implements a multi-agent reinforcement learning system
where agents learn cooperative delivery behaviors in a constrained gridworld environment.

The system demonstrates:

• decentralized decision making  
• shared policy learning  
• collision avoidance strategies  
• cooperative task execution  

The environment simulates a logistics-style delivery task,
which can be interpreted as a simplified agent coordination problem.

---

## Key Components

Environment  
Gridworld simulation with constrained movement and delivery objectives.

Agents  
Multiple agents share a Q-learning policy and must coordinate to avoid collisions.

Learning  
Tabular Q-learning with exploration scheduling and reward shaping.

Evaluation  
Training reward trends and collision statistics visualization.

---

## Demo

The full experiment and visualization are available in:

`multi_agent_behavior_learning.ipynb`
