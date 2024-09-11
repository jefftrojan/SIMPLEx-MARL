# SIMPLEx-MARL

n this project, I created a simple 5x5 grid world environment, where two agents learn to navigate the grid using Q-learning. The goal of each agent is to reach the bottom-right corner of the grid (the goal state) while maximizing its reward. Both agents act independently and learn through interacting with the environment.

The agents receive feedback (rewards) based on their actions. Over time, they learn to navigate the grid more efficiently by improving their policies (set of actions to take from a given state).



### Environment
- A 5x5 grid represents the world.
- Two agents are placed randomly in the grid.
- Agents can move up, down, left, or right in the grid.
- The goal of the agents is to reach the bottom-right corner of the grid.
- The environment is visualized using Matplotlib.

### Agents
- The agents use Q-learning, a model-free reinforcement learning algorithm, to learn how to navigate the grid.
- Each agent maintains a Q-table, which stores the expected rewards for taking certain actions in each state (position in the grid).
- Agents make decisions using a balance of exploration (trying random actions) and exploitation (choosing the best-known action).

### Visualization
- The environment is visualized in real-time using Matplotlib.
- The grid is displayed with different colors for the two agents and their positions are updated as they move.
