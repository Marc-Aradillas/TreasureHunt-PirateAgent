# CS 370: Pirate Intelligent Agent

## Project Overview

### What Code Was Provided

**Starter Code:**
- `TreasureMaze.py` (the environment/maze logic)  
- `GameExperience.py` (experience replay storage)  
- Partially completed `TreasureHuntGame.ipynb` (project notebook skeleton)

### What Code I Created

**Deep Q-Learning Implementation:**  
I completed the `qtrain` function in the notebook, which includes:

- Initializing hyperparameters (episodes, discount factor, exploration rate, etc.)  
- Building the neural network model for Q-value approximation  
- Implementing the training loop to update the model via experience replay  
- Tracking and printing the training progress (loss, win rate, etc.)

By combining the starter files with my own Q-learning logic, I created a functional pirate agent capable of navigating the maze and reliably finding the treasure.


## Connecting Learning to Computer Science

### What Do Computer Scientists Do and Why Does It Matter?

Computer scientists solve complex real-world problems using **algorithmic thinking** and **programming**. In this project, I focused on **reinforcement learning**, a subfield of AI that teaches an agent to make sequential decisions. This approach is crucial in domains like robotics, game development, and autonomous systems, as it allows software to learn from experience and adapt to new situations.

### How Do I Approach a Problem as a Computer Scientist?

I began by breaking down the problem into smaller components:

1. **State Representation**: Understanding how to represent the maze and the pirate’s location.  
2. **Action Space**: Defining valid movements (up, down, left, right).  
3. **Reward Function**: Determining positive rewards for reaching the treasure, negative rewards for losing, and mild penalties for non-terminating steps.  
4. **Algorithm Selection**: Choosing deep Q-learning with experience replay to handle the state space more effectively.  
5. **Iterative Testing**: Training the agent, tuning hyperparameters, and continuously checking performance.

This systematic approach is central to computer science—breaking big challenges into smaller, testable steps.

### Ethical Responsibilities

As a computer scientist, I have a responsibility to ensure that my solutions:

- **Respect User Well-Being**: For AI systems, that means considering bias, fairness, and transparency in decision-making.  
- **Protect Data and Privacy**: Although not the main focus here, many AI projects handle sensitive user data, so secure data handling is essential.  
- **Promote Safety**: Reinforcement learning agents should not produce harmful or unintended outcomes; thorough testing is crucial.

Even in a game context, these ethical principles remind us to be mindful of user impact and the broader societal implications of AI.

## How to Run

1. *Clone the Repository*

git clone https://github.com/YourUsername/Pirate-Intelligent-Agent.git

2. Open the Notebook

Launch Jupyter Notebook (or JupyterLab) and navigate to TreasureHuntGame.ipynb.

3. Run All Cells

Ensure the environment (maze) is correctly set up.
Observe the agent’s training output in the console.
Feel free to reach out if you have any questions or suggestions for improvement.
Contact: aradillasm@gmail.com

This project was completed as part of CS 370 at Southern New Hampshire University. It demonstrates mastery of reinforcement learning concepts and Python programming for AI.
