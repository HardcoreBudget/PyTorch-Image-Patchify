# PyTorch-Image-Patchify
This repo allows the user to split the image into patches of two types:  

1) Custom patchify: allows the user to set the crop size and overlapping size. (When unpatchifying the overlapping patches are averaged)
2) Grid patchify: allows the user to split the image vertically in half then set the number of desired horizontal crops.

The residual/additional pixels in both types are also taken into consideration!
