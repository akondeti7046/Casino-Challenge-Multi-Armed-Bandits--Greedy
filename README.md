
# Casino Challenge — Multi-Armed Bandits & ε-Greedy (Gamified Workshop)

This workshop introduces the **exploration–exploitation trade-off** in **Reinforcement Learning** through a gamified **Multi-Armed Bandit (MAB)** challenge.  
Participants implement ε-greedy strategies, compete for cumulative rewards, and analyze policy behavior in both stationary and non-stationary environments.

The design emphasizes conceptual understanding, hands-on experimentation, and critical reflection, making it suitable for both instructional use and portfolio demonstration.

---

## Overview

The workshop is designed to build strong intuition around decision-making under uncertainty.  
Participants repeatedly choose among multiple actions (bandit arms) with unknown reward distributions and learn how exploration strategies influence long-term outcomes.

Through structured rounds and comparative analysis, the workshop highlights how simple policies can lead to significantly different results depending on environment dynamics.

---

## Learning Objectives

By completing this workshop, participants will be able to:

- Clearly explain the **exploration vs exploitation dilemma**
- Implement **ε-greedy** and **decaying ε-greedy** policies from scratch
- Analyze the effect of different ε values on cumulative reward
- Adapt learning strategies for **non-stationary bandits** using a constant step size (α)
- Interpret reward curves and performance metrics
- Critically reflect on strategic choices and outcomes

---

## Workshop Structure

| Phase | Activity | Description |
|------|----------|-------------|
| 1 | Setup and Introduction | Review MAB concepts, reward structures, and workshop objectives |
| 2 | Round 1 — Stationary Casino | Compete using ε-greedy strategies in a fixed reward environment |
| 3 | Leaderboard and Reflection | Submit results, compare rankings, and discuss strategy effectiveness |
| 4 | Round 2 — Non-Stationary Casino | Adapt policies to drifting reward probabilities using constant α |
| 5 | Final Discussion | Relate bandit learning to real-world systems such as A/B testing, advertising, and recommendation engines |

---

## Gamified Components

### Leaderboards
- Participants submit results to:
  - `submissions_round1.csv`
  - `submissions_round2.csv`
- Rankings are generated based on cumulative reward and consistency

### Performance Categories
- **Efficient Exploiter** — High reward with minimal exploration  
- **Risk Taker** — High exploration with competitive overall performance  
- **Adaptive Strategist** — Strong performance in non-stationary environments  

### Reflection Prompts
Participants are encouraged to analyze:
- Why a specific ε value performed better or worse
- How early exploration impacts long-term reward
- When exploration becomes detrimental
- How bandit strategies relate to real-world decision-making systems

---

## Technical Notes

- Designed to run in **Jupyter Notebook** or **Google Colab**
- Core dependencies:
  - `numpy`
  - `matplotlib`
  - `pandas`
  - `IPython.display`
- Each participant executes experiments locally
- Instructors collect and aggregate leaderboard CSV files for comparison

---

## Files Included

| File | Description |
|------|-------------|
| `Casino_Challenge_MAB_Workshop.ipynb` | Main notebook containing experiments, competition logic, visualizations, and reflection prompts |
| `README.md` | Workshop overview, instructions, and conceptual background |

---

## Instructor Guidance

- Use a fixed random seed (`SEED_ENV`) to ensure fairness across participants
- Do not reveal true reward distributions during competition
- Encourage students to justify strategy choices using observed data
- Promote discussion around trade-offs rather than absolute scores
- Optional extensions:
  - Upper Confidence Bound (UCB)
  - Thompson Sampling
  - Comparison with greedy-only baselines

---

## Educational Context

This workshop serves as a foundational reinforcement learning exercise and acts as a bridge between introductory concepts and advanced algorithms such as Deep Q-Learning and policy-gradient methods.

It is suitable for:
- Undergraduate and postgraduate machine learning courses
- Reinforcement learning labs and tutorials
- Conceptual reinforcement learning demonstrations

---

## Status

- Complete  
- Portfolio-ready  
- Reinforcement Learning fundamentals project  

---

## Student / Author Details

**Name:** Adhitya Kondeti  
**Student ID:** 8997046  
**Course:** CSCN8020 – Reinforcement Learning Programming  
**Program:** Applied Artificial Intelligence & Machine Learning  
**Institution:** Conestoga College  

This workshop was developed and completed as part of academic coursework and is included as a demonstration of reinforcement learning fundamentals, experimental analysis, and instructional design.
```
