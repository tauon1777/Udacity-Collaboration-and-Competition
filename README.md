

# Udacity Collaboration and Competition

### Environment Description

This repository contains code which uses deep deterministic policy gradient to teach two agents to play tennis.


<p align="center">
  <img src="./assets/tennis.png" />
</p>

<p align="center">
Video of 2 agents playing tennis with the Unity ML-Agents Tennis Environment.
</p>



### Setting up the Repository

##### List of Dependencies

Below is the list of requirements.
<ul>
<li> python==3.6.3 </li>
<li> numpy==1.12.1 </li>
<li> matplotlib==2.1.0 </li>
<li> torch==0.4.0 </li>
<li> unityagents==0.4.0 </li>
</ul>

unityagents has been replaced by ml-agents

Can be installed with:
python -m pip install mlagents==0.30.0

##### Installation Procedure
Download the environment from one of the links below. You need only select the environment that matches your operating system:

- Linux: **[click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)**
- Mac OSX: **[click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)**
- Windows (32-bit): **[click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)**
- Windows (64-bit): **[click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)**

Clone this repository using: git clone https://github.com/tauon1777/Udacity-Continuous-Control-Project.git

Place the zip file in the GitHub repository and unzip (or decompress) the file.

The agent should be ready to train.

If needed, additional instructions are located at:

[Udacity Project 2: Continuous Control](https://github.com/udacity/deep-reinforcement-learning/tree/master/p2_continuous-control).

[Udacity Deep Reinforcement Learning Repository](https://github.com/udacity/deep-reinforcement-learning#dependencies).

### Training an Agent

The main function is located in the Continuous_Control.ipynb file. Running the cells in this file will train an agent from scratch. It might be necessary to correct the path to the Reacher environment executable.

The agent trains for 4000 episodes by default, using the same hyperparameters outlined in the report. The performance of the agent should be comparable to the results below.

<p align="center">
  <img src="./assets/DDPG_scores.png" width="600"/>
</p>

The file all_state_dicts.pt contains the saved network weights and optimizer states of a successfully trained agent.
