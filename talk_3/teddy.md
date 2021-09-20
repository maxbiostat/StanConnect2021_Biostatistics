## Summarising enzyme information from online databases using Stan and Arviz

Many systems biology applications require information about the kinetic behaviour of metabolic enzymes, which can be found in databases like BRENDA, which records measurements of kinetic parameters for a wide range of organisms, enzymes and experimental conditions. However, it is not straightforward to use this information in kinetic models as the raw measurements are often scarce, inconsistent and difficult to aggregate. For example, if a certain enzyme/substrate combination’s Michaelis constant has only been measured once, but additional measurements are available for the same substrate and a similar enzyme (say with the same first three digits of the EC number), it is not straightforward to say what is the best guess as to the true value of the
original measured quantity.

Our analysis addresses the problem of summarising the information in BRENDA about kinetic parameters using a nested multilevel statistical model implemented in Stan. We demonstrate how representing structural information like the enzyme classification number and substrate improves the model’s predictive accuracy. We present our model’s results in a web application which we hope will allow systems biologists to more easily use the BRENDA data.

Joint work with Areti Tsigkinopoulou

[Teddy Groves](https://www.linkedin.com/in/teddy-groves-9002b8117/?originalSubdomain=dk) is a postdoctoral researcher at the Technical Universtiy of Denmark.
