[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/AQnCFVmX)
# Homework 5: Solid Waste Management and Stochastic Optimization

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This is the repository for Homework 5 for [BEE 4750](https://viveks.me/environmental-systems-analysis), taught at [Cornell University](https://cornell.edu) in Fall 2024 by [Vivek Srikrishnan](https://viveks.me).

If enrolled in the class, a PDF of the completed notebook, **with all cells evaluated**, should be submitted to Gradescope *no later* than Thursday, December 4, 2025, at 9:00pm. 10% will be deducted for each day that the notebook is late.

## Learning Objectives

After completing this lab, students will be able to:

* formulate a mixed-integer linear program for a solid waste management problem with operational decisions;
* interpret the solution to this program to provide insight into what facilities to operate;
* visualize the solution results as a network of waste flows;
* draw a scenario tree;
* formulate a two-stage stochastic optimization problem given a discrete set of uncertainties.

## Repository Overview

The repository consists of the following files:

- `hw05.ipynb`: Jupyter Notebook for the homework assignment. Students should create code or Markdown blocks as necessary to answer questions. **This is the only file you should need to edit.**
- `Project.toml`, `Manifest.toml`: Julia environment files. These should just work, but feel free to add other packages as needed using the `Pkg` package manager. **This is the only other file that you might end up making changes to, though you should do this using `Pkg`, not directly.**
- `hw05.qmd`: Source file for Jupyter notebook generation. You shouldn't need to or want to touch this; everything is in the `.ipynb` file.
- `data/`: This folder contains data file(s) for the problems.
- `LICENSE`: This material is licensed using the MIT license. You can ignore this for working on the problem set.
- `README.md`: This file. You shouldn't need to touch this.
- `.gitignore`: This tells `git` what files to ignore. You shouldn't need to touch this.
- `.github/`: This folder contains workflow files which generate the notebook. Again, you shouldn't need to touch this.

## Dependencies

This notebook was written using Julia 1.11.5, and depends on the following packages:

- `JuMP.jl`
- `HiGHS.jl`
- `DataFrames.jl`
- `GraphRecipes.jl`
- `Plots.jl`
- `Measures.jl`
- `CSV.jl`

