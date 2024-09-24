# [Play](https://Davo0416.github.io/MouseAI/)

# **Description**
A Unity WebGL game made using Unity2D, VSCode and Krita. The games goal is to help the AI mouse that is trained to follow the cheese placed by you to solve puzzles. It features 5 levels increasing in difficulty and utilising gameplay elements like switches, buttons and enemies.

# **How the AI works**
The AI agent was trained using the deep reinforcement learning framework provided by the MLAgents package. To analyze its surroundings, the agent is equipped with ray-vision configured to differentiate the goals and the hazards. After a couple hundred iterations of training in the training environment, the agent was ready to be deployed.
## **Training Enviroment**
![image](https://github.com/user-attachments/assets/4a22280d-1f7a-449a-80d2-92b5298bdd5e)
The training environment consisted of 4 walls, the AI agent and the goal. Every time the agent collided with the wall it would receive a penalty, and every time it collided with the goal it would receive a reward. This reward was greater when the agent completed the task faster, thus rewarding it for its speed. A time limit was also added to encourage the agent to move instead of doing nothing or moving in circles.

