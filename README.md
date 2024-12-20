# RL-for-WPT

## TD3-INVASE: Efficient and Interpretable Causal Reinforcement Learning

### Twin Delayed Deep Deterministic Policy Gradient (TD3) 
It is a state-of-the-art reinforcement learning algorithm designed for continuous action spaces. TD3 addresses the overestimation bias inherent in its predecessor, DDPG, by introducing two key improvements: (1) learning with two Q-networks to minimize value overestimation and (2) delaying policy updates to stabilize training. These enhancements make TD3 a robust choice for high-dimensional control tasks.

### Instance-wise Variable Selection using Neural Networks (INVASE)
It is a feature selection algorithm that dynamically identifies the most relevant input features for each decision instance. By employing a selector network and a predictor network, INVASE optimizes the balance between selecting essential features and maximizing prediction accuracy, enhancing interpretability in machine learning models.

### IC-INVASE (TD3 + INVASE) 
This integrates TD3 with INVASE to advance causal reinforcement learning. By selecting the most relevant state variables at each decision point, IC-INVASE focuses on causal relationships within the environment, improving both learning efficiency and decision-making. This approach ensures that the agent generalizes better to new scenarios while maintaining interpretability in feature selection, making it ideal for applications where understanding feature relevance is critical.

### In WPT or SWIPT Scenario
In wireless power transfer (WPT) or simultaneous wireless information and power transfer (SWIPT) scenarios, accurately predicting harvested energy is crucial for optimizing system efficiency and ensuring reliable performance. The TD3-INVASE algorithm offers a powerful framework for improving such predictions by selectively focusing on the most relevant state variables, such as channel conditions, transmitted power, and environmental factors. By leveraging instance-wise variable selection, TD3-INVASE can identify the causal relationships between these factors and the harvested energy, enabling more precise and interpretable models. This approach not only enhances energy prediction accuracy but also facilitates adaptive decision-making in dynamic environments, making it invaluable for applications like energy-efficient IoT networks, wireless sensor nodes, and smart grid systems.
