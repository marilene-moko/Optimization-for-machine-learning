# Optimization for Machine Learning — Project Summary

This project explores  some first-order optimization methods through two main experiments:

1. **Gradient Method and Step Size Analysis**  
   A single-hidden-layer neural network is trained on synthetic data to study the influence of the dimension on the learning rate.  
   We analyze convergence speed, stability, and accuracy across several network sizes and identify empirical scaling laws for the optimal step size.

2. **Nesterov Accelerated Gradient Methods**  
   Two variants — *Vanishing Friction* and *Speed Restart* — are implemented and compared on the Rosenbrock function.  
   Both reach the global minimum, but *Speed Restart* shows more stable and precise convergence, with slightly higher computational cost.

Overall, the work illustrates how small modifications in optimization dynamics (learning rate or momentum control) can significantly affect convergence behavior and robustness in non-convex settings.
