# Black Hole Thermodynamics

A small physics/numerics project exploring basic Schwarzschild black hole
thermodynamics.

![Banner](assets/banner.gif)

This repo works through a sequence of standard quantities and estimates:

- Schwarzschild radius
- Hawking entropy
- Hawking temperature
- characteristic Hawking-radiation wavelength
- black hole evaporation lifetime

The work is presented in a Jupyter-driven style, with symbolic derivations,
numerical estimates, and plots.

---

## Overview

For a non-rotating, uncharged black hole of mass $M$, this project computes
and discusses quantities such as

$$
r_s = \frac{2GM}{c^2},
\qquad
S = \frac{8\pi^2 k_\text{B} G M^2}{h c},
\qquad
T = \frac{h c^3}{16\pi^2 k_\text{B} G M},
$$

along with related scaling behavior such as

- $S\propto M^2$
- $T \propto M^{-1}$
- evaporation lifetime $\tau \propto M^3$

The main worked example is a one-solar-mass black hole.

---

## Dependencies

### Python Packages

- `astropy`
- `jupyter`
- `matplotlib`
- `numpy`
- `qrcode`
- `scipy`

---

## More Fun Black Hole Stuff
- ESA Lensing
  - https://www.esa.int/gsp/ACT/phy/Projects/Blackholes/WebGL/
- NASA 360
  - https://www.youtube.com/watch?v=dGEIsnBRWGs
- Other Simulators
  - https://adriwin06.github.io/black-hole/
    - this is where that sweet banner came from
  - https://blackhole-simulation.vercel.app/
  - https://oseiskar.github.io/black-hole/
  - https://invernessdesignstudio.com/free-space-simulations/black-hole-simulator
  - https://testtubegames.com/blackhole.html
