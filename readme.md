# Reinforcement learning on snake-game

## What is this repo?
This repo inspired by patrick loeber's snake game reinforcement learning. This repo simply covers fundamentals of reinforcement learning e.g. bellman equation, Q-value neural net. Currently the agent can not realize Its body, this issue will be handled soon. 

As you can see, after almost 100 games, it can achieve scores of 30s event 40s. However the big issue is the state structure does not include snake's own body coordinates. This issue will be handled in the future versions, I guess :P.
![My Image](figure_1.png)
  
## How to run?
Once you have installed requirements, it enought to write `python agent.py` terminal in project folder. 

## Requirements
All the requirements included in `requirements.txt`. you can install libraries via pip such as: `pip install -r requirements.txt`