# rfim_phi
This is an implementation of the 3 dimensional Random Field Ising Model (RFIM) on Xeon Phi cards. It was used to produce the results published in [arXiv:1601.02455](http://arxiv.org/abs/1601.02455). The code achieves a single spin flip time as short as 6 ps.

## Usage
To compile this code you need the Intel C++ compiler (tested with version 15.0.0). The command-line parameters are documented in the code. For optimal performance you need to load the environment variables from `setenv.sh`.
