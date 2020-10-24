## KDAR NuWro Distributions

1. 'params_all_channels.txt' is a NuWro parameter file.
It sets the the energy and flavor of the neutrino and toggles the interaction channels.
It is invoked by NuWro with the following command: 
```bash
nuwro -i params_all_channels.txt \
      -p "nucleus_target = 2" \
      -p "sf_method = 1" \
      -o all_channels.root
```
This follows the [NuWro tutorial](https://nuwro.github.io/user-guide/getting-started/running/) for a spectral function. 

2. 'all_channels.root' is the output of the above command
3. 'KDAR_NuWro_Distributions.ipynb' extracts and plots the proton and muon kinetic energies from 'all_channels.root'
This is a Jupyter Notebook running Python but it can be viewed in this browser. 
