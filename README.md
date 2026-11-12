# S2D-Net

Official project page for:

**S2D-Net: A Unified Data-Driven CBCT Reconstruction Framework for
High-Resolution Projections from Extremely Sparse to Semi-Dense Views**

## Release status

The complete implementation, including preprocessing, training, inference,
and experiment configuration files, will be publicly released upon acceptance
of the manuscript.

This repository currently serves as the project page and does not yet provide
the implementation or trained weights.

## Method

S2D-Net is a unified data-driven framework for high-resolution cone-beam CT
reconstruction across extremely sparse to semi-dense view configurations. It
combines a grid-preserving projection encoder with multi-projection mixing,
Fourier positional encoding, and voxel-intensity regression.

## Datasets

- LUNA16: <https://luna16.grand-challenge.org/Download/>
- Dental: <https://huggingface.co/datasets/Zhentao-Liu/TMI2024_SVCT_dataset>
- CTSpine1K: <https://github.com/MIRACLE-Center/CTSpine1K>

The repository does not redistribute medical data. Dataset access and use are
subject to the terms of the original providers.

## Citation

Citation metadata is provided in `CITATION.cff`. Publication details will be
updated after acceptance.
