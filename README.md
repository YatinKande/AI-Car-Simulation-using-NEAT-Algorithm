AI Car Simulation using NEAT Algorithm 🏎️
===
This project focuses on simulating and optimizing self-driving cars using NeuroEvolution of Augmenting Topologies (NEAT). The goal is to develop reinforcement learning strategies for cars to navigate complex tracks autonomously while avoiding obstacles. The model evolves through generations to enhance decision-making and adaptability.
## Features
- This project applies NEAT to evolve neural networks via reinforcement learning.

- It includes an obstacle avoidance system using five sensors for real-time data collection.

- Car performance is assessed through a fitness function that tracks collision-free navigation.

- Genetic algorithms help cars evolve by optimizing decision-making over generations.

## Prerequisites

Before running the project, ensure you have Python installed on your system (Python 3.6 or later is recommended).

## Install & Dependence
- pygmes
- python-neat

## Use
- Navigate to the project directory:
  ```
  cd ai-car-simulation/
  ```
- Run the main Python file to start the simulation:
  ```
  python main.py
  ```

## Directory Hierarchy
```
|—— assets
|    |—— Maps
|    |—— Car
|—— csvdata
|    |—— CSV files
|    |—— Data Conversion
|—— main.py
|—— config.txt
```
## Code Details

### Tested Platform

- software
  ```
  OS: macOS (MacBook Pro M4 Pro)
  Python: 3.12.7(anaconda)
  pygmes: 1.9.5
  ```
- hardware
  ```
  CPU: Apple M4 Pro (12-core)
  GPU: Apple M4 Pro GPU (18-core)
  ```
## Video Demonstration
![Watch the video](https://drive.google.com/file/d/1oiag7NzsZJismlO4Z_CMTzZ-nXDf9ZfG/view?usp=share_link)

## License

This project is licensed under the MIT License. See the LICENSE file for details.
