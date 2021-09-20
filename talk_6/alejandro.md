## A Bayesian Approach to Representing Variability in Space in Cardiac Action Potential Properties

Cardiac cells exhibit variability in the shape and duration of their action potentials, among
individuals, and in space and time within a single individual. At short pacing periods, cardiac cells can exhibit a bifurcation that leads them to produce action potentials that alternate in duration, a phenomenon called alternans. Finding parameters for a cardiac action potentials model to reproduce specific alternans dynamics quantitatively is challenging because of the nonlinear dependence on pacing period and the number of parameters involved. We apply a Bayesian approach to find the probability distributions of the parameters of the Mitchel-Schaeffer (MS) cardiac action potential model fitted to action potentials from synthetic data represented on a grid that simulates measurements from optical mapping. We define a hierarchical model on the parameters of MS and simulate correlated values on a grid for one of the parameters. Using a latent Gaussian process as a prior for the grid parameter, we do inference in a subset of sampled locations used as training points to predict the values on the non-sampled locations. We apply a Markov Chain Monte Carlo technique, the Hamiltonian Monte Carlo algorithm implemented in Stan through the Not-U-Turn Sampler.

Joint work with Christopher Krapu, Elizabeth Cherry and Flavio Fenton.

Alejandro Nieto Ramos is a PhD student at the School of Mathematical Sciences, Rochester Institute of Technology.
