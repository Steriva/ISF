# Incompressible Schrodinger Flow (ISF)
This repository collects some codes for the simulation of inviscid and viscous fluids by means of the ISF technique, firstly developed by [Albert Chern](https://cseweb.ucsd.edu/~alchern/).
The original code was conceived for inviscid fluids (governed by the Euler equations), in this repository an extension to viscous fluids is proposed.

Here are some references:
- A. Chern. Fluid Dynamics with Incompressible Schroedinger Flow. PhD thesis, 2017
- A. Chern, F. Knöppel, U. Pinkall, P. Schröder, and S. Weißmann. Schrödinger’s smoke.
ACM Trans. Graph., 35, 7 2016

## How to use it
Two different programming languages are available:
- MATLAB: two simple tutorials (Von Karman and Tube Convergent) are available. To use them download the 'Matlab' folder and execute the two scripts.
- FEniCSx (Python): Colab notebooks have been used, open them in Google Colab to run them. Otherwise, download them as a .py script and execute in your terminal (be sure to have [FEniCSx](https://fenicsproject.org) - some of them require the complex mode - installed).

