# LiDAR-GS++: Improving LiDAR Gaussian Reconstruction via Diffusion Priors
<!-- <h3 align="center">[CVPR 2024 - Highlight]</h3> -->
<!-- <p align="center">
   <a href="https://arxiv.org/abs/2410.05111.pdf">
      <img src='https://img.shields.io/badge/arxiv-2410.05111-red?style=flat' alt='arxiv 2410.05111'></a>
</p> -->

> Qifeng Chen, Jiarun Liu, Rengan Xie, Tao Tang, Sicong Du, Yiru Zhao, Yuchi Huo, Sheng Yang†

This is the official implementation of **LiDAR-GS++: Improving LiDAR Gaussian Reconstruction via Diffusion Priors** (AAAI-26)  [[arxiv](https://github.com/CN-ADLab/LiDAR_GS_plus)](coming soon).

# Abstract
Recent GS-based rendering has made significant progress for LiDAR, surpassing Neural Radiance Fields (NeRF) in both quality and speed. However, these methods exhibit artifacts in extrapolated novel view synthesis due to the incomplete reconstruction from single traversal scans. To address this limitation, we present LiDAR-GS++, a LiDAR Gaussian Splatting reconstruction method enhanced by *diffusion priors* for real-time and high-fidelity re-simulation on public urban roads. 
Specifically, we introduce a controllable LiDAR generation model conditioned on coarsely extrapolated rendering to produce extra geometry-consistent scans and employ an effective distillation mechanism for expansive reconstruction.
By extending reconstruction to under-fitted regions, our approach ensures global geometric consistency for extrapolative novel views while preserving detailed scene surfaces captured by sensors.
Experiments on multiple public datasets demonstrate that \method achieves state-of-the-art performance for both interpolated and extrapolated viewpoints, surpassing existing GS and NeRF-based methods.
