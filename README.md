Experiment: 2D Transient Heat Conduction using Finite Difference Method
Overview:

This experiment focuses on solving the two-dimensional transient heat conduction equation on a 1 m × 1 m square plate using the finite difference method (FDM) in MATLAB. The objective is to analyze how heat propagates over time from a localized high-temperature region and how the system evolves toward thermal equilibrium.

Methodology:

The plate is discretized into a uniform grid in both x and y directions
Explicit finite difference scheme applied:
Time derivative approximated using forward difference
Spatial derivatives approximated using central difference
Initial condition:
Central node assigned a high temperature
All other nodes initialized at 0°C

Boundary conditions:
All edges of the plate maintained at 0°C
Iterative update equation used to compute temperature at each node based on neighboring nodes
Stability condition (Fourier number) maintained to ensure convergence
Simulation carried out over multiple time steps until temperature distribution stabilizes

Results:
Heat diffusion observed radially outward from the central hot node
Temperature gradients reduced progressively over time
Peak temperature decreased as heat spread across the plate
System gradually approached steady-state with near-uniform temperature
Results demonstrated both spatial and temporal evolution of heat transfer
Verified effectiveness of FDM in solving 2D transient heat conduction problems
