ExcitationOnePulse_multipleIntensities.ipynb
- Jupyter notebook to simulate the effect of one pulse by solving the corresponding Schrödinger equation
- Calculates the excitation probabilities after one pulse for the different transition wavelengths later used in the cooling simulation --> pkl files
- Is designed to be run for different intensities

ExcitationOnePulse_unshaped.ipynb
- Jupyter notebook to simulate the effect of one pulse by solving the corresponding Schrödinger equation, here without spectral shaping
- In principle the same as the other notebook - just out of convinience for not having to change too many parameters in the other notebook

Naming of the pkl files:
fin_ex_list<power>_Jmax<Jmax>_sigma<sigma>_shift<shift>GHz.pkl
- power is given in terms of the nominal power (from Zhenlin's paper): 10 means 100% of the power, 01 means 10% etc.
- Jmax is the maximum J considered in the simulation
- sigma is the sharpness of the cut and corresponds to the sigma of the error function used
- shift is how much the cut is detuned from the actual Q-branch transition
