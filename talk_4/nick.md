## Automated kinetic modelling in Stan and its application to the methionine cycle

The methionine cycle is a fundamental pathway in human metabolism. Its intermediates participate in a variety of mechanisms competing for the same resources. These functions all occur simultaneously resulting in a highly regulated pathway with approximately 6 allosteric effectors. In order to understand the operation of the methionine cycle we constructed a kinetic model as a system of ODEs, where the state variables are the metabolite concentrations and the fluxes are constrained by mechanistic rate laws. However, these systems are described as ‘sloppy parameter’ systems, where the marginal parameter distributions can be large, yet still display tight posterior predictions. Furthermore, measuring these parameters independently is obscured by measuring the system in in vitro conditions, as opposed to those experienced in vivo. This prevents the standard practice of placing tight priors on the parameter values.

Our software automates network construction, and conducts parameter sampling in Stan conditioned on in vivo measurements of metabolite concentrations, fluxes, and protein concentrations. The resultant posterior draws take advantage of the HMC algorithm to efficiently sample the highly correlated parameter space and generate sets that describe the kinetic model equally well, despite their broad marginal distributions. This approach is applied to the methionine cycle as an ideal case of a highly regulated and non-linear pathway.

Joint work with Teddy Groves.

[Nicholas Cowie](https://orbit.dtu.dk/en/persons/nicholas-luke-cowie) is a PhD student at the Technical University of Denmark.

## Relevant repositories
* [Maud](https://github.com/biosustain/Maud)
* [Maud_Demo](https://github.com/biosustain/maud_demo)


Data used for joint plots see [here](data/samples)

