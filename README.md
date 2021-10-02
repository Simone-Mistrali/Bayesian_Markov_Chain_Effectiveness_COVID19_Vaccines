# Inference of Covid-19 vaccines effectiveness and uncertainty using bayesian methods

**Authors**: Lorenzo Mandolito and Simone Mistrali 

Project on Markov Chains for Advanced Statistics for Physics Analysis at UniPD.

## Some definitions
### What is effectiveness? 

In medicine, effectiveness relates to how well a treatment works in practice, especially as shown in pragmatic clinical trials, as opposed to efficacy, which measures how well it works in explanatory clinical trials or research laboratory studies.

### The quantitative definition

To give a quantitative definition of the effectiveness we will use the following formula:

<img src="https://latex.codecogs.com/gif.latex?Eff&space;=&space;\frac{\textbf{$\theta$}{Placebo}&space;-\textbf{$\theta$}{Vaccine}}{\textbf{$\theta$}_{Placebo}}100" title="Eff = \frac{\textbf{$\theta$}{Placebo} -\textbf{$\theta$}{Vaccine}}{\textbf{$\theta$}_{Placebo}}100" />

In this project we try to infer the effectiveness of the COVID-19 vaccines using Markov Chains.

We have used R language and `RJAGS` (Just another Gibbs sampler) a library for simulation from Bayesian hierarchical models using Markov chain Monte Carlo. 

We show how to set up a simple Markow Chain simulation and apply it to a simple model, after that we have study the effectiveness of the vaccines using the public data from EMA. We have show that the bayesian approch is really robust if we have "enought data" in the second part (the age group one) we can see that given the restrict numbers the bayesian approach fails.  

## Contact

To properly run this project please clone this directory and install JAGS on you're machine.

Contact Simone Mistrali at simone.mistrali at gmail.com for any questions or comments.

