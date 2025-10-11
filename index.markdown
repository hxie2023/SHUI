---
# layout: default
title: SHUI Book - Home
# hide_from_sidebar: true 
nav_exclude: true 
---

<div class="justify-text">
# Welcome to the Book of SHUI!

SHUI is short for Simulator of catchment Hydrology and nUtrients Interactions. It is a distributed, mechanism-based model for simulating the hydrological cycle, sediments, nutrients, and other contaminants transport processes at the catchment scale. It is a component of the Lake-Catchment Simulator (LCS). SHUI is developed on the Linux operating system and is compiled using GNU GFortran. It dynamically links to the NetCDF library to manage reading and writing operations for .nc format files. It also implements multi-threaded parallel computation through the OpenMP interface. The 1.1 version of the model runs at the daily time step, performs multi-level division and nested calculations of the catchment. Vertically, it divides the land surface grid into canopy, land surface, soil, and aquifer layers. Within each grid cell, it calculates the movement of water and solutes vertically, and laterally simulates runoff and related solutes mobilization. 
The features of this model version include: 
1. Parallel computation for both the land surface grid and river network through OpenMP, with spatial discretization parallelization for the land surface grid and spatiotemporal coupling hierarchical parallelization for the river network, significantly improving computational efficiency on multi-core systems; 
2. Deep integration with NetCDF file operation capabilities, providing flexible model driving methods (by gauge or grid data, in cold or warm start modes) and efficient multi-variable, multi-dimensional data read/write management functions; 
3. Consideration of the dynamic combination and transition between saturation and infiltration-excess runoff mechanisms, which, compared to many hydrological models, offers clearer physical mechanisms and strong applicability.
</div>