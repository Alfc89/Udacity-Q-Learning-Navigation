# Report
## Learning Algorithm
[]: # (The report clearly describes the learning algorithm, along with the chosen hyperparameters. It also describes the model architectures for any neural networks.)
The learning algorithm is a deep Q-learning algorithm, similar to the one described in the [DeepMind paper](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf).

The base of the algorithm (and of its name) is the Temporal-Difference Method called Q-Learning (or Sarsamax). It takes an initial state, applies an action according to an $\epsilon$-greedy policy

The code has three main parts:
* The Q-Network
* The Agent
* The Replay Buffer 


### The Q-Network: Model Architecture

### Hyperparameters chosen


## Plot of Rewards
[]: # (A plot of rewards per episode is included to illustrate that the agent is able to receive an average reward (over 100 episodes) of at least +13. The submission reports the number of episodes needed to solve the environment.)

## Ideas for Future Work
