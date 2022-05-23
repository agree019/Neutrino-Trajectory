All data in this folder are the normalized probablity distributions for the various spectra.

Data is obtained from: http://www.sns.ias.edu/~jnb/SNdata/sndata.html

All original data has been downloaded as "<process>Spectrum.csv"
Any modifications have been saved in new files as "<process>Spectrum2.csv"

	1. In order to make the interpolation more convenient for us, we extend the region of support for all spectra by hand, adding data points to the csv files, from the given range to E: [0.001, 30] MeV.

	2. We have added data points very close to the first data point at the low end of the spectrum to make the interpolation cut off close to the last data value. If you don't do this, the interpolation continues to lower energies than is given in the data.

	3. PP spectrum data taken from table VII of Phys. Rev. C. 56 3391(1997)

	4. In b8Spectrum, we have added an extra zero-flux data point with (E,flux) = (0.01,0) in order to make the interpolation nice