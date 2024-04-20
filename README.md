# VAE-PyTorch
This is a PyTorch implementation of Variational AutoEncoders
This work is inspired from the academic paper [here](https://arxiv.org/abs/1312.6114) and [here](https://openreview.net/forum?id=rJWXGDWd-H)
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
Replace <config-file-name.yaml> with the name of the configuration file for the model you want to run.


## Available Implementations
### 1. Vanilla VAE
### 2. Conditional VAE
# Data

To use this project, you'll need to download the CelebA dataset from [here](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html).

After downloading the dataset, follow these steps:

1. Create a folder named `Data` inside the project folder.
2. Extract the downloaded data into the `Data` folder.

