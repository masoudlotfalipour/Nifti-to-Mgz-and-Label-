# Freesurfer Nifti Mask Conversion

This repository provides a simple workflow for converting Nifti mask files into Freesurfer-compatible formats. The process ensures that the masks are aligned with the subject space and ready for further analysis.

## Requirements
Freesurfer is installed and configured (FREESURFER_HOME is set in your environment).
A Nifti file (.nii) as the input.

## Steps
1. Convert Nifti to Freesurfer Format (.mgz)
2. Register the Mask to Subject Space
3. Create a Binary Label
4. Visualize the Results
