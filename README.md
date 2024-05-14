# Flappy Bird with NEAT

This project implements a Flappy Bird game that uses the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to evolve a neural network to play the game. The goal is to demonstrate how machine learning can be used to create an AI that learns to play Flappy Bird.

## Project Structure

- **assets/**: Contains the images used in the game.
  - `base.png`: Image for the base of the game.
  - `bg.png`: Background image.
  - `bird1.png`, `bird2.png`, `bird3.png`: Images for the bird animation.
  - `pipe.png`: Image for the pipes.
- **classes/**: Contains the game object classes.
  - `base.py`: Contains the `Base` class that handles the moving ground.
  - `bird.py`: Contains the `Bird` class that handles the bird's movements and actions.
  - `pipe.py`: Contains the `Pipe` class that handles the pipes' positions and collisions.
- **flappy_bird.py**: Main script to run the game and NEAT algorithm.
- **custom_statistics.py**: Contains the `Statistics` class for recording and plotting fitness data.
- **config-feedforward.txt**: Configuration file for the NEAT algorithm.

## Requirements

- Python 3.7 or higher
- Pygame
- NEAT-Python
- Matplotlib
