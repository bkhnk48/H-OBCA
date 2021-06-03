# H-OBCA
**How to run the Parking code:
**First steps
Change to the directory

  Install Julia from https://julialang.org/downloads/ (code tested on version 0.5.1 and 0.6.0)

  Open Julia in terminal

  Install Julia package JuMP using Pkg.add("JuMP")

  Install Julia package Ipopt using Pkg.add("Ipopt")

  Install Julia package PyPlot using Pkg.add("PyPlot")

  Install Julia package NearestNeighbors using Pkg.add("NearestNeighbors")

  Install Julia package ControlSystems using Pkg.add("ControlSystems")

**Running the parking example
  Start Julia in terminal

  Type in terminal: include("setup.jl")

  Type in terminal: include("main.jl")

**modifying the code**
  To play with start points, change x0 in main.jl and run the code by: include("main.jl")

  If you change anything in one of the collision avoidance problems, you need to activate the changes by running: include("setup.jl")

  If you change the size of the car in main.jl, the change also need to be made in collision_check.jl

**Note**
  this code has been tested on Julia 0.5.1 and 0.6.0, and might not run on any other Julia versions

  For best results, run code in Julia terminal
