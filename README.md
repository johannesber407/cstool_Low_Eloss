# Cross section tool for Low Eloss

This is a python package supporting the [Nebula Low Eloss](https://github.com/johannesber407/Nebula_Low_Eloss) simulator of electron-matter interaction, which adjusted 
[Nebula](https://github.com/nebula-simulator/nebula) for precise calculation of low Energy losses.
 Full instructions on how to use this
package can be found in the [documentation](https://nebula-simulator.github.io).

# Adjustments
Features that I plan to add to cstool:
- Add files describing the surface excitation of materials; read these files into the .mat file, so they can be processed by Nebula. (done)
- add Temperature into the .mat file, so that doppler broadening in elastic scattering can be handeled correctly (see for example: D, Varga et al., Surf. Interface Anal. 2001; 31: 1019–1026)
- Adding additianal datasets of the ELF to choose from (Maybe at some point in the future)(for example from https://doi.org/10.1063/1.3243762)