# Markovian-Decision-Process in Bipedal Locomotion
*This was done as part of the term project for the course Stochastic Processes (MA41017)*

*Team members: Prasanna Paithankar(21CS30065), Somya Kumar(21CS30050), Bratin Mondal(21CS10016), Swarnabh Mandal(21CS10068), Harsh Sharma(21CS30023)*

*Instructor: Prof.Nitin Gupta*

### Introduction
This project explores the application of Markov processes in modeling environmental feedback for agents involved in bipedal locomotion. The goal is to understand how humans and robots can make near-optimal decisions by learning from previous actions and outcomes.

### Framework
The agent, a legged robot or a learning toddler, performs actions that impact environmental parameters. The transition function is represented by a transition probability matrix (TPM), and a reward function is defined to be maximized in the long run. The agent learns to take actions that lead to higher cumulative rewards and aims to maximize the value function.

### Modelling the Interaction & Learning
Rewards in bipedal locomotion are based on orientation and goal-reaching behavior. Higher rewards are given for maintaining an upright position while moving, while sideways or upside-down positions receive heavy penalties. The action space is infinite, depending on the robot's degrees of freedom, and the state space consists of spatial coordinates.

### Solving MDPs
To solve the Markov Decision Process (MDP), the project utilizes the Bellman equations to find the optimal policy and action space. Exact or approximate solutions can be obtained using dynamic programming, iterative methods, Monte Carlo simulation, or Temporal Difference learning algorithms.

### Conclusion
Reinforcement learning offers a means to make decisions through continual learning, enabling better control agents in complex environments. This approach benefits robotics and provides insights into human decision-making processes.

#### References
[1] Sutton, R. S., & Barto, A. G. (2018). Reinforcement Learning: An Introduction.</br>
[2] Xie, Z., Berseth, G., Clary, P., Hurst, J., & Panne, M. (2018). Feedback Control For Cassie With Deep 
Reinforcement Learning.</br>
[3] Fakoor, M., Kosari, A., & Jafarzadeh, M. (2016). Humanoid robot path planning with fuzzy Markov Decision processes.</br>
[4] Shi, Y., Li, S., Guo, M., Yang, Y., Xia, D., & Luo, X. (2021). Structural Design, Simulation, and Experiment of Quadruped Robot.
