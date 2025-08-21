# confined-polymer-dynamics

This repository contains the LAMMPS code used in our paper to simulate the dynamics of branched polymers in confined environments. You can read our paper [here](). 

To run the script, execute

```bash
lmp -in in.diffuse
```

The `drug.data` file contains a 16-arm star polymer of arm length 15, the `ecm.data` file contains a monodisperse matrix of pore size 11, and `timesteps.txt` includes custom time steps at which we save the trajectory of the diffusing nanoparticle.
