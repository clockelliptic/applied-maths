Computing and Visualizing Multivariable & Vector Calculus and Differential Equations with Python


Click here to view and interact with live, functional python notebooks: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clockelliptic/PSAM1819/master) **Notebooks may take a long time to load. Please be patient.**

**CONTENTS**

**OrdinaryDiffEqs**.ipynb

1  Solve Algebraic Equations with SymPy

2  Ordinary Differential Eqtn.s, Slope Fields, & Solution Curves

2.1  Integrals & Ordinary Differential Eqtn.s with SciPy

2.1.1  Example from Stack Exchange to get started:

2.2  Convert Matplotlib graphs to Plotly graphs

2.3  Slope Fields / Quiver Fields with Plotly

<br />

**PlotlySurfacePlotsAndContourPlots**.ipynb

1  Part 1: Surface Plot of Rectangular Pringle

1.1  Parametric 3D Plot (Spherical Parametrization / Coordinates)

1.2  Mesh 3D: Delaunay Triangulation Method

2  Part 2: Contour Plot

<br />

**SolvingDiffEqsAnalyticallyWithSympy**.ipynb

1  Part 1: Solving Differential Equations Analytically using SymPy

1.1  Defining Symbolic Functions and Statements with SymPy

1.1.1  More than three ways to make a function with SymPy

1.1.1.1  Undefined functions

1.1.1.2  Defined functions

1.1.2  Differentiating Single Variable Functions

1.1.2.1  Proper Syntax for taking derivatives

1.1.2.2  Two ways to take a derivative symbolically

1.1.2.3  Declaring Partial Derivatives

1.2  Solving Differentials Analytically using SymPy

1.2.1  Exploring SymPy Documentation

1.3  Solving Differentials Analytically using sympy.integrate

1.3.1  First Example From Delta College

1.4  Solving Differentials Analytically using sympy.solvers.ode.dsolve

1.4.1  Setting equalities with Eq()

1.4.2  Exploring ode.dsolve

1.4.2.1  classify_ode()

1.5  San Joaquin Delta College Lab Problems

1.5.1  First Problem: Solved!

1.5.1.1  Solving Differentials with Symbolically Defined Functions

1.5.2  Second Lab Problem

1.5.3  Third Lab Problem

2  Part 2: Solving Initial Value Problems

2.0.1  SymPy doesn't handle non-linear initial value problems

2.0.1.1  Solution: Parsing output strings into functions

2.0.1.2  Note to self: Use SciPy + (SpaCy or NLTK) to parse equations into variables and operations

2.0.2  Head developer of SymPy shares info about initial/boundary conditions

2.1  Back to the SJDC Intital Value Problems

2.1.1  Define Python function to extract constants from Eq statement

2.2  Initial Value Example Problems from SymPy Doc

3  Speeding Up SymPy with Cython


<br />

**FindingExtrema**.ipynb

1  Part 1: Using Jupyter and (StackExchange, GitHub, Google, etc.) to learn Python

2  Part 2 & 3: Review & Derivatives

2.1  Derivatives and Partial Derivatives

2.1.1  First-order Partials

2.1.2  Evaluating Partial Derivatives (and symbolic funcs in general)

2.1.3  Higher-order Partials

2.1.4  SymPy's built-in plotting

2.1.5  When SymPy's plots fall short...

2.1.5.1  lambdify and MatPlotLib

3  Part 4: Finding Extrema

3.1  Problem 1

3.1.1  Graphing to identify critical points

3.2  Problem 2

3.2.1  Finding Extrema with nsolve

3.3  Problem 3

3.3.1  nsolve and complicated FODEs

3.4  Problem 4

4  Wrap-up: Optimizing Graph/Surface Visibility

4.1  Setting Surface Opacity

4.2  Setting Hover-Label Opacity


<br />

**MultipleIntegrals**.ipynb

1  Multiple Integrals

1.1  Integrals are Sums and Areas

1.2  Double Integrals

1.2.1  Example 1

1.2.1.1  Method 1

1.3  Visualization

1.3.1  Example 2:

1.3.2  Example 3:

1.4  Triple Integrals

1.5  Exercises

