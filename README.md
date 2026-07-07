# SET11104 - Advanced Software Development: Coursework

> Mateusz Pasternak\
> 40663397\
> MEng Software Engineering

## Optimising PID Controllers For Lower-Limb Robots in Python Using a Hybrid Evolutionary Algorithm

### Abstract

Wearable Lower-Limb Robots require well-tuned PID controllers to minimise tracking error and overshoot during rehabilitation movements. This project replicates the Hybrid GA–PSO optimisation method from Annisa et al. in Python using libraries like sympy, deap, and pyswarms, constructing a full closed-loop model with Laplace Domain transfer functions for hip and knee joints. Although the model produced correct system behaviour, the reliance on symbolic Laplace Transforms and ITAE evaluation resulted in excessive computation times, making full evolutionary optimisation impractical. The project concludes that while Python can replicate the control modelling, more efficient numerical tools or dedicated control libraries may be required for feasible PID optimisation.
