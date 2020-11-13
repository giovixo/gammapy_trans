# GRB190114C: CTA simulation with gammapy
__Authors:__ Giulia Stratta (giulia.stratta@inaf.it), Giovanni De Cesare (giovanni.decesare@inaf.it) 

## Data
From paper of MAGIC collaboration (Nature, 575, 455, 2019)

Redshift: z=0.4245

Power law spectrum, with Gamma=5.4, F0=4.1e-10 ph/Tev/cm2/s at E0=0.475 TeV in the 0.3-1 TeV band. 

Power law light curve, with delta=-1.6

T0=14 January 2019, 20:57:03 UTC

MAGIC observations started T+57s and lasted T0+15912 s

## Light curve simulation
We simulate 6 datasets using the spectral model `PowerLawSpectralModel` and the temporal model  `PowerlawDecayTemporalModel` we have implemented for this study. 