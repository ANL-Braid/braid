### Ptychography


Ptychography is a non-invasive 2D imaging technique that is widely used at synchrotron light sources to study functional, structural, biological, and energy materials at extremely high spatial resolutions.
Asample is continuously raster-scanned using a focused X-ray beam and the corresponding diffraction patterns are acquired on a photon-counting pixelated detector. These diffraction patterns are then processed using an iterative ptychographic reconstruction method to generate 2D real-space projection images.
To enable rapid data analysis and feedback, we [define a Flow](https://github.com/ANL-Braid/flows#ptychography) that (see figure) transfers data from data acquisition machine (edge) to compute cluster (e.g., at ALCF); initiates reconstruction; and transfers reconstructed images back to light source. 
In the future, additional Flows will be added to index, catalog, and archive images.

## Flow Definition

<img align="right" src="images/TekinSystem.png" width="350">


## Links