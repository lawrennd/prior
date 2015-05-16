ReadMe file for the PRIOR toolbox version 0.12 Monday, July 12, 2004 at 19:06:09
Written by Neil D. Lawrence.

License Info
------------

This software is free for academic use. Please contact Neil Lawrence if you are interested in using the software for commercial purposes.

This software must not be distributed or modified without prior permission of the author.


This toolbox allows priors to be placed over parameters, at the moment this is used so that MAP solutions can be found for the parameters rather than type-II maximum likelihood. The priors were written for the Null Category Noise Model (see NCNM toolbox) so that an exponential prior could be placed over the process variances. The rest of its functionality has not been tested, so use with care.

File Listing
------------

gammaPriorExpandParam.m: Expand gamma prior structure from params.
gammaPriorExtractParam.m: Extract params from gamma prior structure.
gammaPriorGradient.m: Gradient wrt x of the log Gaussian prior.
gammaPriorLogProb.m: Log probability of Gamma prior.
gammaPriorParamInit.m: Gamma prior model's parameter initialisation.
gaussianPriorExpandParam.m: Expand Gaussian prior structure from param vector.
gaussianPriorExtractParam.m: Extract params from Gaussian prior structure.
gaussianPriorGradient.m: Gradient wrt x of the log Gaussian prior.
gaussianPriorLogProb.m: Log probability of Gaussian prior.
gaussianPriorParamInit.m: Gaussian prior model's parameter initialisation.
invgammaPriorExpandParam.m: Expand inverse gamma prior structure from params.
invgammaPriorExtractParam.m: Extract params from inverse gamma prior structure.
invgammaPriorGradient.m: Gradient wrt x of the log Gaussian prior.
invgammaPriorLogProb.m: Log probability of inverse gamma prior.
invgammaPriorParamInit.m: Inverse gamma prior model's parameter initialisation.
laplacePriorExpandParam.m: Expand Laplace prior structure from param vector.
laplacePriorExtractParam.m: Extract params from Laplace prior structure.
laplacePriorGradient.m: Gradient wrt x of the log Laplace prior.
laplacePriorLogProb.m: Log probability of Laplace prior.
laplacePriorParamInit.m: Laplace prior model's parameter initialisation.
normuniPriorExpandParam.m: Expand Normal uniform prior structure from param vector.
normuniPriorExtractParam.m: Extract params from normal uniform prior structure.
normuniPriorGradient.m: Gradient wrt x of the log normal uniform prior.
normuniPriorLogProb.m: Log probability of a normal uniform.
normuniPriorParamInit.m: Normal uniform prior model's parameter initialisation.
priorExpandParam.m: Expand the prior model's parameters from params vector.
priorExtractParam.m: Extract the prior model's parameters.
priorGradient.m: Gradient of the prior with respect to its variables
priorLogProb.m: Log probability of Gaussian prior.
priorParamInit.m: Prior model's parameter initialisation.
priorTest.m: Run some tests on the specified prior.
