# Multi-Agent Cooperative Delivery System

This repository presents an experimental multi-agent reinforcement learning system developed independently during my studies at Monash University.

The project investigates how multiple agents can learn cooperative delivery behaviors in a constrained gridworld environment using a shared Q-learning policy.  
Agents must coordinate their movements while avoiding head-on collisions and navigating limited space efficiently.

The environment simulates a simplified logistics-style task where agents repeatedly transport items between two locations while sharing the same workspace.  
This setting provides a compact testbed for studying decentralized coordination and conflict avoidance in multi-agent systems.

---

## Key Features

- Multi-agent gridworld environment for cooperative task execution  
- Shared Q-table reinforcement learning policy  
- Collision-aware action selection strategy  
- Adaptive exploration scheduling during training  
- Quantitative evaluation through reward and collision statistics

---

## System Components

### Environment
A custom gridworld simulator that models constrained movement, shared space, and delivery objectives.

### Agents
Multiple agents interact within the environment and share a common Q-learning policy while learning coordinated navigation strategies.

### Learning Method
Tabular Q-learning with reward shaping and exploration scheduling to balance exploration and policy stability.

### Evaluation
Training progress is analyzed through reward trends, delivery success rates, and collision statistics.

---

## Demo

The full implementation and experiment workflow can be explored in the notebook:

`multi_agent_behavior_learning.ipynb`

The notebook contains environment construction, training procedures, evaluation experiments, and visualization of learning outcomes.
