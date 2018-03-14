# vae_conv
Convolutional variational autoencoder in PyTorch

# Basic VAE Example

This is an improved implementation of the paper [Stochastic Gradient VB and the
Variational Auto-Encoder](http://arxiv.org/abs/1312.6114) by Kingma and Welling.
It uses ReLUs and the adam optimizer, instead of sigmoids and adagrad. These changes make the network converge much faster.

```bash
pip install -r requirements.txt
python main.py
```

