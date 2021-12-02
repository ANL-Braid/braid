
### X-Ray Photon Correlation Spetroscopy

X-ray photon correlation spectroscopy (XPCS) exploits a coherent X-ray to measure sample dynamics. Speckle images are recorded and correlated to show fluctuations in time. The time correlation function can be calculation giving insight into the timescale processes of interest (diffusion, relaxation, reorganization, etc.). XPCS is used to study the slow dynamics of various equilibrium and non-equilibrium processes occurring in condensed matter systems.

## Flows

The XPCS application have two main flows. One that is executed at the beamline during the experiment in order to provide real time feedback and the other one used at a later stage for reprocessing the data with new parameters.

### Definitions

### Steps

### Triggers

Both flows are triggered by a single-use client that can be invoked on a bash terminal with the correct parameters.

`gladier_xpcs -p parameters`

During the experiment this flow-client is invoked by the APS Data Management system that takes care of transfering the data out of the beamline

## Links

See [the Flow](https://github.com/globus-gladier/gladier-xpcs).
