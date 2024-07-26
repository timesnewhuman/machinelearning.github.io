<div align="center" style="width: 200px;">
  <h1>Reinforcement Learning</h1>
  <h3>Multi-armed Bandit Problem</h3>
  <h4>Demonstrating the Thompson sampling algorithm for Bayesian inference</h4>
  <img src="https://github.com/timesnewhuman/machinelearning.github.io/blob/main/bayesian_bandit.gif" alt="Alt Text">
</div>

<div>
  <h5>Initialization</h5>
  <p>We define the number of arms, trials, and the true probabilities of winning for each arm. We also initialize the successes and failures for each arm.</p>
  <h5>Bayesian Update</h5>
  <p>We use the Beta distribution to update our beliefs about the probability of reward for each arm based on observed successes and failures.</p>
  <h5>Thompson Sampling</h5>
  <p>We use Thompson Sampling to select which arm to pull by sampling from the current posterior distributions.</p>
  <h5>Plotting</h5>
  <p>We plot the posterior distributions of the probability of reward for each arm at each trial.</p>
</div>
