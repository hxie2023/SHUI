---
layout: page
title: About
permalink: /about/
---

<style>
.justify-text {
    text-align: justify;
    text-justify: inter-word;
    line-height: 1.6;
}
.justify-text h1, 
.justify-text h2, 
.justify-text h3, 
.justify-text h4, 
.justify-text h5, 
.justify-text h6 {
    text-align: left;
}
</style>

<div class="justify-text">

1. Parallel computation for both the land surface grid and river network through OpenMP, with spatial discretization parallelization for the land surface grid and spatiotemporal coupling hierarchical parallelization for the river network, significantly improving computational efficiency on multi-core systems; 
2. Deep integration with NetCDF file operation capabilities, providing flexible model driving methods (by gauge or grid data, in cold or warm start modes) and efficient multi-variable, multi-dimensional data read/write management functions; 
3. Consideration of the dynamic combination and transition between saturation and infiltration-excess runoff mechanisms, which, compared to many hydrological models, offers clearer physical mechanisms and strong applicability.

</div>