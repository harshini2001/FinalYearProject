# **Route Planning Model for Multi-agent system for a supply chain Management** #
- Factor influencing :
    - Energy use
    - Time
    - Waste
    - Traffic Safety
    - Health (of goods and humans)
    - Economic health
- Objectives:


 ![image](https://user-images.githubusercontent.com/54399043/132229735-6abb21c8-4a90-40d3-affc-bef64d631b6f.png)

- For each factor, an agent is considered.
    - For traffic - *Traffic Load Estimation Agent (TLEA)*. Result is used by Trip Time Estimation Agent.
    - For Weather, *Weather Condition Estimation Agent*.
    - For road type, *Type of Road Agent*.
    - For safety, *Safety of Road Agent*.
    - For route distance and vehicle speed, *Trip Time Estimation Agent **(TTEA)***. This agent receives info from all other agents and calculates **real route rate**



![image](https://user-images.githubusercontent.com/54399043/132229564-1281b33a-a33e-4457-8bd4-3c80cc45c850.png)

- Goal of TTEA:
    - Receive origin and desti from vehicle.
    - Find Primary path
    - Adjust trip plan to satisfy obj
    - Propose path info using Google maps
    - Calculate route rate
    - Propose path info and route rate to RPS algo
    - Receive optimal path

- Algorithms used: *DRP Algorithm and MAS Algorithm*
