# Pirate Intelligent Agent – Portfolio 
## Overview
This project focused on developing an intelligent agent for a treasure hunt game, where the agent represents a pirate competing against the player to find treasure. The agent had to navigate a maze-based environment and make decisions that increased its likelihood of reaching the treasure before the player. This project applied reinforcement learning and neural network concepts to create an adaptive and goal-oriented non-player character (NPC).

## Work Completed
For this project, I was given starter code that defined the maze environment (TreasureMaze) and provided a basic framework for the agent’s training loop. I created and extended code for the Q-learning implementation, including the training function (qtrain), the reward structure, and the integration of a neural network model to approximate Q-values. Additionally, I experimented with hyperparameters such as the exploration factor (epsilon), learning rate, and discount factor to balance exploration and exploitation. These adjustments allowed the agent to learn optimal strategies over time.

## Connection to Computer Science
This project highlights how reinforcement learning and neural networks can be applied to solve real-world problems. In the larger field of computer science, projects like this demonstrate how algorithms can be used to create intelligent systems that adapt and improve from experience. Beyond games, reinforcement learning is applied to robotics, healthcare, finance, and other industries where decision-making under uncertainty is crucial.

## What Computer Scientists Do and Why It Matters
Computer scientists design and develop solutions to complex problems by applying computational thinking, algorithms, and data structures. Their work powers everything from artificial intelligence to secure communication systems, shaping how society interacts with technology. This matters because their solutions often influence efficiency, accessibility, and even ethical decision-making in daily life.

## My Problem-Solving Approach as a Computer Scientist
As a computer scientist, I approach problems by breaking them down into smaller, manageable components. I start with analyzing the environment and constraints, then design algorithms that can operate within those boundaries. In this project, for example, I decomposed the problem into defining states, actions, and rewards, then applied reinforcement learning to iteratively improve the agent’s behavior. I rely on experimentation, testing, and iteration to refine solutions.

## Ethical Responsibilities
Ethics play an important role in computer science. As a developer, I have responsibilities both to the end user and to the organization I work for. To the end user, I must ensure that systems are reliable, secure, and do not exploit or harm. To the organization, I must develop solutions that align with ethical business practices and comply with regulations. In AI, this includes considering fairness, transparency, and avoiding unintended biases in algorithms. For the pirate agent project, while the stakes are low in a game, these same principles apply to larger, real-world AI systems.

## Setup Instructions
### Prerequisites
* Python 3.8+
* Jupyter Notebook or JupyterLab
* Recommended package manager: pip or conda
Installation
1. Clone the repository:
```
git clone https://github.com/mubeenkh4u/cs370-pirate-agent.git
cd cs370-pirate-agent
```
2. Create and activate a virtual environment (recommended):
```
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```
3. Install dependencies:
```
pip install -r requirements.txt
```
(If no requirements.txt is provided, manually install common libraries:)
```
pip install numpy matplotlib keras tensorflow jupyter
```

### Running the Notebook
1. Launch Jupyter Notebook:
```
jupyter notebook
```
3. Open the file:
```
PirateAgent.ipynb
```
3. Run all cells to train and test the pirate agent in the treasure maze environment.

## Testing & Evaluation Tools
* Matplotlib: Used for visualizing training progress and win-rate history.
* Keras / TensorFlow: Used for implementing the neural network model for Q-learning.
* Jupyter Notebook: Used as the main environment for interactive development and testing.

### Results
Through training, the pirate agent demonstrated the ability to learn an optimal policy for navigating the maze.
* **Win Rate Improvement:** The agent’s success rate increased steadily across epochs, showing clear reinforcement learning convergence.
* **Exploration vs. Exploitation:** Early in training, random exploration led to inconsistent results, but as epsilon decreased, the agent relied more on learned strategies.
