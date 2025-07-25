---
title: 'Cyclic Zoom'
date: 2025-07-08
permalink: /posts/2025/07/cyclic-zoom/
tags:
  - cycle of life
  - numerical method
  - GRMHD
---

What is the question?
======

The challenge of simulating accretion and feedback from SMBHs to galactic scales is the vast range of spatial and temporal scales. To tackle this problem, we repeatedly zoom out (derefine) and zoom in (refine) the simulation domain, which we denote as the ''cyclic zoom'' method. The spatial resolution is correspondingly decreased (increased) when we zoom out (in) using AMR to alleviate the time step constraints while keeping the same relative resolution $$\Delta x/x$$ for the region of interest. A mask region in the center is used to preserve the small-scale physics. 
The cyclic zoom method in a spacetime diagram behaves like a ''$$\Lambda$$-cycle'' in the spacetime diagram (or ''V-cycle'', depending on what we choose as the starting point of the simulation). A complete simulation typically consists of tens to hundreds of $$\Lambda$$-cycles.
