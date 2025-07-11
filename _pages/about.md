---
permalink: /
title: "Physics begins in wonder"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<figure>
  <video autoplay muted loop playsinline width="900" controls>
    <source src="https://gominghao.github.io/images/video_background_z3.mp4" type="video/mp4">
  </video>
</figure>

I am Minghao Guo (郭明浩), currently a graduate student at the <a href="https://web.astro.princeton.edu/">Department of Astrophysical Sciences, Princeton University</a>, supervised by Profs. James Stone and Eliot Quataert. I was an undergraduate of <a href="https://www.pku.edu.cn/">Peking Unversity</a>. I am interested in both theoretical and observational astrophysics.

[Get my CV here](https://mh-guo.github.io/CV_Minghao_Guo.pdf)
======

I major in physics with particular interest in astrophysics and broad background in mathematics and computer science. I am interested in a variety of intriguing topics in astronomy and astrophysics, especially black hole astrophysics, galaxy formation, cosmology, gravitational wave and gravity test. I generally use numerical techniques and tools to investigate the abundant phenomenon in various fields in astrophysics. I have experience on doing research involving theoretical, numerical and observational astrophysics, e.g., coevolution between supermassive black holes and host galaxies, black hole accretions as well as modified gravity and the application onto neutron stars.

My research interests include:
- Black holes, high energy astrophysics, accretion disk, general relativistic magnetohydrodynamics (GRMHD)
- Active galactic nuclei (AGN), galaxy formation and evolution, multiphase interstellar medium (ISM)
- Numerical methods and simulations, GPU computing, new numerical techniques
- Neutron stars, pulsars, gravitational waves, modified gravity theory

Research
======
1. Black hole
1. Supernova remnant
1. Multiphase ISM

Black hole accretion and feedback
------

I am currently working on the accretion onto supermassive black hole project, which aims to study the coevolution between supermassive black holes and their host galaxies. The project involves a series of zoom-in simulations that cover the entire range from galaxy formation down to the event horizon of black holes.

<figure>
  <video autoplay muted loop playsinline width="960" controls>
    <source src="https://mh-guo.github.io/assets/amh_proj_all_small.mp4" type="video/mp4">
  </video>
  <figcaption> Zoom-in MHD simulations of black hole accretion from galaxy down to event horizon.</figcaption>
</figure>

<figure>
  <video autoplay muted loop playsinline width="960" controls>
    <source src="https://mh-guo.github.io/assets/Acc_video_render_zoom.mp4" type="video/mp4">
  </video>
  <figcaption> Zoom-in hydrodynamic simulations of black hole accretion from galactic scales.</figcaption>
</figure>

I am currently working on the accretion onto supermassive black hole project, which aims to study the coevolution between supermassive black holes and their host galaxies. The project involves a series of zoom-in simulations that cover the entire range from galaxy formation down to the event horizon of black holes.

Multiscales
------

**Cyclic Zoom**

We present a ``cyclic zoom'' method to capture the dynamics of accretion flows onto black holes across a vast range of spatial and temporal scales in general relativistic magnetohydrodynamic (GRMHD) simulations. In this method, we cyclically zoom out (derefine) and zoom in (refine) the simulation domain while using a central mask region containing a careful treatment of the coarsened fluid variables to preserve the small-scale physics, particularly the magnetic field dynamics. The method can accelerate GRMHD simulations by $\gtrsim 10^5$ times for problems with large scale separation. We demonstrate the validity of the technique using a series of tests, including spherically symmetric Bondi accretion, the Blandford-Znajek monopole, magnetized turbulent Bondi accretion, accretion of a magnetized rotating torus, and the long-term evolution of an accreting torus about both Schwarzschild and Kerr black holes. As applications, we simulate Bondi and rotating torus accretion onto black holes from galactic scales, covering an extremely large dynamic range. In Bondi accretion, the accretion rate is suppressed relative to the Bondi rate by $\sim(10r_\mathrm{g}/r_\mathrm{B})^{1/2}$ with a feedback power of $\sim 0.01 \dot{M} c^2$ for vanishing spin, and $\sim 0.1 \dot{M} c^2$ for spin $a\approx0.9$. In the long-term evolution of a rotating torus, the accretion rate decreases with time as $\dot{M}\propto t^{-2}$ on timescales much longer than the viscous timescale, demonstrating that our method can capture not only quasi-steady problems but also secular evolution. Our new method likewise holds significant promise for applications to many other problems that need to cover vast spatial and temporal scales.


Supernova remnant
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: Phycsis
![Physics](/images/header_image_wallhaven.jpg)

Publications
======


For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
