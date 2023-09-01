# Choroid plexus segmentation

Segmentation tool for the delineation and volumetric quantification of the choroid plexus

## Quick Start Instructions
If you have already installed Docker, you can get the kilianhett/chp_seg:latest image from Docker Hub repository:

> sudo docker pull volbrain/assemblynet:1.0.0
If you have a NVIDIA GPU with at least 8GB, and have already installed NVIDIA Container Toolkit, you can run AssemblyNet on the GPU on the image /absolute/path/to/images/image.nii.gz:

sudo docker run -v /absolute_path_to_folder/:/data/in  -v /absolute_path_to_folder/:/data/out kilianhett/chp_seg --name_pattern <name_of_image>

See Installation instructions for detailed instructions on how to install all the dependencies.
See How to use AssemblyNet for detailed instructions on how to use AssemblyNet.
