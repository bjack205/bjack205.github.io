---
layout: page
title: Code
permalink: /code/
---

As a roboticist and researcher, I am passionate about writing good code and contributing to the robotics and academic community by releasing my code open-source. Below are some of the packages I've
personally developed. While Julia is my perferred language for scientific computing, I am also comfortable with Python and C++.

# Trajectory Optimization
As part of my research in the Robotic Exploration Lab, I have written and now maintain the state-of-the-art packages for trajectory optimization in Julia. This consists of a set of a suite of packages that are registered with the Julia package manager and are written to offer a convenient API and extensible programming paradigm. 

* [RobotDynamics.jl](https://github.com/RoboticExplorationLab/RobotDynamics.jl): The package dedicted to setting up dynamic models. Includes methods for handling 3D rotations (for floating-base sysgtems). 
* [TrajectoryOptimization.jl](https://github.com/RoboticExplorationLab/TrajectoryOptimization.jl): The "core" trajectory optimization package. Essentially a domain-specific language for setting up, defining, and evaluating trajectory optimization problems. Solving these problem definitions is left up to individual solver packages.
* [Altro.jl](https://github.com/RoboticExplorationLab/ALTRO.jl): A state-of-the-art trajectory optimization solver that uses Differential Dynamic Programming with an augmented Lagrangian, coupled with an active-set direct method for solution polishing. Natively handles 3D rotations and second-order cone constraints.
* [RobotZoo.jl](https://github.com/RoboticExplorationLab/RobotZoo.jl): A collection of canonical robot models, defined using RobotDynamics.jl.
* [TrajOptPlots](https://github.com/RoboticExplorationLab/TrajOptPlots.jl): A set of methods for conveniently visualizing robots (for those defined in RobotZoo) and trajectories. Builds off the excellent [MeshCat.jl](https://github.com/rdeits/MeshCat.jl).

# Other
* [Mavlink.jl](https://github.com/bjack205/Mavlink.jl): (in progress) A wrapper for the Mavlink communication protocol in Julia.
* [OpenXY](https://github.com/BYU-MicrostructureOfMaterials/OpenXY): The package I worked on for my undergraduate research. I didn't write the core algorithms, but help improve the implementation and the user interface.

# Why Julia?
<img src="{{ site.baseurl }}/assets/julialogo.png" title="julialogo" class="profile">
I started using Julia in 2018 while at Stanford, and am now a big believer in what the language has to offer. After attending JuliaCon 2019, I was drawn in by the extremely friendly and helpful community. As a language, I love that Julia is easy (and fun) to develop, with a host of excellent packages for scientific computing that are easy to install and easy to use (the documentation in the Julia community is generally very good). On top of offering all the best syntax and ease of development as Python and Matlab, it's crazy fast! For instance, ALTRO beats highly optimized and efficient optimization solvers written in C, C++, or Fortran. All together, it makes writing peformant optimization solvers much easier, and makes a lot of sense for researchers that need to develop ideas quickly but still demonstrate compelling performance.
