# Practical Numerical Methods with Python

## Getting Started
Most of this material seem to be based on Jupyter notebook. The first task of students is to get [Jupyter Notebbok](http://jupyter.org/install.html) and [Git](https://git-scm.com/) working on their machines. It is also recommended to create a [Github](https://github.com/) account. 



## Course Modules

1. [**The phugoid model of glider flight.**](https://github.com/krajit/numerical-mooc/tree/master/lessons/01_phugoid)
Described by a set of two nonlinear ordinary differential equations, the phugoid model motivates numerical time integration methods, and we build it up starting from one simple equation, so that the unit can include 3 or 4 lessons  on initial value problems. This includes: a) Euler's method, 2nd-order RK, and leapfrog; b) consistency, convergence testing; c) stability
Computational techniques: array operations with NumPy; symbolic computing with SymPy; ODE integrators and libraries; writing and using functions.
2. [**Space and Time—Introduction to finite-difference solutions of PDEs.**](https://github.com/krajit/numerical-mooc/tree/master/lessons/02_spacetime)
Starting with the simplest model represented by a partial differential equation (PDE)—the linear convection equation in one dimension—, this module builds the foundation of using finite differencing in PDEs. (The module is based on the “CFD Python” collection, steps 1 through 4.)  It also motivates CFL condition, numerical diffusion, accuracy of finite-difference approximations via Taylor series, consistency and stability, and the physical idea of conservation laws.
Computational techniques: more array operations with NumPy and symbolic computing with SymPy; getting better performance with NumPy array operations.
3. [**Riding the wave: convection problems.**](https://github.com/krajit/numerical-mooc/tree/master/lessons/03_wave)
Starting with an overview of the concept of conservation laws, this module uses the traffic-flow model to study different solutions methods for problems with shocks: upwind, Lax-Friedrichs, Lax-Wendroff, MacCormack, then MUSCL (discussing limiters). Reinforces concepts of numerical diffusion and stability, in the context of solutions with shocks.  It will motivate spectral analysis of schemes, dispersion errors, Gibbs phenomenon, conservative schemes.
4. [**Spreading out: diffusion problems.**](https://github.com/krajit/numerical-mooc/tree/master/lessons/04_spreadout)
This module deals with solutions to parabolic PDEs, exemplified by the diffusion (heat) equation. Starting with the 1D heat equation, we learn the details of implementing boundary conditions and are introduced to implicit schemes for the first time. Another first in this module is the solution of a two-dimensional problem. The 2D heat equation is solved with both explicit and implict schemes, each time taking special care with boundary conditions. The final lesson builds solutions with a Crank-Nicolson scheme. 
5. [**Relax and hold steady: elliptic problems.**](https://github.com/krajit/numerical-mooc/tree/master/lessons/05_relax)
Laplace and Poisson equations (steps 9 and 10 of “CFD Python”), seen as systems relaxing under the influence of the boundary conditions and the Laplace operator. Iterative methods for algebraic equations resulting from discretizign PDEx: Jacobi method, Gauss-Seidel and successive over-relaxation methods. Conjugate gradient methods.


Planned modules:
- **Perform like a pro: making your codes run faster**
Getting performance out of your numerical Python codes with just-in-time compilation, targeting GPUs with Numba and PyCUDA.
- **Boundaries take over: the boundary element method (BEM).**
Weak and boundary integral formulation of elliptic partial differential equations; the free space Green's function. Boundary discretization: basis functions; collocation and Galerkin systems. The BEM stiffness matrix: dense versus sparse;  matrix conditioning. Solving the BEM system: singular and near-singular integrals; Gauss quadrature integration.

## Sponsors

The initial deployment of the GW SEAS Open edX instance and the creation of the first course in the platform (Fall 2014) were funded with a seed grant from the GW VP for Online Education and Academic Innovation, TA support from the GW School of Engineering and Applied Scineces, and additional support from Nvidia Corp. Academic Programs and Amazon AWS (donated cloud credits for the first year).


