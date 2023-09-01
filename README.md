# Choroid plexus segmentation

Segmentation tool for the delineation and volumetric quantification of the choroid plexus

## Quick Start Instructions
If you have already installed Docker, you can get the kilianhett/chp_seg:latest image from Docker Hub repository:

```
sudo docker pull kilianhett/chp_seg:latest
```

Choroid plexus segmentation software currently only support CPU

```
sudo docker run -v /absolute_path_to_folder/:/data/in  -v /absolute_path_to_folder/:/data/out kilianhett/chp_seg --sequence_type T1 --name_pattern <name_of_image>
```

See Installation instructions for detailed instructions on how to install all the dependencies.
See How to use Chp_Seg for detailed instructions on how to use Chp_Seg.
