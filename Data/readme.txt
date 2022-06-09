All data in this folder are the normalized probablity distributions for the various spectra.

Data is obtained from: http://www.sns.ias.edu/~jnb/SNdata/sndata.html

All original data has been downloaded as "<process>Spectrum.csv"
Any modifications have been saved in new files as "<process>Spectrum2.csv"

	1. We have added an extra column labeled "total_flux" with values taken from Table 1 of https://arxiv.org/abs/2107.08613 (Global solar fit subject to the Luminosity Constraint).

	2. PP spectrum data taken from table VII of Phys. Rev. C. 56 3391(1997)

	3. In all spectrum files, we have extended the support from their given energy values to E: [0,100] MeV by adding a zero-flux data point corresponding at (E,flux) = (0,0) and (E,flux) = (100,0). We do this to ensure that when dPhi/dE is computed for a particular energy, the specturm has support.

	
