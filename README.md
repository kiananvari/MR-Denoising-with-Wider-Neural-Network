
# MRI Denoising with Wider Neural Network

This is a Python implementation of denoising of MR (Magnetic Resonance) images with Rician noise using a wider neural network and noise range division. The implementation is based on the paper "Denoising of MR images with Rician noise using a wider neural network and noise range division" by Zhang et al. The implementation includes the training and testing of the neural network on MR images with Rician noise, as well as the evaluation of the denoising performance using various metrics..



# Dataset


The dataset used in this implementation is BrainWeb, which can be accessed at https://brainweb.bic.mni.mcgill.ca/. ↗ The dataset consists of simulated MR images with different levels of Rician noise.
## Implementation

The wider neural network with noise range division technique is implemented in this implementation. The WDNNs, WDNN-1, WDNN-2, WDNN-3, WDNN-4 are trained and tested.


## Results

The denoising performance of the WDNN models is evaluated using the following metrics:

- Peak Signal-to-Noise Ratio (PSNR)
- Structural Similarity Index Measure (SSIM)
- Normalized Mutual Information (NMI)

The results are reported in the paper and can be reproduced using the provided scripts.

