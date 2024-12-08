[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# Inference in Higher-order Undirected Graphical Models and Binary Polynomial Optimization

This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

The software and data in this repository are a snapshot of data and results that were used in the research reported on in the paper [Inference in Higher-order Undirected Graphical Models and Binary Polynomial Optimization](https://doi.org/10.1287/ijoc.2024.0776) by Aida Khajavirad and Yakun Wang.

**Important: This code is being developed on an on-going basis at https://github.com/Yakun1125/Inference-in-Higher-order-Graphical-Model. Please go there if you would like to get a more recent version or would like support.**

## Cite

To cite the contents of this repository, please cite both the paper and this repo, using their respective DOIs.

https://doi.org/10.1287/ijoc.2024.0776

https://doi.org/10.1287/ijoc.2024.0776.cd

Below is the BibTex for citing this snapshot of the repository.

```
@misc{Wang2024,
  author =        {Khajavirad, Aida and Wang, Yakun},
  publisher =     {INFORMS Journal on Computing},
  title =         {Inference in higher-order undirected graphical models and binary polynomial optimization},
  year =          {2024},
  doi =           {10.1287/ijoc.2024.0776.cd},
  url =           {https://github.com/INFORMSJoC/2024.0776},
  note =          {Available for download at \url{https://github.com/INFORMSJoC/2024.0776}},
}
```

## Description
This project explores the use of Linear Programming (LP) relaxations for inference in higher-order undirected graphical models. It specifically focuses on two practical applications:

1. **Image Denoising**: Utilizing graphical models to recover clean image from noisy observation.
2. **Error-Correcting Decoding**: Recover ground turth message transmitted from noisy channel.

## Repository Structure
- **denoising/**: Contains datasets and scripts related to the image denoising experiments.
- **decoding/**: Includes data and scripts for experiments on error-correcting decoding.

See the corresponding subfolders for instructions and scripts to run experiments for each application.