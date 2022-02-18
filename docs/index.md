## Using machine learning to auto-tune chi-squared tests for gravitational wave searches

This page contains links to the relevant codes used in the work "Using machine learning to auto-tune chi-squared tests for gravitational wave searches".

### Code

This [repo](https://github.com/connor-mcisaac/chisqnet) contains the code used to perform the preprocessing of the data and the training of the model.

This code and the search with the model included use a modified version of the PyCBC code found in this [fork](https://github.com/connor-mcisaac/pycbc/tree/chisqnet)

### Results

The trained model used in the paper can be found in this [file](https://github.com/icg-gravwaves/chisqnet/blob/main/results/chisq_model.hdf). To load the model use the function [load_transformation](https://github.com/connor-mcisaac/chisqnet/blob/944c9158e6f9d6806e93ba928ea715a03c253ab9/chisqnet/filtering.py#L1886).

### Contact

Have any questions? E-mail me at connor.mcisaac@port.ac.uk
