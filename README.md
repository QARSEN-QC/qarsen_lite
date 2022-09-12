# QARSEN_lite

Quantum Algorithms for Real Space simulation of Electrons and Nuclei

This repo contains algorithm demos which uses [pyQuEST](https://github.com/rrmeister/pyQuEST) for quantum simulation of particles in real-space grids. It contains the essential elements which went into the numerical simulations reported in [this work](https://arxiv.org/abs/2202.05864).

## Requirements
- pyQuEST
- numpy
- jupyter
- matplotlib

## Installation
More detailed instructions can be found in the first notebook
1. Clone/Download PyQuEST: `git clone -b develop --recursive https://github.com/rrmeister/pyQuEST`

2. Create new python environment: `conda create -n pyquest python=3.9`, then run `conda activate pyquest`

3. Install pyquest into python environment: navigate to the folder where pyquest has been downloaded using anaconda prompt e.g. `cd Downlads/pyQuEST`, and run `pip3 install .`. This should then install pyquest and numpy into the python environment called `pyquest`.

4. Use `pyquest` environment to run notebooks in this repo.

## Examples

[Getting Started](https://github.com/QARSEN-QC/qarsen_lite/blob/main/Getting_started.ipynb) -
Basic methods of defining wavepackets in a grid, using `PhaseFunc` from `pyquest`, extracting phase.

[Custom Potential](https://github.com/QARSEN-QC/qarsen_lite/blob/main/Custom_potentials.ipynb) -
Time propagation of quantum wavepackets under a custom potential, using `pyQuEST` methods.

[Ground state preparation](https://github.com/QARSEN-QC/qarsen_lite/blob/main/Ground_state_preparation.ipynb) -
Driving a loaded wavepacket towards the ground state subject to the interaction potentials, using `pyQuEST` methods to implement PITE.




