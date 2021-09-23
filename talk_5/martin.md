## Hidden Markov models for disease progression data

When detailed information on disease progression is available, Hidden Markov models (HMMs) are an interesting alternative to the commonly used proportional hazards survival/multistate models.
By enforcing additional structure on the transition matrix, HMMs can usefully model more disease states than a proportional hazards model on the same dataset at the cost of introducing additional assumptions.
Additionally, HMMs work well also when the disease progression is observed only noisily or indirectly.
We'll discuss how those models are setup and implemented in fully Bayesian setting and discuss examples modelling progression of dementia and of Covid-19 hospitalization.
