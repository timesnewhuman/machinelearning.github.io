# Reinforcement Learning

### Multi-armed Bandit Problem

#### Demonstrating the Thompson sampling algorithm for Bayesian inference

![Alt Text](https://github.com/timesnewhuman/machinelearning.github.io/blob/main/bayesian_bandit.gif)

##### Initialization

We define the number of arms, trials, and the true probabilities of winning for each arm. We also initialize the successes and failures for each arm.

##### Bayesian Update

We use the Beta distribution to update our beliefs about the probability of reward for each arm based on observed successes and failures.

##### Thompson Sampling

We use Thompson Sampling to select which arm to pull by sampling from the current posterior distributions.

##### Plotting

We plot the posterior distributions of the probability of reward for each arm at each trial.
