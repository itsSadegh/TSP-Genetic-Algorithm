# TSP-Genetic-Algorithm

TSP Genetic Algorithm Python implementation of a Genetic Algorithm to solve the Traveling Salesman Problem (TSP). Optimizes routes using PMX crossover and inversion mutation.

Overview
This Python project implements a Genetic Algorithm to solve the Traveling Salesman Problem (TSP). It utilizes PMX crossover and inversion mutation to optimize routes.

Usage
Install required libraries:
bash
Copy code
pip install matplotlib
Run the algorithm:
python
Copy code

# Example usage

from genetic_algorithm import genetic_algorithm, init_points

data = [...] # Your dataset here
population_size = 100
generations = 10

points = init_points(data)
genetic_algorithm(points, population_size, generations)
Customization
Adjust parameters like population_size and generations for different results.
Explore and modify PMX crossover and inversion mutation functions in genetic_algorithm.py for further optimization.
License
This project is licensed under the MIT License - see the LICENSE file for details.
