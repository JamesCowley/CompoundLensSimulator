# Geometric Optics: Spherical and Chromatic Aberration

### Abstract (from [the report](Report.pdf))
A computer model is used to simulate the properties of variously shaped converging and diverging lenses and to examine how the spherical aberration produced by different kinds of converging lens varies with the dimensions of the lens. It is verified that thinner lenses produce less significant spherical aberration for all shapes modelled, and specific dimensional recommendations are made for reducing spherical aberration in asymmetrical biconvex lenses, concave positive menisci, plano-convex and convex-planar lenses. The comatic aberrations (coma) produced by these lenses are also plotted and hence their natures determined. Chromatic aberration is simulated and measured in different converging lenses, and an achromatic Clark doublet comprised of a borosilicate crown glass positive lens and a flint glass negative lens is examined to determine the separation distance of the two lenses which optimises the doublet’s achromatism. The modelled flint glass lens is then gradually flattened to simulate a Littrow doublet, which is shown to be less effective at reducing chromatic aberrations than the Clark doublet.

### Analytical approach
1. Model individual light rays passing through a boundary between media of different refractive indices.
2. Model solid lenses out of intersecting circular boundaries.
3. Track multiple rays to see how an image would be distorted by each lens.
4. Add mutliple lenses to the system.
5. Vary size, shape and composition of lenses to try and achieve magnification with minimal aberration.

### Usage
Notebook (`.nb`) files can be opened and evaluated in Wolfram [*Mathematica*](https://www.wolfram.com/mathematica).

The file `Functions.nb` contains each important function of the project and an example graphical output.

The file `Aberration_Plots.nb` just contains some plots from the final report.
