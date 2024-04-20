# VAE-PyTorch
This is a PyTorch implementation of Variational AutoEncoders
This work is inspired from the academic paper: https://arxiv.org/abs/1312.6114 and https://openreview.net/forum?id=rJWXGDWd-H
## Installation
```bash
git clone https://github.com/mParthSaharanf/vae-pytorch.git
cd vae-pytorch
pip install -r requirements.txt
```
## Use
```bash
cd vae-pytorch
python run.py -c configs/<config-file-name.yaml>
```
write config file name of the model in place of <config-file-name.yaml>



## Available Implementations
### 1. Vanilla VAE
### 2. Conditional VAE
# Data

To use this project, you'll need to download the CelebA dataset from [here](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html).

After downloading the dataset, follow these steps:

1. Create a folder named `Data` inside the project folder.
2. Extract the downloaded data into the `Data` folder.

Now your project is ready to use with the CelebA dataset.

