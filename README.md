# MS2toMS1fitter

## Overview
Notebook to support analysis in "Following phospholipid transfer through the OmpF3-MlaA-MlaC lipid shuttle with native mass spectrometry."
Example data is also provided.

## Input Requirements
The notebook requires paired mass spectra input:

1. **Deconvolved MS1 spectrum of the protein-ligand complexes**, produced using UniDec. 
   - The spectrum should be acquired with sufficient resolution such that peak widths correspond to the width of the isotopic envelope.
   - We accomplish this by turning off eFT (i.e., use magnitude-mode FT) and acquire with long transients so individual isotopologues can be at least partially resolved.

2. **MS2 spectra** acquired by isolating and activating the entire ensemble of ligand-bound species.

A file used to generate lipid masses (provided) is also required.

## Important Note
This notebook requires extensive manual adjustment and is not suitable for automated analysis. Despite this limitation, it successfully performs the intended analysis.
