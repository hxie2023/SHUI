---
# Just the Docs 
layout: default
title: Preface
nav_order: 1 
---

<div class="justify-text" markdown = "1">
# Preface

This is a website describing the theories, methods, and implementation of the Simulator of catchment Hydrology and nUtrients Interactions (SHUI).
1. Parallel computation for both the land surface grid and river network through OpenMP, with spatial discretization parallelization for the land surface grid and spatiotemporal coupling hierarchical parallelization for the river network, significantly improving computational efficiency on multi-core systems; 
2. Deep integration with NetCDF file operation capabilities, providing flexible model driving methods (by gauge or grid data, in cold or warm start modes) and efficient multi-variable, multi-dimensional data read/write management functions; 
3. Consideration of the dynamic combination and transition between saturation and infiltration-excess runoff mechanisms, which, compared to many hydrological models, offers clearer physical mechanisms and strong applicability.
</div>