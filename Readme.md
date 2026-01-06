# 🐍 AI Snake Game – Reinforcement Learning with Python, PyTorch & Pygame

This project is inspired by the [FreeCodeCamp course](https://www.youtube.com/watch?v=L8ypSXwyBds) **"Python + PyTorch + Pygame Reinforcement Learning – Train an AI to Play Snake"**, with some of my own improvements and tweaks.

The application runs a **Snake game in real time** and uses **reinforcement learning** to train an AI agent to play. Within just **10 minutes of training**, the agent can consistently achieve **10 points**, and with more training it continues to improve.

---

## 🛠️ Installation

Clone the repository and install dependencies:

```bash
conda create -n pygame_env python=3.7
conda activate pygame_env
pip install pygame
pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cpu
pip install matplotlib ipython
python3 ./main.py
```

## 🚀 Features

- Real-time Snake game built with **Pygame**.
- AI agent powered by **PyTorch** reinforcement learning.
- Training loop that improves performance over time.
- Achieves competitive scores quickly (10 points in ~10 minutes).
- Modular codebase for easy experimentation and extension.

---

### Just execute:

```bash
python main.py
```
