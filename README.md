# reinforcement-learning
A repository intended to explain the course of reinforcement learning through relatable analogies, systems and practice use to help base-case users implement it into their own work. 


Core elements that you need to understand with RL: 

1. Agent -> The decision-maker 
2. Environment -> The system that the agent interacts with 
3. State (s) -> The current condition of the environment 
4. Action (a) -> The decision made by the agent 
5. Reward (r) -> Feedback signal measuring the success or failiure of an action 


Core principles to understand within RL: 

1. Markov Decision Process (MDP)
2. Policy (pi) 
3. Cumulative Reward (Return)
4. Exploration vs Exploitation  
5. Value Function 


To begin:

-> Python is generally the main programming language that is used in the developing of RL systems and design 
1. Generally used for its ability to allow the user to rapidly prototype utilize its strong ecosystem of machine learning tools and libraries 

-> C++ can be used for optimizing systems while maintaining objectives such as max speed and low-latency performance
1. Will be seen in products involving robotics and/or high-frequency systems 

-> Rust is noticeably more adopted in the context of RL when we are working on performance-critical systems and fast environment interfacing


Core Frameworks
1. 






FAQ 

1. What is the difference between Reinforcement learning, Unsupervised Learning and Supervised Learning machine learning?

Supervised learning allows you to define both the input and output layers such as when an algorithm is supposed to identify a hand as an image or not if you were to feed it a bunch of random images. 

SL algorithms tend to learn patterns and relationships between inputs and outputs, then it is expected for the model predict an output based on the input data provided. The type of data that is fed into this algorithm is labeled data typically done by a human in a training set.

On the other hand, RL has a defined end goal in achieving the highest award it possibly can through the sequence of actions. RL does not have a prior knowledge base or dataset to work with rather, the result is time-based instead of being a single prediction. It maps inputs with possible outcomes and by rewarding the desired behaviours, you provide more weight to the best outcomes. 



