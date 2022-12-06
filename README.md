# Heat_transfer_sim2

DCGAN model with 2 distribution functions added, including:
- row-wise mean.
- row-wise variance
as second and third channels in addition to the original image channel.

D takes 3-channel image as input.
G outputs 3-channel imags.

A test model was built using jupyter notebook "DCGAN_multiple_distribution_functions". It has been trained on Sim2 dataset for 1500 epochs (3hours). The weights are saved in netD_221206.pth and netG_221206.pth respectively, on December 06, 2022.

