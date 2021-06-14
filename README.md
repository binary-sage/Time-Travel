# Time-Travel
## Introduction
In this project, we are creating a custom environment. The environment is trivial and provides an agent with defined rules and design of a “game”. Here we have starting and ending points. The aim of the AI is to get to the end and with the help of Reinforcement Learning, possibly go several decisions back and improve its performance. What we eventually want to imitate is how the human thinks when making decisions from the experiences based on the reward signal. As might be expected, our model will be designed with the help of a rewarding system, which means there will be a reward score for the agent with every decision it makes. This will be a measure of how much the AI is motivated to make a similar decision. All of the methods and models will be described in the following sections.

## Method
* Reinforcement learning
* PPO
* LSTM
* Actor-critic

## Enviroment
The enviroment is based on the following github. We are using gym-minigrid for the project.
https://github.com/utnnproject/gym-minigrid

## Custom enviroment
We made our own custom enviroment for using time-travel. In the customs.py file, we defined our simple enviroment for the project.

<p align="center">
<img src="image_2021-06-11_11-15-53.png" width=250>
</p>
## Time-Travel
We used a method called time-travel to make the agent learn more efficient. By using time-travel, agent now has a option to go back few frames before to the current frame and change decisions to reach the end point more efficiently.
## Result of Time-Travel

## References
<a id="1">[1]</a> 
https://github.com/DLR-RM/stable-baselines3

<a id="2">[2]</a> 
https://github.com/DLR-RM/rl-baselines3-zoo

<a id="3">[3]</a> 
https://github.com/lcswillems/rl-starter-files

<a id="4">[4]</a> 
https://github.com/lcswillems/torch-ac
