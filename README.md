# Portfolio-Optimization using Deep Q(n) Learning approach
Stock Market Portfolio Optimization provides the weights to the stock by using Reinforcement Learning using the historical data of the stocks selected and the data fetched from Yahoo Finance.
In the reinforcement learning based framework defined for this problem, the algorithm determines the optimal portfolio allocation depending upon the current state of the portfolio of instruments.

The algorithm is trained using Deep QLearning framework and the components of the reinforcement learning environment are:

Agent: Portfolio manager, robo advisor or an individual.

Action: Assignment and rebalancing the portfolio weights. The DQN model provides the Q-values which is further converted into portfolio weights.

Reward function: Sharpe ratio, which consists of the standard deviation as the risk assessment measure is used reward function.

State: The state is the correlation matrix of the instruments based on a specific time window. The correlation matrix is a suitable state variable for the portfolio allocation, as it contains the information about the relationships between different instruments and can be useful in performing portfolio allocation.
