# Cross section tool for Low Eloss

This is a python package supporting the [Nebula Low Eloss](https://github.com/johannesber407/Nebula_Low_Eloss) simulator of electron-matter interaction, which adjusted 
[Nebula](https://github.com/nebula-simulator/nebula) for precise calculation of low Energy losses.
 Full instructions on how to use this
package can be found in the [documentation](https://nebula-simulator.github.io).

# Adjustments
Features that I plan to add to cstool:
- Add files describing the surface excitation of materials; read these files into the .mat file, so they can be processed by Nebula. (done)
- Adding data derived from REELS-Experiments (for example from https://doi.org/10.1063/1.3243762). In case REELS data is provided, the energy loss distribution for a single scattering in the bulk (w_b) is saved into the .mat file, so it can be accessed instead of the optical data. The optical data is still required for the Penn algorithm.