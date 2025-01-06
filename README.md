# Planet Simulation: A Python Mini-Project

## Project Overview
This project is a Python-based simulation of a planetary system that visualizes the orbits of planets around the Sun. The project leverages Object-Oriented Programming (OOP) concepts, simulating gravitational interactions and orbital mechanics using the Pygame library.

## Features
- **Object-Oriented Design**: Each planet is represented as an object with attributes like position, velocity, and mass.
- **Realistic Physics**: Implements gravitational force calculations to simulate orbital mechanics.
- **Interactive Visualization**: Uses Pygame to display planet orbits and their dynamic positions in real-time.

## Files Included
- **`planet_simulation.ipynb`**: The main Python script containing the simulation code.

## Prerequisites
- Python 3.x
- Required libraries:
  - Pygame
  - Math (standard library)

## Installation
1. Install Python 3.x from [python.org](https://www.python.org/).
2. Install the required library using pip:
   ```bash
   pip install pygame
   ```

## How to Run
1. Save the script as `planet_simulation.ipynb`.
2. Open a terminal and navigate to the directory containing the script.
3. Run the script:

## Simulation Details
- **Astronomical Units (AU)**: Distances are scaled to pixels for visualization (1 AU = 149.6 million km).
- **Time Steps**: The simulation advances in 1-day increments to animate orbits realistically.
- **Planets Included**:
  - Sun
  - Earth
  - Mars
  - Mercury
  - Venus

## Key OOP Concepts Demonstrated
1. **Class Definition**:
   - The `Planet` class encapsulates all attributes and behaviors of a planet, such as position, velocity, and gravitational force calculation.
2. **Encapsulation**:
   - Attributes like mass and velocity are encapsulated within the `Planet` class.
3. **Inheritance and Modularity**:
   - The modular design allows easy addition of new planets or celestial objects.
4. **Polymorphism**:
   - Methods like `draw` and `update_position` adapt to each planet instance.

## Potential Enhancements
- Add user interactivity, such as the ability to add or remove planets.
- Include more celestial bodies like moons or asteroids.
- Enhance physics with relativistic effects or advanced gravitational algorithms.

