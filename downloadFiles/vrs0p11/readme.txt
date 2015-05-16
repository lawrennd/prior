ReadMe file for the PRIOR toolbox version 0.11 Thursday, June 17, 2004 at 16:01:38
Written by Neil D. Lawrence.

This toolbox allows priors to be placed over parameters, at the moment this is used so that MAP solutions can be found for the parameters rather than type-II maximum likelihood. The priors were written for the Null Category Noise Model (see NCNM toolbox) so that an exponential prior could be placed over the process variances. The rest of its funcitonality has not been tested, so use with care.

gammaPriorExpandParam.m: Expand gamma prior structure from params.
gammaPriorExtractParam.m: Extract params from gamma prior structure.
gammaPriorGradient.m: Gradient wrt x of the log Gaussian prior.
gammaPriorLogProb.m: Log probability of Gamma prior.
gammaPriorParamInit.m: Gamma prior model's parameter initialisation.
gaussianPrior.m: Constrains a parameter to be between 0 and 1.
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
priorExpandParam.m: Expand the prior model's parameters from params vector.
priorExtractParam.m: Extract the prior model's parameters.
priorGradient.m: Gradient of the prior with respect to its variables
priorLogProb.m: Log probability of Gaussian prior.
priorParamInit.m: Prior model's parameter initialisation.
priorTest.m: Run some tests on the specified prior.
