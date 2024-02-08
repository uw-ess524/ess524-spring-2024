* Atmosphere or ocean dynamics
  - The ozone photochemistry example from Dale Durran's book
  - The Lorenz attractor because we practically have to
  - The rotating shallow water equations, if the fates smile upon us
  - A moist energy balance model, see Gerard's 2015 paper or Flannery 1984
* Hydrology
  - Saturated porous media = the diffusion equation.
  - Unsaturated porous media = the diffusion equation but with the diffusivity proportional to the hydraulic head, making it degenerate and thus have finite propagation speed
  - Overland drainage is another degenerate diffusion equation but with advection too
* Hillslopes
  - Early models of hillslope diffusion = the diffusion equation.
  - Later models (see Roering's work) are the heat equation with a slope-dependent diffusion coefficient.
  - Even later models add mad weirdness (see Perron).
* Seismology
  - Do the wave equation but with damping in part of the earth's interior?
  - Burridge-Knopoff model of stick-slip seismic motion. Looking for travelling wave solutions of the form $u(x - vt)$ gives the van der Pol oscillator equation. See [Burridge and Knopoff (1967)](https://doi.org/10.1785/BSSA0570030341) and [Cartwright et al (1999)](https://doi.org/10.1142/S0218127499001620).
  - Brad tells me Burridge-Knopoff is junk and we should use Rice's 0D earthquake simulator
* Solid earth
  - Mantle convection / Rayleigh-Benard convection fun times; try to add chemistry
  - thermochronometry; temperature at the near surface including combined effects of conduction and exhumation, see for example [Braun (2003)](https://doi.org/10.1016/S0098-3004(03)00052-9)
* Glaciology
  - Phase field model of melting
  - SSA
* Ecology
  - advection-reaction-diffusion models in spatial ecology, see [Lam, Liu, Lou](https://arxiv.org/pdf/2004.07978.pdf), especially the (nonlocal!!) phytoplankton model
  - chemotaxis, organisms following the resource gradient
  - see also ch 15 of Mark Kot's book
  - see also Okubo, Diffusion and Ecological Problems
  - Allee effect / Nagumo model, add space and you get clumping
