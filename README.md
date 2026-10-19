# Multi-fidelity Modelling: A Maxima a Posteriori and Kernel Based Approach

PyTorch code for multi-fidelity regression in which the Hi-Fi uncertainty is large where Hi-Fi data is sparse and small where it is dense. A Lo-Fi model and a parametric discrepancy are fitted first. A Hi-Fi mean and variance network is then trained against an interpolation of the Hi-Fi data. Each Hi-Fi observation is weighted by a kernel density estimate (KDE) of where the Hi-Fi data lies, and the Hi-Fi mean is pulled towards `mu_L + mu_D` by a Gaussian prior.

Early code for unsubmitted manuscript: "Multi-fidelity Modelling: A Maxima a Posteriori and Kernel Based Approach"
