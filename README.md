# Uber-Ride-Network-Tree

This Java project is a tool for analyzing a special ride network created daily by Uber. The tool's objective is to determine whether the ride network, represented as a directed graph, meets the criteria of being a tree. Specifically, it checks whether the directed graph has one less edge than the number of vertices, is connected, and contains no cycles.


## Introduction

 Welcome to the Uber Ride Network Tree Validator program! As a software developer at Uber, your task is to determine whether a given directed graph representing the company's ride network can be considered a tree. To be a tree, the graph must satisfy the following conditions:

- It must have one less edge than the number of vertices.
- It must be connected.
- There must be no cycles in the graph.


## Features

- Analysis of a directed graph to determine if it meets the tree criteria.
- Verification of one less edge than the number of vertices, connectivity, and absence of cycles.
- Clear and extensible Java codebase.

## Getting Started

1. Clone this repository to your local machine.

2. Compile and run the Java program using your preferred Java development environment.

3. Follow the prompts to input the necessary parameters and perform the ride network analysis.

## Usage

To use the Uber Ride Network Analysis tool, follow these steps:

1. Run the Java program.

2. Provide input parameters such as the number of vertices, number of edges, and edge information.

3. The program will analyze the directed graph and display whether it meets the tree criteria or not.

## Input Format

You must first enter the number of taxi pickups in the ride network. 

Then you should enter how many taxi rides there are connecting these taxi pickups. 

Finally, you should specify line by line from which taxi pickup to which one can go.

For example, in the first line, it is stated that there is a one-way departure from Çayyolu to Emek.

<img width="844" alt="Screenshot 2023-11-06 at 23 16 48" src="https://github.com/sarparslan/Uber-Ride-Network-Tree/assets/96438389/d4507a41-9caa-4bc0-8b21-6a19f15d02b7">



## Output Format

The output will indicate whether the provided directed graph meets the conditions of being a tree. It will also provide additional information about the analysis, such as whether it has one less edge than the number of vertices, is connected, and whether any cycles are present.

<img width="806" alt="Screenshot 2023-11-06 at 23 17 02" src="https://github.com/sarparslan/Uber-Ride-Network-Tree/assets/96438389/3fa0ea8b-e4af-4b35-be30-529f32214273">