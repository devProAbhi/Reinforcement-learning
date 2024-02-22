# Reinforcement-learning
Reinforcement learning is a machine learning training method based on rewarding desired behaviors and punishing undesired ones. In general, a reinforcement learning agent -- the entity being trained -- is able to perceive and interpret its environment, take actions and learn through trial and error.

Here in short there is a interaction between Agent which performs action and Environment which give Reward to agent
in chess example, pieces are agent and board is a environment
  
-->>Reinforcement learning elements are as follows:
Policy
Reward function
Value function
Model of the environment

Policy: Policy defines the learning agent behavior for given time period. It is a mapping from perceived states of the environment to actions to be taken when in those states.
```
Policy, Pie(s,a)
Probability(a=a|s=s)
```

Reward function: Reward function is used to define a goal in a reinforcement learning problem.A reward function is a function that provides a numerical score based on the state of the environment
```
Reward, r
r1->r2->r2->r3 ....->rn
```

Value function: Value functions specify what is good in the long run. The value of a state is the total amount of reward an agent can expect to accumulate over the future, starting from that state.
```
Value, V(s)

```

Model of the environment: Models are used for planning.

⚫ Credit assignment problem: Reinforcement learning algorithms learn to generate an internal value for the intermediate states as to how good they are in leading to the goal. The learning decision maker is called the agent. The agent interacts with the environment that includes everything outside the agent. 

The agent has sensors to decide on its state in the environment and takes action that modifies its state.

⚫ The reinforcement learning problem model is an agent continuously interacting with an environment. The agent and the environment interact in a sequence of time steps. At each time step t, the agent receives the state of the environment and a scalar numerical reward for the previous action, and then the agent then selects an action.

Reinforcement learning is a technique for solving Markov decision problems.

⚫ Reinforcement learning uses a formal framework defining the interaction between a learning agent and its environment in terms of states, actions, and rewards. This framework is intended to be a simple way of representing essential features of the artificial intelligence problem.
```
State, s
s1->s2->s2->s3 ....->sn
```

## How Does Reinforcement Learning Work?
Start in a state.
Take an action.
Receive a reward or penalty from the environment.
Observe the new state of the environment.
Update your policy to maximize future rewards.
