# [Play](https://Davo0416.github.io/MouseAI/)

# **Description**
A Unity WebGL game made using Unity2D, VSCode and Krita. The games goal is to help the AI mouse that is trained to follow the cheese placed by you to solve puzzles. It features 5 levels increasing in difficulty and utilising gameplay elements like switches, buttons and enemies.

# **How the AI works**
The AI agent was trained using Deep-Reinforcement learning framework provided by the MLAgents package. To analize its suroundings the agent is equiped with ray-vision configured to differentiate the goals and the hazards. After couple hundred iterations of training in the Training Enviroment the agent was ready to be deployed. 
## **Training Enviroment**
![image](https://github.com/user-attachments/assets/4a22280d-1f7a-449a-80d2-92b5298bdd5e)
The training enviroment consisted of 4 walls the AI agent and the goal. Every time the agent collided to the wall it would recieve a penalty and every time it collided with the goal it would recieve a reward. This reward was greater when the agent completed the task faster thus rewarding it for its speed. 

