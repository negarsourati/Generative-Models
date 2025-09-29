This repository contains five Jupyter notebooks implementing and comparing classic generative modeling families on vision data (mainly MNIST, with optional CIFAR support).

Notebooks

AR-Implementation.ipynb — Auto-Regressive models. Implements FVSBN and NADE baselines and generates samples from each of these models, and compares their performances.

VAEs.ipynb — Variational Autoencoders. Encoder/decoder design, ELBO training, reconstructions, latent traversals, and interpolation.

AR&VAE-Evaluation.ipynb — Unified evaluation toolkit. Provides metrics (FID, Inception Score, bpd, ELBO) for fair model comparison.

NF-GAN-EBM.ipynb — Three paradigms in one: Normalizing Flows (exact likelihood), GANs (adversarial), and EBMs (energy-based). Each includes implementation, training, and sample visualization. The notebook concludes with a comparison table contrasting these models against the earlier approaches.

Diffusion.ipynb — Diffusion models. Forward noising and reverse sampling, denoising objective, sample evolution, and qualitative results for a simple diffusion model.
