# Reinforcement-learning
Reinforcement learning is a machine learning training method based on rewarding desired behaviors and punishing undesired ones. In general, a reinforcement learning agent -- the entity being trained -- is able to perceive and interpret its environment, take actions and learn through trial and error.

Here in short there is a interaction between Agent which performs action and Environment which give Reward to agent
in chess example, pieces are agent and board is a environment
  
# -->>Reinforcement learning elements are as follows:
Policy
Reward function
Value function
Model of the environment

# Terminologies used in Reinforcement Learning
Terminologies in RL - Techvidvan, reinforcement learning
Terminologies in RL – Techvidvan
Agent – is the sole decision-maker and learner

Environment – a physical world where an agent learns and decides the actions to be performed

Action – a list of action which an agent can perform

State – the current situation of the agent in the environment

Reward – For each selected action by agent, the environment gives a reward. It’s usually a scalar value and nothing but feedback from the environment

Policy – the agent prepares strategy(decision-making) to map situations to actions.

Value Function – The value of state shows up the reward achieved starting from the state until the policy is executed

Model – Every RL agent doesn’t use a model of its environment. The agent’s view maps state-action pairs probability distributions over the states

# Reinforcement Learning Workflow

– Create the Environment

– Define the reward

– Create the agent

– Train and validate the agent

– Deploy the policy


# Characteristics of Reinforcement Learning
– No supervision, only a real value or reward signal

– Decision making is sequential

– Time plays a major role in reinforcement problems

– Feedback isn’t prompt but delayed

– The following data it receives is determined by the agent’s actions


# Reinforcement Learning Algorithms
There are 3 approaches to implement reinforcement learning algorithms

Value-Based – The main goal of this method is to maximize a value function. Here, an agent through a policy expects a long-term return of the current states.

Policy-Based – In policy-based, you enable to come up with a strategy that helps to gain maximum rewards in the future through possible actions performed in each state. Two types of policy-based methods are deterministic and stochastic.

Model-Based – In this method, we need to create a virtual model for the agent to help in learning to perform in each specific environment
