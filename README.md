# Reproducing Images Using Genetic Algorithm

Genetic Algorithms (GAs) are a class of algorithms which are based on the natural process of evolution. They can be applied to problems where the search space is too large for exhaustive search algorithms to work efficiently. For instance GAs have been applied to find optimal paths for the Travelling Salesman Problem. In essence they are a search heuristic which allow the algorithm to move towards a defined optimal. GAs are inspired by the process of evolution in nature.

In this repo, we build a genetic algorithm that takes an image as an input and reproduces the image using geometric shapes such as circles, rectangles and lines. The algorithm starts with a few shapes on a canvas, as the starting population, then iteratively it does the following:

1. Compute the fitness of the population
2. Select the fittest
3. Create the next generation (while adding mutations)

This is the very essence of a genetic algorithm.

Here is a visualization of one the runs of the algorithm.
![The Evolving Incredibles Logo](visualizations/incredibles.gif)


By Ivan Hladkyi, Denys Kolomiiets, Tejas Anil Shah for the course **Algorithmics (MTAT.03.238)** at the University of Tartu.

Based on code by [Azad Yasar](https://github.com/azadyasar/AI)