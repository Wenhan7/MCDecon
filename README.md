# MCDecon
# This package contains an algorithm that performs multichannel sparse deconvolution to estimate multi-trace receiver function simultaneously.

# Please cite the reference when you use the code for your research:
# Sun, W., Sacchi, M. D., & Gu, Y. J. (2023). Multichannel Sparse Deconvolution of Teleseismic Receiver Functions with f-x Preconditioning. Journal of Geophysical Research: Solid Earth, accepted.

# The details of this algorithm can be found in this publication.

# The package includes:
# 1 MCDecon_ADMM: The main function of multichannel sparse deconvolution.
# 2 MCDecon_deomo: A synthetic example
# 3 seis.mat, rdm_noi.mat: The synthetic data and additive noise used in the synthetic example.
# 4 fx_decon: The function of fx prediction filter.
# 5 wigb: A matlab function that visualizes waveforms.
# The functions #4-5 are grabbed from SeismicLab, a public MATLAB toolbox. The full package of SeismicLab is accessible from: https://github.com/msacchi/SeismicLab
