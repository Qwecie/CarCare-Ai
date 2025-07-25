# Crude Distillation Column Optimization with PPO

This project applies Proximal Policy Optimization (PPO) to control a simulated crude oil distillation column using a custom OpenAI Gym environment.

## Features

- Model-free control of reboiler duty and reflux ratio
- Comparison with PID controller baseline
- Visual evaluation of energy use and product yield
- Report included: "Reinforcement Learning in Crude Distillation Column"

## File Overview

- `CDU_Opt.ipynb`: PPO training and evaluation
- `crude_env.py`: Environment implementation
- `Reinforcement Learning in Crude Distillation Column.docx`: Final project report
- `checkpoints/`: Trained PPO model files
- `PPO vs PID.png`: Evaluation results

## Results

- PPO agent achieves target top fraction (~0.4) and minimizes reboiler duty
- PID fails to meet specification and saturates reflux
- PPO reward ~−90.2 after 500k timesteps

## Citation

If you use this work, please cite:

> Lagede, A. G. (2025). Reinforcement Learning in Crude Distillation Column. [GitHub Repository](https://github.com/Qwecie/CrudeDistillation-RL)

