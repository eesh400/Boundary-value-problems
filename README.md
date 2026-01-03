# Boundary-value-problems
This is a project which shows how to solve simple boundary value problems in differential equations in Wolfram Language(Mathematica).

1. Overview
   
   This project contains solutions of simple boundary value problems(BVPs) for ordinary differential equations implemented using Wolfram Language/Wolfram Mathematica.

2. Mathematical Formulation
   
   The problems considered are simple first and second-order ODEs of the form:
   
   y'(x)=f(x,y), x ∈ [a, b]
and y''(x) = f(x,y,y')

where y(a) = α,   y(b) = β (Dirichlet)

y'(a) = α,   y'(b) = β (Neumann)

3. Methods Used in Mathematica
   
   • DSolve
   
   • Simplify
   
   • FullSimplify
   
   • Evaluate
   
   • Plot

4. Purpose of Methods Deployed

   • DSolve – obtains exact (symbolic) solutions of differential equations.

   •Simplify – reduces expressions using algebraic identities.

   •FullSimplify – performs deeper simplification using additional transformations.

   •Evaluate – forces evaluation of expressions inside plotting or substitution commands.

   •Plot – visualizes the solution over the given interval.

5. Files included

   • .nb notebook containing worked Mathematica solutions

   • .wl file containing executable Wolfram Language code

   • .pdf file contains exported problem statements and results

6. Academic Context
 
   Intended for coursework and practice in ordinary differential equations using Wolfram Mathematica.
