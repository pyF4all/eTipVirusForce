# Analysis of the Electrostatic Forces between an AFM tip and a virus capsid from Poisson-Boltzmann simulations

This repository contains the force analysis of the electrostatic interaction between a virus capsids and an approaching nanoscale probe. Collaboration between Christopher D. Cooper, Ian Addison-Smith and Horacio V. Guzman. Before running the jupyter notebooks, the following files are required:

- `ZIKV_6CO8_aa_charge_vdw_addspace.pqr`
- `surf_gs1.0_noTER_split.face` and `surf_gs1.0_noTER_split.vert`
- `phi.txt` and `dphir.txt` data from simulations in Pygbe, for distances 2, 4, 6, 8, 10, 12, 14, 16, 20, 50, 100, 500, 1000 Angstrom between capsid and tip

These files can be found in a [Zenodo repository](https://doi.org/10.5281/zenodo.6556469)

Here you'll find:

- `Force_components_afmtip.ipynb` : Jupyter notebook script to get **force qf, db, ib components** plotted between several distances between capsid and tip
- `Forcesqf_afmtip.ipynb` : Jupyter notebook script to get **force qf component** plotted between several aminoacid in slices of capsid
- `generate_vtk_afmtip.py`: Python script which generate the .vtk file who visualize the boundary forces on capsid surface

The manuscript details will be found soon under 'this link'!