1.5.1  Problem 1

1.5.2  Problem 2

1.5.3  Problem 3

1.5.4  Problem 4


<br />

**PolarCoordinatesReview**.ipynb

1  Trigonometry Review & Introduction to Fourier Series

2  Polar Coordinates Review & Introduction to Cylindrical and Spherical Coordinates

2.1  Plotting in Polar Coordinates with matplotlib

2.2  Plotting in polar coordinates with Plotly

2.2.1  r = cos(t)

2.2.2  Your Turn! Try a few...

2.2.3  r = sin(t)

2.2.4  r = sin(2t)

2.2.5  r = sin(3t)

2.2.6  r = sin


<br />

**VectorFieldsAndGradients**.ipynb

1  Vector Functions, Vector Fields, and Gradients

1.1  Part 1: Vector Fields

1.1.1  2D Vector (field) Plot Example

1.1.2  3D Vector (field) Plot Example

1.1.3  Plotting a Vector Field

1.1.3.1  2D Vector Field (Arrow Plot)

1.1.3.2  3D Vector Field (Cone Plot)

1.2  Part 2: Gradient

1.2.1  f(x, y)

1.2.1.1  Surface plot

1.2.1.2  Contour Plot

1.2.1.3  Arrow Plot

1.2.2  f(x, y, z)

1.2.2.1  Contour Plot

1.2.2.2  3D Cones

1.3  Part 3: Putting it all together

2  Solving Differential Equations Numerically and Solving Systems of Differential Equations

2.1  Solving Differential Equations Numerically

2.2  Part 5: Solving Systems of Differential Equations


<br />

**DivGradCurl**.ipynb

1  Part 1: Calculating Divergence and Curl

1.1  Calculating Curl

1.2  Calculating Divergence

2  Part 2: Explore Divergence and Curl

3  Part 3: Exploring Gradient, Div, and Curl


<br />

**NumericalMethodsDiffEqs**.ipynb

1  Numerical Methods for Solving Differential Equations

1.1  Part 1: Numerical Methods

1.1.1  Euler's Method (Predictor)

1.1.2  Heun's Method (Predictor-Corrector)

1.1.3  RK4

1.1.4  RK4 v.2

1.1.5  RK4 v.3 (most elegant code)

1.1.6  Interpolation with Python

1.1.6.1  Testing Polynomial Interpolation

2  PSAM Math Lab 9b: Initial Value Problem Applications

2.1  Solving Homogenous 2nd order LODEs Numerically

2.1.1  Try it out:

2.2  Solving Non-Homogenous 2nd order LODEs Numerically

2.3  Problem: A Simple Pendulum (success)

2.4  Problem: Hanging Wire (Success)

2.5  Problem: Compartmental Analysis


<br />

**CurlDivTheoremsAndVectorFields**.ipynb

1  Visualizing Vector Fields, Curl, and Div; Line Integrals; Green’s Theorem; Flux and the Divergence Theorem

1.1  Part 1: Visualizing Vector Fields with Zero Curl and/or Zero Divergence

1.2  Part 2: Line Integrals

1.2.1  Example 1:

1.2.2  Example 2:

1.2.3  Problems

1.2.3.1  Boas 6.8.17

1.2.3.2  Boas 6.8.18

1.2.3.3  Boas 6.9.5

1.3  Part 3: Green's Theorem

1.4  Part 4: Flux, Divergence, and the Divergence Theorem


<br />

**SteadyStateAndHeatFlowEquations**.ipynb

1  Visualizing Solutions to Partial Differential Equations

1.1  Solving The Heat Equation (Laplace's Equation) with Python

1.1.1  Simplification and Spatial Discretization of The Steady State Heat Equation in 2D and 3D cartesian coordinates.

1.1.1.1  Relaxation Method

1.1.2  Visualizing The Solution

1.1.2.1  Reusable Code

1.2  Solving the Heat Flow (Schroedinger) Equation

1.2.0.1  Rethinking discretization of Laplace's Equation

1.2.1  Warm Handprint on Surface (Cool!)

1.3  Circulation, Curl, and Stokes' Theorem; the Fundamental Theorems of Vector Calculus




