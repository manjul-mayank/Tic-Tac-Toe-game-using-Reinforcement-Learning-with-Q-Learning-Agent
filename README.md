## Question:
- You need to construct a Tic-T ac-T oe game using reinforcement learning, either in Python or another programming language of your choice. Within this task, your goal is to develop a Q learning agent that gains proficiency in the game through experimentation, making moves, and obtaining rewards or penalties based on whether those moves result in a victory, defeat, or tie. You are permitted to utilise standard libraries like T ensorFlow, Keras, pandas, numpy, and similar tools. To be clear and precise your code should have following.

- components: Establishing the ecosystem/environment, Outlining the Tic-T ac-T oe gameplay, Constructing the reinforcement learning framework, Conducting model training, Evaluating the model.

- DO REMEMBER : The agent should employ the Q-learning algorithm to acquire the best strategy for every combination of state and action.

# 🤖 Tic-Tac-Toe Game using Reinforcement Learning

This project implements a reinforcement learning (RL) agent that learns to play the classic Tic-Tac-Toe game. It uses a simple value-based approach to learn optimal moves through self-play. The project is implemented in Python using Jupyter Notebook and provides a great foundation for understanding basic RL concepts.

---

## 🎯 Project Goals

- Build an agent that learns optimal Tic-Tac-Toe strategies through self-play.
- Compare performance of the RL agent against human or random players.
- Visualize value functions and game outcomes.

---

## 🧠 What You’ll Learn

- Basics of reinforcement learning through a tabular value update method.
- How game environments can be framed as a Markov Decision Process (MDP).
- Strategy evaluation by simulating thousands of games.
- Concepts like exploration, exploitation, and value iteration.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- NumPy
- Matplotlib (for visualizations)

### Installation

Clone the repository:
```bash
git clone https://github.com/your-username/tic-tac-toe-rl.git
cd tic-tac-toe-rl
pip install numpy matplotlib notebook
jupyter notebook "Tic-Tac-Toe game using reinforcement learning.ipynb"
📂 Project Structure
📦 tic-tac-toe-rl
├── Tic-Tac-Toe game using reinforcement learning.ipynb
├── README.md
└── results/
```
## 🕹️ How the Game Works
- The game consists of two agents:

 - Player 1 (Agent A): Learns via reinforcement learning.

 - Player 2 (Agent B): Can either be a random agent or another RL agent.
## Key Concepts
- State Space: All possible board configurations.

- Value Function: Estimated probability of winning from a given state.

- Exploration vs Exploitation: Controlled by epsilon-greedy policy.

- Learning: Updates the value of each state based on the reward received at the end of each game.

## Training Loop
- Initialize state-value dictionaries.

- Simulate thousands of games between the two players.

- Update value functions based on game outcomes.

- Save final value functions and use them for policy evaluation.
## The RL agent improves over time and consistently outperforms a random agent.

- Final value functions show high probabilities for optimal board configurations.

- Win rates improve as the number of training episodes increases.

* Visualizations:

 - Value function plots

 - Win/draw/loss stats over games

## 🛠️ Future Improvements
- Train with Q-learning or Deep Q Networks (DQN).

- Create a GUI to allow human players to play against the agent.

- Extend to other board sizes or variants like Connect Four.
## 📜 License
This project is open-source and available under the MIT License.
## 🙏 Acknowledgements
- Inspired by classical RL examples in Sutton & Barto’s book Reinforcement Learning: An Introduction.

- Based on tabular value-function approximation methods.
## Author
- Manjul Mayank

