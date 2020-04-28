# Report 

## Structure of the used network

## Baseline Evaluation
To evaluate the performance of the agents we performed a baseline test at the beginning of the project and run the environment N=100 times with random uniformly distributed actions. Below diagram shows the distribution with its mean and standard deviation from this experiment. Assuming that yellow bananas with reward +1 and blue bananas with reward -1 are evenly distributed in the environment it is reasonable that average score for such an agent is approximately 0.
![](distribution_random_agent.png)

## Learning Algorithm
We utilized an agent with a fully connected neural network with two hidden layers of size 128 and 64, respectively. Each layer is followed by a relu-function.

### Hyperparameters
The following hyperparameters were used throughout.

| Hyperparameter     | Value  |
|--------------------|--------|
| eps_start          | 1.0    |
| eps_end            | 0.01   |
| eps_decay          | 0.995  |
| Replay Buffer Size | 100000 |
| Gamma              | 0.99   |
| Learning Rate      | 0.0005 |
| Tau                | 0.001  |
| Update Rate        | 4      |
|--------------------|--------|



## Results

### DDQN
![](distribution_ddqn_agent.png)