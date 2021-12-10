# LatticeQCD-data-analysis-in-Julia


This workshop is focused on the analysis of highly correlated data coming from Monte Carlo simulations.

We start with a brief introduction of the Julia programming language,  and then we introduce ADerrors.jl,
a package  for error propagation and analysis  of Monte Carlo data with the <img src="https://render.githubusercontent.com/render/math?math=\Gamma">
 -method.
Eventually we introduce Juobs.jl, a package for high-level analysis and observable computations for LatticeQCD

## Outline 
1.  Introduction to Julia
    1.  Why Julia? (slides)
    2.  Getting started (notebook)
    3.  Going in depth (notebook)
    4.  Julia is fast (notebook)
    
2.  The ADerrors.jl package
    1.   Introduction to ADerrors and the <img src="https://render.githubusercontent.com/render/math?math=\Gamma">-method (slides)
    2.   ADerrors in practice (notebook)

3.  The Juobs.jl package
    1.  Introduction to Juobs  (slides)
    2.  Juobs in practie (notebook)


## ADerrors.jl main features
1.  Dealing with uncertainties 
2.  Error analysis with the <img src="https://render.githubusercontent.com/render/math?math=\Gamma">-method
3.  Error propagation in iterative algorithms

## Juobs.jl main features
1.  Readers for openQCD output files, compatible with multiple versions
2.  Computation of LatticeQCD observables
3.  Advanced fitting routines
4.  Implementation of the GEVP variational method for uwreal data type
