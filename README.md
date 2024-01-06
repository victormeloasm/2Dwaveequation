# 2D Wave Equation Simulation in Python

This repository, **2Dwaveequation**, houses a Python implementation of a 2D wave equation simulation named **2Dwave.py**. The simulation leverages the Pygame library to visualize the behavior of waves generated by a water droplet impacting the surface.

## Table of Contents
1. [Introduction](#introduction)
2. [Wave Equation Overview](#wave-equation-overview)
3. [Simulation Details](#simulation-details)
4. [Dependencies](#dependencies)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Customization](#customization)
8. [License](#license)
9. [Acknowledgments](#acknowledgments)

## Introduction

Understanding wave propagation is fundamental across various scientific and engineering disciplines. The wave equation serves as a powerful mathematical tool to describe the dynamics of waves over time and space. This simulation aims to provide a visual representation of wave behavior for educational and exploratory purposes.

![Wave simulation](wave1.jpg)

![Wave simulation](wave2.jpg)

## Wave Equation Overview

The 2D wave equation is expressed as:

![Wave Equation](equation1.jpg)

where:
- \(u\) represents the wave function,
- \(t\) denotes time,
- \(x\) and \(y\) are spatial coordinates,
- \(c\) is the wave velocity.

![Wave Equation](equation2.jpg)

## Simulation Details

The Python simulation utilizes the Pygame library to create a graphical representation of the 2D wave equation. Key features include:
- Initiation of water droplet impact to kickstart the wave generation.
- Time-dependent propagation of waves.
- Implementation of absorbing boundary conditions to minimize wave reflections.
- Visualization of wave dynamics with color-coded intensity.

## Dependencies

Ensure that you have the following dependencies installed:

- Python 3.x
- Pygame

You can install Pygame using:

```bash
pip install pygame
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your_username/2Dwaveequation.git
cd 2Dwaveequation
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the simulation script:

```bash
python 2Dwave.py
```

The simulation window will open, displaying the evolving wave patterns based on the specified conditions.

## Customization

Feel free to explore and modify the simulation by adjusting parameters, such as wave velocity, spatial and temporal steps, and initial conditions within the **2Dwave.py** script.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special gratitude to the Pygame development team for providing an efficient framework to create graphical simulations in Python.

Contributions, issue reports, and suggestions for improvement are welcome. Enjoy exploring the world of wave equations!
