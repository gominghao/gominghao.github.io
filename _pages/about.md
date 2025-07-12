---
permalink: /
# title: "Welcome!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<figure>
  <video autoplay muted loop playsinline width="960" controls>
    <source src="https://gominghao.github.io/images/video_background_z3.mp4" type="video/mp4">
  </video>
</figure>

Welcome! I am Minghao Guo (郭明浩), currently a graduate student at the <a href="https://web.astro.princeton.edu/">Department of Astrophysical Sciences, Princeton University</a>, supervised by Profs. [James Stone](https://www.ias.edu/scholars/stone) and [Eliot Quataert](https://www.astro.princeton.edu/~quataert/). I was an undergraduate of <a href="https://www.pku.edu.cn/">Peking Unversity</a>. I am interested in theoretical, numerical, and observational astrophysics.

[Find my CV here](https://mh-guo.github.io/CV_Minghao_Guo.pdf)
======

I major in physics with particular interest in astrophysics and broad background in mathematics and computer science. I am interested in a variety of intriguing topics in astronomy and astrophysics, especially black hole astrophysics, galaxy formation, cosmology, gravitational wave and gravity test. I generally use numerical techniques and tools to investigate the abundant phenomenon in various fields in astrophysics. I have experience on doing research involving theoretical, numerical and observational astrophysics, e.g., coevolution between supermassive black holes and host galaxies, black hole accretions as well as modified gravity and the application onto neutron stars.

My research interests include:
- Black holes, high energy astrophysics, accretion disk, general relativistic magnetohydrodynamics (GRMHD)
- Active galactic nuclei (AGN), galaxy formation and evolution, multiphase interstellar medium (ISM)
- Numerical methods and simulations, GPU computing, new numerical techniques
- Neutron stars, pulsars, gravitational waves, modified gravity theory

Publications
======
Check out my papers at [ADS](https://ui.adsabs.harvard.edu/search/filter_database_fq_database=AND&filter_database_fq_database=database%3A%22astronomy%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq_database=(database%3A%22astronomy%22)&p_=0&q=%3Dauthor%3A%22Guo%2C%20Minghao%22&sort=date%20desc%2C%20bibcode%20desc) and [Google Scholar]({{site.author.googlescholar}})


Research
======

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

We present a ``cyclic zoom'' method to capture the dynamics of accretion flows onto black holes across a vast range of spatial and temporal scales in general relativistic magnetohydrodynamic (GRMHD) simulations. In this method, we cyclically zoom out (derefine) and zoom in (refine) the simulation domain while using a central mask region containing a careful treatment of the coarsened fluid variables to preserve the small-scale physics, particularly the magnetic field dynamics. The method can accelerate GRMHD simulations by $$\gtrsim 10^5$$ times for problems with large scale separation. We demonstrate the validity of the technique using a series of tests, including spherically symmetric Bondi accretion, the Blandford-Znajek monopole, magnetized turbulent Bondi accretion, accretion of a magnetized rotating torus, and the long-term evolution of an accreting torus about both Schwarzschild and Kerr black holes. As applications, we simulate Bondi and rotating torus accretion onto black holes from galactic scales, covering an extremely large dynamic range. In Bondi accretion, the accretion rate is suppressed relative to the Bondi rate by $$\sim(10r_\mathrm{g}/r_\mathrm{B})^{1/2}$$ with a feedback power of $$\sim 0.01 \dot{M} c^2$$ for vanishing spin, and $$\sim 0.1 \dot{M} c^2$$ for spin $$a\approx0.9$$. In the long-term evolution of a rotating torus, the accretion rate decreases with time as $$\dot{M}\propto t^{-2}$$ on timescales much longer than the viscous timescale, demonstrating that our method can capture not only quasi-steady problems but also secular evolution. Our new method likewise holds significant promise for applications to many other problems that need to cover vast spatial and temporal scales.


Supernova remnant
------
We investigate the evolution of supernova remnants (SNRs) in a two-phase cloudy medium by performing a series of high-resolution (up to $$\Delta x\approx0.01\,\mathrm{pc}$$), 3D hydrodynamical simulations including radiative cooling and thermal conduction. We aim to reach a resolution that directly captures the shock-cloud interactions for the majority of the clouds initialized by the saturation of thermal instability. In comparison to the SNR in a uniform medium with the volume filling warm medium, the SNR expands similarly (following $$\propto t^{2/5}$$) but sweeps up more mass as the cold clouds contribute before shocks in the warm medium become radiative. However, the SNR in a cloudy medium continuously loses energy after shocks toward the cold clouds cool, resulting in less hot gas mass, thermal energy, and terminal momentum. Thermal conduction has little effect on the dynamics of the SNR but smooths the morphology and modifies the internal structure by increasing the density of hot gas by a factor of $$\sim 3-5$$. The simulation results are not fully consistent with many previous 1D models describing the SNR in a cloudy medium including a mass loading term. By direct measurement in the simulations, we find that, apart from the mass source, the energy sink is also important with a spatially flat cooling rate $$\dot{e}\propto t^{-11/5}$$. As an illustration, we show an example 1D model including both mass source and energy sink terms (in addition to the radiative cooling in the volume filling component) that better describes the structure of the simulated SNR.

Can one stand before the void, embraced by nature, and not ask why?
------
![Physics](/images/header_image_wallhaven.jpg)
