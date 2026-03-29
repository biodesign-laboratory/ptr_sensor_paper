# ptr_sensor_paper
Analysis and modeling code for paper "Photothermal Recycling Biosensing for Continuous, Sensitive Molecular Quantification"
=======

collision_rate
This Python script models the deposition and collision rate of beads onto the bottom wall of a rectangular microchannel. By processing the channel geometry (width, height, length) and flow rate into SI units, it calculates the mean flow velocity and residence time. The model evaluates the total collision rate by combining two primary mechanisms: Brownian diffusion and gravitational settling.
For diffusion, the script uses the Stokes-Einstein equation to compute bead diffusivity and applies a 1D diffusion-in-a-slab solution to calculate the probability of a bead hitting a wall during transit, assigning half of these collisions to the bottom wall due to symmetry. For gravitational settling, it calculates the Stokes settling speed and the fraction of beads capable of reaching the bottom before exiting the channel. Finally, the script outputs the combined total collision rate on the bottom wall alongside useful dimensionless numbers for further analysis.
>>>>>>> Stashed changes
