# Extending Transmission Line Models to Second-Harmonic Nonlinear Electrochemical Impedance Spectra

This repository contains the essential code and jupyter notebook for the paper "Extending Transmission Line Models to Second-Harmonic Nonlinear Electrochemical Impedance Spectra"

This repository can be cited with: 


For further information or if this code is used, please go to or cite the following paper:

-------------
### Abstract
-------------

Transmission line models (TLMs) are finite algebraic representations of porous electrodes, providing extraordinary flexibility to include materials physics that makes traditional porous electrode analysis intractable. We provide an algebraic framework for extending traditional linear TLMs to second harmonic nonlinear TLMs (2nd-nTLMs) and validate it against analytical porous electrode theory developed previously. To demonstrate the flexibility of 2nd-nTLMs, we introduce core-shell particles (common in batteries) into the porous electrode and explore the EIS and 2nd-NLEIS response. The ability of half-cell 2nd-NLEIS to discriminate among models is explored using TLMs and 2nd-nTLMs with core-shell structured particles (along with diffusion impedance) under the limit of high solid conductivity compared to electrolyte conductivity. The 2nd-NLEIS response is shown to amplify small parameters differences under conditions where EIS is insensitive. Parameter identifiability is further evaluated for identical and overlapping RC time constants in the core and shell by curve fitting with a single RC time constant model. While simultaneous EIS and 2nd-NLEIS analysis cannot discern homogeneous or core-shell particles in the limiting case of identical RC time constants, it can identify inapplicable models where the EIS spectrum is well fit but not the 2nd-NLEIS spectrum, even with overlapping time constants.



### Software Dependencies
----------------------------------------------------------------
This repository was developed using the following versions of the subsequent softwares:

* Python 3.11.10
* Conda 23.1.0
* Git Bash for MacOS

The conda environment used for this work can be recreated with the following commands:

```conda env create -f environment.yml```

```conda activate tlm```

----------------------------------------------------------------
### Folders and Files
----------------------------------------------------------------
**nleis**: This folder contains unreleased version of nleis.py that has all TLM/2nd-nTLM functionality built in. 

**nTLM.ipynb**: This is the main jupyter notebook that is   used to generate figures for this work

**figures**: This folder contains all figures in the paper
