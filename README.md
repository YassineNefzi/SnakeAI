<h1 align="center">SnakeAI</h1>

![PerroAI](https://github.com/YassineNefzi/SnakeAI/blob/main/snakeai.jfif)


This project implements a reinforcement learning model trained to play the classic Snake game. It's inspired by a tutorial from freeCodeCamp which can be found [here.](https://www.youtube.com/watch?v=L8ypSXwyBds)

## About the Project
This project explores the application of reinforcement learning to control an agent in a simple environment. The agent (the snake) learns through trial and error to maximize its reward (eating food) and avoid punishment (hitting walls or itself).

## Getting Started
### Clone Repository
```bash
git clone git clone https://github.com/YassineNefzi/SnakeAI.git
```
### Install dependencies
```bash
pip install -r requirements.txt
```
### Run
```bash
python agent.py
```
## Project Structure
- **game.py:** This file defines the Snake game environment, including game logic and reward calculation.
- **model.py:** This file implements the neural network and the training loop (Deep Q Learning).
- **agent.py:** This file implements the reinforcement learning agent.
- **plot.py:** This file contains a plotting function used to display the training steps of our agent.

## Usage 
Upon running the agent.py file, two windows will open :
- The first window will contain the snake game, the agent (the snake) will begin to move and discover the environment on its own.
- The second window will display some plots which will display the score and the mean score.

Note that it will take some time (≈ 5 to 10 minutes) for the agent to start getting high scores.

## Contact
For any inquires please contact : ynyassine7@gmail.com
