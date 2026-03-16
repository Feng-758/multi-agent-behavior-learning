# Multi-Agent Behavior Learning

Reinforcement Learning | Multi-Agent Systems | Gridworld Simulation

A multi-agent reinforcement learning system where agents learn cooperative strategies for coordination and collision avoidance in a shared gridworld environment.

This project explores how multiple agents can learn cooperative behaviors through reinforcement learning to complete delivery tasks efficiently while avoiding collisions.

---

## Project Overview

In many real-world applications such as autonomous delivery systems, warehouse robots, and multi-robot coordination, multiple agents must operate in the same environment while avoiding conflicts.

This project implements a **multi-agent reinforcement learning system** where agents learn coordination strategies in a grid-based environment.

Key objectives of the system:

- Learn cooperative policies among multiple agents
- Avoid head-on collisions in shared paths
- Improve task completion efficiency
- Analyze agent behavior through training and evaluation

---

## Key Features

- Multi-agent gridworld simulation
- Reinforcement learning using **Tabular Q-learning**
- Shared policy learning among agents
- Collision avoidance mechanism
- Centralized clock scheduling for deterministic agent execution
- Training and evaluation metrics for system performance

---

## System Design

The system consists of the following components:

### Environment

A gridworld environment where multiple agents navigate between two task locations.

Features:

- Shared environment for all agents
- Collision detection
- Task pickup and delivery
- Reward and penalty mechanisms

---

### Agent

Each agent learns a policy using **Q-learning**.

Agent state includes:

- Current grid position
- Whether the agent is carrying an item
- Relative positions of task locations
- Neighboring agents information

Agents update their policy based on environment feedback and rewards.

---

### Coordination Mechanism

To prevent conflicts between agents, the system includes:

- Collision penalty
- Neighbor awareness
- Centralized update order (Central Clock)

These mechanisms encourage agents to learn **cooperative navigation strategies**.

---

## Training Process

The agents are trained through repeated interactions with the environment.

Training loop:

1. Observe environment state
2. Select action using ε-greedy policy
3. Execute action
4. Receive reward
5. Update Q-table

Over time, agents learn policies that minimize collisions and maximize successful deliveries.

---

## Evaluation

The system evaluates performance using several metrics:

- Delivery success rate
- Number of collisions
- Learning convergence
- Task completion efficiency

Visualization tools are used to analyze training results.

---

## Tech Stack

- Python
- Reinforcement Learning
- Multi-Agent Systems
- Simulation Environment

---

## Repository Structure
