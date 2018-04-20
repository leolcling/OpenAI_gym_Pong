# Neuroevolution - Genetic Algorithms on OpenAI Gym 

#### Environment:

> In the game of Pong, the policy could take the pixels of the screen and compute the probability of moving the player’s paddle Up or Down.(https://blog.openai.com/evolution-strategies/)




#### Action:
Action 0 & 1 makes the racket stay

Action 2 & 4 makes the racket go up

Action 3 & 5 makes the racket go down



## Genetic Algorithms

#### Requirement
- numpy: 1.14.0
- Keras: 2.1.1
- gym:   0.9.5
- Python 3


Run Genetic_main.py to start training the agent. We recommend increasing the population to get better result. 

```bash
python Genetic_main.py
```

## DQN

### How to run the programs:

#### Environment Requirement
-   Tensorflow:  1.2.1
-   gym:         0.9.5
-   Python:      2.7


#### Deep Q-Learning (DQN)

Our DQN agent can be ran from the ./dqn directory. You can run it by using the command:

```bash
python main.py --env_name=Pong-v0 --is_train=True --display=True
```


This will run the program on the Pong environment with Training Mode and Rendering
turned on.

### Acknowledgement:

The code for our DQN approach is the existing code from devisers.
The original repository can be found [here](https://github.com/yashbhutwala/pong-ai/tree/master/dqn)


### Reference:
Mnih, Volodymyr, Kavukcuoglu, Koray, Silver, David, Rusu, Andrei A, Veness, Joel, Bellemare, Marc G, Graves, Alex, Riedmiller, Martin, Fidjeland, Andreas K, Ostrovski, Georg, et al. Human-level control through deep reinforcement learning. Nature, 518(7540):529– 533, 2015.

https://github.com/erilyth/Flappy-Bird-Genetic-Algorithms

https://github.com/mkturkcan/Keras-Pong/blob/master/keras_pong.py

https://blog.coast.ai/lets-evolve-a-neural-network-with-a-genetic-algorithm-code-included-8809bece164



