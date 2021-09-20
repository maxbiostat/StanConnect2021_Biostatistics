## Normalized power prior models in Stan

The power prior (Chen and Ibrahim, 2000) enables practitioners to utilize historical data to obtain a flexible informative prior. However, the prior may be sensitive to hyperparameter specification. Typically, such sensitivity is eliminated by treating the hyperparameter as random, that is, utilizing a hierarchical model. Unfortunately, for the vast majority of models, the normalizing constant of the power prior is unavailable.

In this talk, we present computational techniques to estimate normalized power prior (NPP) models using Stan. Specifically, we utilize a two-stage process that first estimates the normalizing constant for a wide range of values, and then utilizes a second round of sampling to obtain samples from the posterior density using the normalized power prior. The methodology and software will be invaluable to practitioners and regulators who wish to incorporate prior knowledge on the basis of historical data, but are skeptical of tuning parameters.

[Ethan Alt](https://www.linkedin.com/in/ethanalt/) is postdoctoral researcher 
