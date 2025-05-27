An implementation of the Double Deep Q Network as described in the 2015 Google Deepmind paper: [Deep Reinforcement Learning with Double Q-learning](https://arxiv.org/pdf/1509.06461)

Applied to the bipedal walker environment by discretizing the action space into letting each of the 4 joints move at min speed, 0 speed, or max speed for a total of 3^4 = 81 unique actions per state.

![Alt Text](trainingLogs/generation.gif)
